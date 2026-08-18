---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/hdri-tools/hdr-merge.html"
breadcrumb-title: ''
description: Substance 3D Sampler의 HDR 병합 도구를 사용하여 여러 노출 이미지를 단일 High Dynamic Range 이미지로 병합합니다.
helpx_creative_field: ""
helpx_description: Sampler > Filters > HDRI Tools > HDR Merge
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: HDR 병합
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '249'
ht-degree: 2%

---


# HDR 병합

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/S_HDRMerge_18_N_D.png)

**내부:** HDRI 도구

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 설명

**HDR 병합** **필터**&#x200B;를 사용하면 SDR(표준 동적 범위) 이미지 컬렉션을 병합하여 HDR 이미지를 만들 수 있습니다.

아래 이미지는 **HDR 병합**&#x200B;의 결과를 보여 줍니다.

![](../../assets/3d-2d-filters-cropped-0027-hdr-merge-in.jpg)

**HDR 병합**&#x200B;이 완료되기 전에 **3D 보기**&#x200B;의 구가 기본 환경 조명을 반사합니다. **2D 보기**&#x200B;는 기본적으로 첫 번째 스캔 이미지에 대해 가져온 이미지 데이터를 표시하며, 이 경우 가장 낮은 노출 이미지입니다.

![](../../assets/3d-2d-filters-cropped-0026-hdr-merge-out.jpg)

**HDR 병합** **필터**&#x200B;이 추가되면 구는 입력 이미지에서 생성된 HDR 이미지인 새 환경 조명을 반사합니다.

</td>
</tr>
</table>

## 매개 변수

**기본 매개 변수**

* **입력 노출 델타(EV)**: 0-2\
  가장 높은 입력 노출과 가장 낮은 입력 노출 사이의 노출 차이를 설정합니다. 높은 노출 델타는 병합 작업의 결과 대비를 증가시킬 것이다.
* **출력 자동 노출**: 전환\
  자동 노출 조정을 활성화하거나 비활성화합니다.
* **출력 노출 오프셋(EV)**: -5 - 5\
  노출을 상쇄합니다.

## 사용 안내서

이 영상을 보고 **HDR 병합 필터**&#x200B;와 SDR 이미지를 HDR 환경 조명으로 변환하는 데 도움이 되는 다른 필터를 사용하는 방법을 알아보십시오.

**HDR 병합** **필터**&#x200B;를 사용하는 기본 단계는 다음과 같습니다.

1. 레이어 스택으로 병합할 이미지 세트를 가져옵니다.
1. **HDR 병합 필터**&#x200B;를 레이어 스택에 추가합니다.
1. 노출 값이 정확하도록 매개 변수를 수정합니다.
