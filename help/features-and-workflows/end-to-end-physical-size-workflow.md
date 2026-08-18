---
helpx_url: "https://helpx.adobe.com/kr/substance-3d-sampler/features-and-workflows/end-to-end-physical-size-workflow.html"
breadcrumb-title: ''
description: Substance 3D Sampler의 종단 간 물리적 크기 워크플로를 사용하여 실제 규모에 맞는 물리적으로 정확한 재질을 만드는 방법을 알아봅니다.
helpx_creative_field: ""
helpx_description: Sampler > Features and workflows > End to end Physical Size Workflow
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 엔드투엔드 물리적 크기 워크플로우
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '356'
ht-degree: 0%

---


# 엔드투엔드 물리적 크기 워크플로우

스캔한 샘플 및 이미지의 실제 물리적 크기를 디지털 컨텍스트와 일치시켜 응용 프로그램 간에 물리적으로 정확한 비주얼을 만들 수 있습니다.

## 스캔 가져오기

1. 재료 생성 템플릿을 선택합니다.
1. 물리적 크기 확인란을 선택합니다.

   ![](../assets/screenshot-2022-01-20-at-16-15-53.png)
1. 물리적 크기 설정을 위한 두 가지 방법:

   3a. 수동 측정(manual measure) - 측정(Measure) 도구를 클릭하면 샘플의 두 피쳐 사이의 물리적 크기를 교정할 수 있습니다.\
   두 지점 간 추적 -> enter

   ![](../assets/screenshot-2022-01-20-at-16-31-26.png)

   3b. 자동 물리적 크기 - 자동 측정 도구를 사용하면 이미지 메타데이터(dpi)를 기반으로 샘플의 예상 측정값을 얻을 수 있습니다. 이 기능은 더 빠르지만 저장된 dpi를 사용하여 정확한 시작 크기를 계산하기 때문에 스캔에서만 작동합니다.

   <b>이제 스캔을 처리할 수 있습니다</b>
1. 자르기를 추가하고 샘플에 조정합니다. 2D 뷰포트의 오른쪽 하단에 표시된 물리적 크기가 업데이트된 것을 확인할 수 있습니다.

   작업 중인 지도를 정확하게 보기 위해 2D 뷰포트에 실제 비율과 함께 표시합니다.\
   2D 보기를 물리적 크기에 맞게 설정하여 화면 비율의 DPI가 재질 비율과 일치하도록 할 수 있습니다. 즉, 실제 샘플을 화면 옆에 배치하여 치수를 확인할 수 있습니다.

   ![](../assets/cq5dam.web.1280.png)
1. [균일화]를 추가하여 그레이디언트를 제거합니다.
1. 타일링을 추가하여 바둑판식 보정이
1. 필요한 경우 뒤틀기 변형은 맵의 일부만 다시 정렬하는 데 유용합니다.

   <b>내보낼 준비</b>
1. 내보내기 형식

   Sbsar 형식을 선택하면 Sampler이 물리적 크기를 메타데이터로 넣습니다. 다른 응용 프로그램에서도 이 정보를 읽고 사용할 수 있습니다.\
   이미지를 내보낼 수도 있습니다. 물리적 크기 비율을 준수합니다.

   언제든지 물리적 크기를 사용해야 하는 경우 *물리적 크기 패널*&#x200B;을 사용하세요.

   이미지로 내보낼 때 이미지의 크기가 물리적 크기 비율을 유지하도록 할 수 있습니다.

## 비디오 자습서

이 기능을 사용하는 데 도움이 되는 비디오 튜토리얼도 찾을 수 있습니다.
