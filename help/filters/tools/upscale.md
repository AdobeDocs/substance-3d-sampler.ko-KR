---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/upscale.html"
breadcrumb-title: ''
description: Substance 3D Sampler의 [크기 조절] 도구를 사용하여 AI 기반 크기 조절 기술을 사용하여 텍스처 해상도를 높입니다.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 확장
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '198'
ht-degree: 2%

---


# 확장

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![필터 아이콘](../../assets/SAPR_SuperResolution_18_N_D.png)

**내부:** 도구

</td>
<td style="border: 0;" valign="top">

## 설명

<b>업스케일 </b>필터는 AI를 사용하여 아래 레이어의 PBR 채널(BaseColor, Roughness, Normal, Metallic, Height)을 업샘플링합니다.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">



</td>
<td style="border: 0;" valign="top">

![](../../assets/F5W_vAHaYAQLsz7.jpg)

</td>
</tr>
</table>

이 예제에서는 1024x1024px 이미지로 시작하지만 출력 결과는 4098x4098px입니다. <b>Upscale</b> 필터를 사용하는 결과를 더 정의합니다.

</td>
<td style="border: 0;" valign="top">

>[!NOTE]
>
> **고급 필터**
> 
> <b>Upscale</b>은 고급 필터입니다.\
> 최대 용량에서 사용하고 흐릿한 결과를 피하려면 [레이어 입력 최대] 또는 [레이어 입력 최소]에서 레이어를 <b>확대</b> 이하로 설정하는 것이 좋습니다.
> 
> 사용할 수 있는 <b>업스케일 </b>필터의 수에는 제한이 없지만 8k 해상도를 초과하는 업샘플링은 성능에 상당한 영향을 줄 수 있습니다.

</td>
</tr>
</table>

## 매개변수

<b>기본 매개 변수</b>

* <b>샘플 위로</b>: 단추 그룹 전환\
  확대할 곱하기 요소 선택

## 방법

![](../../assets/SAPR_Upscale_screen_001.png)

위의 이미지에서 저해상도 이미지는 [Image to Material(AI 작동)](image-to-material.md)에 의해 처리됩니다.

![](../../assets/SAPR_Upscale_Screen_003.png)

<b>확대</b> 필터가 추가되어 결과를 샘플링합니다. 재질의 품질을 유지하면서 더 높은 해상도에 도달하기 위해 세부 사항을 정제합니다. 업샘플링할 속성에서 2 또는 4를 선택할 수 있습니다.
