# 🏠 부동산

### 정보 보기 명령어

|                                 |                                                                |
| ------------------------------- | -------------------------------------------------------------- |
| **/res show, /땅경계**             | 부동산 <mark style="color:blue;">**경계**</mark>를 확인합니다.            |
| **/res list, /땅목록**             | 소유 <mark style="color:blue;">**부동산 목록**</mark>을 확인합니다.         |
| **/res info, /땅정보**             | 해당 부동산의 가치나 권한 <mark style="color:blue;">**정보**</mark>를 확인합니다. |
| **/res sublist \[부동산명] \[페이지]** | 현재 부동산의 <mark style="color:blue;">**서브존 목록**</mark>을 확인합니다.    |

### 부동산 구매 명령어

<table><thead><tr><th width="368"></th><th></th></tr></thead><tbody><tr><td><strong>/res select size</strong><br><strong>/땅가격</strong></td><td>선택한 영역의 부동산 <mark style="color:blue;"><strong>가격</strong></mark>을 확인합니다.<br>1 블록 = <mark style="color:red;"><strong>1원</strong></mark></td></tr><tr><td><strong>/res create [부동산명]</strong><br><strong>/땅구매 [부동산명]</strong></td><td>부동산을 생성합니다.</td></tr><tr><td><strong>/res auto [부동산명] [숫자]</strong><br><strong>/땅범위구매 [부동산명] [숫자]</strong></td><td><mark style="color:blue;"><strong>[숫자]</strong></mark> 만큼 부동산을 생성합니다.</td></tr><tr><td><strong>/res remove [부동산명]</strong><br><strong>/땅삭제 [부동산명]</strong></td><td>부동산을 <mark style="color:red;"><strong>삭제</strong></mark>합니다.<br> (구매가의 <mark style="color:red;"><strong>30%</strong></mark>만 환불)</td></tr><tr><td><strong>/res expand [숫자]</strong><br><strong>/땅확장 [숫자]</strong></td><td>바라보는 방향대로 <mark style="color:blue;"><strong>[숫자]</strong></mark> 만큼 <br>부동산 영역을 <mark style="color:blue;"><strong>확장</strong></mark>합니다.</td></tr><tr><td><strong>/res contract [숫자]</strong><br><strong>/땅축소 [숫자]</strong></td><td>바라보는 방향대로 <mark style="color:blue;"><strong>[숫자]</strong></mark> 만큼 <br>부동산 영역을 <mark style="color:blue;"><strong>축소</strong></mark>합니다.</td></tr><tr><td><strong>/res rename [부동산명] [새이름]</strong><br><strong>/땅새이름 [부동산명] [새이름]</strong></td><td>부동산 이름을 <mark style="color:blue;"><strong>변경</strong></mark>합니다.</td></tr><tr><td><strong>/res message [부동산명] [enter/leave] [할말]</strong><br><strong>/땅메시지 [부동산명] [enter/leave] [할말]</strong></td><td><mark style="color:green;"><strong>enter</strong></mark> 는 부동산에 <mark style="color:green;"><strong>입장</strong></mark>할 때 메시지, <br><mark style="color:red;"><strong>leave</strong></mark> 는 <mark style="color:red;"><strong>퇴장</strong></mark>할 때 메시지를 설정합니다.</td></tr><tr><td><strong>/res message [부동산명] remove [enter/leave]</strong></td><td>부동산 입퇴장 메시지를 <mark style="color:red;"><strong>제거</strong></mark>합니다.</td></tr><tr><td><strong>/res give [부동산명] [닉네임]</strong><br><strong>/땅주기 [부동산명] [닉네임]</strong><br><strong>/땅양도 [부동산명] [닉네임]</strong></td><td>해당 유저에게 부동산 주인을 <mark style="color:blue;"><strong>양도</strong></mark>합니다.</td></tr></tbody></table>

### 영역 설정 (고급편)

* **/res select \[x y z]** \
  – 예시로 **/res select 5 5 5** 명령어를 입력하면,  \
  – 본인을 기준으로 **상/하/좌/우** 각각 <mark style="color:purple;">**5블록**</mark>씩 선택되어서  \
  – <mark style="color:purple;">**직육면체**</mark> 모양으로 부동산 영역을 선택하게 됩니다.\
  – 반드시 x, y, z 세 자리에 숫자를 모두 입력해야 합니다!
* **/res select chunk** \
  – 본인이 위치해 있는 **청크 경계선** 만큼 부동산 영역을 선택합니다.\
  – 청크 경계선 확인은 키보드에서 <mark style="color:purple;">**F3+G 키**</mark>를 누르세요.
* **/res select \[부동산명]** – **부동산**의 전체크기만큼 영역을 선택합니다.
* **/res select shift \[숫자]** – 바라보는 방향대로 선택 영역을 **축소**합니다.
* **/res select expand \[숫자]** – 바라보는 방향대로 선택 영역을 **확장**합니다.
* **/res select vert** – 선택한 영역에서 **y좌표** 범위를 **위+아래** 최대로 확장합니다.
* **/res select sky** – 선택한 영역에서 **y좌표** 범위를 **하늘 끝**까지 최대로 확장합니다.
* **/res select bedrock** – 선택한 영역에서 **y좌표** 범위를 **기반암** 지점까지 최대로 확장합니다.

### 장기 미접속 부동산

* 장기 미접속 부동산에 관련된 내용은 [여기](./#undefined-4) 를 눌러 확인해 주세요.
