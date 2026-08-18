---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/hdri-tools/exposure-preview.html"
breadcrumb-title: ''
description: 변경 사항을 적용하기 전에 Substance 3D Sampler의 노출 미리 보기 도구를 사용하여 HDRI 이미지의 노출 조정을 미리 볼 수 있습니다.
helpx_creative_field: ""
helpx_description: Sampler > Filters > HDRI Tools > Exposure Preview
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 노출 미리 보기
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '239'
ht-degree: 0%

---


# 노출 미리 보기

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-exposurepreview-18-n-d.png)

**내부:** HDRI 도구

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 설명

**노출 미리 보기** **필터**&#x200B;를 사용하면 노출 값의 스펙트럼을 빠르게 미리 볼 수 있습니다.

아래에서는 **노출 미리 보기 필터**&#x200B;의 기능을 확인할 수 있습니다.

![](../../assets/3d-2d-filters-cropped-0029-exposure-preview-in.jpg)

위의 이미지에서는 환경 조명이 만들어졌으며 HDR 이미지 데이터가 **2D 보기**&#x200B;에 표시됩니다.

![](../../assets/filters-cropped-0028-exposure-preview-out.jpg)

레이어 스택에 **노출 미리 보기** **필터**&#x200B;가 추가되어 다양한 노출에서 환경 빛을 표시하는 새 채널인 환경 진단 을 사용할 수 있습니다.

</td>
</tr>
</table>

## 매개변수

**기본 매개 변수**

* **최소 노출(EV)**: -8~8\
  노출이 가장 적은 이미지의 노출을 설정합니다.
* **최대 노출(EV)**: -8~8\
  가장 많이 노출된 이미지의 노출을 설정합니다.

## 사용 안내서

**노출 미리 보기 필터**&#x200B;는 다른 Sampler 필터와 약간 다르게 작동합니다. 이 도구는 환경 조명에 대한 올바른 노출을 찾는 데 도움이 되는 도구이지만 실제로 환경 채널에 영향을 미치지는 않습니다. 대신 레이어 스택에 **노출 미리 보기 필터**&#x200B;를 추가하면 **2D 보기**(환경 진단 채널)에서 볼 수 있는 추가 채널을 사용할 수 있게 됩니다.

환경 진단 채널을 보는 경우 다양한 노출 값에서 2D 환경 이미지의 몇 가지 인스턴스를 볼 수 있습니다. **노출 미리 보기 필터**&#x200B;의 매개 변수를 조정하여 환경 진단 채널에서 볼 수 있는 노출 범위를 변경합니다.
