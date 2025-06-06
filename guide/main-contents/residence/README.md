# 🏠 부동산

## 명령어

### 정보 보기

|                             |                      |
| --------------------------- | -------------------- |
| /res show, /땅표시             | 현재 서 있는 부동산 경계 보기    |
| /res info, /땅정보             | 해당 부동산의 가치나 권한 정보 확인 |
| /res list, /땅목록             | 소유 부동산 목록 보기         |
| /res sublist \[부동산명] \[페이지] | 현재 부동산의 서브존 목록 보기    |

### 부동산 구매

<table><thead><tr><th width="360"></th><th></th></tr></thead><tbody><tr><td>/res create [부동산명]<br>/땅구매 [부동산명]</td><td>부동산 생성</td></tr><tr><td>/res auto [부동산명] [숫자]<br>/땅범위구매 [부동산명] [숫자]</td><td>[숫자] 만큼 부동산 영역 생성</td></tr><tr><td>/res select size<br>/땅가격</td><td>선택한 영역의 부동산 가격 확인<br>1 블록 = <mark style="color:red;"><strong>1원</strong></mark></td></tr><tr><td>/res remove [부동산명]<br>/땅삭제 [부동산명]</td><td>부동산 삭제 (구매가의 <mark style="color:red;"><strong>30%</strong></mark>만 환불)</td></tr><tr><td>/res expand [숫자]<br>/땅확장 [숫자]</td><td>바라보는 방향대로 [숫자] 만큼 부동산 영역 <strong>확장</strong></td></tr><tr><td>/res contract [숫자]<br>/땅축소 [숫자]</td><td>바라보는 방향대로 [숫자] 만큼 부동산 영역 <strong>축소</strong></td></tr><tr><td>/res set<br>/땅설정</td><td>부동산 전체에 <mark style="color:purple;">플래그(땅권한)</mark> 설정</td></tr><tr><td>/res pset [닉네임] <br>/땅유저설정 [닉네임]</td><td>해당 유저에게 <mark style="color:purple;">플래그(땅권한)</mark> 설정</td></tr><tr><td>/res rename [부동산명] [새이름]<br>/땅새이름 [부동산명] [새이름]</td><td>부동산 이름 변경</td></tr><tr><td>/res message [부동산명] [enter/leave] [할말]<br>/땅메시지 [부동산명] [enter/leave] [할말]</td><td><mark style="color:green;"><strong>enter</strong></mark> 는 부동산에 <mark style="color:green;"><strong>입장</strong></mark>할 때 메시지, <br><mark style="color:red;"><strong>leave</strong></mark> 는 <mark style="color:red;"><strong>퇴장</strong></mark>할 때 메시지를 설정합니다.</td></tr><tr><td>/res message [부동산명] remove [enter/leave]</td><td>부동산 입퇴장 메시지 제거</td></tr><tr><td>/res give [부동산명] [닉네임]<br>/땅주기 [부동산명] [닉네임]<br>/땅양도 [부동산명] [닉네임]</td><td>해당 플레이어에게 부동산 양도</td></tr></tbody></table>

### 영역 설정 (고급편)

* **/res select \[x y z]** \
  – 예시로 **/res select 5 5 5** 명령어를 입력하면,  \
  – 본인을 기준으로 **상/하/좌/우** 각각 <mark style="color:purple;">**5블록**</mark>씩 선택되어서  \
  – <mark style="color:purple;">**직육면체**</mark> 모양으로 부동산 영역을 선택하게 됩니다.\
  – 반드시 x, y, z 세 자리에 숫자를 모두 입력해야 합니다!
* **/res select chunk** \
  – 본인이 위치해 있는 **청크 경계선** 만큼 부동산 영역을 선택합니다.\
  – 청크 경계선 확인은 키보드에서 <mark style="color:purple;">**F3+G 키**</mark>를 누르세요.
* **/res select \[부동산명]** – **부동산**의 크기만큼 영역을 선택합니다.
* **/res select shift \[숫자]** – 바라보는 방향대로 선택 영역을 **축소**합니다.
* **/res select expand \[숫자]** – 바라보는 방향대로 선택 영역을 **확장**합니다.
* **/res select vert** – 선택한 영역에서 **y좌표** 범위를 **위+아래** 최대로 확장합니다.
* **/res select sky** – 선택한 영역에서 **y좌표** 범위를 **하늘 끝**까지 최대로 확장합니다.
* **/res select bedrock** – 선택한 영역에서 **y좌표** 범위를 **기반암** 지점까지 최대로 확장합니다.

### 장기 미접속 부동산

* 장기 미접속 부동산에 관련된 내용은 [여기](./#undefined-4) 를 눌러 확인해 주세요.
