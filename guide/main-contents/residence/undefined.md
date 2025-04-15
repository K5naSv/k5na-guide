# 권한 및 플래그 설정 (수정중)

## 플레이어 권한

|                                                   |                    |   |
| ------------------------------------------------- | ------------------ | - |
| <p>/res padd [닉네임]<br>/권한주기 [닉네임]</p>             | 해당 플레이어에게 부동산 권한주기 |   |
| <p>/res pdel [닉네임]<br>/권한뺏기 [닉네임]</p>             | 해당 플레이어에게 부동산 권한뻇기 |   |
| /res pset \[닉네임] \[권한] \[true/false/remove]       |                    |   |
| **/res check \[residence] \[flag] (playername)**  |                    |   |
| /플래그알바추가 \[닉네임]                                   |                    |   |
| /플래그알바제거 \[닉네임]                                   |                    |   |

### 플래그

{% hint style="info" %}
**플래그란?** 부동산 내에서 어떠한 행동에 대한 **True**(t), **False**(f), **Remove**(r) 값을 **세부적으로** 설정하는 시스템
{% endhint %}

<table data-header-hidden><thead><tr><th width="243.33333333333331"></th><th width="303"></th><th>예시</th></tr></thead><tbody><tr><td>/플래그설정, /res set</td><td>플래그 GUI 열기</td><td></td></tr><tr><td>/플래그무브허용</td><td>부동산 내 다른 플레이어 입장 허용</td><td>​</td></tr><tr><td>/플래그무브비허용</td><td>부동산 내 다른 플레이어 입장 비허용</td><td>​</td></tr><tr><td>/res set [플래그] [t/f/r]</td><td>[플래그] 설정값 변경</td><td>/res set day t</td></tr><tr><td></td><td>​</td><td>​(항상 낮으로 설정)</td></tr><tr><td>/res default [residence]</td><td>플래그 설정 초기화</td><td></td></tr></tbody></table>

<table><thead><tr><th width="226">플래그</th><th>설명</th></tr></thead><tbody><tr><td><strong>도축</strong> animalkilling ★★★</td><td>동물 및 주민 살해</td></tr><tr><td><strong>동물스폰</strong> animals</td><td>동물 스폰</td></tr><tr><td><strong>모루</strong> anvil</td><td>모루 사용</td></tr><tr><td><strong>신호기</strong> beacon</td><td>신호기 상호작용</td></tr><tr><td><strong>수면</strong> bed</td><td>침대 사용</td></tr><tr><td><strong>양조</strong> brew</td><td>양조기 사용</td></tr><tr><td><strong>솔질</strong> brush</td><td>솔 사용</td></tr><tr><td><strong>건축</strong> build ★★★</td><td>블록 설치</td></tr><tr><td><strong>발화</strong> burn</td><td>동물 및 주민 발화</td></tr><tr><td><strong>버튼</strong> button ★</td><td>버튼 사용</td></tr><tr><td><strong>케이크</strong> cake</td><td>케이크 섭취</td></tr><tr><td><strong>채팅</strong> chat</td><td>부동산 채팅 접속</td></tr><tr><td><strong>후렴과</strong> chorustp</td><td>후렴과를 사용한 텔레포트</td></tr><tr><td>container ★★★</td><td>상자, 화로 및 공급기 접근</td></tr><tr><td>copper</td><td>구리 상태 변화</td></tr><tr><td>day</td><td>항상 낮</td></tr><tr><td>decay</td><td>나뭇잎 부패</td></tr><tr><td>destroy ★★★</td><td>블록 파괴</td></tr><tr><td>diode</td><td>레드스톤 중계기 비교기 등 회로 사용</td></tr><tr><td>door</td><td>문 사용</td></tr><tr><td>dye</td><td>양털 염색</td></tr><tr><td>elytra</td><td>겉날개 사용</td></tr><tr><td>enchant</td><td>마법부여대 사용</td></tr><tr><td>enderpearl</td><td>엔더 진주를 사용한 텔레포트</td></tr><tr><td>fireball</td><td>화염구 사용</td></tr><tr><td>flow</td><td>액체류 흐름</td></tr><tr><td>flowerpot</td><td>화분 상호작용</td></tr><tr><td>glow</td><td>유저 발광 효과</td></tr><tr><td>goathorn</td><td>염소 뿔 사용</td></tr><tr><td>harvest</td><td>열매류 수확</td></tr><tr><td>honey</td><td>꿀 채집</td></tr><tr><td>honeycomb</td><td>벌집 조각 채집</td></tr><tr><td>hook</td><td>낚시 바늘에 걸린 대상 당김</td></tr><tr><td>iceform</td><td>얼음 생성</td></tr><tr><td>icemelt</td><td>얼음 해동</td></tr><tr><td>ignite</td><td>부싯돌과 부시를 사용한 방화</td></tr><tr><td>lavaflow</td><td>용암 흐름</td></tr><tr><td>leash</td><td>끈 사용</td></tr><tr><td>lever ★</td><td>레버 사용</td></tr><tr><td>move</td><td>부동산 접근</td></tr><tr><td>nametag</td><td>이름표 사용</td></tr><tr><td>nanimals</td><td>동물 스폰</td></tr><tr><td>night</td><td>항상 밤</td></tr><tr><td>note</td><td>소리 블록 사용</td></tr><tr><td>piston</td><td>피스톤 사용</td></tr><tr><td>place ★★★</td><td>블록 설치</td></tr><tr><td>pressure</td><td>압력판 사용</td></tr><tr><td>pvp</td><td>유저간 전투</td></tr><tr><td>riding</td><td>동물 탑승</td></tr><tr><td>sanimals</td><td>동물 생성 알 사용</td></tr><tr><td>shear</td><td>양털 깎기</td></tr><tr><td>shoot</td><td>발사체 아이템 사용</td></tr><tr><td>snowball</td><td>눈덩이 던지기</td></tr><tr><td>snowtrail</td><td>눈사람 밑에 눈 쌓이기</td></tr><tr><td>spread</td><td>잔디 번짐</td></tr><tr><td>subzone</td><td>서브존 권한</td></tr><tr><td>sun</td><td>항상 날씨 맑음</td></tr><tr><td>table</td><td>제작대 사용</td></tr><tr><td>trade</td><td>주민 거래</td></tr><tr><td>vehicledestroy ★</td><td>탑승물 파괴</td></tr><tr><td>waterflow</td><td>물 흐름</td></tr></tbody></table>
