# 💬 채팅

<table data-full-width="false"><thead><tr><th width="272">명령어</th><th>설명</th></tr></thead><tbody><tr><td><strong>/act , /ㅁㅊㅅ</strong></td><td>지역채팅 기능을 끄고 켭니다.<br>반경 <mark style="color:blue;"><strong>50블록</strong></mark> 내의 사람들과 대화할 수 있습니다.</td></tr><tr><td>​<strong>/ac [할말]</strong></td><td>​지역채팅 토글없이<br>메시지를 지역채팅에 바로 전송합니다.</td></tr><tr><td><strong>/msg [닉네임] [할말]</strong></td><td>해당 유저에게 귓속말을 보냅니다.</td></tr><tr><td><strong>/r [할말]</strong></td><td>가장 최근에 도착한 귓속말에 대해 빠르게 답장합니다.</td></tr><tr><td><strong>/mail send [닉네임] [할말]</strong><br><strong>/쪽지전송 [닉네임] [할말]</strong></td><td>온/오프라인 유저에게 쪽지를 보냅니다.</td></tr><tr><td><strong>/mail, /쪽지</strong></td><td>쪽지함을 확인합니다.<br>쪽지함에서 <mark style="color:red;"><strong>x</strong></mark> 표시를 눌러 개별 삭제가 가능합니다.</td></tr><tr><td><strong>/쪽지비우기</strong></td><td>쪽지함에 있는 모든 쪽지를 삭제합니다.</td></tr><tr><td><strong>/광고 [할말]</strong></td><td><mark style="color:blue;"><strong>500원</strong></mark>을 소모하여 전체 서버에 광고를 게시합니다. (3분 쿨타임)</td></tr><tr><td>[item] 또는 <strong>##</strong></td><td>손에 든 아이템을 채팅창에 자랑합니다.</td></tr></tbody></table>



## 🏠 부동산 채팅 <a href="#reschat" id="reschat"></a>

{% hint style="info" %}
#### 부동산 내에서 <mark style="color:blue;">**/rc**</mark> 또는 <mark style="color:blue;">/res rc \[부동산]</mark> 명령어를 입력하여 해당 부동산 채팅에 입장할 수 있습니다.&#x20;
{% endhint %}

{% hint style="warning" %}
부동산 채팅에 입장하려면 해당 부동산의 <mark style="color:blue;">**채팅(chat)**</mark> 플래그 권한이 필요합니다.
{% endhint %}

{% hint style="warning" %}
부동산 채팅에 입장하려면 <mark style="color:blue;">**거주 서버**</mark> 내에 있어야 합니다.
{% endhint %}

<table><thead><tr><th width="269">명령어</th><th>설명</th></tr></thead><tbody><tr><td><strong>/res rc leave</strong></td><td>부동산 채팅에서 퇴장합니다.</td></tr><tr><td><strong>/res rc setcolor [색코드]</strong> </td><td>부동산 채팅 색상을 [색코드] 로 지정합니다.</td></tr><tr><td><strong>/res rc setprefix [이름]</strong></td><td>부동산 채팅 칭호를 [이름] 으로 지정합니다.</td></tr><tr><td><strong>/res rc kick [닉네임]</strong> </td><td>부동산 채팅에서 해당 유저를 강제퇴장 합니다.</td></tr></tbody></table>

![](<../../.gitbook/assets/image (12) (1).png>)

## 🗨️한글 채팅

{% hint style="info" %}
/engtokor toggle 또는 /engtokor 전환 으로 한글 채팅 기능을 키거나 끌 수 있습니다.
{% endhint %}

* 플레이어 닉네임은 변환되지 않습니다 (해당   플레이어가접속중일때)
* \[ENG] 또는 ./ 로 시작되는 문장은 변환이 되지 않습니다.
* `` ` ``  로 시작되는 단어는 변환되지 않습니다

#### 예시

```yaml
./abcd abc -> ./abcd abc
`hello there! -> `hello there!
dkssudgktpdy`hello` -> 안녕하세요 `hello`
D0_REMI sla djeldlTdjdy? -> D0_REMI 님 어디있어요?
```

