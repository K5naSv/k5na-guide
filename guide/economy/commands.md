# 💰 경제 명령어

<table><thead><tr><th width="272">명령어</th><th>설명</th></tr></thead><tbody><tr><td><strong>/pay [닉네임] [금액]</strong><br><strong>/지불 [닉네임] [금액]</strong></td><td>해당 유저에게 <mark style="color:blue;"><strong>[금액]</strong></mark> 만큼 송금합니다.</td></tr><tr><td><strong>/돈, /ehs</strong></td><td>본인 소지금을 확인합니다.</td></tr><tr><td><strong>/trade, /거래</strong></td><td>1:1 거래 관련 도움말을 확인합니다.</td></tr><tr><td><strong>/trade offer [닉네임]</strong><br><strong>/거래제안 [닉네임]</strong></td><td>해당 유저에게 1:1 거래 제안을 보냅니다.</td></tr><tr><td><strong>/trade accept</strong><br><strong>/거래수락</strong></td><td>1:1 거래 제안을 <mark style="color:green;"><strong>수락</strong></mark>합니다. </td></tr><tr><td><strong>/trade deny [닉네임]</strong><br><strong>/거래거절</strong></td><td>해당 유저에게서 온 1:1 거래 제안을 <mark style="color:red;"><strong>거절</strong></mark>합니다.</td></tr><tr><td><strong>/trade block [닉네임]</strong><br><strong>/거래차단</strong></td><td>해당 유저의 1:1 거래 제안을 <mark style="color:red;"><strong>차단</strong></mark>합니다.</td></tr><tr><td><strong>/trade toggle</strong><br><strong>/거래토글</strong></td><td>1:1 거래 제안 받기 기능을 끄거나 켭니다.</td></tr><tr><td><strong>/trade history</strong><br><strong>/거래내역</strong></td><td>1:1 거래 내역을 확인합니다.</td></tr></tbody></table>



### 💸 돈 랜덤지급

{% hint style="info" %}
접속 중인 유저들에게 나의 소지금을랜덤으로 나눠주어 멋짐✨을 뽐내는 기능입니다. (거주 서버만 가능)
{% endhint %}

1. **균등분배**&#x20;

* <mark style="color:blue;">**/지불 랜덤지급 균등분배 \[금액] \[분배인원]**</mark>
* &#x20;\[분배인원]에게 1/N으로 돈을 지급합니다.\
  예시) /지불 랜덤지급 균등분배 10000 5 -> 5명에게 2000원씩 지급

2. **클릭지급** (선착순)

* <mark style="color:blue;">**/지불 랜덤지급 클릭지급 \[금액] \[분배인원]**</mark>
* 메세지를 클릭한 유저에게 랜덤으로 지급합니다.\
  (금액은 랜덤이며, 꽝도 있고, 한번만 받을 수 있습니다.)

<mark style="color:blue;">**\[분배인원]**</mark> 미입력 시 서버 **전체인원**으로 설정됩니다.
