# 🏃 이동

{% tabs %}
{% tab title="서버 이동" %}
### 서버 이동

<mark style="color:blue;">**Shift + F**</mark> 혹은 <mark style="color:blue;">**/메뉴**</mark> 명령어를 입력 후\
가운데 **지구모양**을 눌러 다른 서버로 이동할 수 있습니다.\
서버↔서버 이동 시에는 <mark style="color:blue;">**3초**</mark>의 지연이 발생되며 움직일 경우 이동이 <mark style="color:red;">**취소**</mark>됩니다.\
\
거주 혹은 자원 서버에서 **/거주** **/광질** 명령어를 입력하여 랜덤 텔레포트를 이용할 경우, \
다음 랜덤 텔레포트까지 <mark style="color:blue;">**3분**</mark>의 쿨타임을 기다려야 합니다. \
<mark style="color:orange;">**자원 서버에서 랜덤 텔레포트를 이용하였다 하더라도 거주 서버에도 동일한 쿨타임이 적용됩니다.**</mark>\
\
바로 이전 장소로 되돌아가고 싶을 때는 <mark style="color:blue;">**/back**</mark> 명령어를 입력할 수 있습니다. \
※ 특수한 기능으로(유저워프 등) 이동한 경우에는 back 기능의 정상적인 인식이 불가합니다.


{% endtab %}

{% tab title="TPA" %}
### 유저 간 이동 (TPA)

<mark style="color:blue;">**/tpa \[닉네임]**</mark> 명령어를 입력하여 해당 유저의 위치로 이동하는 요청을 보낼 수 있습니다. \
<mark style="color:blue;">**/tpahere \[닉네임]**</mark> 명령어를 입력하여 해당 유저에게 본인의 위치로 이동하는 요청을 보낼 수 있습니다.\
위의 요청들은 <mark style="color:blue;">**/y, /ㅇ**</mark> 명령어로 수락하거나, <mark style="color:blue;">**/n, /ㄴ**</mark>명령어로 거절할 수 있습니다.\
또는 채팅창을 열어 **\[수락하기]**, **\[거절하기]** 버튼을 누를 수도 있습니다.\
\
이동 요청 수신을 일시적으로 차단하고 싶을 때는 <mark style="color:blue;">**/tpignore, /텔포토글**</mark> 명령어를 입력하세요.\
차단을 해제할 때도 동일한 명령어를 입력하면 됩니다.


{% endtab %}

{% tab title="홈" %}
### 홈

{% hint style="info" %}
기본적으로 <mark style="color:red;">**1개**</mark>의 홈을 저장할 수 있으며, 유저 [등급](../main-contents/rank.md) 승급을 통해 최대 <mark style="color:blue;">**30개**</mark>까지 늘릴 수 있습니다.
{% endhint %}

{% hint style="warning" %}
한글 이름은 가능하나, 특수 문자를 홈 이름으로 설정할 경우 오류가 발생될 수 있습니다.&#x20;
{% endhint %}

<table><thead><tr><th width="173">명령어</th><th width="516.3333333333333">설명</th></tr></thead><tbody><tr><td><strong>/sethome [홈이름]</strong> <br><strong>/셋홈 [홈이름]</strong></td><td>서있는 위치 기준으 홈을 저장합니다.</td></tr><tr><td><strong>/home [홈이름]</strong> <br><strong>/홈 [홈이름]</strong></td><td>해당 홈으로 이동합니다.</td></tr><tr><td><strong>/delhome [홈이름]</strong> <br><strong>/홈삭제 [홈이름]</strong></td><td>해당 홈을 삭제합니다.</td></tr><tr><td><strong>/homelist</strong><br><strong>/홈목록</strong></td><td>홈 목록 GUI를 엽니다.</td></tr></tbody></table>


{% endtab %}
{% endtabs %}
