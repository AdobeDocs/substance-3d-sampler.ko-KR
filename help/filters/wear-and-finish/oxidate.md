---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/wear-and-finish/oxidate.html"
breadcrumb-title: ''
description: Substance 3D Sampler의 옥시데이트 필터를 사용하면 오래된 외관의 금속 재료에 산화 및 변색 효과를 추가할 수 있습니다.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Oxidate
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 옥시데이트
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '395'
ht-degree: 0%

---


# 옥시데이트

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-oxidate-18-n-d.png)

**내부:** 마모 및 완료

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 설명

재질 상단에 산화 레이어를 추가합니다.*주름진 표면에는&#x200B;**산화 날짜 필터**가 적용되어 있습니다.*

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0019-oxidate-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0018-oxidate-out.jpg){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

## 매개변수

**기본 매개 변수**

* **임의화**:\
  임의식은 이 필터에서 임의성을 사용하는 다른 매개 변수의 임의값을 결정합니다.
* **대상 영역**: 토글\
  산화 효과가 재료에 적용되는 방법을 변경하려면 활성화합니다. 활성화되면 다음 컨트롤이 나타납니다.
  * **대상 영역 강도**: 0-1\
    대상 영역 효과의 스프레드를 조정합니다.
  * **확산**: 0-1\
    산화가 확산되는 거리를 조정합니다.
* **색상**: 색상 선택\
  필터의 기본 색상을 선택합니다. 기본 색상은 산화 효과를 구성하는 모든 색상의 색조를 수정합니다.
* **색상 변형**: 0-1\
  색상 변형 효과의 비율을 조정합니다.
* **밀도**: 0-1\
  효과의 적용 범위 밀도를 변경합니다.
* **가장자리 도련**: 0-1\
  산화 효과의 가장자리가 산화되지 않은 영역으로 들어오는 방식을 수정합니다.
* **패치**: 0-1\
  이는 산화된 영역과 산화되지 않은 영역 사이에서 마스크를 수정하기 위한 별도의 컨트롤이다. 이것을 밀도 및 다른 컨트롤과 결합하여 산화된 영역의 가장자리를 미세 조정합니다.
* **조각**: 0-1\
  산화된 부분을 칩 아웃하여 밑에 있는 재질을 드러냅니다.
* **염색**: 0-1\
  물질 위에 겹쳐 있는 얼룩 양을 조절합니다.
* **부식 거칠음**: 0-1\
  산화된 영역의 거칠기를 조정합니다.
* **부식 금속**: 0-1\
  산화된 영역의 금속 값을 조정합니다.
* **노이즈 강도**: 0-1

**마스크**

* **사용자 지정 마스크 사용**: 전환\
  사용자 정의 마스크 사용을 활성화하거나 비활성화합니다. 활성화하면 다음 매개변수가 나타납니다.
  * **마스크**: 이미지/브러시\
    마스크로 사용할 이미지를 선택하거나 브러시를 사용하여 2D 보기에서 직접 사용자 정의 마스크를 칠합니다.
  * **사용자 지정 마스크 - 흐림 효과**: 0-1\
    마스크를 흐리게 합니다.
  * **사용자 지정 마스크 - 반전**: 전환\
    마스크를 반전합니다.
  * **사용자 지정 마스크 불투명도**: 0-1\
    마스크의 불투명도를 조정합니다.

**기술 매개 변수**

다음 매개 변수를 사용하면 **명도/대비** 또는 **색조/채도**&#x200B;와 같은 조정 레이어를 추가하지 않고 전체 재질의 명명된 값을 조정할 수 있습니다

* **광도**: 0-1
* **대비**: -1 대 1
* **색조 이동**: 0-1
* **채도**: 0-1
* **표준 강도**: 0-1
* **Height 범위**: 0-1
* **Height 위치**: 0-1
* **주변 오클루전 강도**: 0-1
