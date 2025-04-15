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

<table><thead><tr><th width="226">플래그</th><th>설명</th></tr></thead><tbody><tr><td>animalkilling</td><td>동물 및 주민 살해</td></tr><tr><td>animals</td><td>동물 스폰</td></tr><tr><td>anvil</td><td>모루 사용</td></tr><tr><td>beacon</td><td>신호기 상호작용</td></tr><tr><td>bed</td><td>침대 사용</td></tr><tr><td>brew</td><td>양조기 사용</td></tr><tr><td>brush</td><td>솔 사용</td></tr><tr><td>build</td><td>블록 설치</td></tr><tr><td>burn</td><td>동물 및 주민 발화</td></tr><tr><td>button</td><td>버튼 사용</td></tr><tr><td>cake</td><td>케이크 섭취</td></tr><tr><td>chat</td><td>부동산 채팅 접속</td></tr><tr><td>chorustp</td><td>후렴과를 사용한 텔레포트</td></tr><tr><td>container</td><td>상자, 화로 및 공급기 접근</td></tr><tr><td>copper</td><td>구리 상태 변화</td></tr><tr><td>day</td><td>항상 낮</td></tr><tr><td>decay</td><td>나뭇잎 부패</td></tr><tr><td>destroy</td><td>블록 파괴</td></tr><tr><td>diode</td><td>레드스톤 중계기 비교기 등 회로 사용</td></tr><tr><td>door</td><td>문 사용</td></tr><tr><td>dye</td><td>양털 염색</td></tr><tr><td>elytra</td><td>겉날개 사용</td></tr><tr><td>enchant</td><td>마법부여대 사용</td></tr><tr><td>enderpearl</td><td>엔더 진주를 사용한 텔레포트</td></tr><tr><td>fireball</td><td>화염구 사용</td></tr><tr><td>flow</td><td>액체류 흐름</td></tr><tr><td>flowerpot</td><td>화분 상호작용</td></tr><tr><td>glow</td><td>유저 발광 효과</td></tr><tr><td>goathorn</td><td>염소 뿔 사용</td></tr><tr><td>harvest</td><td>열매류 수확</td></tr><tr><td>honey</td><td>꿀 채집</td></tr><tr><td>honeycomb</td><td>벌집 조각 채집</td></tr><tr><td>hook</td><td>낚시 바늘에 걸린 대상 당김</td></tr><tr><td>iceform</td><td></td></tr><tr><td>icemelt</td><td></td></tr><tr><td>ignite</td><td></td></tr><tr><td>lavaflow</td><td></td></tr><tr><td>leash</td><td></td></tr><tr><td>lever</td><td></td></tr><tr><td>move</td><td></td></tr><tr><td>nametag</td><td></td></tr><tr><td>nanimals</td><td></td></tr><tr><td>night</td><td></td></tr><tr><td>note</td><td></td></tr><tr><td>piston</td><td></td></tr><tr><td>place</td><td></td></tr><tr><td>pressure</td><td></td></tr><tr><td>pvp</td><td></td></tr><tr><td>riding</td><td></td></tr><tr><td>sanimals</td><td></td></tr><tr><td>shear</td><td></td></tr><tr><td>shoot</td><td></td></tr><tr><td>snowball</td><td></td></tr><tr><td>snowtrail</td><td></td></tr><tr><td>spread</td><td></td></tr><tr><td>subzone</td><td></td></tr><tr><td>sun</td><td></td></tr><tr><td>table</td><td></td></tr><tr><td>trade</td><td></td></tr><tr><td>vehicledestroy</td><td></td></tr><tr><td>waterflow</td><td></td></tr></tbody></table>
