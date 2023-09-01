# 🏠 부동산

## 정보 보기

* **/res show** – shows bounds of current residence you are standing in
* **/res current** – show residence you’re currently in
* **/res info** – get info on a residence, leave off to view info on the one your standing in.
* **/res list \[player]** – list residences you own or a player
* **/res listall** – list all residences
* **/res sublist \[residence] \[page]** – list all subzones in current residence. Residence Name and page required to get to additional pages.

## 영역 설정

* **/res select \[x y z]** – select a cuboid area to protect, using either the selection tool (wooden axe by default) or specifying X, Y, and Z as a distance on those axes from the center point where you are standing (“10 5 10” would select an area 21 wide x 11 high x 21 long.
* **/res select chunk** – Select a whole chunk for protection.
* **/res select auto \[playername]** – Turns on auto selection tool
* **/res select expand \[amount]** – Expand selection in direction your looking.
* **/res select size** – show selected area size
* **/res select shift \[amount]** – Shift selection in direction your looking.
* **/res expand \[amount]** – Expands residence you are standing in direction you are facing by specified amount.
* **/res contract \[amount]** – Contracts residence you are standing in direction you are facing by specified amount.

<table><thead><tr><th width="381">명령어</th><th>설명</th></tr></thead><tbody><tr><td>/땅가격</td><td>부동산 영역을 잡은 만큼의 가격 확인<br>(한 블록당 0.05원)</td></tr><tr><td>/res create [부동산명]<br>/땅구매 [부동산명]</td><td>부동산 구매(설정)</td></tr><tr><td>/res remove [부동산명]<br>/땅삭제 [부동산명]</td><td>부동산 삭제<br> *골드 환불 불가*</td></tr><tr><td>/res expand [숫자]<br>/땅선택확장 [숫자]</td><td>바라보는 방향으로 [숫자]만큼 부동산 확장</td></tr><tr><td></td><td></td></tr><tr><td>/res set</td><td></td></tr><tr><td>/res padd [닉네임]<br>/권한주기 [닉네임]</td><td>해당 플레이어에게 부동산 권한주기</td></tr><tr><td>/res pdel [닉네임]<br>/권한뺏기 [닉네임]</td><td>해당 플레이어에게 부동산 권한뻇기</td></tr><tr><td>/res pset [닉네임] [권한] [true/false/remove]</td><td></td></tr><tr><td>/res give [부동산명] [닉네임]</td><td>해당 플레이어에게 부동산 양도</td></tr><tr><td></td><td></td></tr><tr><td>/res info [부동산명]</td><td>해당 부동산의 가치나 권한 정보 확인</td></tr><tr><td>/res list</td><td>소유 부동산 목록 보기</td></tr><tr><td>/res rename [부동산명] [새이름]</td><td>부동산 이름 변경</td></tr><tr><td>/res show</td><td>부동산 경계 보기</td></tr><tr><td>/입장메세지 [할말]<br>예)&#x26;a%player님 어서오세요!<br>→ABC님 어서오세요!</td><td>부동산 입장 메세지 설정<br>&#x26;a=색깔코드 %player=입장한 플레이어 표시</td></tr><tr><td>/퇴장메세지 [할말]</td><td>부동산 퇴장 메세지 설정</td></tr><tr><td></td><td></td></tr><tr><td>/rc</td><td>부동산 채팅 기능 끄고 켜기<br>chat 권한이 있는 유저만 해당 부동</td></tr></tbody></table>



## 설정

* **/res message \[residence] remove \[enter/leave]** – removes a enter or leave message.
* **/res mirror \[source] \[target]** – mirrors permissions from one residence to another. You must be owner of both to do this.

\


### 플래그

💡 **플래그란?** 부동산 내에서 어떠한 행동에 대한 **True**(t), **False**(f), **Remove**(r) 값을 **세부적으로** 설정하는 시스템

* **/res check \[residence] \[flag] (playername)** – Check flag state for you
* **/res flags** – List of all flag\
  **/res default \[residence]** – Restores residence to default flags.

