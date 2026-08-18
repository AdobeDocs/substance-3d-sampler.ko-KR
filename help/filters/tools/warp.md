---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/warp.html"
breadcrumb-title: ''
description: Substance 3D Sampler의 뒤틀기 도구를 사용하여 텍스처 및 재질 레이어에 방향 뒤틀기 및 왜곡 효과를 적용합니다.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Warp
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 뒤틀기
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '269'
ht-degree: 1%

---


# 뒤틀기

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-warp-18-n-d.png)

**내부:** 도구

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 설명

**뒤틀기 필터**&#x200B;를 사용하면 생성된 노이즈의 수에 따라 재질을 뒤틀 수 있습니다.

</td>
</tr>
</table>

## 매개변수

**기본 매개 변수**

* **임의화**:\
  임의식은 이 필터에서 임의성을 사용하는 다른 매개 변수의 임의값을 결정합니다.
* **노이즈 선택**:\
  뒤틀기의 기준으로 사용할 노이즈를 선택합니다. 노이즈가 다르면 효과가 달라질 수 있습니다.
* **노이즈 비율**: 0-10\
  소스 노이즈의 비율을 조정합니다. 노이즈는 항상 바둑판식으로 표시됩니다.
* **유형**:\
  재질을 뒤트는 데 사용할 방법을 선택합니다. **방향 뒤틀기** 또는 **다중 방향 뒤틀기**&#x200B;를 선택하면 추가 매개 변수가 나타납니다.
  * **뒤틀기 각도**: 0-1\
    뒤틀기가 발생하는 방향 조정
* **강도**: 0-1\
  뒤틀기의 강도를 조정합니다.
* **사용자 지정 노이즈**: 토글\
  **노이즈 선택**&#x200B;에서 선택 항목 대신 사용자 지정 노이즈를 사용하도록 설정합니다. 사용 가능한 매개 변수는 **사용자 지정 노이즈**&#x200B;의 사용 여부를 기준으로 변경됩니다. 활성화하면 다음 매개 변수가 나타납니다.
  * **사용자 지정 노이즈 흐림 효과**: 0-1\
    사용자 정의 노이즈 흐리게 하기
  * **사용자 지정 노이즈**: 이미지/브러시\
    뒤틀기 소스로 사용할 사용자 정의 노이즈 맵을 가져옵니다.
* **채널당 뒤틀기**: 전환\
  활성화되면 각 채널의 뒤틀기를 독립적으로 제어하는 추가 섹션이 나타납니다. 각 채널에 대해 다음 매개 변수를 사용할 수 있습니다.
  * ***채널 이름***: 전환\
    이 채널이 **비틀기 필터**&#x200B;의 영향을 받는지 여부를 전환합니다.
  * **혼합 모드**:\
    이 채널에 대한 뒤틀기 결과가 기본 레이어와 혼합되는 방법을 선택합니다
  * **불투명도**: 0-1\
    이 채널에 대한 필터 결과의 불투명도를 변경합니다.
