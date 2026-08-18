---
helpx_url: "https://helpx.adobe.com/kr/substance-3d-sampler/filters/hdri-tools/nadir-patch.html"
breadcrumb-title: ''
description: Substance 3D Sampler의 Nadir Patch 툴을 사용하여 HDRI 이미지의 기본 영역을 패치하여 매끄러운 환경 맵을 만들 수 있습니다.
helpx_creative_field: ""
helpx_description: Sampler > Filters > HDRI Tools > Nadir Patch
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Nadir Patch
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '381'
ht-degree: 0%

---


# Nadir Patch

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-nadirpatch-18-n-d.png)

**내부:** HDRI 도구

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 설명

환경 조명의 도메인을 패치하여 가공물이나 이음새를 숨깁니다.

아래 이미지에서는 **Nadir Patch**&#x200B;를 사용하여 이 파노라마 이미지에서 카메라 스탠드를 제거하는 방법을 확인할 수 있습니다.

![](../../assets/3d-2d-filters-cropped-0011-nadir-patch-in.jpg)![](../../assets/3d-2d-filters-cropped-0010-nadir-patch-out.jpg)

</td>
</tr>
</table>

## 매개변수

**기본 매개 변수**

* **사용**: 토글\
  패치를 켜거나 끕니다. 이렇게 하면 레이어 가시성을 변경하지 않고도 패치의 영향을 빠르게 확인할 수 있습니다.
* **프레임 도우미 표시**: 전환\
  프레임 스위치를 켜거나 끕니다.
* **프레임 Thickness**: 0-1\
  프레임의 Thickness을 조정합니다. 이 기능은 패치의 원본이 원본과 멀리 떨어져 있을 때 유용합니다.
* **패치 크기**: 0-1\
  패치할 영역의 경계를 조정합니다.
* **패치 크기**:\
  패치의 크기를 조정합니다.
* **패치 회전**: 0-1\
  패치 경계를 회전합니다. 이렇게 하면 소스와 패치 위치가 모두 회전하므로 패치의 방향은 여전히 같습니다. 패치를 제자리에서 회전하려면 **소스 회전 오프셋**&#x200B;을 사용하십시오.
* **패치 Alpha**:\
  패치 마스크에 사용할 모양을 선택합니다. **마스크 입력**&#x200B;을 선택하면 추가 매개 변수가 나타납니다.
  * **마스크 입력**: 이미지/브러시\
    마스크로 사용할 이미지를 가져오거나 **2D 보기**&#x200B;에서 마스크를 직접 페인트합니다.
* **패치 경도**: 0-1\
  패치 마스크의 가장자리에서 흐림 효과를 조정합니다.
* **원본 회전 오프셋**: 0-1\
  소스의 회전을 오프셋합니다. 이렇게 하면 패치가 회전합니다.

## 사용 안내서

사진에서 환경 빛을 만들 때 발생하는 일반적인 문제는 텍스처의 위쪽과 아래쪽 근방에서 발생하는 아티팩트입니다. **Nadir Patch** **필터**&#x200B;를 사용하면 이러한 문제를 최소화할 수 있습니다.

1. 레이어 스택의 맨 위에 **Nadir Patch 필터**&#x200B;를 추가합니다.
1. **2D 보기**&#x200B;의 핸들을 사용하여 패치의 원본 위치를 변경합니다.
   1. 패치된 nadir은 소스의 위치에 따라 변경됩니다. 소스가 텍스처 공간의 아래쪽 절반에 있으면 아래쪽 nadir이 패치되고, 소스가 위쪽 절반에 있으면 위쪽 nadir이 패치됩니다.
1. 매개 변수를 수정하여 솔기와 아티팩트를 가장 잘 숨길 수 있도록 패치 변형을 미세 조정합니다.
