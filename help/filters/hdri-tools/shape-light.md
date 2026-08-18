---
helpx_url: "https://helpx.adobe.com/kr/substance-3d-sampler/filters/hdri-tools/shape-light.html"
breadcrumb-title: ''
description: Substance 3D Sampler의 모양 조명 도구를 사용하여 창의적인 조명을 위해 HDRI 환경에 사용자 정의 모양의 광원을 추가합니다.
helpx_creative_field: ""
helpx_description: Sampler > Filters > HDRI Tools > Shape Light
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 도형 조명
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '264'
ht-degree: 0%

---


# 도형 조명

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-shapelight-18-n-d.png)

**내부:** HDRI 도구

</td>
<td width="58.30%" style="border: 0;" valign="top">

## 설명

직사각형 또는 디스크 모양의 조명을 만듭니다.

</td>
</tr>
</table>

## 매개변수

**기본 매개 변수**

* **모양 색상 모드**:\
  조명의 색상을 결정하는 데 사용할 방법을 선택합니다. 이 선택 항목에 따라 사용 가능한 매개 변수가 변경됩니다.
  * **온도(켈빈)**
    * **온도**: 1000 - 27000\
      조명의 온도를 조정합니다.
  * **RGB**
    * **색상**: 색상 선택\
      조명의 색상을 선택합니다.
  * **이미지 입력**
    * **모양 이미지 입력**: 이미지/브러시\
      색상으로 사용할 이미지를 가져옵니다. 브러시 도구를 사용하여 **2D 보기**&#x200B;에서 바로 페인트할 수 있지만 이 필터를 사용하면 예기치 않은 결과가 발생할 수 있습니다.
* **핫스팟 노출(EV)**: 0-10\
  핫스폿의 노출을 조정합니다. 핫스폿은 때때로 보기가 어렵거나 불가능할 수 있습니다. 새로운 **모양 조명 필터**&#x200B;에서는 **모양 온도**&#x200B;를 1000으로 설정하고 **핫스팟 노출** **(EV)**&#x200B;을(를) 10으로 설정하여 모양의 중앙에서 핫스폿을 봅니다.
* **모양**:\
  조명의 모양을 설정합니다.

**위치**

* **핫스팟 위치**: 0-1\
  핫스팟 위치 오프셋
* **행렬 오프셋**: -2 - 2\
  모양 조명의 위치를 변경합니다. **2D 보기**&#x200B;에서 조명을 드래그하여 위치를 변경할 수도 있습니다.

**모양**

* **모양 노출(EV)**: 0-10\
  빛 노출 조정
* **모양 경도**: 0-1\
  빛의 가장자리 부드럽게 하기
* **핫스팟 크기**: 0-1
* **핫스팟 밝기 감소**: 0-1\
  핫스팟 가장자리의 부드러움을 조정합니다.

**배경**

* **배경 감마**:\
  배경 감마를 결정하는 데 사용할 색상 시스템을 선택합니다.
