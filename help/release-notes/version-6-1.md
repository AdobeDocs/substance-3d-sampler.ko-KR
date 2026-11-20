---
description: Substance 3D Sampler 버전 6.1의 릴리스 노트를 통해 새로운 기능, 개선 사항 및 워크플로우 개선 사항에 대해 알아보십시오.
title: 버전 6.1
hold: true
source-git-commit: 99bb504f8dd5c485bf0d208a85cc3825d186c55f
workflow-type: tm+mt
source-wordcount: '1167'
ht-degree: 0%
---

# 버전 6.1

**Kooign amann**(Breton 레이어로 구성된 페이스트리)

![대체 텍스트](../../help/assets/Sampler_splash_large.jpg)

이 릴리스에서는 성능 모드를 도입하여 워크플로우가 느려질 수 있는 설정을 누구나 끌 수 있도록 하고, 하드웨어가 가벼운 사용자도 보호할 수 있도록 자동 안정성을 개선합니다.

주요 새로운 기능은 다음과 같습니다.

## 성능 모드

Sampler에서 더 빠르고 반응형 경험을 얻으십시오. 새로운 **성능 모드**&#x200B;에는 해상도 제한, 그림자, 변위 품질 및 경로 추적과 같이 작업 과정을 느리게 할 수 있는 모든 설정이 함께 사용됩니다. 성능과 응답성을 개선할 필요가 없는 기능을 끄십시오.

