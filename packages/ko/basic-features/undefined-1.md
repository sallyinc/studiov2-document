---
description: 조건을 충족하면 자동으로 발동하는 액션을 설정할 수 있습니다.
---

# 트리거

## 트리거 새로 만들기

트리거는 왼쪽 위의 ♦ 마크에서 새로 만듭니다.

<figure><img src="../.gitbook/assets/01 (62).png" alt="" width="563"><figcaption></figcaption></figure>

「＋새 트리거」를 클릭하고, 「무슨 일이 일어나면(발동 조건)」과 「어떻게 되었으면 하는지(결과 액션)」를 설정합니다.

아래 예시는 캐릭터 텍스트 읽기가 시작될 때 전원을 자동으로 음소거하는 트리거입니다.

<figure><img src="../.gitbook/assets/02 (49).png" alt="" width="563"><figcaption></figcaption></figure>

※자동으로 발동하는 것이 아니라 **누군가가 버튼을 누른 뒤에 발동**하게 하고 싶다면, [액션](https://docs.studio.uzu-app.com/ko/basic-features/action)으로 설정해 주세요.

## 트리거 활용 예시

### **단계가 시작될 때 자동으로 음소거하기** <a href="#ex-mute" id="ex-mute"></a>

**텍스트 읽기 단계, 투표 단계, 추리 발표 단계** 등에서 활용할 수 있습니다. 음소거로 바뀐 것을 플레이어가 알아차리기 어려우므로, **「알림 보내기」나 「SE 재생」** **등도 함께 설정해 두는 것**을 추천합니다.

※음소거를 자동으로 해제하는 기능은 없습니다. 사정이 있어 음소거해 둔 상태에서 음소거가 자동으로 풀려 버리는 문제를 막기 위해서입니다.

<figure><img src="../.gitbook/assets/03 (40).png" alt="" width="563"><figcaption></figcaption></figure>

### **특정 단계로 강제 전환하기** <a href="#ex-phase" id="ex-phase"></a>

아래는 **특정 단서가 공개**되면 해당하는 **함께 읽기 단계로 강제 전환**하도록 설정한 예시입니다. 단서가 공개되는 순간 바로 전환되면 단서를 읽을 시간이 없으므로, **몇 초 지연시켜 발동하게 하는 것**을 추천합니다.

<figure><img src="../.gitbook/assets/04 (31).png" alt="" width="563"><figcaption></figcaption></figure>

### **단계가 시작되고 몇 분 뒤에 무언가를 일으키기** <a href="#ex-delay" id="ex-delay"></a>

아래는 토론이 시작되고 5분 뒤에 목표를 업데이트하고, 10분 뒤에 조사 토큰을 1장 추가하도록 설정한 예시입니다.

그 밖에도 「토론 시작 ○분 뒤에 추가 정보 공개」, 「밀담 시작 ○분 뒤에 추가 더미를 조사할 수 있게 됨」, 「최종 토론 시작 ○분 뒤에 BGM 변경」 같은 설정을 할 수 있습니다.

<figure><img src="../.gitbook/assets/05 (25).png" alt="" width="563"><figcaption></figcaption></figure>