| /플래그설정, /res set                 | 플래그 GUI 열기              | Text                 |
| -------------------------------- | ----------------------- | -------------------- |
| /플래그농작물보호                        | 농작물 보호 관련 플래그 활성화       | ​                    |
| /플래그몬스터허용                        | 부동산 내 몬스터 스폰 활성화        | ​                    |
| /플래그몬스터비허용                       | 부동산 내 몬스터 스폰 비활성화       | ​                    |
| /플래그무브허용                         | 부동산 내 다른 플레이어 입장 허용     | ​                    |
| /플래그무브비허용                        | 부동산 내 다른 플레이어 입장 비허용    | ​                    |
| ​                                | ​                       | ​                    |
| /res set \[플래그] \[t/f/r]         | \[플래그] 설정값 변경           | /res set day t       |
| (항상 낮으로 설정)                      | ​                       | ​                    |
| /res pset \[닉네임] \[플래그] \[t/f/r] | 해당 플레이어의 \[플래그] 권한 변경   | /res pset ABC move t |
| (플레이어 접근 허용)                     | ​                       | ​                    |
| /res pset \[닉네임]                 | 해당 플레이어에게 설정된 플래그 항목 확인 | ​                    |



<table><thead><tr><th width="226">플래그</th><th>설명</th></tr></thead><tbody><tr><td>anchor</td><td>리스폰 정박기 사용 허용</td></tr><tr><td>animalkilling ★★★</td><td>동물 살해 허용</td></tr><tr><td>animals ★</td><td>동물 스폰 허용</td></tr><tr><td>anvil</td><td>모루 사용 허용</td></tr><tr><td>anvilbreak</td><td>모루 파괴 허용</td></tr><tr><td>​</td><td>​</td></tr><tr><td>beacon ★</td><td>신호기 설정 변경 허용</td></tr><tr><td>bed</td><td>침대 사용 허용</td></tr><tr><td>brew</td><td>양조기 사용 허용</td></tr><tr><td>build ★★★</td><td>블록 설치 허용</td></tr><tr><td>burn</td><td>몬스터가 불타는 것을 허용</td></tr><tr><td>button ★★</td><td>버튼 사용 허용</td></tr><tr><td>​</td><td>​</td></tr><tr><td>cake</td><td>케이크 먹는 것을 허용</td></tr><tr><td>canimals</td><td>커스텀 동물 스폰 허용</td></tr><tr><td>chorustp</td><td>후렴과를 사용한 텔러포트 허용</td></tr><tr><td>cmonsters</td><td>커스텀 몬스터 스폰 허용</td></tr><tr><td>container ★★★</td><td>상자/화로/깔대기 등 물체 접근 허용</td></tr><tr><td>craft</td><td>조합대, 인챈트 테이블, 양조기 사용 허용</td></tr><tr><td>​</td><td>​</td></tr><tr><td>day ★★</td><td>부동산을 낮으로 설정</td></tr><tr><td>decay</td><td>부동산 내에서 나뭇잎 부패 허용</td></tr><tr><td>destroy ★★★</td><td>부동산 내 파괴 허용</td></tr><tr><td>diode</td><td>레드스톤 리피터 사용 허용</td></tr><tr><td>door ★★</td><td>문/다락문 사용 허용</td></tr><tr><td>dye</td><td>양 염색 허용</td></tr><tr><td>​</td><td>​</td></tr><tr><td>enchant</td><td>인챈트 테이블 사용 허용</td></tr><tr><td>enderpearl</td><td>엔더 진주 텔레포트 허용</td></tr><tr><td>explode ★★</td><td>폭발 허용</td></tr><tr><td>​</td><td>​</td></tr><tr><td>fireball</td><td>화염구 허용</td></tr><tr><td>firespread</td><td>불 번짐 허용</td></tr><tr><td>flow</td><td>액체 흐름 허용</td></tr><tr><td>flowerpot</td><td>화분 사용 허용</td></tr><tr><td>​</td><td>​</td></tr><tr><td>glow</td><td>부동산 내 플레이어 발광 설정 활성화</td></tr><tr><td>​</td><td>​</td></tr><tr><td>honey</td><td>꿀 채취 허용</td></tr><tr><td>honeycomb</td><td>벌집 조각 채취 허용</td></tr><tr><td>​</td><td>​</td></tr><tr><td>iceform</td><td>얼음 생성 허용/비허용</td></tr><tr><td>icemelt</td><td>얼음이 녹는 것을 허용</td></tr><tr><td>ignite ★★</td><td>불이 붙는 것을 허용</td></tr><tr><td>​</td><td>​</td></tr><tr><td>lava flow ★★</td><td>용암 흐름 허용</td></tr><tr><td>leash</td><td>동물 목줄 사용 허용</td></tr><tr><td>​</td><td>​</td></tr><tr><td>mobkilling</td><td>몬스터 킬 허용</td></tr><tr><td>monsters ★★</td><td>몬스터 스폰</td></tr><tr><td>move ★★</td><td>입장&#x26;움직임 허용</td></tr><tr><td>​</td><td>​</td></tr><tr><td>nametag</td><td>이름표 사용</td></tr><tr><td>nanimals</td><td>자연적 동물 스폰 허용</td></tr><tr><td>night ★★</td><td>밤으로 고정 활성화</td></tr><tr><td>nmonsters</td><td>자연적 몬스터 스폰 허용</td></tr><tr><td>note</td><td>노트 블록 사용 허용</td></tr><tr><td>​</td><td>​</td></tr><tr><td>phantomspawn ★</td><td>팬텀 스폰 허용</td></tr><tr><td>piston</td><td>피스톤 사용 허용</td></tr><tr><td>pistonprotection</td><td>부동산 안/밖으로 피스톤 작동 비활성화</td></tr><tr><td>place ★★★</td><td>블럭 설치 허용 (>build)</td></tr><tr><td>pressure</td><td>압력판/갑압판 사용 허용</td></tr><tr><td>​</td><td>​</td></tr><tr><td>redstone</td><td>button, pressure, lever, note 등 레드스톤 플래그 허용</td></tr><tr><td>riding</td><td>말 타기 허용</td></tr><tr><td>​</td><td>​</td></tr><tr><td>sanimals</td><td>스포너 / 스폰알을 통한 동물 스폰 허용</td></tr><tr><td>shear</td><td>양에게 가위 사용 허용</td></tr><tr><td>shoot</td><td>발사체 사용 허용</td></tr><tr><td>smonsters</td><td>스포너/ 스폰알을 통한 몬스터 스폰 허용</td></tr><tr><td>snowball</td><td>눈덩이 허용</td></tr><tr><td>snowtrail</td><td>눈길 생성 허용</td></tr><tr><td>spread</td><td>(눈,잔디 등) 번짐 허용</td></tr><tr><td>subzone</td><td>서브존 생성 허용</td></tr><tr><td>sun ★★</td><td>날씨를 맑음으로 고정 활성화</td></tr><tr><td>​</td><td>​</td></tr><tr><td>table</td><td>조합대 사용 허용</td></tr><tr><td>tnt</td><td>티엔티 폭발 허용</td></tr><tr><td>trade</td><td>주민 거래 허용</td></tr><tr><td>trample ★★★</td><td>경작지가 일반 흙이 되는 것을 허용</td></tr><tr><td>trusted</td><td>use, container, build, move 권한 허용</td></tr><tr><td>​</td><td>​</td></tr><tr><td>use ★★★</td><td>문, 버튼, 레버, 독서대 등 사용 허용</td></tr><tr><td>​</td><td>​</td></tr><tr><td>vehicledestroy</td><td>카트/보트 등 탈것 부수기 허용</td></tr><tr><td>​</td><td>​</td></tr><tr><td>waterflow ★★</td><td>물 흐름 허용/비허용</td></tr><tr><td>​</td><td>​</td></tr></tbody></table>



## 권한



## 서브존

💡 부동산을 **여러 구역**으로 나누고 **각 구역의** **플래그** **설정을 다르게** 설정할 수 있는 시스템💡 부동산 영역을 잡을 때와 동일한 방법으로 **막대기**로 서브존 영역을 지정한 후

`**/res subzone [서브존명]**` 명령어를 입력하면 서브존으로 설정할 수 있습니다.

`**/res remove [부동산명].[서브존명]**` 명령어를 입력하면 해당 서브존을 삭제합니다. 예시) /res remove 이것은부동산.이것은서브존

\<aside> 💡 서브존 내에서 **플래그 설정**을 하면 해당 **서브존의 플래그 설정**이 바뀝니다. 서브존 내에서 **플레이어에게 권한**을 주면 해당 **서브존 내에만** 적용됩니다.

* 서브존에서만 권한을 주면 **해당 구역만 공용 구역**으로 사용할 수 있습니다.
* 농장을 서브존으로 지정하면 테러 시 농장 외에 다른 구역의 **테러를 방지**할 수 있습니다.
