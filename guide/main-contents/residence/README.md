# 🏠 부동산

## 명령어

### 정보 보기

|                               |                      |
| ----------------------------- | -------------------- |
| /res show                     | 현재 서 있는 부동산 경계 보기    |
| /res info                     | 해당 부동산의 가치나 권한 정보 확인 |
| /res list                     | 소유 부동산 목록 보기         |
| /res sublist \[부동산 이름] \[페이지] | 현재 부동산의 서브존 목록 보기    |

### 부동산 구매

|                                                     |                                       |
| --------------------------------------------------- | ------------------------------------- |
| /땅구매 \[부동산 이름] \[크기]                                |                                       |
| /땅가격                                                | <p>선택한 영역의 부동산 가격 확인<br>1 블록 = 1원</p> |
| /res create \[부동산 이름]                               |                                       |
| <p>/res remove [부동산명]<br>/땅삭제 [부동산명]</p>            | 부동산 삭제 (구매가의 30%만 환불)                 |
| <p>/res expand [숫자]<br>/땅선택확장 [숫자]</p>              | 바라보는 방향으로 \[숫자]만큼 부동산 확장              |
| **/res contract \[amount]**                         |                                       |
|                                                     |                                       |
| /res rename \[부동산명] \[새이름]                          | 부동산 이름 변경                             |
| /res give \[부동산명] \[닉네임]                            | 해당 플레이어에게 부동산 양도                      |
| <p>/res message [부동산 이름] [enter/leave]<br>[할말]</p>  |                                       |
| /**res message \[residence] remove \[enter/leave]** |                                       |

### 영역 설정 (고급편) (수정중)

* **/res select \[x y z]** – select a cuboid area to protect, using either the selection tool (wooden axe by default) or specifying X, Y, and Z as a distance on those axes from the center point where you are standing (“10 5 10” would select an area 21 wide x 11 high x 21 long.
* **/res select chunk** – Select a whole chunk for protection.
* **/res select auto \[playername]** – Turns on auto selection tool
* **/res select expand \[amount]** – Expand selection in direction your looking.
* **/res select size** – show selected area size
* **/res select shift \[amount]** – Shift selection in direction your looking.
* **/res select vert** – expand selection from sky to bedrock
* **/res select worldedit** – use an area defined by WorldEdit

### 장기 미접속 부동산

* 장기 미접속 부동산에 관련된 내용은 [여기](./#undefined-4) 를 눌려 확인해주세요