추가 정보 [*여기*](https://www.adobe.com/go/substance-3d-sampler-6.1-performance-mode)

![](../assets/v6.1/6_1-Performance_Mode.png)

## 최소 사양 머신에 대한 지원 향상

하드웨어가 [최소 사양](../getting-started/system-requirements.md) 미만으로 떨어지면 이제 Sampler이 자동으로 조정되어 안정적으로 유지됩니다. 속도가 느려지거나 충돌을 일으킬 가능성이 높은 기능은 자동으로 꺼집니다.

추가 정보 [*여기*](https://www.adobe.com/go/substance-3d-sampler-6.1-low-specs-mode)

![](../assets/v6.1/6_1-Checked.png)

## V6.1 릴리스 노트

*(릴리스: 2026년 11월 19일)*

## 추가됨

* &amp;lbrack;Application&amp;rbrack; 최소 하드웨어 요구 사항 경고를 보고하는 새로운 방법
* &amp;lbrack;Captis&amp;rbrack; 4각과 8각 중 하나를 선택하는 옵션을 추가합니다
* &amp;lbrack;Captis&amp;rbrack; 새로운 Captis 빠른 작업
* &amp;lbrack;Export&amp;rbrack; 사용자에게 내보내기 실패를 올바로 보고합니다.
* &amp;lbrack;Export&amp;rbrack; Unreal Engine 4 내보내기 사전 설정 업데이트(Unreal Engine 5로 이름 변경)
* &amp;lbrack;Performance&amp;rbrack; 파일에서 에셋 생성이 이제 비동기적입니다.
* &amp;lbrack;성능&amp;rbrack; 주 스레드에서 작업자 스레드로 작업 로드 이동
* &amp;lbrack;성능&amp;rbrack; 새로운 성능 모드
* &amp;lbrack;프로젝트 저장 실패 시 사용자에게 경고(&amp;r)
* &amp;lbrack;Scripting&amp;rbrack; 자산에 대한 새로운 generate_thumbnail 메서드 및 리소스에 대한 새로운 유형 속성
* &amp;lbrack;스크립팅&amp;rbrack; Python 모듈에서 파일에 3D 보기 스냅숏 렌더링
* &amp;lbrack;UI&amp;rbrack; 놓기 영역의 아무 곳이나 클릭하면 파일 대화 상자가 열립니다.
* &amp;lbrack; 왼쪽 탐색 도구(equalize crop, tiling bar, 변환, repair, color..)에 대한 단축키.
* &amp;lbrack;UI&amp;rbrack; qt-spectrum을 업그레이드하여 최신 아이콘 가져오기

## 고정

* &amp;lbrack;3D 보기&amp;rbrack; 즉각적인 UV 오프셋 및 회전 수정, OpenPBR에 대한 일반 비율 제거
* &amp;lbrack;3D 보기&amp;rbrack; 뷰포트가 삭제되는 동안 스테이지 편집이 수행되지 않도록 하여 충돌을 방지합니다
* &amp;lbrack;3D 보기&amp;rbrack; 표시된 에셋을 변경할 때 변위(Height) 정보를 올바르게 제거
* &amp;lbrack;3D 보기&amp;rbrack; 메시 삭제 시 문서를 올바르게 업데이트
* &amp;lbrack;Application&amp;rbrack; 동적 필터 디버그 정보를 계산할 때 표면이 활성 상태로 유지되도록 합니다.
* &amp;lbrack;Application&amp;rbrack; 장면의 종료 시 충돌 수정
* &amp;lbrack;Application&amp;rbrack; 자산 데이터베이스 서비스가 종료되는 동안 자산을 삭제할 때 발생할 수 있는 충돌 수정
* &amp;lbrack;Application&amp;rbrack; 캐시 디버그 정보 스레드를 안전하게 만들어 충돌 방지
* &amp;lbrack;Application&amp;rbrack; 충돌이 노드에 액세스하기 전에 null이 아닌지 테스트하여 노드를 방지합니다.
* &amp;lbrack;Application&amp;rbrack; 빈 벡터의 첫 번째 요소에 액세스해서 발생하는 충돌 방지
* &amp;lbrack;Application&amp;rbrack; invalidateVisibleIfs에서 충돌 방지
* 데이터베이스 서비스가 종료되는 동안 에셋을 만들 때 충돌을 방지합니다(&amp;lbrack;Application&amp;rbrack;)
* &amp;lbrack;Application&amp;rbrack; 종료 시 경쟁 상태 방지
* &amp;lbrack;Assets&amp;rbrack; 올바른 잠금 뒤에서 리소스가 제대로 보호되는지 확인
* 수동 모드에서 강도 값이 있는 &amp;lbrack;Captis&amp;rbrack; 버그
* &amp;lbrack;Captis&amp;rbrack; 사용자가 백엔드에서 허용하는 것보다 큰 영역을 선택하지 못하도록 합니다.
* &amp;lbrack;채널 설정&amp;rbrack; ASM에서 SpecularColor의 이중 발생
* &amp;lbrack;채널 설정&amp;rbrack; 문자열에서 만든 사용 ID 수정
* &amp;lbrack;내용&amp;rbrack; Atlas Scatter 불투명도 문제
* &amp;lbrack;Content&amp;rbrack; 자수 필터에 금속 기능이 없습니다.
* &amp;lbrack;Content&amp;rbrack; 천공 필터 수정
* &amp;lbrack;Content&amp;rbrack; 스타일화 필터 범주 수정 및 리소스 패널의 일부 수정
* &amp;lbrack;내용&amp;rbrack; 채우기 필터 업데이트
* &amp;lbrack;Creative Cloud&amp;rbrack; Creative Cloud에서 3D 에셋에 대한 경로 수정
* &amp;lbrack;Engine&amp;rbrack; 작업이 취소된 동안 엔진 데이터에 액세스할 때 충돌 방지
* &amp;lbrack;내보내기&amp;rbrack; 구조의 트리가 null이 아닌지 확인하기 위한 방어 코드 추가
* &amp;lbrack;SBS 생성 시 충돌을 방지하기 위한 내보내기&amp;rbrack; 방어 코드
* &amp;lbrack;Export&amp;rbrack; 사용자 정의 사용을 엔진에 의해 알려진 경우에도 출력 가능
* &amp;lbrack;내보내기&amp;rbrack; 내보내기 사전 설정 수정
* &amp;lbrack;내보내기&amp;rbrack; 노멀 맵은 USD에서 raw로 내보내집니다.
* &amp;lbrack;Export&amp;rbrack; 사전 설정으로 내보낼 때 사용 대신 출력 레이블을 사용합니다.
* &amp;lbrack;노출된 매개 변수&amp;rbrack; 동적 필터에서 노출된 매개 변수 수정
* &amp;lbrack;Exposed Parameters&amp;rbrack; 이름 변경 시 노출된 매개 변수의 업데이트 수정
* &amp;lbrack;Filters&amp;rbrack; 모든 플랫폼에서 실행되는 모든 간에 동적 필터 수정 식별자가 동일한지 확인합니다.
* &amp;lbrack;Filters&amp;rbrack; 자동 타일링 맵 선택에서 지원되지 않는 사용 숨기기
* &amp;lbrack;레이어&amp;rbrack; 레이어 가시성을 변경하면 항상 구조가 다시 생성됩니다.
* 복제 스탬프를 특정 영역 위에 병합할 때 &amp;lbrack;Layers&amp;rbrack; 충돌
* &amp;lbrack;Layers&amp;rbrack; 이제 스택에 직접 생성기를 삽입하면 비틀기와 노드 이름이 올바르게 설정됩니다.
* &amp;lbrack;Layers&amp;rbrack; 칠이 있는 생성기를 삽입하면 피커에 텍스처가 제대로 표시됩니다
* &amp;lbrack;Localization&amp;rbrack; 중국어 문자 집합 규격을 GB로 수정합니다18030
* 복제 스탬프에 페인팅한 후 저장할 때 &amp;lbrack;Project&amp;rbrack; 충돌
* &amp;lbrack;프로젝트&amp;rbrack; 세션 및 프로젝트 이름이 실제로 저장되는지 확인
* &amp;lbrack;프로젝트&amp;rbrack; 트리 저장 시 충돌 방지
* &amp;lbrack;프로젝트&amp;rbrack; 데이터베이스에서 손상된 프로젝트 복원 중
* &amp;lbrack;빠른 작업&amp;rbrack; 스택에 이미지가 없을 때 이미지 선택 팝업을 표시합니다.
* &amp;lbrack;빠른 작업&amp;rbrack; 빠른 작업 문제 해결; 빠른 작업을 취소해도 더 이상 빠른 시작이 닫히지 않습니다.
* &amp;lbrack;빠른 작업&amp;rbrack; 텍스처 가져오기에서 일부 채널을 사용하도록 설정하라는 메시지가 표시되며 활성화해서는 안 됩니다.
* &amp;lbrack;빠른 작업&amp;rbrack; 빠른 작업이 로드되지 않을 경우 충돌 방지
* &amp;lbrack;빠른 작업&amp;rbrack; 빠른 작업 콘텐츠 업데이트
* &amp;lbrack;Rendering&amp;rbrack; ASM 재질에 대한 combineNormalAndHeight 수정
* &amp;lbrack;Rendering&amp;rbrack; Vulkan이 있는 표시 가능한 텍스처의 사용 수정
* &amp;lbrack;렌더링&amp;rbrack; 고유 사용 출력이 변경되면 트리를 더티(dirty)로 표시
* &amp;lbrack;렌더링&amp;rbrack; 정확한 참조 구조를 사용하여 계산할 트리 노드를 계산합니다
* &amp;lbrack;Scripting&amp;rbrack; 내보내기 중 문제가 발생하면 실행하지 마십시오
* &amp;lbrack;Scripting&amp;rbrack; import_images()가 가져온 레이어를 반환하는지 확인
* &amp;lbrack;스크립팅&amp;rbrack; 이미지 자산 참조에 대한 이미지 변경 설정이 실패함
* &amp;lbrack;Scripting&amp;rbrack; get_filters()가 동적 필터를 반환하지 않음
* &amp;lbrack;Thumbnail&amp;rbrack; 축소판 생성 시 잠재적인 충돌 수정
* &amp;lbrack;Thumbnail&amp;rbrack; 레이아웃이 변경되면 축소판 생성기를 다시 만듭니다.
* &amp;lbrack;UI&amp;rbrack; 자산을 변경하면 Height 비율을 슬라이더 최대 값으로 설정할 수 있습니다.
* &amp;lbrack;UI&amp;rbrack; 텍스처에서 그리면 텍스처 피커가 실시간으로 업데이트됩니다
* &amp;lbrack;UI&amp;rbrack; 최대화되지 않은 채 전체 화면 모드로 들어가는 것이 이제 전체 창을 채웁니다.
* &amp;lbrack;UI&amp;rbrack; Substance 매거진에 대한 끊어진 링크 수정
* &amp;lbrack;UI&amp;rbrack; 내보내기 팝업 여백 수정
* &amp;lbrack;UI&amp;rbrack; 섹션 제목 크기 수정
* &amp;lbrack;UI&amp;rbrack; 문자열의 오타 수정
* &amp;lbrack;UI&amp;rbrack; Linux 파일 대화 상자에서 이제 GTK 플러그인을 사용합니다.
* &amp;lbrack;UI&amp;rbrack; 이모지 표시 시 충돌 방지
* &amp;lbrack;UI&amp;rbrack; .ssa 파일의 이름을 &#39;Adobe Substance 3D Sampler 보관&#39;(버전 또는 Beta 없음)으로 바꾸기
* &amp;lbrack;UI&amp;rbrack; 마우스 사용 시 깜박임 감속 복원
* &amp;lbrack;UI&amp;rbrack; &#39;새 재질 만들기&#39; 대화 상자의 작은 수정
