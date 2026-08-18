---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/wear-and-finish/corrode.html"
breadcrumb-title: ''
description: Substance 3D Sampler의 Corrode 필터를 사용하여 금속 재료에 부식 및 화학적 열화 효과를 추가할 수 있습니다.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Corrode
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 부식성
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '370'
ht-degree: 0%

---


# 부식성

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/corrode-filter-icon.png)

**내부:** 마모 및 완료

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 설명

부식된 필터는 당신의 재료에 산이 스며들어 구멍과 표면의 손상을 남기는 효과를 모방합니다.

</td>
</tr>
</table>

## 매개변수

**기본 매개 변수**

* **임의화**:\
  임의식은 이 필터에서 임의성을 사용하는 다른 매개 변수의 임의값을 결정합니다.
* **영향을 받는 영역**:\
  서피스 곡률이 필터 효과에 미치는 영향을 선택합니다.
* **천공 수준**: 0-1\
  생성된 구멍 수를 조정합니다.
* **곡률 위치**: 0-1\
  영향을 받을 곡률 범위를 수정합니다.
* **곡률 매끄럽게**: 0-1\
  곡률 맵을 부드럽게 합니다.
* **손상 거리**: 0-1\
  부식 영역 주위의 손상 반경을 제어합니다.
* **손상 강도**: 0-1\
  영향을 받는 영역의 손상 정도를 조정합니다.
* **Height 강도**: 0-1\
  Height 맵이 손상되는 영향을 제어합니다.
* **돌출 위치**: 토글\
  Height 맵에서 손상 방향을 전환합니다. 비활성화하면 손상이 표면에 스며들고 활성화하면 손상이 표면에서 바깥쪽으로 형성됩니다.

**마스크**

* **사용자 지정 마스크 사용**: 전환\
  사용자 정의 마스크 사용을 활성화하거나 비활성화합니다. 활성화하면 다음 매개변수가 나타납니다.
  * **마스크**: 이미지/브러시\
    마스크로 사용할 이미지를 선택하거나 브러시를 사용하여 2D 보기에서 직접 사용자 정의 마스크를 칠합니다.
  * **사용자 지정 마스크 - 흐림 효과**: 0-1\
    마스크를 흐리게 합니다.
  * **사용자 지정 마스크 - 반전**: 전환\
    마스크를 반전합니다.

**고급 매개 변수**

일부 고급 매개 변수는 이 필터로 수정된 영역에만 영향을 주지 않고 전체 재질에 영향을 줍니다.

* **광도**: 0-1\
  전체 재질의 광도 또는 밝기를 조정합니다.
* **대비**: -1 대 1\
  전체 재질에 대한 알베도 대비를 조정합니다.
* **색조 이동**: 0-1\
  전체 재질에 있는 색상의 색조 값을 오프셋합니다.
* **채도**: 0-1\
  전체 재질의 채도를 조정합니다.
* **표준 강도**: 0-1\
  **부식 필터**&#x200B;의 영향을 받은 표준 지도의 강도를 조정합니다.
* **Height 범위**: 0-1\
  전체 재질에 대한 Height 맵의 값 범위를 늘립니다.
* **Height 위치**: 0-1\
  전체 재질의 Height을 오프셋합니다.
* **주변 오클루전 강도**: 0-1\
  **부식성 필터**&#x200B;로 인한 AO 충격의 강도를 조정합니다.
