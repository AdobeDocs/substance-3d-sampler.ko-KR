---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/getting-started/export/managing-custom-presets.html"
breadcrumb-title: ''
description: Substance 3D Sampler에서 작업 과정 최적화를 위한 Substance Designer을 사용하여 사용자 정의 내보내기 사전 설정을 만들고 편집하는 방법을 알아보십시오.
helpx_creative_field: ""
helpx_description: Sampler > Getting Started > Export > Managing custom presets
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 사용자 정의 사전 설정 만들기 및 편집
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '278'
ht-degree: 1%

---


# 사용자 정의 사전 설정 만들기 및 편집

Substance 3D Designer을 사용하여 사용자 정의 사전 설정을 만들 수 있습니다.

사용자 정의 사전 설정을 만들면 Sampler용 사용자 정의 필터를 만드는 것과 동일한 규칙이 적용됩니다. 설명서는 [여기](../../filters/custom-filters.md)에서 사용할 수 있습니다.

## 생성

## 그래프 만들기

Substance Designer 를 열고 새 Substance 그래프를 만듭니다.

그래프 속성을 열고 다음 필수 정보를 입력합니다.

* 레이블: Sampler 인터페이스에 사용할 사용자 정의 사전 설정의 이름을 입력합니다.
* 사용자 데이터: <b>alchemist::type=filter</b>

## 입력 및 출력 정의

### 입력

입력은 내보내기 전에 변형할 재질 채널을 나타냅니다.

재질 채널당 입력 색상 노드(또는 회색 음영)를 만들고 각 입력 노드에 특성에 <b>사용량</b>을 추가하여 재질이 사용자 정의 사전 설정과 연결되도록 합니다.

예: 기본 색상 입력의 정의

![](../../assets/custom-input.png){width="600px"}

### 출력

출력은 텍스처 내보내기 결과를 나타냅니다.

텍스처당 하나의 출력 노드를 만들고 각 출력 노드에 특성에 <b>사용량</b> 및 <b>레이블</b>을 추가합니다. <b>레이블</b>이 내보내기 창의 채널 목록과 텍스처 파일의 이름에 표시됩니다.

예: 사용자 정의 텍스처 색상 불투명도 정의

![](../../assets/custom-output.png){width="600px"}

#### 채널 패킹 및 채널 변환의 예

하나의 RGB 텍스처에서 3개의 회색 음영 채널로 이루어진 패킹:

![](../../assets/channel-packing-example.png){width="600px"}

PBR 금속/거칠기에서 PBR Specular/광택으로 채널 변환:

![](../../assets/channel-conversion.png){width="600px"}

## 가져오기

새 사전 설정을 가져오려면:

1. <b>사전 설정 드롭다운</b>의 오른쪽에 있는 <b>사전 설정 관리 </b>버튼을 클릭합니다.
1. <b>사전 설정 목록</b>의 아래쪽에 있는 <b>사전 설정 가져오기</b> 단추를 사용하십시오.

![](../../assets/Managing-presets-Dropdown.png.img.png){width="400px"}
