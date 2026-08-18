---
helpx_url: 'https://helpx.adobe.com/substance-3d-sampler/release-notes/all-changes.html'
breadcrumb-title: ''
description: Substance 3D Sampler 버전 전체의 모든 변경 내용 및 업데이트를 검토하여 시간의 흐름에 따른 기능 변화 및 개선 사항을 추적하세요.
helpx_description: Sampler > Release Notes > All Changes
title: 모든 변경 내용
user-guide-description: ''
user-guide-title: ''
source-git-commit: dc832dc546735437051226f4e1e731b55147b3ea
workflow-type: tm+mt
source-wordcount: '24926'
ht-degree: 0%

---


# 모든 변경 내용

이 페이지에서는 Substance 3D Sampler에 발생한 모든 변경 사항을 새로운 기능에서 버그 수정에 이르기까지 다시 그룹화합니다.

## 버전 6

### **6.0.2**

*(릴리스: 2026년 6월 25일)*

**추가됨:**

* &amp;lbrack;Assets&amp;rbrack; sbsar 버전을 확인하고 엔진이 너무 오래되어 읽을 수 없음을 사용자에게 경고합니다
* &amp;lbrack;Captis&amp;rbrack; 환경 설정에 captis 측광을 저장하는 옵션 다시 추가

**고정:**

* &amp;lbrack;2D 보기&amp;rbrack; 물리적 크기가 비활성화된 경우 &#39;물리적 비율로 표시&#39;하지 않음
* &amp;lbrack;Analytics&amp;rbrack; 분석 이벤트 누락
* &amp;lbrack;Analytics&amp;rbrack; vk devicelost에서 충돌 보고를 위한 크래시패드 방지
* &amp;lbrack;Application&amp;rbrack; nvidia 드라이버에서 충돌이 발생하지 않도록 종료 시 vkdevices를 제거하지 마십시오
* &amp;lbrack;응용 프로그램&amp;rbrack; 연결된 컬렉션 감시기 종료 + 채널 관리자 수정
* &amp;lbrack;응용 프로그램(&amp;r); 종료 시 충돌 방지
* &amp;lbrack;Content&amp;rbrack; &quot;metal finish&quot; 필터는 금속에 영향을 주지 않습니다.
* &amp;lbrack;Content&amp;rbrack; 누락된 동적 필터에 물리적 크기 추가
* &amp;lbrack;필터&amp;rbrack; 숨겨진 에셋 목록에서 내용 인식 채우기 제거
* &amp;lbrack;Layers&amp;rbrack; &#39;모든 설정 재설정&#39;을 클릭해도 &#39;적용 대상&#39; 드롭다운이 재설정되지 않습니다
* &amp;lbrack;레이어&amp;rbrack; 위치 위젯의 최소 및 최대 조정 수정
* &amp;lbrack;Layers&amp;rbrack; 필터 올바르게 업데이트
* &amp;lbrack;물리적 크기&amp;rbrack; 물리적 크기가 어디서나 작동하는지 확인합니다. + 동적 필터로 물리적 크기를 확인합니다.
* &amp;lbrack;프로젝트&amp;rbrack; 새 에셋을 만들 때 에셋 해상도가 기본 해상도(2k x2k)인지 확인합니다.
* &amp;lbrack;프로젝트&amp;rbrack; 이전 버전을 여는 데 사용된 현재 프로젝트를 다시 엽니다.
* &amp;lbrack;Project&amp;rbrack; Sampler은 더 이상 손상된 프로젝트의 백업을 복원하지 않습니다.
* &amp;lbrack;Rendering&amp;rbrack; 최대 2k 해상도로 재질 축소판 렌더링
* 사용자가 UI보다 빠른 경우 충돌을 방지하는 &amp;lbrack;UI&amp;rbrack; 방어 코드

### **6.0.1**

*(릴리스: 2026년 5월 21일)*

**추가됨:**

* &amp;lbrack;Application&amp;rbrack; 3D 개체 또는 환경 조명이 있는 프로젝트를 열 때 사용자에게 경고합니다
* &amp;lbrack;Captis&amp;rbrack; UI를 작은 화면에 맞게 조정
* &amp;lbrack;Captis&amp;rbrack; Captis UI 업데이트
* &amp;lbrack;Channel Settings&amp;rbrack; ASM에서 SSS 채널을 사용할 때 SSS 자동 활성화
* &amp;lbrack;엔진&amp;rbrack; Substance 엔진을 버전 9.4.3으로 업데이트
* &amp;lbrack;Preset&amp;rbrack; 기본적으로 &#39;사전 설정 축소판 값 적용&#39; 전환
* &amp;lbrack;Resources&amp;rbrack; 기본적으로 [리소스] 패널에서 &#39;스타터 에셋&#39; 대신 &#39;모든 라이브러리&#39;를 표시
* &amp;lbrack;Scripting&amp;rbrack; 레이어의 &#39;적용 대상&#39;을 관리하기 위한 Python 함수 추가
* &amp;lbrack;UI&amp;rbrack; 에셋 목록이 반응함: 에셋 크기가 컨테이너에 맞게 조정됨
* &amp;lbrack;UI&amp;rbrack; 기본적으로 3D/2D 보기 표시
* &amp;lbrack;UI&amp;rbrack; 탐색기에서 재료를 놓을 때 재료 최적화 팝업을 표시합니다.
* &amp;lbrack;UI&amp;rbrack; 장치 막대 단추 뒤집기 사용 도구 설명

**고정:**

* &amp;lbrack;응용 프로그램&amp;rbrack; 색상 공간 문제 수정
* &amp;lbrack;응용 프로그램 &amp;rbrack; 설정 업데이트 수정
* &amp;lbrack;응용 프로그램&amp;rbrack; 스캔 채널이 자동으로 설정되어 있을 때 활성화 상태로 만듭니다.
* 홈 화면의 &amp;lbrack;응용 프로그램&amp;rbrack; 새 프로젝트 단추는 더 이상 같은 이름의 이전 프로젝트를 지우지 않습니다.
* &amp;lbrack;응용 프로그램(&amp;r); macOS 종료 시 충돌 방지
* &amp;lbrack;Application&amp;rbrack; 잘못된 에셋 참조의 에셋에 액세스하지 못하도록 방지
* &amp;lbrack;Application&amp;rbrack; Tweak에서 VersionedImage의 표면에 액세스할 때 충돌 방지
* &amp;lbrack;Application&amp;rbrack; 스테이지가 없을 때 스테이지 삭제 시 충돌 방지
* &amp;lbrack;Captis&amp;rbrack; Sampler을 닫기 전에 Captis의 연결이 끊어졌는지 확인
* &amp;lbrack;Captis&amp;rbrack; USB-2 경고가 두 번 표시되지 않도록 방지
* &amp;lbrack;채널 설정&amp;rbrack; OpenPBR 채널 이름 수정
* &amp;lbrack;채널 설정&amp;rbrack; OpenPBR 채널의 긴 레이블 업데이트
* &amp;lbrack;Content&amp;rbrack; SSS 값에 대한 모든 메시 단위를 미터에서 센티미터로 업데이트합니다.
* &amp;lbrack;내보내기&amp;rbrack; 기본값이 동적 필터에 연결되어 있는지 확인합니다.
* 이제 &amp;lbrack;Export&amp;rbrack; 이미지가 작업자 스레드에 저장되어 성능이 향상됩니다.
* 배율 전환 시 &amp;lbrack;Filters&amp;rbrack; 내용 인식 채우기가 충돌함
* &amp;lbrack;Filters&amp;rbrack; 에셋 패널에서 동적 필터의 위치를 열 수 없습니다.
* &amp;lbrack;Filters&amp;rbrack; 자동 타일링 조정 단계에서 모두 재설정 수정
* &amp;lbrack;Filters&amp;rbrack; 복원 트리 구조 생성에서 사용 비활성화 처리
* &amp;lbrack;Filters&amp;rbrack; upscale 매개 변수에 대한 올바른 기본값 설정
* &amp;lbrack;Filters&amp;rbrack; 생성기가 채우기 레이어에 있는 경우에도 업데이트합니다
* &amp;lbrack;Layers&amp;rbrack; 입력 레이어 헤더 또는 자리 표시자 레이어의 이름을 변경하지 못하도록 합니다.
* &amp;lbrack;Layers&amp;rbrack; 매달리기 포인터로 인한 레이어 삽입 중 충돌 방지
* &amp;lbrack;Layers&amp;rbrack; 병합 레이어 이름에 잘못된 수의 이미지가 있습니다.
* &amp;lbrack;Localization&amp;rbrack; 언어를 전환할 때 사전 설정 이름이 업데이트되었는지 확인
* 리소스 패널의 &amp;lbrack;Localization&amp;rbrack; 다중 번역 문제
* &amp;lbrack;로컬라이제이션&amp;rbrack; 빠른 작업은 로컬라이제이션 문제를 분류합니다.
* &amp;lbrack;성능&amp;rbrack; 열린 구역에서만 수정 영역 불러오기
* &amp;lbrack;환경 설정&amp;rbrack; 환경 설정 캐시 경로를 지우면 이전 값으로 재설정됩니다.
* 경로 추적기를 사용할 때 &amp;lbrack;Rendering&amp;rbrack; 메모리 누수
* &amp;lbrack;Rendering&amp;rbrack; Vulkan이 계속 액세스할 수 있는 텍스처를 삭제하지 못하게 합니다.
* &amp;lbrack;렌더링&amp;rbrack; 텍스처 회전이 0-1에서 0-360으로 변환되지 않았습니다.
* &amp;lbrack;Scripting&amp;rbrack; Python 설명서에서 존재하지 않는 클래스 제거
* &amp;lbrack;Scripting&amp;rbrack; selectedAsset이 선택된 에셋이 없으면 없음을 반환합니다.
* &amp;lbrack;도구&amp;rbrack; 이제 텍스처 값을 재설정하면 페인팅이 중지되고 패치 보기가 지워집니다.
* &amp;lbrack;UI&amp;rbrack; 어떤 것이 수정될 때마다 속성 패널에서 섹션을 닫지 마십시오
* &amp;lbrack;UI&amp;rbrack; 마우스 오버 시 표시되지 않는 노출된 색상 조정 레이블
* &amp;lbrack;UI&amp;rbrack; 자산 목록 반응형 동작 수정
* &amp;lbrack;UI&amp;rbrack; AssetItem 도구 설명의 바인딩 루프 수정
* &amp;lbrack;UI&amp;rbrack; 선택한 사전 설정 그룹에 대한 더블 클릭 수정
* &amp;lbrack;UI&amp;rbrack; 이미지 발표자의 놓기 영역 수정
* &amp;lbrack;UI&amp;rbrack; 모든 언어에 대해 단추가 포함된 레이블 수정
* &amp;lbrack;UI&amp;rbrack; Height 목록 팝업에서 일본어에 대한 줄 채널 수정
* &amp;lbrack;UI&amp;rbrack; 길이 필드의 수락된 신호 수정
* &amp;lbrack;UI&amp;rbrack; 왼쪽 긴 제어 항목으로 팝업 폭 수정
* &amp;lbrack;UI&amp;rbrack; 에셋 항목의 미리 보기 팝업 수정
* &amp;lbrack;UI&amp;rbrack; 거칠음/반사 피커 수정
* &amp;lbrack;UI&amp;rbrack; 문자열 줄임표 수정
* &amp;lbrack;UI&amp;rbrack; 문자열 잘림 문제 수정
* &amp;lbrack;UI&amp;rbrack; 스위치 수정 조정 재설정 버튼
* &amp;lbrack;UI&amp;rbrack; 사용자 정의 내보내기 사전 설정이 선택되면 재질 모델 드롭다운을 숨깁니다.
* &amp;lbrack;UI&amp;rbrack; 내보내기 팝업의 채널 목록에서 해상도 제거
* &amp;lbrack;UI&amp;rbrack; 기본 레이아웃으로 재설정하면 투영 뷰어 설정이 유지됨
* &amp;lbrack;UI&amp;rbrack; &#39;Photoshop에서 편집&#39; 및 &#39;Illustrator에서 편집&#39; 메뉴 항목 복원

**제거됨:**

* &amp;lbrack;UI&amp;rbrack; 이미지 가져오기 레이어의 &#39;적용 대상&#39; 섹션 제거
* &amp;lbrack;UI&amp;rbrack; 처음 실행 시 자동 열기 빠른 작업 도구 설명 제거

## 버전 5

### **5.1.3 ÎLE FLOTTANTE**

*(릴리스: 2026년 1월 6일)*

**추가됨:**

* &amp;lbrack;Captis&amp;rbrack; 방화벽에 의해 FTP 프로토콜이 비활성화되면 경고를 표시합니다

**고정:**

* &amp;lbrack;Captis&amp;rbrack; 캡처 중 중단하면 오류가 발생할 수 있습니다.
* &amp;lbrack;Captis&amp;rbrack; 캡처 끝에서 결과를 다운로드하면 많은 RAM이 사용됩니다.
* &amp;lbrack;Captis&amp;rbrack; 자동 강도 직후 자동 초점을 실행하면 오류가 발생할 수 있습니다.
* &amp;lbrack;Captis&amp;rbrack; HDR 디스플레이가 [요약] 패널로 표시됩니다.
* &amp;lbrack;UI&amp;rbrack; 경우에 따라 MacOS의 폴더 대화 상자에서 올바른 폴더를 선택하지 않습니다

### **5.1.2 ÎLE FLOTTANTE**

*(릴리스: 2025년 11월 20일)*

**추가됨:**

* &amp;lbrack;Application&amp;rbrack; 그래픽 장치 손실을 감지하고 사용자에게 경고한 후 적절하게 종료합니다
* &amp;lbrack;Layers&amp;rbrack; 레이어 병합 시 메시징 개선
* &amp;lbrack;Layers&amp;rbrack; 이미지 가져오기 및 병합 레이어 레이어의 축소판 개선
* &amp;lbrack;Onboarding&amp;rbrack; 홈 화면의 학습 콘텐츠 업데이트됨
* &amp;lbrack;프로젝트&amp;rbrack; 충돌 전에 마지막으로 저장된 세션 상태 복구
* &amp;lbrack;UI&amp;rbrack; 응용 프로그램 아이콘 업데이트

**고정:**

* &amp;lbrack;Application&amp;rbrack; 레이어 스택에 재질을 삽입하면 macOS에서 충돌이 발생할 수 있습니다
* &amp;lbrack;응용 프로그램&amp;rbrack; macOS에서 과부하 시 가능한 충돌
* &amp;lbrack;응용 프로그램&amp;rbrack; 비디오 메모리가 가득 찼을 때 레이어를 추가할 때 충돌이 발생할 수 있습니다.
* &amp;lbrack;Application&amp;rbrack; 프로젝트를 열 때 충돌이 발생할 수 있습니다.
* &amp;lbrack;Captis&amp;rbrack; 자동 강도 보정 직후 자동 포커스가 실행되는 경우 실패
* &amp;lbrack;Captis&amp;rbrack; 첫 번째 캡처 후 안정성 및 성능 문제
* &amp;lbrack;Captis&amp;rbrack; 캡처 끝에서 파일 복사 시 성능 저하 및 오류 발생
* &amp;lbrack;Captis&amp;rbrack; Captis 장치 정보를 쿼리할 때 작은 메모리 누수
* &amp;lbrack;Export&amp;rbrack; 다중 슬라이더 노출 매개 변수는 손상된 .sbsar 파일을 생성합니다.
* 에셋을 전환할 때 자동 타일링 패턴이 기본값으로 재설정됨(&amp;lbrack; Layers&amp;rbrack;)
* &amp;lbrack;Layers&amp;rbrack; 기본 사용자 정의 기본 색상이 빨간색으로 표시됨
* &amp;lbrack;Layers&amp;rbrack; 복제 도장 하위 레이어를 부분적으로 병합할 수 있으며 렌더링 문제가 발생합니다.
* &amp;lbrack;Layers&amp;rbrack; 렌더링이 진행되는 동안 레이어 스택을 수정하면 충돌이 발생할 수 있습니다
* &amp;lbrack;Layers&amp;rbrack; 소스 채널을 변경할 때 관심 영역 자동 타일링 단계에서 예기치 않은 오류가 발생했습니다.
* &amp;lbrack;프로젝트&amp;rbrack; 새 재질을 만들 때 축소판이 잘못되는 경우가 있습니다.
* &amp;lbrack;빠른 작업&amp;rbrack; 일부 빠른 작업의 입력 수가 잘못되었습니다.
* &amp;lbrack;UI&amp;rbrack; 작업 그룹 버튼의 너비가 다름
* &amp;lbrack;UI&amp;rbrack; 텍스트 필드의 지우기 단추 가 포커스 손실을 트리거하는 경우가 있습니다.
* &amp;lbrack;UI&amp;rbrack; 콤보 상자와 텍스트 필드가 너무 큽니다.
* &amp;lbrack;UI&amp;rbrack; 아이콘 및 레이블이 잘못 정렬됨
* &amp;lbrack;UI&amp;rbrack; 이름 필드 레이블이 잘못 배치됨
* &amp;lbrack;UI&amp;rbrack; 빠른 작업 단추 레이블이 잘못 정렬됨
* &amp;lbrack;UI&amp;rbrack; 슬라이더에 후행 0이 너무 많이 표시됨

**제거됨:**

* &amp;lbrack;Generative AI&amp;rbrack; Generative AI 기능 제거. *이 기능은 응용 프로그램에서 제거되었으며 3월 5일에 이전 버전의 Sampler에서 서비스가 작동하지 않습니다.*

### **5.1.1 ÎLE FLOTTANTE**

*(릴리스: 2025년 9월 18일)*

**추가됨:**

* &amp;lbrack;2D View&amp;rbrack; 고해상도 텍스처를 위해 2D 보기에서 더 많이 축소할 수 있습니다.
* &amp;lbrack;Captis&amp;rbrack; 파일 복사 시 사용자에게 경고
* 레이어를 복제할 때 &amp;lbrack;Layers&amp;rbrack; 새 레이어 이름에 증분 번호를 사용합니다

**고정:**

* &amp;lbrack;2D View&amp;rbrack; 복제 도장의 모든 속성을 재설정한 후 획을 페인트할 때 이전에 생성된 획이 다시 나타납니다
* &amp;lbrack;Application&amp;rbrack; &quot;현재 프로젝트를 저장하시겠습니까?&quot; 팝업이 잘못된 프로젝트 이름을 사용함
* &amp;lbrack;응용 프로그램(&amp;r); 종료 시 충돌
* &amp;lbrack;응용 프로그램&amp;rbrack; 잠재적 충돌
* &amp;lbrack;Application&amp;rbrack; 때때로 썸네일이 잘못된 자료로 생성됩니다
* &amp;lbrack;Captis&amp;rbrack; 일부 장치에서 고해상도로 스캔을 수행할 때 Height 맵이 검정색입니다
* &amp;lbrack;Captis&amp;rbrack; 캡처 이름이 설정되지 않았고 보정이 실행 중일 때 &quot;캡처 시작&quot; 버튼이 더 이상 비활성화되지 않습니다
* &amp;lbrack;Export&amp;rbrack; .sbsar 파일을 내보낼 때 사용자에게 알리지 않고 내보내기가 실패할 수 있습니다
* 매개 변수를 조정할 때 자동 타일링 필터의 [필터](&amp;lbrack; Filters&amp;rbrack; Advanced parameters] 화면이 깜박이는 경우가 있음
* &amp;lbrack;Filters&amp;rbrack; 타일링 필터의 기본 매개 변수는 출력에 회색 아티팩트를 생성합니다
* &amp;lbrack;Filters&amp;rbrack; 고해상도 입력이 필요한 경우 [자동 타일링] 필터 고급 설정이 개별 패턴 점을 표시하지 않는 경우가 있습니다
* &amp;lbrack;Filters&amp;rbrack; 사용자 정의 크기 자동 타일링 매개변수의 패턴 크기에 잘못된 기본값이 있습니다
* &amp;lbrack;Layers&amp;rbrack; 자동 타일링 필터의 색상 문제가 때때로 빨간색 재질에 주로 나타납니다
* &amp;lbrack;Layers&amp;rbrack; 때때로 레이어를 추가하면 일부 수정이 기본값으로 재설정됩니다
* &amp;lbrack;물리적 크기&amp;rbrack; 물리적 크기가 있는 에셋의 축소판의 Height 배율이 잘못되었습니다.
* &amp;lbrack;UI&amp;rbrack; 노출된 매개 변수의 이름을 바꿀 수 없음
* &amp;lbrack;UI&amp;rbrack; 채널 활성화 버튼이 정사각형이 아님
* &amp;lbrack;UI&amp;rbrack; 슬라이더 레이블이 너무 길면 재설정 버튼에 액세스할 수 없습니다.
* &amp;lbrack;UI&amp;rbrack; Return 키를 누르거나 클릭 시 텍스트 필드에서 포커스가 제거되지 않음
* &amp;lbrack;UI&amp;rbrack; 때때로 물리적 크기 패널에 원하지 않는 툴팁이 나타납니다
* &amp;lbrack;UI&amp;rbrack; 빈 프로젝트를 생성할 때 3D 보기에 잘못된 메쉬가 표시됩니다
* &amp;lbrack;UI&amp;rbrack; 색상 피커 입력을 노출하는 경우, 마우스를 위로 가져가면 레이블이 사라집니다
* &amp;lbrack;UI&amp;rbrack; 매개 변수를 표시할 때 색상 점의 위치가 잘못 지정되는 경우가 있습니다

### **5.1.0 ÎLE FLOTTANTE**

*(릴리스: 2025년 8월 7일)*

**추가됨:**

* &amp;lbrack;2D 보기&amp;rbrack; 브러시 크기가 이제 현재 텍스처 해상도에 맞게 조정됩니다.
* &amp;lbrack;3D 보기&amp;rbrack; 환경 설정의 3D 렌더링을 위한 기본 표시 크기 전환
* &amp;lbrack;응용 프로그램&amp;rbrack; 렌더링 엔진 업데이트
* &amp;lbrack;Captis&amp;rbrack; 미리 보기 중에 &quot;정사각형 만들기&quot; 가능성 추가
* &amp;lbrack;Captis&amp;rbrack; 자동 물리적 크기 감지
* &amp;lbrack;Captis&amp;rbrack; 새 재질을 캡처하면 새 자산이 생성됩니다.
* &amp;lbrack;Captis&amp;rbrack; 드롭다운에서 최대 영역의 픽셀 해상도 대신 인치 또는 센티미터당 픽셀로 해상도 선택을 변경합니다
* &amp;lbrack;Captis&amp;rbrack; 정렬 교정에 대한 문맥 도움말
* &amp;lbrack;Captis&amp;rbrack; 거칠기 맵 생성
* &amp;lbrack;Captis&amp;rbrack; 기본 보정 파일이 누락된 경우 사용자에게 경고합니다
* &amp;lbrack;Filters&amp;rbrack; 구조화된 재료 및 스캔을 위한 자동 타일링 필터
* &amp;lbrack;Filters&amp;rbrack; 새로운 접기 제거 필터
* &amp;lbrack;Filters&amp;rbrack; 복제 도장 필터 내의 새로운 기능
* &amp;lbrack;Filters&amp;rbrack; 균일화 필터 내의 새로운 기능
* &amp;lbrack;Layers&amp;rbrack; 레이어 병합 기능
* 레이어를 마우스 오른쪽 버튼으로 클릭하여 이름을 바꾸거나, 복제하거나, 삭제하거나, 병합할 때 &amp;lbrack;Layers&amp;rbrack; 컨텍스트 메뉴
* &amp;lbrack;Onboarding&amp;rbrack; 시작 및 새로운 기능 화면 업데이트 내용
* &amp;lbrack;성능&amp;rbrack; 자르기 필터 사용 시 성능 향상
* &amp;lbrack;성능&amp;rbrack; 3D 보기의 메모리 사용 개선
* &amp;lbrack;성능&amp;rbrack; 3D 뷰 업데이트가 더 빠릅니다
* &amp;lbrack;물리적 크기&amp;rbrack; 물리적 크기가 활성화되어 있을 때 Substance 필터에서 작업할 때 &quot;실제 비율과 함께 표시&quot; 활성화
* &amp;lbrack;물리적 크기&amp;rbrack; 빈 스택에 이미지를 가져올 때 이미지 비율에 더 일관적인 해상도를 제안합니다
* &amp;lbrack;빠른 작업&amp;rbrack; 스캔 처리를 위한 3개의 새로운 빠른 작업
* 레이어를 병합하는 &amp;lbrack;스크립팅&amp;rbrack; API
* &amp;lbrack;Scripting&amp;rbrack; 이미지 가져오기 레이어의 각 이미지 파일 이름 가져오기
* &amp;lbrack;Scripting&amp;rbrack; 자산의 지정된 채널을 활성화/비활성화하는 새로운 기능
* &amp;lbrack;UI&amp;rbrack; [레이어] 패널의 아이콘과 버튼을 새 기능에 맞게 재작업합니다
* &amp;lbrack;UI&amp;rbrack; 환경 조명 작성 사용 중단 경고

**고정:**

* &amp;lbrack;2D 보기&amp;rbrack; Substance 필터를 사용할 때 &#39;실제 비율로 표시&#39;를 선택하면 작동하지 않을 수 있습니다.
* &amp;lbrack;3D 캡처&amp;rbrack; Svg 파일이 파일 선택기에 나열되지만 지원되지 않음
* &amp;lbrack;3D View&amp;rbrack; 셰이더 설정의 방출 강도 매개 변수가 작동하지 않습니다.
* &amp;lbrack;3D View&amp;rbrack; 때때로 새 에셋을 생성할 때 메시 위치가 잘못되는 경우가 있습니다
* &amp;lbrack;3D 보기&amp;rbrack; 경로 추적 렌더링으로 전환하면 지원되지 않는 하드웨어에서 충돌이 발생합니다.
* 크기를 설정하지 않고 수동 측정 팝업을 닫으면 &amp;lbrack;응용 프로그램(&amp;r)
* &amp;lbrack;응용 프로그램(&amp;r); 충돌
* &amp;lbrack;응용 프로그램 &amp;rbrack; 바탕 화면을 표시할 때 Windows에서 멈춤(Windows 키 + D 키보드 단축키)
* &amp;lbrack;응용 프로그램&amp;rbrack; 언어를 전환할 때 충돌이 발생할 수 있습니다.
* &amp;lbrack;Captis&amp;rbrack; 미리 보기 데이터가 유효하지 않으면 충돌합니다.
* &amp;lbrack;Captis&amp;rbrack; 확대 후 완전히 축소할 수 없음
* &amp;lbrack;Captis&amp;rbrack; 일부 마법사 단계에서 지역화가 누락됨
* &amp;lbrack;Captis&amp;rbrack; Captis를 사용할 때 종료 시 충돌이 발생할 수 있음
* 디바이스에 보정 파일이 없는 경우 &amp;lbrack;Captis&amp;rbrack; 검사가 작동하지 않음
* 복제 도장 필터를 사용할 때 &amp;lbrack;Filters&amp;rbrack; 브러시 미리 보기가 텍스처 및 브러시 크기에 따라 잘못될 수 있습니다
* &amp;lbrack;Filters&amp;rbrack; 업스케일 필터 사용 후 잘못된 출력 크기
* &amp;lbrack;Filters&amp;rbrack; 환경 회전 및 스타일화 필터에 대한 누락된 아이콘
* &amp;lbrack;필터&amp;rbrack; 일부 필터를 업데이트하면 렌더링이 잘못될 수 있습니다
* &amp;lbrack;Layers&amp;rbrack; 두 재질을 혼합할 때 첫 번째 렌더링이 잘못됨
* &amp;lbrack;Layers&amp;rbrack; 단 하나의 업데이트가 있더라도 레이어 업데이트 버튼에는 &quot;모두 업데이트&quot;가 표시됩니다
* 레이어 스택에서 이미지를 가져올 때 불필요한 계산(&amp;lbrack;Layers&amp;rbrack;)
* &amp;lbrack;성능&amp;rbrack; 렌더링 시간을 줄이기 위해 표준 맵 포맷 처리 개선
* &amp;lbrack;물리적 크기&amp;rbrack; 수동 측정 팝업은 자동 측정을 수행한 후에만 작동합니다.
* &amp;lbrack;물리적 크기&amp;rbrack; 물리적 크기가 활성화되어 있을 때 내보내기 팝업의 내보내기 해상도가 잘못되었습니다.
* &amp;lbrack;빠른 작업&amp;rbrack; 생성된 자산 이름에 대한 지역화가 누락됨
* &amp;lbrack;UI&amp;rbrack; 마우스를 위로 가져가면 에셋 미리보기가 표시되지 않을 수 있습니다.
* &amp;lbrack;UI&amp;rbrack; 기본값으로 재설정 버튼을 클릭하면 일부 컨트롤이 깨질 수 있습니다
* &amp;lbrack;UI&amp;rbrack; 프로젝트를 전환할 때 오류 메시지가 지워지지 않음
* &amp;lbrack;UI&amp;rbrack; 에셋이 없을 때 뷰포트 및 속성 패널의 재질 이름이 비어 있는지 확인합니다
* &amp;lbrack;UI&amp;rbrack; POV 매개 변수의 기본값으로 재설정 버튼이 작동하지 않음
* &amp;lbrack;UI&amp;rbrack; 기본값으로 재설정 버튼 겹침
* &amp;lbrack;UI&amp;rbrack; 패널 고정 해제 시 일부 단추를 클릭할 수 없음
* &amp;lbrack;UI&amp;rbrack; 텍스처 틸링 V 매개 변수가 뷰어 설정 및 3D 보기에서 부분적으로 숨겨짐

**제거됨:**

* &amp;lbrack;3D 캡처&amp;rbrack; 3D 캡처 지원 제거
* &amp;lbrack;Application&amp;rbrack; macOS x86 지원 제거

### **5.0.3 헤이즐넛**

*(릴리스: 2025년 6월 3일)*

**추가됨:**

* &amp;lbrack;Captis&amp;rbrack; 기존 재료 이름과 동일한 이름을 지정할 수 있습니다.
* &amp;lbrack;Captis&amp;rbrack; 오류 메시지를 토스트 대신 팝업으로 이동
* &amp;lbrack;Filters&amp;rbrack; 자수 업데이트
* &amp;lbrack;환경 설정&amp;rbrack; 뷰어 설정 및 셰이더에 재설정 추가
* &amp;lbrack;UI&amp;rbrack; 프로젝트 에셋에 &#39;위치 표시&#39; 메뉴 항목을 표시하지 않음

**고정:**

* &amp;lbrack;3D 캡처&amp;rbrack; 메시 사후 프로세스 필터가 필요한 맵을 출력하지 않습니다.
* &amp;lbrack;3D View&amp;rbrack; 3D 뷰가 셰이더 캐시 손상으로 인해 작동하지 않음
* &amp;lbrack;3D View&amp;rbrack; 장면이 Z-up일 때 기준 평면 및 격자가 수직입니다.
* &amp;lbrack;3D View&amp;rbrack; 메쉬가 때때로 사라집니다
* &amp;lbrack;Application&amp;rbrack; 로그인 없이 시작 시 로그인 창을 닫으면 때때로 앱이 충돌합니다
* 플러그인 구성 파일에 대한 액세스가 거부되면 &amp;lbrack;Application&amp;rbrack;이 충돌합니다.
* 프로젝트가 저장되면 현재 재질이 선택 취소됨(&amp;lbrack; Application&amp;rbrack;)
* &amp;lbrack;응용 프로그램&amp;rbrack; 기본 레이아웃으로 재설정하면 해상도가 64x64로 설정됩니다.
* 레이어 스택을 렌더링할 때 &amp;lbrack;Application&amp;rbrack; Sampler이 때때로 충돌합니다
* &amp;lbrack;내보내기&amp;rbrack; 내보내기 해상도가 64x64로 재설정되는 경우가 있습니다.
* &amp;lbrack;Export&amp;rbrack; .sbs/.sbsar 파일을 내보낼 수 없는 경우가 있습니다.
* 재질이 비어 있는 경우 &amp;lbrack;Layers&amp;rbrack; [기본 재질 추가] 버튼이 작동하지 않습니다.
* 재질을 복제할 때 &amp;lbrack;Layers&amp;rbrack; 텍스처 타일링이 변경됨
* 이미지를 가져오기 전에 [물리적 크기] 패널이 고정된 경우 &amp;lbrack;물리적 크기&amp;rbrack; 자동 측정이 작동하지 않습니다.
* &amp;lbrack;Scripting&amp;rbrack; 자동 저장 플러그인이 끊어졌습니다.
* &amp;lbrack;UI&amp;rbrack; 내보내기 대화 상자의 간격이 잘못되었습니다.
* &amp;lbrack;UI&amp;rbrack; 트위크의 슬라이더 애니메이션이 더 이상 작동하지 않습니다.
* &amp;lbrack;UI&amp;rbrack; 슬라이더가 필요할 때 정수 값에 스냅되지 않습니다.
* &amp;lbrack;UI&amp;rbrack; 일부 드롭다운 메뉴가 잘립니다.

### **5.0.2 헤이즐넛**

*(릴리스: 2025년 4월 22일)*

**고정:**

* 홈페이지의 &amp;lbrack;Application&amp;rbrack; [뒤로] 버튼이 깨짐
* 이전 버전의 손상된 데이터가 디스크에 있는 경우 &amp;lbrack;Application&amp;rbrack; Sampler이 실행되지 않는 경우가 있습니다
* &amp;lbrack;Application&amp;rbrack; 가져온 이미지가 뷰포트나 레이어 스택에 나타나지 않습니다
* &amp;lbrack;Captis&amp;rbrack; Sampler을 다시 시작한 후에도 Captis IP 주소 필드가 비어 있습니다
* &amp;lbrack;Captis&amp;rbrack; 라이브 카메라 미리 보기는 응용 프로그램 언어가 영어로 설정된 경우에만 작동합니다.
* &amp;lbrack;Export&amp;rbrack; 내보내기 중 충돌 &amp;lbrack;Layers&amp;rbrack; 페인팅이 이전에 저장된 프로젝트에서 작동하지 않는 경우가 있습니다.
* &amp;lbrack;Layers&amp;rbrack; Sampler은 한 채널만 업데이트하면 때때로 모든 텍스처를 업데이트합니다
* &amp;lbrack;Layers&amp;rbrack; 5.0.x로 업그레이드한 후 레이어 스택에서 재질 혼합을 사용할 수 없음
* &amp;lbrack;Layers&amp;rbrack; 이전 Image to Material(AI) 버전으로 프로젝트를 업데이트하면 재질이 모두 검은색으로 표시됩니다
* &amp;lbrack;Layers&amp;rbrack; 지원되지 않는 이미지를 가져오려고 하면 Sampler에서 끊어진 레이어를 만듭니다
* &amp;lbrack;Scripting&amp;rbrack; Python API의 일부가 빈 프로젝트에서 작동하지 않음
* &amp;lbrack;UI&amp;rbrack; 메뉴 항목이 때때로 파일 메뉴에서 오버플로우됩니다

### **5.0.1 헤이즐넛**

*(릴리스: 2025년 3월 20일)*

**추가됨**

* &amp;lbrack;Application&amp;rbrack; 업데이트된 그래픽 드라이버 호환성 목록
* &amp;lbrack;Captis&amp;rbrack; 운영 체제 정책에 의해 HP Z Captis 사용이 차단될 때 팝업 표시
* &amp;lbrack;빠른 작업&amp;rbrack; 도구 설명에서 빠른 작업이 비활성화된 이유를 설명합니다.
* &amp;lbrack;UI&amp;rbrack; 충돌 보고서 창 UI 스타일 지정
* &amp;lbrack;UI&amp;rbrack; 클립보드에 복사할 때 완료를 알리는 토스트를 표시합니다

**고정:**

* &amp;lbrack;2D 보기&amp;rbrack; 구형 투영이 꺼져 있으면 노출 슬라이더가 작동하지 않습니다.
* &amp;lbrack;2D View&amp;rbrack; 텍스처 외부에서 페인팅하면 중단된 선이 만들어집니다
* &amp;lbrack;2D 보기&amp;rbrack; 노출 버튼에 툴팁이 없습니다.
* &amp;lbrack;2D View&amp;rbrack; 정사각형이 아닌 이미지 옆을 확대/축소하면 마우스가 따라오지 않음
* &amp;lbrack;3D 캡처&amp;rbrack; 3D 캡처가 Windows 11 24H2에서 작동하지 않음
* &amp;lbrack;3D 캡처&amp;rbrack; 메시 재구성 단계 동안 Sampler을 종료하면 충돌이 발생합니다
* &amp;lbrack;3D View&amp;rbrack; 계산 시간이 0ms로 표시되는 경우가 있습니다.
* &amp;lbrack;3D View&amp;rbrack; 투영을 직교형에서 원근으로 변경하면 뷰포트가 회색으로 바뀝니다.
* &amp;lbrack;응용 프로그램&amp;rbrack; GPU 기능 확인 시 시작 시 충돌 발생
* &amp;lbrack;Application&amp;rbrack; 설치 중 충돌(&amp;r)
* &amp;lbrack;응용 프로그램 &amp;rbrack; 메타데이터 필드를 마우스 오른쪽 단추로 클릭한 후 종료할 때 충돌 발생
* 운영 체제 파일 탐색기에서 SBSAR을 열 때 &amp;lbrack;Application&amp;rbrack; 환경 조명이 누락됨
* &amp;lbrack;응용 프로그램&amp;rbrack; Sampler이 실행 중일 때 .sbsar을 열면 텍스처 타일링 설정이 변경됩니다
* &amp;lbrack;Captis&amp;rbrack; 일부 메타데이터가 캡처 단계 간에 전송되지 않을 수 있습니다.
* &amp;lbrack;Captis&amp;rbrack; 생성된 자산의 이름이 메타데이터 필드에 입력된 이름이 아닙니다
* &amp;lbrack;Content&amp;rbrack; 샘플 프로젝트는 필터 업데이트를 요청하는 메시지를 표시하지만 이미 최신 상태입니다
* &amp;lbrack;Filters&amp;rbrack; 일반/Height 조정 필터에 아이콘이 없음
* &amp;lbrack;Layers&amp;rbrack; 이미지 가져오기 레이어에서 이미지를 변경할 수 없습니다.
* 업스케일 필터를 사용할 때 &amp;lbrack;Layers&amp;rbrack;가 충돌합니다.
* &amp;lbrack;Layers&amp;rbrack; 이전 이미지가 있는 프로젝트를 Material로 업데이트하면 재질이 모두 검은색으로 바뀝니다.
* 에셋을 만든 후 즉시 레이어 스택을 수정하면 렌더링이 중단됩니다(&amp;lbrack; Rendering&amp;rbrack;)
* &amp;lbrack;Scripting&amp;rbrack; 프로젝트에 에셋이 없으면 자동 저장 플러그인이 충돌합니다.
* 브러시 도구 모음에 &amp;lbrack;도구&amp;rbrack; 브러시 크기 값이 없습니다.
* &amp;lbrack;UI&amp;rbrack; 응용 프로그램 언어를 변경해도 홈 화면의 일부 레이블이 업데이트되지 않습니다
* &amp;lbrack;UI&amp;rbrack; 슬라이더 텍스트 필드에서 Esc 또는 Enter 키를 눌러도 포커스가 손실되지 않습니다.
* 속성 패널에서 모두 재설정 버튼과 자산 이름 레이블이 겹칩니다
* 패널 고정 및 고정 해제 시 &amp;lbrack;UI&amp;rbrack; 문제
* &amp;lbrack;UI&amp;rbrack; 오버레이 패널에서 스크롤하면 기본 창에서도 스크롤됩니다.
* 홈 화면의 최근 프로젝트 섹션에서 목록 보기로 전환하는 &amp;lbrack;UI&amp;rbrack;이 작동하지 않습니다
* &amp;lbrack;UI&amp;rbrack; 뷰포트 표시 모드 버튼 아이콘은 항상 2D/3D를 표시합니다

### **5.0.0 헤이즐넛**

*(릴리스: 2025년 2월 20일)*

**추가됨**

* &amp;lbrack;Onboarding&amp;rbrack; 학습 콘텐츠, 샘플 프로젝트, 빠른 작업 및 최근 프로젝트에 빠르게 액세스할 수 있는 새 홈페이지.
* &amp;lbrack;Onboarding&amp;rbrack; 홈페이지 및 전용 패널에서 액세스할 수 있는 새로운 빠른 작업으로 빠르게 시작하기
* &amp;lbrack;Onboarding&amp;rbrack; &amp;lbrack;Content&amp;rbrack; 빠른 작업은 레이어 스택을 가장 많이 사용되는 레이어로 채우는 미리 정의된 워크플로우입니다
* &amp;lbrack;Onboarding&amp;rbrack; 빠른 작업 또는 사용자 정의 프로젝트를 통해 새로운 빠른 시작 메뉴를 통해 새 프로젝트를 만들 수 있습니다.
* &amp;lbrack;Onboarding&amp;rbrack; 전용 버튼을 통해 홈페이지에서 직접 빈 프로젝트를 만들 수 있는 가능성
* &amp;lbrack;3D View&amp;rbrack; 새로운 렌더링 기능(코팅, 광택, 투명도, 표면 아래 분산 등의 속성)과 Substance 에코시스템 전반의 시각적 일관성을 제공하는 새로운 고급 래스터라이저 및 패스파트레서
* 이제 3D 보기에서 직접 &amp;lbrack;3D 보기&amp;rbrack; 뷰어 설정에 액세스할 수 있습니다.
* &amp;lbrack;3D View&amp;rbrack; 렌더링 스냅샷을 클립보드 또는 파일에 저장할 수 있음
* &amp;lbrack;3D View&amp;rbrack; 장면 원점을 시각화하기 위한 격자 표시
* &amp;lbrack;3D View&amp;rbrack; 그라운드 평면에서 그림자와 반사를 포착할 수 있도록 활성화
* &amp;lbrack;3D View&amp;rbrack; 그라운드 평면의 반사 및 불투명 정도를 제어합니다
* &amp;lbrack;3D 캡처&amp;rbrack; 바닥에 메시 배치
* &amp;lbrack;Application&amp;rbrack; 응용 프로그램 시작 시 하드웨어 호환성 확인
* &amp;lbrack;Application&amp;rbrack; 충돌 발생 직후 충돌 보고 창이 열립니다
* &amp;lbrack;Content&amp;rbrack; 샘플 프로젝트를 열어 쉽게 시작
* &amp;lbrack;Export&amp;rbrack; USD 파일의 Adobe Standard 재질 셰이더 내보내기
* &amp;lbrack;Generative AI&amp;rbrack; 이미지를 [텍스처] 작업 과정에 대한 입력으로 사용할 때 &quot;추론하지 않음&quot; 태그를 확인하십시오.
* &amp;lbrack;프로젝트&amp;rbrack; 축소판은 프로젝트 열기 속도를 높이기 위해 프로젝트 파일 내에 저장됩니다.
* &amp;lbrack;프로젝트&amp;rbrack; 다른 모드(캐시 없음, 라이트 캐시, 전체 캐시)로 프로젝트 파일 내에 캐시 데이터를 저장하도록 환경 설정에서 설정합니다.
* &amp;lbrack;Scripting&amp;rbrack; &amp;lbrack;Breaking change&amp;rbrack; Qt6.15로의 Qt 마이그레이션 - 기존 플러그인의 호환성 영향
* 이제 &amp;lbrack;Scripting&amp;rbrack; 기본 플러그인 및 스크립트 폴더가 Documents 폴더에 있습니다.
* &amp;lbrack;Scripting&amp;rbrack; 기본 Sampler 패널과의 시각적 일관성을 위한 플러그인용 새로운 UI
* &amp;lbrack;Scripting&amp;rbrack; Sampler 플러그인 기능을 확인하기 위한 2가지 플러그인 예 액세스
* &amp;lbrack;Scripting&amp;rbrack; 새로운 open_3d_catpure() 함수
* &amp;lbrack;Scripting&amp;rbrack; 레이어를 삽입할 때 레이어를 대상 위치의 위나 아래에 삽입할지 여부를 제어합니다

**고정:**

* &amp;lbrack;3D 캡처&amp;rbrack; macOS에서 개체 캡처를 시작할 수 없는 경우 충돌
* &amp;lbrack;응용 프로그램(&amp;r); 종료 시 충돌
* 프로젝트 패널에 에셋을 추가하는 동안 &amp;lbrack;Application&amp;rbrack; 종료 시 멈춤
* &amp;lbrack;Application&amp;rbrack; 프로젝트 에셋의 이름을 바꾸는 작업은 enter 키를 누르지 않으면 작동하지 않습니다.
* &amp;lbrack;Application&amp;rbrack; 실행 취소 및 재실행 메뉴 항목이 비활성화되어야 할 때 비활성화되지 않습니다.
* &amp;lbrack;Assets&amp;rbrack; 에셋 패널의 모든 라이브러리 섹션에서 에셋을 삭제할 수 없음
* &amp;lbrack;Content&amp;rbrack; Atlas creator - 기존 불투명도 맵이 있는 경우 사용
* &amp;lbrack;내용&amp;rbrack; 색상 ID 혼합 - 기본 색상의 색상 피킹 수정
* &amp;lbrack;Layers&amp;rbrack; 생성기 사용 시 쓸모없는 계산 방지
* &amp;lbrack;Layers&amp;rbrack; 생성기를 조정하면 너무 많은 계산이 트리거될 수 있습니다.
* &amp;lbrack;성능&amp;rbrack; GPU 메모리 관리 개선
* 앱을 다시 시작할 때 &amp;lbrack;Performance&amp;rbrack; 렌더링 캐시를 사용하지 못할 수 있습니다.
* &amp;lbrack;Resources&amp;rbrack; 읽기 전용 파일이 에셋 패널에 표시되지 않음
* &amp;lbrack;스크립팅&amp;rbrack; 다른 레이어를 추가한 후 레이어 재사용 허용
* &amp;lbrack;스크립팅&amp;rbrack; 한 스크립트에서 레이어 스택 구조를 여러 번 변경하면 실패할 수 있습니다

**제거됨:**

* &amp;lbrack;Application&amp;rbrack; .dng 및 .nef 이미지 파일에 대한 지원 제거

## 버전 4

### **4.5.2 GRUYERE**

*(릴리스: 2024년 11월 7일)*

**고정:**

* &amp;lbrack;내용&amp;rbrack; 자르기, 자수 및 Height 혼합 필터

### **4.5.1 GRUYERE**

*(릴리스: 2024년 7월 30일)*

**고정:**

* &amp;lbrack;Layers&amp;rbrack; 회색조 마스크 페인팅이 작동하지 않으며, [복제 도장], [페인트 비틀기], [내용 인식 채우기]와 같은 도구에 영향을 줍니다

### **4.5.0 GRUYERE**

*(릴리스: 2024년 7월 18일)*

**추가됨**

* &amp;lbrack;Interoperability&amp;rbrack; UE5, Blender, Maya, 3DsMax Unity로 재질 보내기
* &amp;lbrack;내용&amp;rbrack; 새 텍스처 생성기 범주 - 그레이디언트
* &amp;lbrack;내용&amp;rbrack; HDRI 도구 - 새 환경 회전 필터

**고정:**

* &amp;lbrack;노출 매개 변수&amp;rbrack; .sbsar 입력 값을 노출해도 작동하지 않음
* &amp;lbrack;Layers&amp;rbrack; 기본 색상이 회색 음영 이미지로 빨간색으로 변합니다.
* &amp;lbrack;렌더링&amp;rbrack; 색상 채널에 사용된 회색 음영 이미지의 색상 공간이 잘못되었습니다.
* &amp;lbrack;스크립팅&amp;rbrack; 내보내기 사전 설정을 사용하면 원하는 채널을 내보내지 못하는 경우가 있습니다
* &amp;lbrack;Content&amp;rbrack; Dirt - 이미지에 Dirt 필터를 적용하면 검은색 표준이 생성됩니다
* &amp;lbrack;Content&amp;rbrack; 엠보스 - 엠보스 필터에서 패턴 비율이 0과 1 사이의 직선이 아닙니다.
* &amp;lbrack;Content&amp;rbrack; 바둑판식으로 만들기 - 일반 및 Height 일관성 향상

### **4.4.1 FONDUE**

*(릴리스: 2024년 6월 6일)*

**고정:**

* &amp;lbrack;Content&amp;rbrack; Dirt 필터가 없습니다.
* 이미지를 텍스처로 사용할 때 &amp;lbrack;생성형 AI&amp;rbrack; 네트워크 오류가 발생하는 경우가 있습니다.

### **4.4.0 FONDUE**

*(릴리스: 2024년 5월 23일)*

**추가됨:**

* 이제 &amp;lbrack;Application&amp;rbrack; 3D 캡처 캐시가 별도의 하위 폴더에 저장됩니다.
* &amp;lbrack;생성형 인공지능&amp;rbrack; 텍스처에 이미지(베타)
* &amp;lbrack;생성형 인공지능&amp;rbrack; 텍스트 패턴(베타)
* &amp;lbrack;생성형 인공지능&amp;rbrack; 텍스트-텍스처(Beta)
* &amp;lbrack;Scripting&amp;rbrack; 에셋에 이제 &#39;리소스&#39; 속성이 있습니다.
* &amp;lbrack;스크립팅&amp;rbrack; 레이어에는 이제 &#39;output_usage&#39; 속성이 있습니다

**고정:**

* &amp;lbrack;Application&amp;rbrack; 손상된 프로젝트 파일을 열 때 충돌 발생
* &amp;lbrack;Application&amp;rbrack; 프로젝트에 손상된 에셋이 포함된 경우 충돌 발생
* &amp;lbrack;Windows에서 모니터 플러그를 뽑으면 응용 프로그램 &amp;rbrack;이 충돌합니다.
* &amp;lbrack;Application&amp;rbrack; Windows 작업 표시줄의 잘못된 응용 프로그램 아이콘
* &amp;lbrack;응용 프로그램&amp;rbrack; 기본 구성 파일 손상으로 인해 파일이 삭제될 수 있습니다.
* &amp;lbrack;Application&amp;rbrack; 패널이 팝업 앞에 표시됨
* &amp;lbrack;내용&amp;rbrack; 텍스처 생성기에 흐린 축소판이 있음
* .sbs/.sbsar를 내보낼 때 가져온 이미지에서 생성된 불투명도 채널(&amp;lbrack;Export&amp;rbrack;)
* &amp;lbrack;Filters&amp;rbrack; 업스케일은 입력 레이어에 따라 충돌할 수 있습니다.
* &amp;lbrack;Generative AI&amp;rbrack; 서비스에서 예기치 않은 결과를 받으면 발생할 수 있는 충돌이 발생합니다
* &amp;lbrack;Scripting&amp;rbrack; 환경 변수에서 플러그인을 자동 로드할 때 충돌함
* &amp;lbrack;Scripting&amp;rbrack; API를 사용하여 출력 사용을 할당할 때 충돌이 발생할 수 있습니다.

### **4.3.3 EMPANADA**

*(릴리스: 2024년 3월 26일)*

**추가됨:**

* &amp;lbrack;3D 캡처&amp;rbrack; 사후 처리 중 새로운 고급 자동 UV 매개 변수
* &amp;lbrack;Filters&amp;rbrack; 천공 필터: 사용자 정의 패턴을 반전하고 크기를 변경하는 기능

**고정:**

* macOS에서 &amp;lbrack;3D 캡처&amp;rbrack; 기본 색상이 잘못될 수 있습니다.
* &amp;lbrack;3D 캡처&amp;rbrack; 새 버전을 처리할 때 충돌 발생
* &amp;lbrack;3D 캡처&amp;rbrack; 후처리 단계가 macOS에서 충돌할 수 있음
* &amp;lbrack;3D 캡처&amp;rbrack; 메시 변형 레이어가 잘못 렌더링될 수 있습니다
* &amp;lbrack;Application&amp;rbrack;에서 이전 인스턴스가 내보내는 동안 Sampler을 시작할 때 충돌이 발생합니다
* &amp;lbrack;Application&amp;rbrack; Sampler이 처음으로 시작되면 잠시 응답하지 않습니다
* &amp;lbrack;내보내기&amp;rbrack; 비등방성 각도 맵이 내보내지지 않음
* &amp;lbrack;Filters&amp;rbrack; 레이어 스택에 천 직조를 추가하면 충돌이 발생할 수 있습니다.
* &amp;lbrack;Filters&amp;rbrack; 레이어 스택에 엠보스를 추가하면 충돌이 발생할 수 있습니다.
* 32비트 이미지를 사용할 때 &amp;lbrack;Filters&amp;rbrack; 내용 인식 채우기가 충돌함
* &amp;lbrack;Filters&amp;rbrack; 엠보스: 아래 레이어의 불투명도가 완전히 무시되지 않음
* &amp;lbrack;Filters&amp;rbrack; 채우기: 혼합 모드가 Designer 및 Painter에서 작동하지 않음
* &amp;lbrack;Filters&amp;rbrack; 자수: 자동 색상 선택이 해제됨
* &amp;lbrack;Preferences&amp;rbrack; 3D 캡처 캐시에 대해 지원되지 않는 경로 설정 방지
* &amp;lbrack;기본 설정&amp;rbrack; 표준 형식 기본 설정이 작동하지 않음
* &amp;lbrack;Scripting&amp;rbrack; Asset.export_material의 채널 매개 변수는 대/소문자를 구분합니다

### **4.3.2 EMPANADA**

*(릴리스: 2024년 2월 22일)*

**고정:**

* &amp;lbrack;Application&amp;rbrack; Windows에서 네트워크 공유에 프로젝트를 저장하면 프로젝트 파일이 손상됨

### **4.3.1 EMPANADA**

*(릴리스: 2024년 2월 15일)*

**고정:**

* &amp;lbrack;3D 캡처&amp;rbrack; 마스크를 일괄 생성하는 동안 이미지 파일에 액세스할 수 없게 되면 충돌이 발생합니다
* &amp;lbrack;Export&amp;rbrack; 자르기 또는 상대적 입력 정책 레이어가 있는 재질을 내보내면 잘못된 결과가 나옵니다
* &amp;lbrack;Layers&amp;rbrack; 레이어 스택을 렌더링할 때 드물게 충돌이 발생합니다
* &amp;lbrack;Filters&amp;rbrack; 자수 - MacOS에서 재료 입력을 사용할 때 문제 수정
* &amp;lbrack;Filters&amp;rbrack; 스타일화 - 텍스처 생성기 지원
* &amp;lbrack;Filters&amp;rbrack; 패턴 - 매개변수 이름 수정
* &amp;lbrack;Localization&amp;rbrack; &quot;다른 이름으로 저장...&quot; 도움말 메뉴의 하드웨어 정보 창에 현지화되지 않은 메시지가 표시됩니다.

### **4.3.0 EMPANADA**

*(릴리스: 2024년 1월 25일)*

**추가됨**

* &amp;lbrack;Assets&amp;rbrack; 새로운 에셋 유형: 텍스처 생성기
* &amp;lbrack;Assets&amp;rbrack; 스타터 에셋에 포함된 새 재질
* &amp;lbrack;Assets&amp;rbrack; [속성] 패널의 이미지 매개 변수에 대한 새로운 에셋 선택기
* &amp;lbrack;Assets&amp;rbrack; 에셋 패널의 텍스처 생성기를 속성 패널의 이미지 선택기로 드래그하여 놓기
* &amp;lbrack;Assets&amp;rbrack; 운영 체제 파일 탐색기에서 텍스처 생성기를 드래그하여 놓기
* &amp;lbrack;Assets&amp;rbrack; 필터는 이미지 입력의 사용자 태그를 통해 맞춤 생성기를 제안할 수 있습니다.
* &amp;lbrack;Assets&amp;rbrack; Texture Generators는 사용자 태그를 통해 제안해야 할 필터를 정의할 수 있습니다.
* &amp;lbrack;내용&amp;rbrack; 새로운 원근 자르기 필터
* &amp;lbrack;콘텐츠&amp;rbrack; 새로운 스타일화 필터
* &amp;lbrack;내용&amp;rbrack; 칠 필터의 혼합 모드
* &amp;lbrack;Content&amp;rbrack; 자수 필터 업데이트
* &amp;lbrack;Content&amp;rbrack; 업데이트된 페인트 감싸기 필터
* &amp;lbrack;Content&amp;rbrack; 텍스처 생성기를 지원하도록 모든 필터를 업데이트했습니다.
* &amp;lbrack;Layers&amp;rbrack; 레이어 스택에 추가할 때 텍스처 생성기 출력 채널을 선택하는 기능
* &amp;lbrack;Layers&amp;rbrack; 텍스처 생성기에서 사전 설정을 쉽게 나열하고 적용할 수 있는 기능
* &amp;lbrack;Layers&amp;rbrack; 이미지 피커에서 텍스처 생성기 미리 보기 표시
* &amp;lbrack;Layers&amp;rbrack; 텍스처 생성기 매개 변수를 노출하고 내보낼 수 있습니다.
* &amp;lbrack;Layers&amp;rbrack; 텍스처 가져오기 생성 템플릿으로 단일 이미지를 가져올 때 기본 색상 사용을 할당합니다
* 속성 패널의 이미지 선택기에서 호환되지 않는 파일을 드래그 앤 드롭하려고 할 때 &amp;lbrack;Layers&amp;rbrack; 피드백
* &amp;lbrack;Layers&amp;rbrack; 가져온 이미지의 알파 채널에서 불투명도 채널 생성
* &amp;lbrack;Layers&amp;rbrack; Image to Material(AI) 범주를 변경할 때 계산 속도가 더 빠름
* &amp;lbrack;Layers&amp;rbrack; 생성 템플릿 사용 후 가장 관련 있는 레이어 선택
* &amp;lbrack;Layers&amp;rbrack; 이제 고급 매개 변수 그룹의 슬라이더로 위치 위젯을 조정할 수 있습니다.
* &amp;lbrack;Export&amp;rbrack; 원시 숫자 대신 대기열에 백분율 표시
* &amp;lbrack;Interoperability&amp;rbrack; 불투명도 채널이 이제 Painter으로 전송할 때 알파 채널로 인식됩니다.
* 하드웨어 정보를 표시하고 저장하는 &amp;lbrack;Application&amp;rbrack; New 대화 상자
* &amp;lbrack;응용 프로그램&amp;rbrack; 모든 프로젝트의 기본 Height 배율을 변경하는 새 환경 설정
* &amp;lbrack;Application&amp;rbrack; 오래된 에셋의 표시 방식 개선
* &amp;lbrack;Scripting&amp;rbrack; 새로운 asset.documentResolution() 및 asset.documentResolution() 함수
* &amp;lbrack;Scripting&amp;rbrack; 새 select_asset() 함수
* &amp;lbrack;Scripting&amp;rbrack; 텍스처 생성기용 Python API
* &amp;lbrack;Scripting&amp;rbrack; get_project_assets()가 이제 3D 개체를 반환합니다.
* &amp;lbrack;UI&amp;rbrack; 에셋 패널에서 에셋 축소판 크기를 변경할 수 있습니다
* &amp;lbrack;UI&amp;rbrack; 업데이트된 뷰포트 표시 아이콘

**고정:**

* &amp;lbrack;2D 보기&amp;rbrack; 마우스 휠을 사용한 확대/축소가 244%에서 차단됨
* &amp;lbrack;Application&amp;rbrack;은 그래픽 API를 초기화할 때 시작할 때 충돌합니다.
* 프로젝트 이름에 # 문자가 포함된 경우 &amp;lbrack;Application&amp;rbrack;Crash
* &amp;lbrack;응용 프로그램&amp;rbrack; 이전 프로젝트를 열 때 충돌이 발생할 수 있습니다.
* &amp;lbrack;응용 프로그램&amp;rbrack; 현재 프로젝트를 다시 열면 충돌이 발생할 수 있습니다
* &amp;lbrack;Application&amp;rbrack; 저장되지 않은 경우 프로젝트를 닫을 때 일부 프로젝트 변경 사항이 등록되지 않으며 경고 없이 유실됩니다
* 동일한 이름의 파일을 여러 개 사용할 때 &amp;lbrack;Export&amp;rbrack; .sbs/.sbsar 내보내기 문제
* &amp;lbrack;Export&amp;rbrack; 내보낸 회색 음영 이미지 .sbs/.sbsar 파일의 색상 공간이 잘못되었습니다.
* &amp;lbrack;Filters&amp;rbrack; 불투명도 혼합 비헤이비어 문제
* &amp;lbrack;Layers&amp;rbrack; .svg 파일이 때때로 올바른 해상도로 렌더링되지 않습니다
* &amp;lbrack;성능&amp;rbrack; 일부 프로젝트 저장이 필요 없음
* &amp;lbrack;프로젝트&amp;rbrack; 이전 프로젝트를 가져오면 연결된 사전 설정이 로드되지 않음
* &amp;lbrack;Scripting&amp;rbrack; 첫 번째로 삽입된 레이어의 매개 변수를 가져올 수 없음
* &amp;lbrack;UI&amp;rbrack; 에셋에 마우스를 가져가면 미리보기 팝업이 잘못된 위치 또는 화면에 나타날 수 있습니다
* 시작 화면 상단에서 도킹되지 않은 패널(&amp;lbrack;UI&amp;rbrack;)이 표시되고 사용할 수 있습니다

### **4.2.2 DORAYAKI**

*(릴리스: 2023년 12월 5일)*

**추가됨:**

* &amp;lbrack;3D 캡처&amp;rbrack; 3D 캡처가 이제 Windows에서 5%~10% 더 빨라졌습니다.
* &amp;lbrack;3D 캡처&amp;rbrack; 데시메이션 전에 메시 정리를 개선합니다
* &amp;lbrack;엔진&amp;rbrack; Substance 엔진을 버전 9.0.3으로 업데이트
* &amp;lbrack;Layers&amp;rbrack; 내용 인식 채우기: 업스트림 업데이트, 다양한 사용 사례 수정 및 Linux 지원

**고정:**

* &amp;lbrack;3D 캡처&amp;rbrack; 정렬 후 &quot;뒤로&quot;를 클릭하면 &quot;다음&quot;이 포인트 클라우드를 업데이트하지 않음
* 프로젝트에 추가된 후 구멍과 함께 표시된 &amp;lbrack;3D 캡처&amp;rbrack; 메시
* &amp;lbrack;응용 프로그램(&amp;r); 3D 캡처 후 전체 화면 모드를 종료하면 충돌이 발생합니다.
* &amp;lbrack;응용 프로그램&amp;rbrack;이 제작된 이미지 파일과 충돌합니다.
* &amp;lbrack;Application&amp;rbrack; Sampler을 종료할 때 &#39;모든 라이브러리&#39;에 있는 경우 다시 시작할 때 [에셋] 패널이 비어 있게 됩니다
* 자료를 내보낼 때 &amp;lbrack;Application&amp;rbrack; 메모리 누수
* &amp;lbrack;Application&amp;rbrack; 이전 Sampler 버전에서 프로젝트 저장을 열면 충돌이 발생할 수 있습니다
* &amp;lbrack;Application&amp;rbrack; 3D 메시 변환 실패 시 잠재적 충돌
* &amp;lbrack;Application&amp;rbrack; Sampler 실행 중 .sbsar를 열 때 자동 충돌
* &amp;lbrack;Export&amp;rbrack; 사용자 정의 사용으로 .sbs/.sbsar 파일을 내보낼 때 충돌함
* &amp;lbrack;Export&amp;rbrack; 내보낸 표준 맵은 사용자 설정에 관계없이 항상 DirectX 상태입니다.
* &amp;lbrack;내보내기&amp;rbrack; macos에서 3D 오브젝트를 FBX 파일로 내보내는 기능이 작동하지 않습니다
* 자수 필터가 있는 레이어 스택을 .sbs/.sbsar 파일로 내보낼 때 &amp;lbrack;Export&amp;rbrack;의 불일치
* &amp;lbrack;내보내기&amp;rbrack; 때때로 .sbs/.sbsar 파일 내보내기가 작동하지 않습니다
* &amp;lbrack;Export&amp;rbrack; .sbs/.sbsar 파일 이미지를 내보낼 때 비트 심도가 올바르지 않은 경우가 있습니다.
* &amp;lbrack;Layers&amp;rbrack; 스플래터 레이어를 보이지 않게 하면 첫 번째 하위 레이어가 대신 렌더링됩니다.
* &amp;lbrack;Layers&amp;rbrack; 명도/대비 레이어에서 마스크를 로드할 때 충돌 발생
* &amp;lbrack;Layers&amp;rbrack; 레이어 삭제 후 잘못된 오류 메시지가 표시됨
* 에셋을 다운그레이드할 때 &amp;lbrack;Layers&amp;rbrack; 충돌이 발생할 수 있습니다
* &amp;lbrack;Layers&amp;rbrack; 일부 출력은 [채널 설정] 패널에서 강제로 사용하지 않으면 입력에 연결되지 않습니다
* &amp;lbrack;물리적 크기&amp;rbrack; 참조 레이어 드롭다운이 실수로 재설정될 수 있음
* &amp;lbrack;UI&amp;rbrack; 템플릿 정보 가져오기 아이콘을 업데이트해야 합니다.
* 뷰포트 레이아웃이 변경될 때마다 &amp;lbrack;UI&amp;rbrack; 뷰포트 단축키 팁이 표시됨

### **4.2.1 DORAYAKI**

*(릴리스: 2023년 9월 21일)*

**추가됨 :**

* &amp;lbrack;Content&amp;rbrack; Image to Material - 일반 맵에서 마이크로디테일 생성 개선
* &amp;lbrack;Content&amp;rbrack; Image to Material - 새로운 흐림 강도 매개 변수
* &amp;lbrack;Layers&amp;rbrack; 이미지 가져오기 레이어에 이미지를 추가할 수 있습니다.
* 이미지 가져오기 레이어에서 제거(&amp;lbrack;Layers&amp;rbrack;)
* &amp;lbrack;Layers&amp;rbrack; 이제 잘못된 레이어를 삭제할 수 있습니다.
* &amp;lbrack;2D 보기&amp;rbrack; 채널을 다시 순환하는 Shift+C 단축키
* &amp;lbrack;3D 캡처&amp;rbrack; 사용자가 20개 미만의 이미지를 가져올 때 경고 알림 표시
* &amp;lbrack;응용 프로그램&amp;rbrack; 기본 질감 타일링 값을 설정하는 새 환경 설정
* &amp;lbrack;Onboarding&amp;rbrack; Image to Material(AI) 및 Upscale에 대한 자습서 UI 업데이트
* &amp;lbrack;Scripting&amp;rbrack; 3D 캡처 API: Capture3dState가 정렬되도록 설정된 경우 DatasetInfo에 더 많은 데이터가 있습니다.
* &amp;lbrack;Scripting&amp;rbrack; create_asset()에 대한 새 select_asset 인수. 새 함수: wait_for_computation() 및 clear_render_cache()

**고정:**

* 자르기 영역이 매우 작을 때 &amp;lbrack;Layers&amp;rbrack;가 충돌함
* &amp;lbrack;Layers&amp;rbrack; 자르기 필터를 추가하거나 수정할 때 충돌이 발생함
* &amp;lbrack;Layers&amp;rbrack; 자르기 영역을 정사각형으로 만들면 잘못된 재질 출력 해상도가 나옵니다
* 여러 레이어가 비활성화된 경우 &amp;lbrack;Layers&amp;rbrack; 출력이 때때로 사라지는 경우
* &amp;lbrack;Layers&amp;rbrack; 렌더 캐시가 이미지-재질(AI) 및 업스케일 필터와 함께 제대로 무효화되지 않을 수 있습니다.
* 경고 팝업에서 &quot;이 메시지를 다시 표시하지 않음&quot;을 선택할 때 &amp;lbrack;Layers&amp;rbrack; Unable to add Upscale filter
* &amp;lbrack;Layers&amp;rbrack; 수정 후 자수 필터에서 이미지를 복원할 수 없음
* &amp;lbrack;Export&amp;rbrack; 표준 형식을 변경할 때 내보낸 표준 맵 해상도가 변경됩니다.
* &amp;lbrack;내보내기&amp;rbrack; 환경을 내보낼 때 &quot;\_environment&quot; 파일 이름 접미어를 제거합니다.
* &amp;lbrack;Export&amp;rbrack; 레이어 스택에 뒤틀기 변형 레이어가 있는 경우 .sbsar 파일을 내보낼 수 없습니다
* &amp;lbrack;2D View&amp;rbrack; 해상도 변경 시 &quot;화면에 맞추기&quot;가 작동하지 않음
* &amp;lbrack;Application&amp;rbrack; 계산 중에 응용 프로그램 창을 닫은 후 응용 프로그램 프로세스가 계속 실행 중일 수 있습니다
* &amp;lbrack;응용 프로그램(&amp;r); 종료 시 충돌
* &amp;lbrack;응용 프로그램&amp;rbrack; GPU 가속 신경망을 전환할 때 렌더링 캐시를 무효화합니다.
* &amp;lbrack;Scripting&amp;rbrack; 플러그인을 기존 패널 이름으로 지정하면 예기치 않은 동작이 발생합니다
* &amp;lbrack;UI&amp;rbrack; 도구 설명이 있는 항목을 클릭하면 다시 시작할 때까지 도구 설명이 사라집니다
* 에셋 전환 시 &amp;lbrack;UI&amp;rbrack; Height 비율 값이 변경될 수 있음
* &amp;lbrack;UI&amp;rbrack; 콤보 상자의 잘못된 여백

### **4.2 DORAYAKI**

*(릴리스: 2023년 9월 5일)*

**추가됨:**

* &amp;lbrack;Content&amp;rbrack; AI(Image to Material) 및 Delighter 필터를 크게 개선했습니다.
* &amp;lbrack;Content&amp;rbrack; 새로운 업스케일 필터
* &amp;lbrack;Content&amp;rbrack; 이제 자르기 필터에 동적 출력 해상도가 있습니다.
* &amp;lbrack;재료 생성 템플릿&amp;rbrack; 문서 크기 추가 설정.
* &amp;lbrack;재질 생성 템플릿&amp;rbrack; 새로운 &quot;자르기 추가&quot; 토글 버튼.
* &amp;lbrack;재료 생성 템플릿&amp;rbrack; 새로운 &quot;설비 확장&quot; 토글
* &amp;lbrack;재료 생성 템플릿&amp;rbrack; 가져온 이미지 크기 표시
* &amp;lbrack;재질 생성 템플릿&amp;rbrack; 가져온 이미지 중 일부를 사용할 수 없는 경우 피드백 제공
* &amp;lbrack;재료 생성 템플릿&amp;rbrack; 이미지 크기가 일관되지 않을 때 경고
* &amp;lbrack;재료 생성 템플릿&amp;rbrack; 새 경고 및 도구 설명
* &amp;lbrack;Layers&amp;rbrack; 레이어 스택의 레이어 해상도를 표시합니다.
* 이제 &amp;lbrack;Layers&amp;rbrack; 레이어 계산 해상도를 문서 크기 또는 입력 크기로 설정할 수 있습니다
* &amp;lbrack;Layers&amp;rbrack; 레이어 스택의 레이어 해상도 표시
* &amp;lbrack;Layers&amp;rbrack; 해당되는 경우 레이어 해상도 정책을 문서 또는 레이어 입력으로 전환합니다.
* &amp;lbrack;Layers&amp;rbrack; 업스케일 필터가 수동으로 추가되면 사용자에게 경고하고 몇 가지 문서를 제공합니다.
* &amp;lbrack;Layers&amp;rbrack; 선형 업스케일을 수행할 때 사용자에게 경고하고 대신 업스케일 필터를 사용하도록 제안합니다.
* 이제 레이어 스택을 조정할 때 렌더링 시간을 개선하기 위해 &amp;lbrack;Layers&amp;rbrack; AI(Image to Material) 레이어 계산을 더 빨리 취소할 수 있습니다
* 이제 레이어 스택을 조정할 때 렌더링 시간을 개선하기 위해 &amp;lbrack;Layers&amp;rbrack; 업스케일 레이어 계산을 더 빠르게 취소할 수 있습니다
* &amp;lbrack;Export&amp;rbrack; 내보낸 텍스처의 재정의 해상도 허용
* 이제 내보낼 &amp;lbrack;내보내기&amp;rbrack; 채널 목록이 정렬됩니다.
* &amp;lbrack;Export&amp;rbrack; 내보낼 채널 목록에 채널 해상도 표시
* &amp;lbrack;응용 프로그램&amp;rbrack; GPU 가속 신경망을 활성화하거나 비활성화하는 새 환경 설정
* &amp;lbrack;UI&amp;rbrack; 해상도 드롭다운 향상
* &amp;lbrack;UI&amp;rbrack; 메쉬 변환, 메쉬 포스트 프로세스 및 직조 필터용 새 아이콘
* &amp;lbrack;UI&amp;rbrack; &quot;공유&quot; 패널의 이름을 &quot;내보내기&quot;로 변경
* &amp;lbrack;스크립팅&amp;rbrack; 내보내기 API에 레이어 출력 해상도 추가
* &amp;lbrack;Scripting&amp;rbrack; 이미지 가져오기 API에 자르기, 확대 및 문서 크기 추가
* &amp;lbrack;Onboarding&amp;rbrack; 새 자습서
* &amp;lbrack;Onboarding&amp;rbrack; 시작 및 새로운 기능 화면 업데이트 내용
* &amp;lbrack;엔진&amp;rbrack; Substance 엔진을 버전 9.0.1로 업데이트

**고정:**

* &amp;lbrack;3D 캡처&amp;rbrack; 정렬 설정 매개변수의 정밀도 옵션 이름 개선
* &amp;lbrack;응용 프로그램&amp;rbrack; 16차원이 아닌 이미지를 가져오면 충돌이 발생할 수 있습니다.
* 프로젝트 패널에서 에셋을 복제할 때 &amp;lbrack;Application&amp;rbrack;가 충돌함
* 프로젝트 패널에서 에셋을 전환할 때 &amp;lbrack;Application&amp;rbrack;가 충돌함
* &amp;lbrack;Content&amp;rbrack; Snow 필터에 대한 사용자 정의 마스크 페인팅이 제대로 작동하지 않습니다
* &amp;lbrack;노출된 매개변수&amp;rbrack; 재료를 전환할 때 노출된 매개변수 변경 사항이 손실될 수 있습니다.
* &amp;lbrack;Interoperability&amp;rbrack; 내보내기 패널에서 자료를 보내면 충돌이 발생할 수 있습니다
* &amp;lbrack;Layers&amp;rbrack; 내용 인식 채우기는 단일 이미지 입력에서 재료 입력으로 전환할 때 계산을 중지합니다.
* &amp;lbrack;Layers&amp;rbrack; 재질이 포함된 환경 조명을 복제한 후 충돌
* 이미지 파일의 이름이 바뀐 경우 이미지 가져오기 레이어가 [속성] 패널에 잘못된 이미지 이름을 표시함(&amp;lbrack; Layers&amp;rbrack;)
* &amp;lbrack;Layers&amp;rbrack; 비활성 레이어에 회전자가 표시되는 경우가 있습니다
* &amp;lbrack;Layers&amp;rbrack; 때때로 이미지 가져오기 레이어에서 이미지의 출력 사용을 변경할 수 없습니다
* 작성 템플릿 창의 &amp;lbrack;Layers&amp;rbrack; Typos
* &amp;lbrack;UI&amp;rbrack; 3D 뷰포트 온보딩 도구 설명에 포커스 문제가 있음
* 파일 이름이 너무 길면 &amp;lbrack;UI&amp;rbrack; 이미지 이름이 오버플로될 수 있습니다.
* 지우개를 사용할 때 &amp;lbrack;UI&amp;rbrack; 부 브러시 도구 모음 레이아웃 문제
* 뷰어 설정 패널에서 일부 언어의 &amp;lbrack;UI&amp;rbrack; 문자열이 잘립니다
* &amp;lbrack;UI&amp;rbrack; 뷰포트 도구 설명 팝업이 표시되는 동안 &quot;space&quot;를 누르면 새 프로젝트가 생성됩니다

### **4.1.2 CANNOLI**

*(릴리스: 2023년 6월 20일)*

**고정:**

* &amp;lbrack;Layers&amp;rbrack; Substance 재질 및 필터를 수정할 때 메모리 누수가 발생하여 충돌이 발생합니다.

### **4.1.1 CANNOLI**

*(릴리스: 2023년 6월 6일)*

**추가됨**

* &amp;lbrack;엔진&amp;rbrack; Substance 엔진을 버전 9.0으로 업데이트
* &amp;lbrack;Interoperability&amp;rbrack; Stager 및 Painter으로 3D 개체 보내기

**고정:**

* 3D 캡처 렌더러 실패 시 3D 캡처 응용 프로그램 충돌(&amp;lbrack;&amp;rbrack; Applications)
* 이미지를 로드할 수 없을 때 &amp;lbrack;3D 캡처&amp;rbrack; 충돌
* 메시 재구성 단계에 도달하면 &amp;lbrack;3D 캡처&amp;rbrack;이 충돌합니다
* 테두리 상자 크기를 조정할 때 &amp;lbrack;3D 캡처&amp;rbrack; 충돌
* &amp;lbrack;3D 캡처&amp;rbrack; 규칙에 따라 마스크를 가져오면 마스크가 제대로 할당되지 않습니다
* 테두리 상자를 조정할 때 &amp;lbrack;3D 캡처&amp;rbrack; 렌더링 문제가 발생합니다.
* &amp;lbrack;3D 캡처&amp;rbrack; 3D 캡처 사후 처리 중 버전 전환과 렌더링 옵션 전환이 느립니다.
* &amp;lbrack;3D 캡처&amp;rbrack; 3D 캡처 후처리 단계 중 버전 간 전환이 중단되는 경우가 있습니다.
* &amp;lbrack;응용 프로그램(&amp;r); 시작 시 충돌
* 이름이 변경된 재질을 복제할 때 &amp;lbrack;Application&amp;rbrack;가 충돌함
* &amp;lbrack;Application&amp;rbrack;에서 종속성 폴더 없이 레거시 .alch 프로젝트를 열 때 충돌이 발생함
* &amp;lbrack;Application&amp;rbrack; 화면을 플러그/뽑거나 컴퓨터가 절전 모드로 전환되거나 원격으로 액세스될 때 충돌이 발생합니다.
* 비영구 자산 관리와 관련된 &amp;lbrack;Application&amp;rbrack; 충돌 및 메모리 누수
* &amp;lbrack;내보내기&amp;rbrack; 텍스처를 포함하거나 참조하는 3D 개체 파일 유형에 대한 재질 형식 선택을 비활성화해야 합니다.
* &amp;lbrack;Export&amp;rbrack; 3D 오브젝트 내보내기 중 문제가 발생하면 충돌함
* &amp;lbrack;Export&amp;rbrack; .sbs/.sbsar 파일을 내보낼 때 충돌함
* &amp;lbrack;Export&amp;rbrack;에서 레이블은 같지만 파일 이름은 동일하지 않은 사용자 정의 사전 설정을 가져올 때 충돌이 발생합니다
* &amp;lbrack;내보내기&amp;rbrack; 환경 빛을 .sbs/.sbsar 파일로 내보내는 기능이 작동하지 않는 경우가 있습니다
* &amp;lbrack;Export&amp;rbrack; Gltf/Glb export는 base64의 텍스처를 인코딩합니다.
* &amp;lbrack;Export&amp;rbrack; Name 텍스트 필드가 다시 포커싱할 때 작동하지 않음
* 이미지를 재질(AI 지원) 레이어로 .sbs/.sbsar 파일로 내보낼 때 &amp;lbrack;내보내기&amp;rbrack; 타일링 보존이 작동하지 않음
* &amp;lbrack;Export&amp;rbrack; gltf를 내보내고 파일을 바꿀 때 바꿀 파일 목록이 올바르지 않습니다.
* &amp;lbrack;노출된 매개 변수&amp;rbrack; 임의 시드는 내보낸 .sbs/.sbsar 파일에서 작동하지 않습니다.
* &amp;lbrack;Layers&amp;rbrack; 내용 인식 채우기를 두 번째로 추가할 때 때때로 충돌합니다.
* 레이어 스택을 계산할 때 &amp;lbrack;Layers&amp;rbrack; 충돌
* &amp;lbrack;Layers&amp;rbrack; AI(Image to Material) 디스크 캐시가 작동하지 않음
* &amp;lbrack;Layers&amp;rbrack; 레이어 트위킹 시 충돌이 발생할 수 있음
* &amp;lbrack;성능&amp;rbrack; 메모리 누수
* &amp;lbrack;프로젝트(&amp;r); 프로젝트 저장 시 충돌 발생
* &amp;lbrack;프로젝트&amp;rbrack; 동일한 프로젝트를 한 행에 두 번 가져오면 에셋이 중복됨
* 아이콘만 있는 라운디드 버튼(&amp;lbrack;UI&amp;rbrack;)이 올바르게 렌더링되지 않음

### 4.1.0 Cannoli

*(릴리스: 2023년 3월 28일)*

**추가됨:**

* &amp;lbrack;Content&amp;rbrack; 새로운 자수 필터
* &amp;lbrack;내용&amp;rbrack; 새로운 페인트 뒤틀기 필터
* &amp;lbrack;UI&amp;rbrack; 파일 메뉴의 내보내기 추가 옵션
* 이제 맞춤 단계에서 &amp;lbrack;3D 캡처&amp;rbrack; 뒤로 버튼을 사용할 수 있습니다.
* &amp;lbrack;3D 캡처&amp;rbrack; 이미지 처리 JPEG EXIF 방향
* &amp;lbrack;3D 캡처&amp;rbrack; 스크립팅 - 새 dataset_info.camera 속성
* &amp;lbrack;3D 캡처&amp;rbrack; Linux 추가 지원(설명서 참조)
* &amp;lbrack;3D 캡처&amp;rbrack; 가져온 이미지의 읽기 액세스 확인
* &amp;lbrack;Onboarding&amp;rbrack; 학습 - 2개의 새로운 자습서(자수 및 페인트 뒤틀기)
* &amp;lbrack;Onboarding&amp;rbrack; 새로운 기능 콘텐츠 업데이트됨

**고정:**

* &amp;lbrack;3D 캡처 &amp;rbrack; 버전 변경 시 카메라 위치 유지
* &amp;lbrack;3D 캡처&amp;rbrack; 개체의 모든 그룹을 하나로 병합
* &amp;lbrack;3D 캡처&amp;rbrack; 생성된 메쉬의 이름이 원래로 변경됨
* &amp;lbrack;Application&amp;rbrack;이 존재하지 않는 이미지의 축소판을 생성하려고 할 때 충돌함
* 에셋 패널에서 &amp;lbrack;에셋&amp;rbrack; 휴지통 아이콘이 아무 작업도 하지 않음
* &amp;lbrack;Content&amp;rbrack; 재료 슬롯이 있는 필터 업데이트가 예상대로 작동하지 않음
* &amp;lbrack;Export&amp;rbrack; 특정 필터를 사용하여 에셋을 내보낼 때 충돌이 발생할 수 있습니다
* &amp;lbrack;Export&amp;rbrack; SBS/SBSAR 내보내기 - 이미지 가져오기 레이어가 이미지 매개 변수보다 우선 순위가 높음
* &amp;lbrack;Export&amp;rbrack; UE4 내보내기 사전 설정이 PNG에서 작동하지 않음
* &amp;lbrack;Layers&amp;rbrack; OS 탐색기에서 재질과 필터를 동시에 놓을 때 충돌이 발생합니다
* &amp;lbrack;Layers&amp;rbrack; 이미지 파일이 있는 SBSAR 파일을 드래그할 때 충돌함
* &amp;lbrack;Layers&amp;rbrack; 자수 불투명도 채널은 완전히 흰색일 수 있습니다.
* Linux에서는 기본적으로 중국어(&amp;lbrack;Localization&amp;rbrack;)가 표시될 수 있습니다.
* &amp;lbrack;Performance&amp;rbrack; 에셋에서 레이어를 제거할 때 발생하는 메모리 문제를 수정했습니다.
* &amp;lbrack;프로젝트&amp;rbrack; 저장 시 충돌이 발생할 수 있음
* &amp;lbrack;UI&amp;rbrack; 버전의 메뉴 버튼에 누락된 간격 추가
* &amp;lbrack;UI&amp;rbrack; 취소 버튼이 제대로 표시되지 않음
* &amp;lbrack;UI&amp;rbrack; 3D 캡처 후처리 매개변수에 대한 슬라이더 애니메이션 비활성화
* &amp;lbrack;UI&amp;rbrack; 외부를 클릭할 때 재료 생성 템플리트 창이 닫히지 않습니다.
* &amp;lbrack;UI&amp;rbrack; 필터 빠른 접근자가 바깥쪽을 클릭하면 자동으로 닫힙니다

**알려진 문제:**

* &amp;lbrack;색상 피커&amp;rbrack; 다른 해상도의 두 번째 모니터에서 색상 선택이 작동하지 않을 수 있습니다
* &amp;lbrack;Content&amp;rbrack; 모양 라이트 위젯이 구형 투영 모드에서 작동하지 않음
* &amp;lbrack;Interoperability&amp;rbrack; Stager로 전송된 변위가 있는 재질은 변위 컨트롤을 잃게 됩니다.

### 4.0.2 바나나

*(릴리스: 2023년 3월 9일)*

**추가됨:**

* &amp;lbrack;3D 캡처&amp;rbrack; 디스크 사용량은 사용된 양을 표시합니다.
* &amp;lbrack;3D 캡처&amp;rbrack; 사진 가져오기가 비동기적이고 빨라짐
* &amp;lbrack;Scripting&amp;rbrack; 3D 캡처 기능을 스크립팅하는 새로운 클래스 및 함수
* &amp;lbrack;Scripting&amp;rbrack; 내보내기가 완료, 실패 또는 취소될 때 작업을 수행하는 새 ExportController 클래스
* &amp;lbrack;Scripting&amp;rbrack; —run-script로 실행되는 인수 python 스크립트 전달
* 레이어 패널 위로 에셋을 드래그할 때 &amp;lbrack;UI&amp;rbrack; UI 피드백
* &amp;lbrack;Content&amp;rbrack; [색온도] 필터가 이제 재질에 대해 작업 중입니다.
* &amp;lbrack;Content&amp;rbrack; Height에 맞게 표준 필터에는 타일링 유지를 위한 새로운 옵션이 있습니다.

**고정:**

* &amp;lbrack;3D 캡처&amp;rbrack; 데이터 집합 정렬 단계에서 이미지 크기가 수정되었습니다.
* &amp;lbrack;3D 캡처&amp;rbrack; UV 감싸기 해제 후 중복 정점 제거
* &amp;lbrack;3D 캡처&amp;rbrack; MacOS - 3D 캡처가 있는 경우 감지 개선
* 이미지를 가져오는 동안 3D 캡처 창을 닫을 때 &amp;lbrack;3D 캡처&amp;rbrack;가 충돌함
* &amp;lbrack;3D 캡처&amp;rbrack; 새 버전을 생성할 때 충돌함
* &amp;lbrack;3D 캡처&amp;rbrack; 뷰어에서 3D 개체를 로드하려고 할 때 충돌이 발생합니다
* &amp;lbrack;3D 캡처&amp;rbrack; UTF8 문자가 아닌 경로를 사용할 때 충돌 발생
* &amp;lbrack;3D 캡처&amp;rbrack; 적중 및 팁 오타
* &amp;lbrack;3D 캡처&amp;rbrack; 메시는 더 이상 단위 큐브에 맞게 크기가 조정되지 않습니다.
* &amp;lbrack;3D 캡처&amp;rbrack; 렌더링 중 3D 캡처를 닫을 때 충돌 방지
* &amp;lbrack;3D 캡처&amp;rbrack; 마스크를 제거하면 이미지가 사라집니다.
* &amp;lbrack;응용 프로그램&amp;rbrack; 한 에셋을 두 번 동시에 가져올 때 충돌이 발생합니다.
* &amp;lbrack;Application&amp;rbrack; 백업하지 않은 자산을 프로젝트를 열 때 자산의 이전 버전을 백업합니다.
* &amp;lbrack;응용 프로그램&amp;rbrack;모든 맵이 베이크되지 않은 경우 베이킹된 맵을 올바르게 캐시합니다.
* 3D 개체가 표시되면 &amp;lbrack;Application&amp;rbrack; Fullscreen이 충돌합니다.
* 프로젝트를 저장할 때 마지막 재질이 복제되는 &amp;lbrack;Application&amp;rbrack;
* &amp;lbrack;Application&amp;rbrack; 굽기 단계 동안 메시 사후 처리 계산을 취소할 때 충돌 방지
* &amp;lbrack;응용 프로그램&amp;rbrack; 현재 프로젝트를 다시 열면 변경 사항이 취소되지 않습니다.
* &amp;lbrack;응용 프로그램 &amp;rbrack; 3D 오브젝트에 대한 축소판 생성 중지
* 브러시 도구를 사용할 때 &amp;lbrack;2D 보기&amp;rbrack; 충돌 발생
* &amp;lbrack;내용 인식 채우기(&amp;r) - 계산 중단 가능
* &amp;lbrack;Content&amp;rbrack; Atlas Creator 필터가 불투명도 채널을 다운스케일하고 있습니다.
* &amp;lbrack;내보내기&amp;rbrack; 실패 내보내기 대기열 지우기 수정
* &amp;lbrack;Export&amp;rbrack; OBJ 내보내기가 예상보다 100배 작은 개체를 만듭니다.
* 이제 회색 음영 채널로 가져온 &amp;lbrack;Layers&amp;rbrack; 색상 이미지가 회색 음영으로 간주됩니다.
* &amp;lbrack;Export&amp;rbrack; FBX 파일은 타사 응용 프로그램으로 가져올 수 없습니다.
* &amp;lbrack;Export&amp;rbrack; USD 파일의 셰이더 출력 이름이 올바르지 않습니다.
* &amp;lbrack;Layers&amp;rbrack; OS 탐색기에서 이름을 변경할 때 이미지 이름이 업데이트되지 않습니다.
* &amp;lbrack;Scripting&amp;rbrack; 잘못된 스크립트를 다시 로드할 때 오류 메시지를 표시합니다
* 사용할 수 없는 경우 &amp;lbrack;UI&amp;rbrack; 기본 재질 버튼이 비활성화됨
* &amp;lbrack;UI&amp;rbrack; 재료 생성 템플리트 창의 파일 대화상자에 액세스할 때 충돌함
* 레이어 패널이 닫혀 있어도 &amp;lbrack;UI&amp;rbrack; 빠른 접근자에 액세스할 수 있습니다.
* &amp;lbrack;UI&amp;rbrack; 보내기 아이콘이 잘못 정렬됨
* &amp;lbrack;UI&amp;rbrack; 혼합 아이콘을 클릭하면 레이어 아이콘이 변경됩니다.

**알려진 문제:**

* &amp;lbrack;색상 피커&amp;rbrack; 다른 해상도의 두 번째 모니터에서 색상 선택이 작동하지 않을 수 있습니다
* &amp;lbrack;Content&amp;rbrack; 모양 라이트 위젯이 구형 투영 모드에서 작동하지 않음
* &amp;lbrack;Interoperability&amp;rbrack; Stager로 전송된 변위가 있는 재질은 변위 컨트롤을 잃게 됩니다.

### 4.0.1 바나나

*(릴리스: 2023년 2월 7일)*

**고정:**

* &amp;lbrack;3D 캡처&amp;rbrack; 마스크를 사용할 때 텍스처 투영이 깨질 수 있습니다
* &amp;lbrack;3D 캡처&amp;rbrack; 가공물이 개체에 나타날 수 있음
* &amp;lbrack;3D 캡처&amp;rbrack; 내보낸 메쉬가 매우 작을 수 있습니다

**알려진 문제:**

* &amp;lbrack;3D 캡처&amp;rbrack; FBX 및 OBJ 내보내기 다운스케일 결과
* 하드웨어가 호환되지 않는 경우에도 &amp;lbrack;3D 캡처&amp;rbrack; 3D 캡처를 MacOS에서 사용할 수 있습니다. 설명서를 확인하십시오.
* &amp;lbrack;3D 캡처&amp;rbrack;메쉬 재구성이 완료되면 충돌합니다.
* &amp;lbrack;레이어&amp;rbrack; 내용 인식 채우기는 아래의 레이어를 수정하면 중단될 수 있습니다
* &amp;lbrack;색상 피커&amp;rbrack; 다른 해상도의 두 번째 모니터에서 색상 선택이 작동하지 않을 수 있습니다
* &amp;lbrack;Content&amp;rbrack; 모양 라이트 위젯이 구형 투영 모드에서 작동하지 않음
* &amp;lbrack;Interoperability&amp;rbrack; Stager로 전송된 변위가 있는 재질은 변위 컨트롤을 잃게 됩니다.

### 4.0.0 바나나

*(릴리스: 2023년 1월 31일)*

**추가됨:**

* &amp;lbrack;3D 캡처&amp;rbrack; 이미지에서 3D 개체 만들기
* &amp;lbrack;3D 캡처&amp;rbrack; 전용 3D 캡처 마법사
* &amp;lbrack;3D 캡처&amp;rbrack; 데이터 세트에 흑백 마스크 가져오기 또는 생성
* &amp;lbrack;3D 캡처&amp;rbrack; 정렬 결과 - 일치하는 모든 기능을 포인트 클라우드로 보기
* &amp;lbrack;3D 캡처&amp;rbrack; 정렬 결과 - 정렬된 각 사진과 연결된 카메라 보기 및 상호 작용
* &amp;lbrack;3D 캡처&amp;rbrack; 테두리 상자 위젯을 사용하여 재구성 영역을 정의합니다
* &amp;lbrack;3D 캡처&amp;rbrack; 테두리 상자 위젯의 모든 축에 대해 크기 조정, 변환 및 회전
* &amp;lbrack;3D 캡처&amp;rbrack; 재구성된 메쉬의 형상 정밀도를 정의합니다
* &amp;lbrack;3D 캡처&amp;rbrack; 새 버전을 만들어 메시 및 텍스처 최적화
* &amp;lbrack;3D 캡처&amp;rbrack; 각 버전은 자동으로 대상 면 번호 세트로 데시메이션됩니다.
* &amp;lbrack;3D 캡처&amp;rbrack; 후처리 단계는 자동으로 줄 바꿈을 풀고 텍스처를 다시 프로젝트한 다음 하이 폴리 메쉬에서 일반 Height과 AO 정보를 가져옵니다
* &amp;lbrack;3D 캡처&amp;rbrack; Sampler 프로젝트에 원래 결과 또는 버전을 추가합니다.
* &amp;lbrack;3D 캡처&amp;rbrack; 기본 메시 레이어의 세부 사항을 자동으로 데시메이션하고, 래핑을 해제하고, 재투영하고, 베이킹하는 새로운 메시 후처리 레이어
* &amp;lbrack;3D 캡처&amp;rbrack; 기본 메시 레이어의 비율 조정, 회전 또는 변환을 위한 새로운 메시 변환 레이어
* &amp;lbrack;내보내기&amp;rbrack; 새 내보내기 창
* 에셋 유형(재질, 환경 조명, 메시)에 따른 &amp;lbrack;내보내기&amp;rbrack; 전용 설정 및 UI
* &amp;lbrack;내보내기&amp;rbrack; 메시를 USD, USDA, USDZ, glTF, glb, obj, fbx, stl로 내보냅니다.
* &amp;lbrack;Export&amp;rbrack; Substance 파일을 내보낼 때 재질 유형 정의(SBSAR, SBS)
* &amp;lbrack;UI&amp;rbrack; 환경 설정 팝업에서 캐시 설정을 새 탭으로 이동
* 이제 &amp;lbrack;Application&amp;rbrack; 2D 및 3D 뷰포트의 크기를 세로로 변경, 스왑 및 스택할 수 있습니다.
* &amp;lbrack;Application&amp;rbrack; 추가 스타터 에셋을 추가하는 새로운 SAMPLER_RESOURCES_PATH 환경 변수
* &amp;lbrack;Scripting&amp;rbrack; 시작 시 플러그인 및 스크립트를 가져오기 위해 SAMPLER_PLUGIN_PATH 및 SAMPLER_SCRIPT_PATH 환경 변수를 추가했습니다
* &amp;lbrack;Scripting&amp;rbrack; 재료, 환경 조명 및 3d 오브젝트에 대한 내보내기 기능 추가
* &amp;lbrack;스크립팅&amp;rbrack; 식별자, 기본값, 최소값 및 최대값, 레이블, 매개 변수에 열거형 값 추가
* &amp;lbrack;Scripting&amp;rbrack; 이미지를 가져오는 동안 사용자 정의된 사용을 입력하는 import_textures 함수를 추가했습니다.

**고정:**

* &amp;lbrack;Application&amp;rbrack;에서 최근 프로젝트를 열고 확인 대화 상자에 저장할 때 충돌이 발생합니다.
* &amp;lbrack;응용 프로그램&amp;rbrack; 파일 대화 상자에서 .ssa 파일을 열 수 없습니다.
* macOS의 배경 창에 &amp;lbrack;Application&amp;rbrack; 파일 대화 상자가 표시될 수 있습니다.
* &amp;lbrack;응용 프로그램&amp;rbrack; 3.2 프로젝트를 열 때 잠재적 충돌
* &amp;lbrack;응용 프로그램&amp;rbrack; 파일을 선택하면 경고를 표시하기 전에 파일 대화 상자가 닫힙니다
* &amp;lbrack;노출된 매개 변수&amp;rbrack; 매개 변수 환경 조명 내보내기가 작동하지 않음
* &amp;lbrack;Layers&amp;rbrack; 레이어 스택의 &quot;여기를 클릭하여 찾아보기&quot; 링크가 더 이상 작동하지 않습니다.
* &amp;lbrack;Layers&amp;rbrack; 동일한 레이어 내에서 여러 이미지를 페인팅할 때 때때로 작동하지 않습니다
* &amp;lbrack;Layers&amp;rbrack; 레이어 속성에서 이미지를 설정해도 이미지 피커 축소판이 업데이트되지 않습니다
* 레이어로 추가된 Sampler 에셋을 수정할 수 없습니다(&amp;lbrack;Layers&amp;rbrack;).
* &amp;lbrack;프로젝트&amp;rbrack; 프로젝트를 열 때 원치 않는 에셋 업데이트
* &amp;lbrack;Scripting&amp;rbrack; Windows에서 플러그인 폴더 찾기가 때때로 실패함
* &amp;lbrack;Scripting&amp;rbrack; Python 스크립트에서 &#39;open_project()&#39;를 사용할 때 충돌이 발생합니다.
* &amp;lbrack;Scripting&amp;rbrack; JPEG 내보내기가 API에 없습니다.
* &amp;lbrack;스크립팅&amp;rbrack; 로그 패널이 읽기 전용이 아닙니다.
* &amp;lbrack;Scripting&amp;rbrack; image_picker 매개 변수 값이 작동하지 않음
* &amp;lbrack;UI&amp;rbrack; 프로젝트 패널에 환경 조명에 대한 에셋 아이콘이 없습니다.
* &amp;lbrack;UI&amp;rbrack; 환경 설정 팝업의 Designer 형식으로 보내기 드롭다운은 비어 있을 수 있습니다.
* &amp;lbrack;UI&amp;rbrack; 일부 버튼의 스타일이 잘못되었습니다.
* &amp;lbrack;UI&amp;rbrack; 레이블이 버튼 그룹 위젯의 버튼과 겹침
* 도구 설정 메뉴의 &quot;물리적 크기&quot;에 대한 &amp;lbrack;UI&amp;rbrack; 도구 설명 위치가 잘못되었습니다.
* &amp;lbrack;UI&amp;rbrack; 언어를 변경할 때 [파일] 메뉴가 잘못 정렬됨

**알려진 문제:**

* &amp;lbrack;3D 캡처&amp;rbrack; 마스크를 사용할 때 텍스처 투영이 깨질 수 있습니다
* &amp;lbrack;3D 캡처&amp;rbrack; 메쉬 변환의 배율이 너무 작은 경우 개체에 작은 아티팩트가 나타날 수 있습니다
* &amp;lbrack;3D 캡처&amp;rbrack; 내보낸 메쉬가 매우 작을 수 있습니다. 메쉬 변형의 비율을 재설정하고 다시 내보내기
* &amp;lbrack;색상 피커&amp;rbrack; 다른 해상도의 두 번째 모니터에서 색상 선택이 작동하지 않을 수 있습니다
* &amp;lbrack;Content&amp;rbrack; 모양 라이트 위젯이 구형 투영 모드에서 작동하지 않음
* &amp;lbrack;Interoperability&amp;rbrack; Stager로 전송된 변위가 있는 재질은 변위 컨트롤을 잃게 됩니다.

## 버전 3

### 3.4.1 아란치니

*(릴리스: 2022년 10월 6일)*

**추가됨:**

* &amp;lbrack;Onboarding&amp;rbrack; 새로운 시작 및 새로운 기능 화면
* &amp;lbrack;Onboarding&amp;rbrack; 홈 화면 UI 업데이트됨
* 홈 화면의 &amp;lbrack;Onboarding&amp;rbrack; 새로운 학습 내용
* &amp;lbrack;Scripting&amp;rbrack; 메서드가 인식되지 않을 때 로그 패널에 오류를 기록합니다.
* &amp;lbrack;Scripting&amp;rbrack; 로그 패널에 인쇄할 수 있는 새로운 ssa.helpers 모듈
* &amp;lbrack;Application&amp;rbrack; Substance 3D Designer의 새로운 side-by-side 단추 위젯 지원

**고정:**

* 누락된 이미지를 참조하는 .sbsar 파일을 내보낼 때 &amp;lbrack;Export&amp;rbrack;이 충돌합니다
* &amp;lbrack;Export&amp;rbrack; 손상된 이미지 파일을 참조하는 에셋을 내보낼 때 충돌이 발생합니다.
* &amp;lbrack;Export&amp;rbrack; 자수 레이어가 있는 .sbsar 파일을 내보내면 회색 재료가 생성됩니다
* &amp;lbrack;내보내기&amp;rbrack; 재질을 .sbs/sbsar 파일로 내보내면 완전히 투명한 재질이 생성될 수 있습니다
* &amp;lbrack;내보내기&amp;rbrack; 일반 형식 매개 변수가 .sbs/.sbsar 파일에 올바르게 표시되지 않음
* &amp;lbrack;Export&amp;rbrack; .svg 파일을 참조하는 레이어 스택의 Sbs/sbsar 내보내기가 끊어짐
* &amp;lbrack;내보내기&amp;rbrack; 변형 레이어가 제대로 내보내지지 않음 / 업데이트됨 인스케이프 - 내보내기 사전 설정 수정
* &amp;lbrack;Exposed Parameters&amp;rbrack; 노출된 매개 변수가 포함된 레이어를 삭제하면 충돌이 발생합니다
* &amp;lbrack;노출된 매개 변수&amp;rbrack; 레이어 스택에서 오래된 레이어를 업데이트하면 노출된 매개 변수 목록이 손상될 수 있습니다.
* &amp;lbrack;노출 매개 변수&amp;rbrack; 내보낼 수 없는 매개 변수는 계속 내보냅니다.
* &amp;lbrack;노출된 매개 변수&amp;rbrack; 레이어를 삭제할 때 혼합 필터를 제거해도 매개 변수가 노출되지 않습니다
* &amp;lbrack;노출된 매개 변수&amp;rbrack; 텍스트 매개 변수 나누기 .sbs/.sbsar 내보내기
* &amp;lbrack;Layers&amp;rbrack; 다른 레이어 스택에서 레이어 스택을 놓을 때 충돌이 발생합니다.
* &amp;lbrack;Layers&amp;rbrack; 필터 로드 실패 시 충돌
* 이미지 필드를 재설정할 때 &amp;lbrack;Layers&amp;rbrack;에서 이전 이미지를 다시 로드할 수 없음
* &amp;lbrack;Layers&amp;rbrack; 변환 도구 변경을 실행 취소/다시 실행할 수 없음
* &quot;모든 설정 재설정&quot;을 클릭하면 &amp;lbrack;Layers&amp;rbrack; 복제 도장 레이어가 멈춥니다.
* &amp;lbrack;Layers&amp;rbrack; 재설정 버튼을 사용하면 이미지 필드에 그려지지 않습니다
* &amp;lbrack;Layers&amp;rbrack; 재설정 버튼을 사용하면 이미지 필드에서 드로잉 마스크가 지워지지 않습니다
* &amp;lbrack;Layers&amp;rbrack; 사용자가 그림을 그렸다면 이미지 필드의 재설정 버튼은 아무것도 하지 않습니다
* 브러시 도구를 사용할 때 &amp;lbrack;Layers&amp;rbrack; 렌더링 캐시가 작동하지 않습니다
* &amp;lbrack;Layers&amp;rbrack; 삭제된 레이어는 여전히 [속성] 패널에 표시될 수 있습니다.
* 프로젝트 에셋 간에 전환할 때 레이어 계산이 정지될 수 있음(&amp;lbrack;Layers&amp;rbrack;)
* &amp;lbrack;프로젝트&amp;rbrack; 때로는 Sampler이 디스크에서 프로젝트를 열 수 없는 경우가 있습니다
* &amp;lbrack;2D View&amp;rbrack; 2D 보기는 항상 [재질 출력]으로 기본 설정됩니다

**알려진 문제:**

* &amp;lbrack;색상 피커&amp;rbrack; 다른 해상도의 두 번째 모니터에서 색상 선택이 작동하지 않을 수 있습니다
* &amp;lbrack;Content&amp;rbrack; 모양 라이트 위젯이 구형 투영 모드에서 작동하지 않음
* &amp;lbrack;Interoperability&amp;rbrack; Stager로 전송된 변위가 있는 재질은 변위 컨트롤을 잃게 됩니다.

### 3.4.0 아란치니

*(릴리스: 2022년 9월 6일)*

**추가됨:**

* &amp;lbrack;노출 매개 변수&amp;rbrack; 새 노출된 파라미터 패널
* &amp;lbrack;노출됨 매개 변수&amp;rbrack; 매개 변수 위에 있는 [새] 단추를 누르면 [속성] 패널에서 매개 변수가 노출되거나 노출되지 않습니다.
* &amp;lbrack;표시된 매개변수&amp;rbrack; 속성 패널에서 매개변수를 표시하고 표시하지 않으려면 매개변수에 대한 새로운 마우스 오른쪽 버튼 클릭 컨텍스트 메뉴를 사용합니다.
* &amp;lbrack;노출 매개변수&amp;rbrack; 노출 매개변수가 노출된 파라미터 패널에 나열됩니다.
* &amp;lbrack;Exposed Parameters&amp;rbrack; 노출된 매개 변수를 쉽게 식별할 수 있도록 여러 위치에 색상 점과 색상 디스크가 추가됩니다
* &amp;lbrack;노출 매개변수&amp;rbrack; 매개변수 레이블은 노출된 파라미터 패널에서 편집할 수 있습니다
* &amp;lbrack;Exposed Parameters&amp;rbrack; 내보낼 수 없는 매개 변수에 대한 경고 표시
* &amp;lbrack;Exposed Parameters&amp;rbrack; 노출된 블렌드 매개변수가 있는 레이어를 숨겨진 곳으로 이동하면 경고를 표시합니다.
* &amp;lbrack;노출된 매개 변수&amp;rbrack; 노출된 매개 변수는 SBS 및 SBSAR 형식으로 내보내집니다.
* &amp;lbrack;Metadata&amp;rbrack; 사용자 정의 메타데이터 템플릿 지원
* &amp;lbrack;Metadata&amp;rbrack; 새 CLO 물리적 속성 메타데이터 템플릿
* &amp;lbrack;Metadata&amp;rbrack; 사용자 정의 메타데이터를 추가/제거하기 위한 호버 상의 아이콘 추가
* &amp;lbrack;Python API&amp;rbrack; 새로운 Python API
* 에셋 제작을 위한 &amp;lbrack;Python API&amp;rbrack; API
* 레이어 관리를 위한 &amp;lbrack;Python API&amp;rbrack; API
* 매개 변수 관리를 위한 &amp;lbrack;Python API&amp;rbrack; API
* 프로젝트 관리를 위한 &amp;lbrack;Python API&amp;rbrack; API
* &amp;lbrack;Python API&amp;rbrack; 플러그인은 활성화 및 비활성화할 수 있습니다.
* 도움말 메뉴에서 액세스할 수 있는 &amp;lbrack;Python API&amp;rbrack; Python API 설명서
* 환경 설정 팝업의 &amp;lbrack;스크립팅&amp;rbrack; 새 플러그인 및 스크립트 섹션
* &amp;lbrack;Scripting&amp;rbrack; 플러그인 생성 및 가져오기를 통해 나만의 패널로 Sampler 인터페이스를 사용자 정의
* &amp;lbrack;Scripting&amp;rbrack; 플러그인은 Sampler 인터페이스의 일부가 되며 표준 Sampler 패널처럼 고정하고 이동할 수 있습니다.
* Sampler 오른쪽 도구 모음의 플러그인에 대한 &amp;lbrack;Scripting&amp;rbrack; 전용 버튼 모음
* &amp;lbrack;스크립팅&amp;rbrack; 주어진 작업 목록을 수행하기 위한 스크립트 작성 및 가져오기
* &amp;lbrack;스크립팅&amp;rbrack; 스크립트 메뉴를 통해 Python 스크립트 실행
* &amp;lbrack;Scripting&amp;rbrack; 플러그인 및 스크립트는 환경 설정 창에서 삭제, 순서 변경 및 다시 로드할 수 있습니다.
* &amp;lbrack;스크립팅&amp;rbrack; 추가됨 —run-script 명령줄 매개 변수
* &amp;lbrack;로그&amp;rbrack; 새 로그 패널
* 환경 설정 창에서 로그 패널 사용(&amp;l)
* &amp;lbrack;Logs&amp;rbrack; 로그 지우기, 복사/붙여넣기 및 내보내기를 위한 새로운 작업 표시줄
* &amp;lbrack;등록 정보&amp;rbrack; 매개 변수 마우스를 위로 가져가면 매개 변수 값이 재설정됩니다.
* &amp;lbrack;등록 정보&amp;rbrack; 매개 변수에 대한 새로운 마우스 오른쪽 클릭 컨텍스트 메뉴를 사용하여 매개 변수 값을 재설정합니다.
* &amp;lbrack;Content&amp;rbrack; Image to Material(AI 작동)이 이제 MacOS에서 작동합니다.
* &amp;lbrack;엔진&amp;rbrack; Substance 엔진을 v8.6.0으로 업데이트

**고정:**

* 축소판 생성이 진행 중일 때 종료 시 &amp;lbrack;Application&amp;rbrack; 응용 프로그램이 충돌할 수 있습니다.
* &amp;lbrack;종료 시 &#39;다른 이름으로 저장&#39;을 사용할 때 응용 프로그램 &amp;rbrack; 응용 프로그램이 충돌할 수 있음
* macOS에서 종료하는 동안 &amp;lbrack;응용 프로그램(&amp;r);이 중단될 수 있습니다.
* &amp;lbrack;응용 프로그램 &amp;rbrack; 색상 대화 상자를 열고 저장하면 변경 사항이 저장되지 않음
* 내보낼 때 &amp;lbrack;Export&amp;rbrack; 사용 명명 규칙이 올바르지 않음
* &amp;lbrack;Layers&amp;rbrack; 필터 위에 재질을 놓으면 충돌이 발생할 수 있습니다
* &amp;lbrack;Layers&amp;rbrack; 오래된 레이어 스택을 업데이트하면 관련되지 않은 레이어 스택이 업데이트될 수 있습니다
* &amp;lbrack;Metadata&amp;rbrack; 빈 필드를 내보냅니다.
* &amp;lbrack;Metadata&amp;rbrack; 메타데이터 항목이 하나만 있는 경우 UI에서 순서를 변경할 수 있습니다
* &amp;lbrack;프로젝트&amp;rbrack; 재료 복제 후 계산이 끝나지 않음
* &amp;lbrack;프로젝트&amp;rbrack; 프로젝트 자산이 초기 프로젝트 저장 후 복제됩니다.
* 에셋을 전환할 때 &amp;lbrack;프로젝트&amp;rbrack; 불필요한 계산
* &amp;lbrack;렌더링&amp;rbrack; 일부 레이어 스택이 레이어 삭제 후 제대로 렌더링되지 않음
* &amp;lbrack;Security&amp;rbrack; 수정 CVE-2015-20107
* &amp;lbrack;UI&amp;rbrack; 2D 출력이 창 크기에 따라 흐릿해질 수 있습니다.
* &amp;lbrack;UI&amp;rbrack; 응용 프로그램이 포커스를 잃을 때 에셋 미리보기를 맨 위에 열어 둘 수 있습니다.
* &amp;lbrack;UI&amp;rbrack; 스플래시 화면 둥근 모서리의 배경이 정사각형입니다.

**알려진 문제:**

* &amp;lbrack;색상 피커&amp;rbrack; 다른 해상도의 두 번째 모니터에서 색상 선택이 작동하지 않을 수 있습니다
* &amp;lbrack;Content&amp;rbrack; 모양 라이트 위젯이 구형 투영 모드에서 작동하지 않음
* &amp;lbrack;Interoperability&amp;rbrack; Stager로 전송된 변위가 있는 재질은 변위 컨트롤을 잃게 됩니다.

### 3.3.2 애호박

*(릴리스: 2022년 6월 28일)*

**고정:**

* &amp;lbrack;Application&amp;rbrack; 프로젝트를 열 때 발생할 수 있는 충돌 수정
* &amp;lbrack;Export&amp;rbrack; Sampler을 다시 시작하면 가져온 사용자 정의 내보내기 사전 설정 목록이 중단됩니다.
* &amp;lbrack;Interoperability&amp;rbrack; Designer에서 보낸 자료가 삭제된 후 Designer에서 다시 전송될 때 충돌 수정
* &amp;lbrack;프로젝트&amp;rbrack; 프로젝트의 마지막 에셋인 경우 마지막 재질 또는 환경 조명을 삭제할 수 없습니다.
* &amp;lbrack;프로젝트&amp;rbrack;환경 표시등을 마우스 오른쪽 단추로 클릭하면 &quot;저장되지 않은 수정&quot; 별표가 나타납니다

**알려진 문제:**

* &amp;lbrack;색상 피커&amp;rbrack; 다른 해상도의 두 번째 모니터에서 색상 선택이 작동하지 않을 수 있습니다
* &amp;lbrack;Content&amp;rbrack; 모양 라이트 위젯이 구형 투영 모드에서 작동하지 않음
* &amp;lbrack;Interoperability&amp;rbrack; Stager로 전송된 변위가 있는 재질은 변위 컨트롤을 잃게 됩니다.

### 3.3.1 호박

*(릴리스: 2022년 6월 7일)*

**추가됨:**

* &amp;lbrack;Application&amp;rbrack; 기본 Apple silicon(M1) 지원
* &amp;lbrack;UI&amp;rbrack; 2D 보기에서 채널을 순환하는 새 단축키 &quot;C&quot;
* 브러시 도구 모음에서 회색 음영 색상 값을 편집하는 &amp;lbrack;도구&amp;rbrack; 숫자 필드

**고정:**

* &amp;lbrack;Tools&amp;rbrack; Windows에서 분할 UI 비율(150%)과 함께 브러시 도구를 사용하면 선이 오프셋됩니다
* &amp;lbrack;성능&amp;rbrack; 메모리 소비 개선
* 이 기능을 활성화하면 &amp;lbrack;물리적 크기&amp;rbrack; 물리적 크기 정보가 누락될 수 있습니다.
* &amp;lbrack;UI&amp;rbrack; Alt 키를 누를 때 마우스 스크롤이 예상대로 작동하지 않는 경우가 있습니다
* 저장된 프로젝트를 열 때 &amp;lbrack;Application&amp;rbrack; 응용 프로그램이 충돌할 수 있습니다.
* &amp;lbrack;Application&amp;rbrack;에서 여러 이미지를 드래그 앤 드롭하고 재질 생성 템플릿 창에서 텍스처 가져오기를 사용할 때 충돌이 발생합니다
* &amp;lbrack;Application&amp;rbrack; 사용자 정의 필터가 포함된 프로젝트를 저장할 때 잠재적 충돌
* &amp;lbrack;응용 프로그램&amp;rbrack; 응용 프로그램을 전환할 때 때때로 제어 키 상태가 손실됩니다.
* 로컬 폴더 이름 변경 시 &amp;lbrack;Assets&amp;rbrack; 충돌

**알려진 문제:**

* &amp;lbrack;색상 피커&amp;rbrack; 다른 해상도의 두 번째 모니터에서 색상 선택이 작동하지 않을 수 있습니다
* &amp;lbrack;Content&amp;rbrack; 모양 라이트 위젯이 구형 투영 모드에서 작동하지 않음
* &amp;lbrack;Interoperability&amp;rbrack; Stager로 전송된 변위가 있는 재질은 변위 컨트롤을 잃게 됩니다.

### 3.3.0 호박

*(릴리스: 2022년 5월 17일)*

**추가됨:**

* &amp;lbrack;Content&amp;rbrack; 새로운 내용 인식 채우기 필터(Windows 및 Mac)
* &amp;lbrack;Content&amp;rbrack; [내용 인식 채우기]가 이미지, PBR 재질 및 환경 조명에서 작업하고 있습니다.
* &amp;lbrack;Content&amp;rbrack; 이미지에 &quot;타일링 유지&quot; 매개 변수 추가(AI 기반)
* &amp;lbrack;Content&amp;rbrack; [원근감 변형] 필터는 네 지점 사이에 격자를 표시할 수 있습니다
* &amp;lbrack;Interoperability&amp;rbrack; Adobe Substance 3D Stager으로 자료 보내기
* &amp;lbrack;도구&amp;rbrack; 변형 또는 자르기 도구 크기를 조정할 때 Ctrl 키를 눌러 변형 가운데 맞춤
* &amp;lbrack;도구&amp;rbrack; 변형 또는 자르기 도구 크기를 조정할 때 Shift 키를 눌러 비율을 정사각형으로 잠급니다
* &amp;lbrack;Tools&amp;rbrack; 복제 도장 커서는 도장될 내용을 미리 볼 수 있습니다.
* 복제 도장 사용 시 지우개 커서에서 원본 내용 미리 보기(&amp;lbrack; Tools&amp;rbrack;)
* &amp;lbrack;도구&amp;rbrack; Ctrl+클릭으로 복제 도장 레이어에 새 도장 만들기
* &amp;lbrack;도구&amp;rbrack; 연속 복제 스탬프가 이제 단일 레이어 내에 그룹화됩니다.
* &amp;lbrack;도구&amp;rbrack; 브러시 도구 모음 UI 수정
* &amp;lbrack;Tools&amp;rbrack; 브러시 도구 모음 위치는 세션 동안 유지됩니다
* &amp;lbrack;도구&amp;rbrack; 축별 새로운 브러시 타일링 옵션
* &amp;lbrack;도구&amp;rbrack; 페인팅 시 2D 보기 위에 오버레이를 숨기거나 표시
* &amp;lbrack;도구&amp;rbrack; 새 단축키 &quot;X&quot; - 브러시와 지우개 간에 전환
* &amp;lbrack;도구&amp;rbrack; 브러시 크기를 변경하기 위한 새 단축키 &quot;&amp;lbrack;&quot; &quot;&amp;rbrack;&quot;
* &amp;lbrack;도구&amp;rbrack; 새 단축키 &quot;E&quot; - 지우개 전환
* &amp;lbrack;2D View&amp;rbrack; 환경 조명을 만들 때 새 구형 투영 모드
* &amp;lbrack;2D View&amp;rbrack; 브러시 도구는 구형 투영 모드에서 지원됩니다.
* &amp;lbrack;2D 보기&amp;rbrack; 위치 도구가 구형 투영 모드에서 지원됩니다.
* &amp;lbrack;2D 보기(&amp;r); 구형 투영 모드에서는 실행 취소/다시 실행이 지원됩니다.
* &amp;lbrack;2D View&amp;rbrack; 구형 투영에서 환경 중심을 보도록 기본 위치를 설정합니다
* &amp;lbrack;2D 보기&amp;rbrack; 새로운 노출 제어
* &amp;lbrack;UI&amp;rbrack; [속성] 패널에서 이미지 조정에는 콘텐츠의 소스(이미지 또는 레이어에서)가 표시됩니다
* &amp;lbrack;UI&amp;rbrack; 레이어/재질 출력 드롭다운 배경 개선
* &amp;lbrack;UI&amp;rbrack; 2D 보기에서 해상도 정보의 새 위치
* 3D 보기 탐색 컨트롤 단축키가 포함된 &amp;lbrack;UI&amp;rbrack; 새로운 도구 설명
* &amp;lbrack;UI&amp;rbrack; 브러시 컨트롤을 사용한 새 도구 설명
* &amp;lbrack;UI&amp;rbrack; 투영 탐색 컨트롤 단축키가 있는 새로운 도구 설명
* &amp;lbrack;컴파운드 필터&amp;rbrack; 컴파운드 필터는 이미지, PBR 재질 및 환경 조명에서 작업할 수 있는 변형을 처리합니다.
* &amp;lbrack;복합 필터&amp;rbrack; 비틀기 순서는 복합 필터의 노드 목록 순서와 일치합니다.
* &amp;lbrack;컴파운드 필터&amp;rbrack; 그룹이 동일한 다른 노드의 트위크가 [속성] 패널에서 하나의 단일 그룹으로 병합됩니다.
* &amp;lbrack; 응용 프로그램 &amp;rbrack;에는 에셋 유형별로 전용 뷰어 설정이 있습니다.

**고정:**

* &amp;lbrack;2D 보기로 전환할 때 응용 프로그램 &amp;rbrack; 응용 프로그램이 충돌할 수 있음
* &amp;lbrack;Application&amp;rbrack; 여러 번 내보낼 때 발생할 수 있는 교착 상태 또는 충돌 수정
* &amp;lbrack;응용 프로그램&amp;rbrack; Substance 3D Designer과 일치하는 채널의 기본값을 만듭니다.
* &amp;lbrack;Application&amp;rbrack; 프로젝트를 로드해도 재질 재계산이 트리거되지 않습니다.
* &amp;lbrack;Application&amp;rbrack; 텍스처 가져오기 설명서에 대한 URL을 업데이트했습니다.
* &amp;lbrack;Content&amp;rbrack; 복합 필터를 사용할 때 다시 로드할 때 언제 업데이트해야 하는지 묻습니다
* 불투명도 혼합을 사용하면 Height 맵의 &amp;lbrack;Content&amp;rbrack; 세부 정보가 사라집니다.
* 색상 대화 상자에서 슬라이더의 텍스트 필드를 사용하여 범위를 벗어날 수 있습니다.
* &amp;lbrack;UI&amp;rbrack; 사용 목록에 쓸모없는 세로 스크롤 막대가 있습니다.

**알려진 문제:**

* &amp;lbrack;색상 피커&amp;rbrack; 다른 해상도의 두 번째 모니터에서 색상 선택이 작동하지 않을 수 있습니다
* &amp;lbrack;Content&amp;rbrack; 모양 라이트 위젯이 구형 투영 모드에서 작동하지 않음
* &amp;lbrack;Interoperability&amp;rbrack; Stager로 전송된 변위가 있는 재질은 변위 컨트롤을 잃게 됩니다.

### 3.2.1 야키토리

*(릴리스: 2022년 3월 8일)*

**추가됨:**

* &amp;lbrack;내보내기&amp;rbrack; 이미지 파일의 dpi 메타데이터 내보내기
* &amp;lbrack;물리적 크기&amp;rbrack; 실제 치수를 편집할 때 정사각형이 아닌 텍스처로 비율을 유지합니다
* &amp;lbrack;물리적 크기 변경 시 물리적 크기 메타데이터가 즉시 적용됩니다.&amp;rbrack; 물리적 크기 변경 시
* &amp;lbrack;UI&amp;rbrack; 물리적 크기 활성화 시 모든 종류의 재질에 영향을 줄 수 있도록 Height 배율 최대 슬라이더를 조정합니다
* &amp;lbrack;UI&amp;rbrack; [에셋] 패널의 검색 필터에 대한 새로운 도구 설명
* &amp;lbrack;UI&amp;rbrack; [에셋] 패널에서 단추가 비활성화된 경우를 설명하기 위해 도구 설명을 사용합니다.
* &amp;lbrack;내용&amp;rbrack; 명도 대비 필터 업데이트

**고정:**

* 자르기 및 변형 도구의 &amp;lbrack;2D 보기&amp;rbrack; 90도 회전 버튼이 예상대로 작동하지 않음
* &amp;lbrack;2D 보기&amp;rbrack; 자르기 위젯이 가끔 누락됩니다.
* &amp;lbrack;응용 프로그램&amp;rbrack;이미지 매개 변수를 지우는 경우 기본 레이어가 다시 연결되지 않습니다.
* &amp;lbrack;Application&amp;rbrack; 프로젝트를 저장한 후 종료 시 충돌 발생
* &amp;lbrack;Application&amp;rbrack;에서 현재 재질을 [에셋] 패널의 컬렉션으로 드래그하여 놓을 때 충돌이 발생합니다
* &amp;lbrack;Application&amp;rbrack; 뷰포트에 에셋을 드래그하여 놓으면 충돌이 발생할 수 있습니다
* &amp;lbrack;Content&amp;rbrack; 일반 혼합에 임의화 수정이 있습니다.
* &amp;lbrack;Content&amp;rbrack; Snow 필터에 새로 나온 눈 및 녹은 눈 매개 변수 값에 따라 잘못된 일반 출력이 있습니다.
* &amp;lbrack;Content&amp;rbrack; 쪽매 필터: 예기치 않은 이음새 수정
* &amp;lbrack;Content&amp;rbrack; 자수 필터: 금속 맵에서 스레드 제거
* &amp;lbrack;Content&amp;rbrack; 바닥 타일 필터: x 및 y 타일 수 수정
* &amp;lbrack;내용&amp;rbrack; 벽돌 벽 필터: 일반 출력 및 16비트 Height
* &amp;lbrack;Export&amp;rbrack; 내보내기 팝업의 기본 파일 이름이 현재 재료 이름이 아닙니다.
* &amp;lbrack;내보내기&amp;rbrack; 내보내기 사전 설정을 사용하여 실제 비율로 내보내면 치수가 올바르지 않음
* CLO 내보내기 사전 설정에서 &amp;lbrack;Export&amp;rbrack; Metallic이 누락되었습니다.
* &amp;lbrack;Export&amp;rbrack; 내보내기 사용자 정의 사전 설정을 바꿀 때 표시 이름이 업데이트되지 않습니다
* &amp;lbrack;Layers&amp;rbrack; 첫 번째로 삽입된 레이어의 사용자 정의 채널이 검색되지 않습니다.
* 숨겨진 레이어의 변경 내용을 변경하면 &amp;lbrack;Layers&amp;rbrack; 재질이 다시 평가됩니다.
* &amp;lbrack;Localization&amp;rbrack; 도구 설명이 내보내기 패널에서 현지화되지 않음
* &amp;lbrack;물리적 크기&amp;rbrack; 에셋의 물리적 크기를 비활성화해도 물리적 스케일이 제거되지 않음
* &amp;lbrack;물리적 크기&amp;rbrack; Height 크기 값은 처음으로 슬라이더 경계 외부에서 설정할 수 없습니다.
* &amp;lbrack;물리적 크기&amp;rbrack; 물리적 크기가 없는 이미지를 가져오면 프로젝트를 열 수 없습니다.
* &amp;lbrack;물리적 크기&amp;rbrack; 물리적 크기가 누락 시 0으로 잘못 설정됨
* &amp;lbrack;물리적 크기&amp;rbrack; 물리적 크기 실제 비율 체크박스 상태가 처음 표시될 때 업데이트되지 않음
* &amp;lbrack;UI&amp;rbrack; 기본 재질 및 Height에 표준
* 이미지를 페인트할 때 커서가 보이지 않는 경우가 있는 &amp;lbrack;UI&amp;rbrack;
* &amp;lbrack;UI&amp;rbrack; 텍스트 필드가 비어 있는 경우 편집 메뉴에서 &quot;모두 복사&quot; 및 &quot;모두 잘라내기&quot; 옵션 비활성화
* &amp;lbrack;UI&amp;rbrack; 필터 이름에 잘못된 문자가 있습니다.
* &amp;lbrack;UI&amp;rbrack; 물리적 크기 잠금 버튼에 올바른 스타일이 없습니다.
* &amp;lbrack;UI&amp;rbrack; 에셋 패널의 검색 표시줄에 있는 닫기 버튼이 검색 문자열을 지우지 않습니다

**알려진 문제:**

* &amp;lbrack;색상 피커&amp;rbrack; 다른 해상도의 두 번째 모니터에서 색상 선택이 작동하지 않을 수 있습니다

### 3.2.0 야키토리

*(릴리스: 2022년 1월 25일)*

**추가됨:**

* &amp;lbrack;물리적 크기&amp;rbrack; 새 물리적 크기 패널
* &amp;lbrack;물리적 크기&amp;rbrack; 재료 생성 템플리트 창에 물리적 크기 옵션 추가
* &amp;lbrack;물리적 크기&amp;rbrack; 물리적 크기 측정 추가 도구
* &amp;lbrack;물리적 크기&amp;rbrack; 물리적 크기 자동 측정 추가 도구
* &amp;lbrack;물리적 크기(&amp;r); 물리적 크기 진단 도구 추가
* &amp;lbrack;물리적 크기&amp;rbrack; 물리적 크기의 z 값 설정을 허용합니다.
* 2D 보기에서 확대/축소 레벨을 설정하는 &amp;lbrack;물리적 크기&amp;rbrack; 드롭다운 위젯
* &amp;lbrack;물리적 크기&amp;rbrack; 확대/축소 드롭다운 수준의 새로운 &quot;물리적 비율로 표시&quot; 옵션
* &amp;lbrack;물리적 크기&amp;rbrack; 확대/축소 드롭다운 수준의 새로운 &quot;물리적 크기에 맞추기&quot; 옵션
* &amp;lbrack;물리적 크기&amp;rbrack; 2D 보기에서 물리적 크기 표시
* &amp;lbrack;물리적 크기&amp;rbrack; 3D 뷰포트에 물리적 크기 표시
* &amp;lbrack;물리적 크기&amp;rbrack; 이미지 가져오기 대화 상자에서 가져온 물리적 크기 맵이 있는 경우 Height 깊이 표시
* &amp;lbrack;물리적 크기&amp;rbrack; 에셋 컨텍스트 메뉴에 물리적 크기 표시
* &amp;lbrack;물리적 크기&amp;rbrack; 환경 설정에서 길이 단위 설정
* &amp;lbrack;물리적 크기&amp;rbrack; 실제 비율에 따라 텍스처를 내보냅니다
* &amp;lbrack;Metadata&amp;rbrack; 사용자가 작성한 에셋에 사용자 정의 메타데이터를 추가하는 기능
* &amp;lbrack;내보내기&amp;rbrack; 사용자 정의 메타데이터를 .sbs(ar) 파일로 내보내기
* &amp;lbrack;Export&amp;rbrack; 설명, 범주, 작성자 및 태그 메타데이터를 .sbs(ar) 파일로 내보내기
* &amp;lbrack;내보내기&amp;rbrack; .sbs(ar) 파일로 물리적 크기 내보내기
* &amp;lbrack;내보내기&amp;rbrack; .sbsar 파일 압축 설정 지정
* &amp;lbrack;내보내기&amp;rbrack; 에셋 축소판을 .sbs(ar) 파일로 내보내기
* &amp;lbrack;Export&amp;rbrack; .sbs(ar) 파일을 내보낼 때 그래프 유형을 설정합니다
* &amp;lbrack;Application&amp;rbrack; Realtime Engine 2021을 더 이상 사용할 수 없습니다.
* &amp;lbrack;응용 프로그램&amp;rbrack; 실행 취소/다시 실행 기능이 이제 타일링(U,V) 및 Height 비율 슬라이더 변경을 지원합니다.
* &amp;lbrack;렌더링&amp;rbrack; 작성된 에셋이 저장될 때 디스크 캐시 생성
* &amp;lbrack;Assets&amp;rbrack; 리소스 패널에서 여러 에셋 유형 필터를 활성화하려면 Ctrl+클릭 사용
* &amp;lbrack;UI&amp;rbrack; 타일링(U,V) 슬라이더를 잠그는 기능
* &amp;lbrack;UI&amp;rbrack; 텍스트 필드에 &quot;복사&quot;, &quot;잘라내기&quot;, &quot;붙여넣기&quot;, &quot;모두 복사&quot; 및 &quot;모두 잘라내기&quot;가 있는 상황별 메뉴 추가
* &amp;lbrack;UI&amp;rbrack; 길이 단위(미터, 인치, 파섹 등) 레이블 및 텍스트 필드 지원
* &amp;lbrack;UI&amp;rbrack; 사용자가 숫자를 표시하는 데 사용되는 소수점 자릿수를 설정할 수 있습니다.
* &amp;lbrack;UI&amp;rbrack; 관련된 모든 곳에서 단위를 측정 단위로 사용합니다.
* 이제 &amp;lbrack;Localization&amp;rbrack; 기본 새 에셋 이름이 현지화됩니다.
* &amp;lbrack;Content&amp;rbrack; New Cloth Weave generator
* &amp;lbrack;내용&amp;rbrack; 새 채널 전환 필터
* &amp;lbrack;내용&amp;rbrack; 이제 모든 관련 필터에서 물리적 크기를 인식합니다.
* &amp;lbrack;Content&amp;rbrack; 나무 마감을 위한 새로운 아이콘
* &amp;lbrack;Content&amp;rbrack; 이제 모든 필터가 ASM(Adobe 표준 재질) 채널과 호환됩니다.
* &amp;lbrack;Content&amp;rbrack; 필터에는 이제 &quot;환경&quot; 변형이 있을 수 있습니다.

**고정:**

* &amp;lbrack;2D View&amp;rbrack; 채널이 제거되어도 목록에 남아 있음
* &amp;lbrack;Application&amp;rbrack;에서는 운영 체제 파일 탐색기에서 로드한 에셋을 복제할 수 없습니다.
* &amp;lbrack;응용 프로그램(&amp;r); 종료 시 충돌
* &amp;lbrack;Application&amp;rbrack; 에셋 패널에서 &quot;스타터 에셋&quot;을 클릭할 때 때때로 충돌이 발생합니다
* &amp;lbrack;응용 프로그램&amp;rbrack; 재료 삭제 시 충돌
* &amp;lbrack;Application&amp;rbrack; 환경 변수 &quot;SUBSTANCE_DISABLE_SPECIFIC_FEATURES&quot;가 &quot;0&quot; 또는 &quot;&quot;로 설정된 경우에도 여전히 활성 상태입니다.
* &amp;lbrack;Application&amp;rbrack; 여러 재질이 있는 프로젝트를 저장하는 동안 멈춤
* &amp;lbrack;응용 프로그램&amp;rbrack; 이미지를 가져오면 충돌이 발생할 수 있습니다.
* &amp;lbrack;Application&amp;rbrack; 첫 실행 시 일부 시작 에셋이 누락됩니다.
* &amp;lbrack;내보내기&amp;rbrack; 에셋을 내보내면 충돌이 발생하는 경우가 있습니다
* &amp;lbrack;Layers&amp;rbrack; 레이어 패널이 닫혀 있거나 보이지 않으면 이미지를 가져올 수 없습니다.
* &amp;lbrack;Layers&amp;rbrack; 언어를 변경하면 현재 에셋이 다시 계산됩니다
* &amp;lbrack;Layers&amp;rbrack; 가져온 이미지의 사용을 변경해도 사용할 필터 변형이 업데이트되지 않습니다
* &amp;lbrack;Layers&amp;rbrack; Image to Material(AI)이 그 아래의 레이어를 수정할 때 계산되지 않는 경우가 있습니다
* &amp;lbrack;Layers&amp;rbrack; Image to Material(AI)이 때때로 필요하지 않을 때 다시 계산합니다.
* &amp;lbrack;Layers&amp;rbrack; 사용자 정의 필터를 디스크에서 업데이트할 때 업데이트가 권장되지 않습니다.
* &amp;lbrack;Layers&amp;rbrack; 표준 채널의 픽셀 형식이 잘못된 경우가 있습니다.
* &amp;lbrack;Layers&amp;rbrack; 일부 레이어는 표시되지 않더라도 여전히 계산됩니다.
* &amp;lbrack;Layers&amp;rbrack; 레이어 가시성을 전환할 때 2D 보기 도구가 깨질 수 있습니다
* &amp;lbrack;Layers&amp;rbrack; Image to Material(AI)을 사용할 때 UI가 멈춤
* &amp;lbrack;Layers&amp;rbrack; 변형 필터 레이어의 가시성을 전환하면 2D 보기 도구가 깨지고 충돌이 발생할 수 있습니다
* &amp;lbrack;Layers&amp;rbrack; 레이어 스택에서 레이어를 제거할 때 재계산이 너무 많습니다
* &amp;lbrack;Layers&amp;rbrack; 복합 필터에 비정상적인 또는 사용자 정의 입력/출력이 포함되어 있으면 Sampler에서 이를 계산하지 않습니다
* &amp;lbrack;성능&amp;rbrack; 에셋 패널이 느리게 열립니다
* &amp;lbrack;성능&amp;rbrack; 레이어 스택의 일부 불필요한 재계산 방지
* &amp;lbrack;성능&amp;rbrack; 프로젝트 에셋 로드 시간이 너무 오래 걸림
* &amp;lbrack;성능&amp;rbrack; 디스크의 렌더링 캐시는 사용할 수 없습니다.
* &amp;lbrack;성능&amp;rbrack; 레이어 간 전환이 느립니다.
* &amp;lbrack;성능&amp;rbrack; 재료 또는 필터의 트위킹이 느립니다
* &amp;lbrack;프로젝트&amp;rbrack; 종료 시 프로젝트를 저장하면 충돌이 발생할 수 있습니다
* &amp;lbrack;렌더링&amp;rbrack; 이미지 제거 시 모든 출력이 제거될 수 있음
* &amp;lbrack;Rendering&amp;rbrack; 뷰포트에 표시된 렌더링 시간이 조정할 때 잘못됨
* &amp;lbrack;UI&amp;rbrack; 필요할 때 내보내기 팝업에서 세로로 스크롤할 수 없습니다.
* &amp;lbrack;UI&amp;rbrack; 내보낼 항목이 없을 때 내보내기 팝업을 열 수 있습니다
* &amp;lbrack;UI&amp;rbrack; 일부 팝업은 콘텐츠가 오버플로되는 경우 스크롤되지 않습니다.
* &amp;lbrack;UI&amp;rbrack; 텍스트 필드는 클릭하거나 메뉴를 열 때 선택되지 않습니다
* &amp;lbrack;UI&amp;rbrack; 등록 정보 패널의 혼합 모드 이름이 정확하지 않을 수 있습니다
* &amp;lbrack;UI&amp;rbrack; 파일 메뉴의 저장 옵션이 회색으로 표시되는 경우가 있습니다.
* &amp;lbrack;UI&amp;rbrack; 두 재료의 이름을 바꾼 후 텍스트 필드가 사라지지 않습니다
* 환경 설정 팝업에서 &amp;lbrack;UI&amp;rbrack; 입력

**알려진 문제:**

* &amp;lbrack;색상 피커&amp;rbrack; 다른 해상도의 두 번째 모니터에서 색상 선택이 작동하지 않을 수 있습니다

### 3.1.2 Xocoatl

*(릴리스: 2021년 12월 14일)*

**고정:**

* &amp;lbrack;Interoperability&amp;rbrack; Bridge에서 Substance 3D Sampler으로 .sbsar 파일 열기 실패(Windows)
* &amp;lbrack;Layers&amp;rbrack; 아래에서 레이어만 이동하면 충돌합니다.
* 언어를 변경하면 &amp;lbrack;UI&amp;rbrack; 채널 설정 버튼이 사라짐
* &amp;lbrack;UI&amp;rbrack; 프로젝트를 저장한 후 속성 패널의 재질 이름이 사라집니다
* &amp;lbrack;Assets&amp;rbrack; &quot;모든 라이브러리&quot;를 클릭하면 충돌이 발생할 수 있습니다

**알려진 문제:**

* &amp;lbrack;Realtime Engine 2021&amp;rbrack; 과도한 계산으로 응용 프로그램이 충돌할 수 있음
* &amp;lbrack;Realtime Engine 2021&amp;rbrack; Realtime Engine 2021이 AMD CPU와 Nvidia GPU가 모두 설치된 Windows 시스템에서 충돌합니다.
* &amp;lbrack;색상 피커&amp;rbrack; 다른 해상도의 두 번째 모니터에서 색상 선택이 작동하지 않을 수 있습니다

### 3.1.1 Xocoatl

*(릴리스: 2021년 11월 24일)*

**추가됨:**

* &amp;lbrack;Interoperability&amp;rbrack; Substance 3D Designer으로 에셋(SBS 또는 SBSAR) 보내기
* &amp;lbrack;Interoperability&amp;rbrack; 환경 설정에서 Substance 3D Designer과의 상호 운용성을 위한 기본 형식을 설정합니다.
* &amp;lbrack;Interoperability&amp;rbrack; Adobe Bridge에서 여러 에셋 받기
* &amp;lbrack;UI&amp;rbrack; 새 임의화 위젯
* &amp;lbrack;UI&amp;rbrack; 컨텍스트 메뉴 업데이트
* &amp;lbrack;Assets&amp;rbrack; 에셋 패널에서 속성 패널로 이미지를 드래그하여 놓기
* &amp;lbrack;프로젝트&amp;rbrack; 특정 문자를 사용하지 않도록 자산 이름 기밀 정보 가리기
* &amp;lbrack;브랜딩&amp;rbrack; SBSAR 파일에 대한 파일 업데이트 아이콘
* &amp;lbrack;엔진&amp;rbrack; Substance 엔진 버전 8.3.0 업데이트

**고정:**

* &amp;lbrack;Content&amp;rbrack; 자르기 - 정사각형이 아닌 이미지를 자를 때 비율 유지
* &amp;lbrack;Content&amp;rbrack; Transform - 위젯을 사용할 때 수평 변환이 반전되지 않음
* &amp;lbrack;Content&amp;rbrack; Gravel - 모든 채널에서 사용자 정의 마스크 페인팅 수정
* &amp;lbrack;Content&amp;rbrack; 바닥 타일 - 패턴 타일링 및 반복 문제 수정
* &amp;lbrack;Assets&amp;rbrack; 설치되지 않은 경우 회색으로 표시 Adobe Bridge 옵션
* &amp;lbrack;색상 선택기&amp;rbrack; Esc 키로 색상 선택기가 닫힘
* &amp;lbrack;렌더링&amp;rbrack; 회색 음영 입력 사용 시 분산 거리 비율 수정
* &amp;lbrack;공유&amp;rbrack; 보내기 옵션은 Adobe 라이선스에서만 사용할 수 있습니다.
* &amp;lbrack;프로젝트&amp;rbrack; 메모리 성능 문제 수정

**알려진 문제:**

* &amp;lbrack;Realtime Engine 2021&amp;rbrack; 과도한 계산으로 응용 프로그램이 충돌할 수 있음
* &amp;lbrack;Realtime Engine 2021&amp;rbrack; Realtime Engine 2021이 AMD CPU와 Nvidia GPU가 모두 설치된 Windows 시스템에서 충돌합니다.
* &amp;lbrack;색상 피커&amp;rbrack; 다른 해상도의 두 번째 모니터에서 색상 선택이 작동하지 않을 수 있습니다

### 3.1.0 Xocoatl

*(릴리스: 2021년 9월 28일)*

**추가됨:**

* &amp;lbrack;색상 피커&amp;rbrack; 새 색상 피커 UI
* &amp;lbrack;색상 피커&amp;rbrack; 현재 및 이전 색상을 나란히 미리 봅니다.
* &amp;lbrack;색상 선택기&amp;rbrack; 16진수로 색상을 입력합니다.
* &amp;lbrack;색상 피커&amp;rbrack; 색상 미리보기가 있는 새 스포이드
* &amp;lbrack;색상 피커&amp;rbrack; 스포이드는 Sampler 외부의 색상을 선택할 수 있습니다
* &amp;lbrack;색상 선택기&amp;rbrack; RGB 또는 HSV 색상 공간에서 색상을 조정합니다.
* &amp;lbrack;색상 선택기&amp;rbrack; 견본 저장 및 관리
* &amp;lbrack;Interoperability&amp;rbrack; 이미지 가져오기 레이어 또는 이미지 매개 변수에서 Illustrator의 이미지 편집
* &amp;lbrack;Interoperability&amp;rbrack; 이미지 가져오기 레이어 또는 이미지 매개 변수에서 Photoshop의 이미지 편집
* &amp;lbrack;위젯&amp;rbrack; 새 자르기 위젯
* &amp;lbrack;Widget&amp;rbrack; 자르기를 확인하려면 Enter를 누릅니다.
* &amp;lbrack;Widget&amp;rbrack; [자르기] 위젯은 이미지 크기를 위젯에 맞게 읽고 크기를 조정할 때 비율을 유지합니다
* &amp;lbrack;UI&amp;rbrack; 새로운 회색 음영 슬라이더 UI
* &amp;lbrack;응용 프로그램&amp;rbrack; 기본 설정에서 일반 형식 선택 추가
* &amp;lbrack;Application&amp;rbrack; 이미지 가져오기 레이어의 일반 포맷은 환경 설정에 설정된 기본 일반 포맷을 따릅니다
* &amp;lbrack;Application&amp;rbrack;2D 보기에서는 기본 설정에 지정된 표준 형식에 따라 표준이 표시됩니다
* &amp;lbrack;Application&amp;rbrack; 일반은 환경 설정에 지정된 일반 형식으로 내보내집니다
* &amp;lbrack;Export&amp;rbrack; SBS 및 SBSAR 파일 내보내기에 일반 형식 매개 변수 추가
* &amp;lbrack;Export&amp;rbrack; SBS 및 SBSAR 파일 내보내기에 셰이더 설정을 추가합니다.
* &amp;lbrack;Export&amp;rbrack; 내보낸 SBS 그래프의 기본 해상도 설정
* &amp;lbrack;컴파운드 필터&amp;rbrack; 7z의 패키지 SSA 필터
* &amp;lbrack;컴파운드 필터&amp;rbrack; 컴파운드 필터에 범주 메타데이터 추가
* &amp;lbrack;컴파운드 필터&amp;rbrack; 컴파운드 필터에는 축소판이 포함될 수 있습니다.
* &amp;lbrack;컴파운드 필터&amp;rbrack;에서 [내용 가져오기] 파일 대화 상자에 컴파운드 필터 확장자(.ssafilter)를 추가했습니다
* 에셋 패널에서 &amp;lbrack;컴파운드 필터&amp;rbrack; 컴파운드 필터(.ssafilter) 가져오기
* &amp;lbrack;엔진&amp;rbrack; Substance 엔진을 v8.2.0으로 업데이트

**고정:**

* &amp;lbrack;응용 프로그램&amp;rbrack; 연결된 로컬 폴더가 중단될 수 있음
* &amp;lbrack;응용 프로그램(&amp;r); 종료 시 충돌
* &amp;lbrack;Application&amp;rbrack; Sampler의 두 인스턴스를 실행할 때 충돌함
* &amp;lbrack;Content&amp;rbrack; 자르기 필터에 임의화 수정이 있음
* &amp;lbrack;Content&amp;rbrack; 일부 Substance 재질이 업그레이드되지 않는 경우가 있습니다.
* &amp;lbrack;Export&amp;rbrack; 새로 추가된 사용자 정의 사전 설정을 사용하여 내보낼 때 충돌이 발생함
* 내보내기 팝업에서 패키지의 예상 크기가 누락됨(&amp;lbrack; Export&amp;rbrack;)
* &amp;lbrack;Export&amp;rbrack; SBS 및 SBSAR 파일을 내보낼 때 메모리 누수 수정
* &amp;lbrack;컴파운드 필터&amp;rbrack; 컴파운드 필터에는 중복 입력이 있을 수 있습니다.
* &amp;lbrack;복합 필터&amp;rbrack; 필터에 충족되지 않은 참조가 있는 경우 충돌합니다.
* &amp;lbrack;복합 필터&amp;rbrack; 복합 필터를 사용하여 레이어 스택의 순서를 변경하면 충돌함
* &amp;lbrack;컴파운드 필터&amp;rbrack; 렌더링이 가끔 중단됩니다
* &amp;lbrack;이미지 가져오기&amp;rbrack; 이미지 가져오기는 여러 렌더링을 트리거합니다.
* &amp;lbrack;레이어&amp;rbrack; 실행 취소/다시 실행 시 충돌
* &amp;lbrack;Layers&amp;rbrack; 기본 재질 추가 시 충돌
* &amp;lbrack;Layers&amp;rbrack; 환경 조명으로 잘못된 이미지를 사용할 때 충돌이 발생합니다.
* &amp;lbrack;Layers&amp;rbrack; 여러 그래프가 있는 필터를 삽입할 때 중복 가져오기 수정
* &amp;lbrack;레이어&amp;rbrack; 레이어 재정리가 작동하지 않는 경우가 있음
* &amp;lbrack;프로젝트&amp;rbrack; 불완전한 프로젝트 파일을 로드할 때 충돌이 발생합니다.
* &amp;lbrack;프로젝트&amp;rbrack; 손상된 프로젝트를 열 때 충돌
* &amp;lbrack;프로젝트&amp;rbrack; 일부 에셋이 프로젝트에서 사라질 수 있습니다.
* &amp;lbrack;등록 정보&amp;rbrack; 누락된 필터 사전 설정 수정
* &amp;lbrack;UI&amp;rbrack; 각도 매개 변수를 설정할 수 없습니다.
* &amp;lbrack;UI&amp;rbrack; 필터 메타데이터는 에셋 패널에 표시됩니다.
* &amp;lbrack;UI&amp;rbrack; 범주별로 그룹화하면 필터가 숨겨집니다.
* 에셋 패널의 &amp;lbrack;UI&amp;rbrack; 스크롤 문제
* &amp;lbrack;UI&amp;rbrack; 이제 내보내기 패널에 스크롤 막대가 있습니다.
* &amp;lbrack;UI&amp;rbrack; 이미지 선택기의 일부 이미지 포맷에 대해 축소판이 표시되지 않습니다

**알려진 문제:**

* &amp;lbrack;Realtime Engine 2021&amp;rbrack; 과도한 계산으로 응용 프로그램이 충돌할 수 있음
* &amp;lbrack;Realtime Engine 2021&amp;rbrack; Realtime Engine 2021이 AMD CPU와 Nvidia GPU가 모두 설치된 Windows 시스템에서 충돌합니다.
* &amp;lbrack;색상 피커&amp;rbrack; 다른 해상도의 두 번째 모니터에서 색상 선택이 작동하지 않을 수 있습니다

### 3.0.1 와플

*(릴리스: 2021년 7월 27일)*

**추가됨:**

* 이미지 입력이 지원하는 경우 브러시 도구에서 색상 활성화(&amp;lbrack; Brush&amp;rbrack;)
* &amp;lbrack;Brush&amp;rbrack; 브러시 도구에서 Shift 키를 누르고 있으면 직선이 그려집니다
* &amp;lbrack;Brush&amp;rbrack; 브러시 도구에서 shift 키를 누른 경우 선 미리 보기 표시
* &amp;lbrack;브러시&amp;rbrack; 브러시 도구가 이제 실행 취소 및 다시 실행을 지원합니다.
* &amp;lbrack;2D View&amp;rbrack; 페인팅 시 이미지 입력 기본 색상이 사용됨
* &amp;lbrack;Layers&amp;rbrack; SBSAR 파일의 Substance 입력 기본값 읽기
* &amp;lbrack;렌더링&amp;rbrack; Height과 일반 결합 허용
* &amp;lbrack;Rendering&amp;rbrack; 하위 표면 분산 지원(MacOS에서는 사용할 수 없음)
* &amp;lbrack;Assets&amp;rbrack; SBSAR 그래프 유형을 사용하여 에셋 유형 결정
* &amp;lbrack;Assets&amp;rbrack; 자산 패널의 검색 및 자산 검색 성능 향상
* &amp;lbrack;Assets&amp;rbrack; 모든 라이브러리의 모든 에셋을 표시하는 &#39;모든 라이브러리&#39; 항목이 에셋 패널에 추가되었습니다.
* &amp;lbrack;Assets&amp;rbrack; 사용자는 이제 자산을 범주 또는 유형별로 그룹화하도록 선택할 수 있습니다.
* &amp;lbrack;Import&amp;rbrack; 가져올 때 비등방성, 코트, 광택 및 Specular edge color 텍스처를 자동으로 감지
* &amp;lbrack;UI&amp;rbrack; 등록된 패널 제목을 아이콘으로 바꾸기
* &amp;lbrack;UI&amp;rbrack; 텍스트 필드 스타일 업데이트
* 환경 조명 템플릿 생성 창의 새 설명 텍스트(&amp;lbrack;UI&amp;rbrack;)
* &amp;lbrack;Application&amp;rbrack; 외부 애플리케이션으로 전송할 때 현재 해상도로 에셋 내보내기
* &amp;lbrack;Application&amp;rbrack; Material 기본 해상도는 이제 2048\*2048입니다(macos의 경우 1024\*1024).
* &amp;lbrack;Content&amp;rbrack; 바닥 타일 필터의 새 패턴
* &amp;lbrack;Content&amp;rbrack; 색상 대체 필터의 새로운 이중 색상 모드

**고정:**

* &amp;lbrack;2D 보기&amp;rbrack; 브러시 도구의 첫 번째 선이 때때로 끊기는 경우가 있습니다.
* 브러시 도구가 표시되지 않을 때 &amp;lbrack;2D View&amp;rbrack; 자유 리소스
* &amp;lbrack;2D View&amp;rbrack; 변형 위젯에서 오른쪽 크기 조정 커서를 사용합니다.
* 사용자가 이전에 2D 보기에서 패닝한 경우 &amp;lbrack;2D View&amp;rbrack; 위젯이 표시되지 않습니다.
* &amp;lbrack;Application&amp;rbrack; 워크플로가 중단된 프로젝트를 열 때 충돌 발생
* &amp;lbrack;Application&amp;rbrack; 쓸모없는 오류로 로그가 범람하는 것을 방지하기 위해 응용 프로그램 종료를 수정합니다
* &amp;lbrack;응용 프로그램 &amp;rbrack; 재실행, 삭제 및 저장 키보드 단축키가 일부 운영 체제에서 작동하지 않음
* &amp;lbrack;응용 프로그램&amp;rbrack; 가져오기 레이어에서 이미지 사용 변경 실행 취소/다시 실행이 중단됨
* &amp;lbrack;내보내기&amp;rbrack; 내보내기 색상 내보낸 이미지에 잘못된 이름이 있습니다.
* SBSAR 내보내기를 사용할 때 &amp;lbrack;Export&amp;rbrack; 환경이 8비트
* &amp;lbrack;내보내기&amp;rbrack; 내보낸 이미지 파일 이름에서 추가 공백 제거
* &amp;lbrack;내보내기&amp;rbrack; 사용자 정의 내보내기 사전 설정 바꾸기 또는 삭제 충돌
* 입력 개수 불일치가 있는 경우 충돌 방지(&amp;lbrack;Layers&amp;rbrack;)
* &amp;lbrack;Layers&amp;rbrack; 기본 재질 레이어 삽입 시 충돌
* &amp;lbrack;Layers&amp;rbrack; 필터 입력 수가 기본값으로 제한됨
* &amp;lbrack;Layers&amp;rbrack; 다시 실행을 통해 혼합 유형을 Height 혼합으로 잘못 변경
* &amp;lbrack;레이어&amp;rbrack; 입력 헤더 위의 놓기 영역 제거
* &amp;lbrack;Layers&amp;rbrack; 레이어가 입력 머리글 주위의 잘못된 위치에 삽입됩니다.
* &amp;lbrack;레이어&amp;rbrack; 모든 설정 재설정 버튼은 드롭다운 위젯 값을 재설정하지 않습니다
* &amp;lbrack;Layers&amp;rbrack; 이미지 가져오기 레이어에서 이미지를 변경할 때 실행 취소/다시 실행을 하면 프로젝트가 수정된 것으로 표시되어 저장됩니다
* &amp;lbrack;Layers&amp;rbrack; 사용이 혼합 레이어에 의해 중지될 수 있음
* &amp;lbrack;Project&amp;rbrack; 종속성 폴더가 누락된 레거시 프로젝트를 로드할 때 충돌 발생
* &amp;lbrack;프로젝트&amp;rbrack; 저장 후 실행 취소/다시 실행을 사용할 때 충돌 발생
* &amp;lbrack;프로젝트&amp;rbrack; 환경 조명이 포함된 SBSAR 파일을 열면 재질 에셋이 만들어집니다
* &amp;lbrack;프로젝트&amp;rbrack; 재료의 이름을 변경하면 축소판 생성이 트리거될 수 있습니다.
* &amp;lbrack;프로젝트&amp;rbrack; 재료 이름을 바꾼 후 저장하면 프로젝트가 수정되지 않은 것으로 표시됩니다.
* &amp;lbrack;프로젝트&amp;rbrack; 재료 이름 변경 후 일부 변경 사항은 저장되지 않습니다
* &amp;lbrack;Rendering&amp;rbrack; 2020 실시간 엔진이 있는 환경에서 밝은 점이 보임
* &amp;lbrack;Rendering&amp;rbrack; 실시간 엔진 2021을 사용하여 크기를 조정할 때 충돌
* &amp;lbrack;렌더링&amp;rbrack; Height 레벨 변경 시 그림자 다시 계산
* &amp;lbrack;Assets&amp;rbrack; 연결된 폴더는 잘못된 파일을 추가할 때 새 에셋의 색인을 중지합니다
* &amp;lbrack;Assets&amp;rbrack; 재료가 많은 로컬 폴더를 연결할 때 충돌
* &amp;lbrack;UI&amp;rbrack; 2D/3D 보기 단추 도구 설명 누락
* &amp;lbrack;UI&amp;rbrack; 자산 패널의 모든 자산이 시작 시 강조 표시됨
* 자료를 가져올 때 에셋 패널에서 &amp;lbrack;UI&amp;rbrack; 탐색 기록이 사라지는 경우가 있습니다.
* &amp;lbrack;UI&amp;rbrack; 언어 변경은 프로젝트 패널에 영향을 주지 않습니다.
* &amp;lbrack;UI&amp;rbrack; 채널 설정 패널에 레거시 워크플로우 정보가 표시됨
* &amp;lbrack;UI&amp;rbrack; [속성] 패널에 수정 사항이 없는 필터에 대해 &quot;이 항목에 대한 설정 없음&quot; 텍스트를 올바르게 맞춤
* 시작 화면 및 환경 설정 팝업에서 &amp;lbrack;UI&amp;rbrack; 요소가 잘못 정렬됨
* &amp;lbrack;UI&amp;rbrack; 패널 제목의 너비가 잘못되었습니다.
* 속성 패널에서 &amp;lbrack;UI&amp;rbrack; 스크롤이 끊기는 경우가 있습니다.
* &amp;lbrack;UI&amp;rbrack; 시작 화면의 비율이 잘못되었으며 화면이 흐려짐
* &amp;lbrack;UI&amp;rbrack; 전체 화면 모드가 전체 화면이 아닙니다.
* &amp;lbrack;UI&amp;rbrack; 도킹되지 않은 패널은 MacOS에서 응용 프로그램이 활성화되어 있지 않아도 항상 맨 위에 있습니다
* &amp;lbrack;UI&amp;rbrack; 시작 화면 배너 이미지 업데이트
* &amp;lbrack;내용&amp;rbrack; 타일링 필터가 주변 오클루전 채널을 처리하지 않음
* &amp;lbrack;Content&amp;rbrack; 퀼트 스티치(quilt stitch) 문제(용접 어셈블리 솔기 선택 및 다이아몬드 패턴)
* &amp;lbrack;Content&amp;rbrack; 엠보스 필터는 256px x 256px에서 작동합니다.
* &amp;lbrack;Content&amp;rbrack; 오프셋이 0보다 클 때 바닥 타일의 타일링 문제 수정

**알려진 문제:**

* &amp;lbrack;Realtime Engine 2021&amp;rbrack; 대규모 계산, 응용 프로그램 충돌
* &amp;lbrack;Realtime Engine 2021&amp;rbrack; Realtime Engine 2021이 AMD CPU 및 Nvidia GPU가 모두 있는 Windows 시스템에서 충돌합니다.

### 3.0.0 와플

*(릴리스: 2021년 6월 23일)*

**추가됨:**

* &amp;lbrack;Branding&amp;rbrack; Substance Alchemist이 Adobe Substance 3D Sampler이 됨
* &amp;lbrack;브랜딩&amp;rbrack; 새 응용 프로그램 아이콘
* &amp;lbrack;UI&amp;rbrack; 새로운 사용자 경험 및 사용자 인터페이스
* &amp;lbrack;UI&amp;rbrack; 새로운 화면
* &amp;lbrack;UI&amp;rbrack; 패널은 인터페이스에서 연결 및 연결이 불가능합니다.
* &amp;lbrack;UI&amp;rbrack; 동일한 열에 최대 3개 패널 고정
* &amp;lbrack;UI&amp;rbrack; 동일한 패널에서 최대 3개 패널 고정(탭)
* &amp;lbrack;UI&amp;rbrack; 패널을 고정 해제하여 같거나 다른 화면에 별도의 창을 만듭니다
* 아이콘을 클릭하면 &amp;lbrack;UI&amp;rbrack; 닫힌 패널 팝업이 표시됨
* &amp;lbrack;UI&amp;rbrack; 패널 아이콘을 이동하여 왼쪽 및 오른쪽 막대를 다시 정렬합니다.
* &amp;lbrack;UI&amp;rbrack; 직접 특정 필터에 액세스할 수 있는 새 도구 모음(자르기, 변형, 원근감 변형, 복제 도장)
* &amp;lbrack;UI&amp;rbrack; 왼쪽 막대의 새로운 &quot;내용 가져오기&quot; 버튼
* &amp;lbrack;UI&amp;rbrack; 콘텐츠 가져오기 버튼을 사용하여 에셋에서 직접 파일 가져오기
* &amp;lbrack;UI&amp;rbrack; 내용 가져오기 버튼을 사용하여 파일을 레이어에 직접 가져오기
* &amp;lbrack;UI&amp;rbrack; 컨텐츠 가져오기 버튼으로 직접 Adobe Substance 3D Assets 웹 사이트에 액세스
* 이제 뷰포트에서 &amp;lbrack;UI&amp;rbrack; 해상도 위젯에 직접 액세스할 수 있습니다.
* &amp;lbrack;UI&amp;rbrack; 이제 모든 UI 요소가 동적으로 로드됩니다.
* &amp;lbrack;UI&amp;rbrack; 단축키 - &quot;2&quot;를 사용하여 2D 보기의 가시성을 전환합니다.
* &amp;lbrack;UI&amp;rbrack; 단축키 - &quot;3&quot;을 사용하여 3D 보기의 가시성을 전환합니다.
* &amp;lbrack;시작 화면&amp;rbrack; 새로 만들기 버튼을 사용하여 한 번의 클릭으로 프로젝트 만들기
* &amp;lbrack;시작 화면&amp;rbrack; 새 아트워크 배너
* &amp;lbrack;프로젝트&amp;rbrack; 이제 모든 프로젝트가 고유한 파일에 연결됩니다.
* &amp;lbrack;프로젝트&amp;rbrack; 새 프로젝트 파일 확장자 .ssa
* &amp;lbrack;프로젝트(&amp;r); 프로젝트로 저장 시 프로젝트를 저장할 위치를 선택하라는 메시지가 표시됩니다.
* &amp;lbrack;프로젝트&amp;rbrack; Sampler을 닫으면 저장되지 않은 경우 프로젝트를 저장하라는 메시지가 표시됩니다.
* &amp;lbrack;Project&amp;rbrack; Sampler을 닫으면 마지막 저장 이후에 수정 사항이 있는 경우 프로젝트를 저장하라는 메시지가 표시됩니다
* &amp;lbrack;프로젝트&amp;rbrack; 프로젝트의 이름이 뷰포트 위에 표시됩니다
* &amp;lbrack;프로젝트&amp;rbrack; 저장되지 않았거나 마지막 저장 이후에 수정 사항이 포함된 경우 프로젝트 이름에 별이 붙습니다
* &amp;lbrack;프로젝트&amp;rbrack; OS 탐색기에서 직접 .ssa 프로젝트 파일을 엽니다.
* &amp;lbrack;프로젝트&amp;rbrack; OS 탐색기에서 .sbsar를 열면 이 .sbsar 파일을 사용할 수 있는 새 프로젝트와 함께 Sampler이 실행됩니다
* &amp;lbrack;프로젝트&amp;rbrack; OS 탐색기에서 .alch(레거시 Substance Alchemist 파일)를 엽니다
* &amp;lbrack;프로젝트 패널(&amp;r); 프로젝트 내에서 생성된 모든 에셋을 포함할 새 패널
* &amp;lbrack;프로젝트 패널&amp;rbrack; + 아이콘을 사용하여 에셋(재질 또는 환경 조명) 만들기
* &amp;lbrack;프로젝트 패널&amp;rbrack; 에셋을 마우스 오른쪽 버튼으로 클릭하면 컨텍스트 메뉴가 열립니다.
* &amp;lbrack;프로젝트 패널&amp;rbrack;마우스 오른쪽 단추 클릭 상황에 맞는 메뉴에서 에셋을 삭제할 수 있습니다
* &amp;lbrack;프로젝트 패널&amp;rbrack;마우스 오른쪽 단추 클릭 상황에 맞는 메뉴에서 에셋을 복제할 수 있습니다
* &amp;lbrack;프로젝트 패널&amp;rbrack;마우스 오른쪽 단추 클릭 상황에 맞는 메뉴에서 에셋의 이름을 바꿀 수 있습니다
* &amp;lbrack;프로젝트 패널&amp;rbrack; 에셋 간 전환해도 수정 사항이 손실되지 않습니다.
* &amp;lbrack;해상도&amp;rbrack; 이제 모든 에셋에 대해 정사각형이 아닌 해상도를 설정할 수 있습니다
* &amp;lbrack;해상도&amp;rbrack; 해상도 값은 프로젝트 내의 에셋에 의해 저장됩니다
* &amp;lbrack;환경 조명&amp;rbrack; Substance 3D Sampler 내에서 환경 조명 만들기
* &amp;lbrack;환경 조명&amp;rbrack; 환경 조명을 만들 때 이미지를 드래그하여 놓으면 환경 조명 만들기 템플릿 창이 표시됩니다
* &amp;lbrack;환경 조명&amp;rbrack; 환경 조명 생성 템플릿에서 환경 가져오기 를 선택하여 3D 보기의 환경에 이미지를 할당합니다
* &amp;lbrack;환경 조명&amp;rbrack;환경 조명 생성 템플릿에서 HDR 병합 을 선택하여 노출이 다른 여러 360도 이미지에서 환경 조명을 만듭니다
* 환경 조명을 만들기 전에 환경 조명 만들기 템플릿에서 &quot;비트맵으로 사용&quot;을 선택하여 이미지를 편집합니다.
* &amp;lbrack;환경 조명&amp;rbrack; 이미지 가져오기 레이어의 환경 사용을 할당하여 3D 보기의 환경에 이미지를 직접 할당합니다
* &amp;lbrack;환경 조명&amp;rbrack;환경 채널의 2D 보기에서는 3D 보기에서와 같이 렌더링이 표시되도록 자동 색상 교정이 있습니다
* &amp;lbrack;환경 조명&amp;rbrack; 환경 조명 생성을 위한 새로운 전용 콘텐츠
* &amp;lbrack;에셋 패널(&amp;r); 리소스 및 필터 패널이 새 에셋 패널에 병합됩니다.
* &amp;lbrack;에셋 패널(&amp;r); 이제 에셋 패널은 재질, 필터 및 이미지 에셋 유형을 지원합니다.
* &amp;lbrack;에셋 패널(&amp;rbrack; 모든 스타터 에셋은 스타터 에셋 섹션에서 액세스할 수 있습니다.
* &amp;lbrack;에셋 패널&amp;rbrack; 스타터 에셋 섹션은 읽기 전용입니다.
* &amp;lbrack;에셋 패널&amp;rbrack; 새로운 &quot;내 에셋&quot; 섹션
* &amp;lbrack;Assets Panel&amp;rbrack; &quot;내 에셋&quot; 섹션은 모든 리소스를 가져올 수 있는 곳입니다
* &amp;lbrack;에셋 패널&amp;rbrack; &quot;내 에셋&quot;의 모든 에셋이 내 문서의 특정 폴더에 추가됩니다
* &amp;lbrack;에셋 패널(&amp;r); 에셋 패널에서 로컬 폴더를 연결하여 새 섹션 추가
* &amp;lbrack;에셋 패널&amp;rbrack; 검색은 현재 폴더와 그 하위 폴더를 검색합니다.
* &amp;lbrack;에셋 패널&amp;rbrack; 탐색 경로를 사용하여 폴더와 하위 폴더 간 탐색
* &amp;lbrack;에셋 패널&amp;rbrack; 현재 폴더를 재질, 필터 또는 이미지별로 필터링합니다.
* &amp;lbrack;에셋 패널&amp;rbrack; 여러 필터를 결합하여 재질과 이미지만 가져옵니다.
* &amp;lbrack;에셋 패널&amp;rbrack; 격자 또는 목록 사이를 전환하여 표시 변경
* &amp;lbrack;에셋 패널(&amp;r); 필터는 아이콘으로 표시됩니다.
* &amp;lbrack;에셋 패널(&amp;r); 이미지가 미리 보기로 표시됨
* &amp;lbrack;에셋 패널&amp;rbrack; 너비를 늘리면 특정 보기에서 패널의 레이아웃이 변경되어 폴더 간에 탐색됩니다
* &amp;lbrack;에셋 패널&amp;rbrack;읽기 전용 섹션이 아닌 경우 에셋을 저장소 아이콘에 드래그하여 놓아 삭제합니다
* &amp;lbrack;에셋 패널&amp;rbrack; 에셋을 마우스 오른쪽 버튼으로 클릭하면 컨텍스트 메뉴가 열립니다.
* &amp;lbrack;자산 패널&amp;rbrack; 마우스 오른쪽 버튼 클릭 컨텍스트 메뉴에서 자산 메타데이터(이름, 범주, 위치)에 액세스합니다
* &amp;lbrack;에셋 패널&amp;rbrack;마우스 오른쪽 단추 클릭 상황에 맞는 메뉴에서 에셋을 삭제합니다(읽기 전용 이외의 섹션에서만 사용 가능)
* &amp;lbrack;에셋 패널&amp;rbrack; 마우스 오른쪽 단추 클릭의 상황에 맞는 메뉴에서 Adobe Bridge에서 에셋을 검색합니다
* &amp;lbrack;레이어 패널(&amp;r); 레이어 위에 기본 재질을 직접 추가하는 새로운 아이콘
* &amp;lbrack;레이어 패널&amp;rbrack; 단축키 - Shift + B를 사용하면 레이어 위에 기본 재질이 추가됩니다.
* &amp;lbrack; 레이어 패널(&amp;r); 레이어에 축소판 미리 보기(재질 축소판, 필터 아이콘 또는 이미지 미리 보기)가 있음
* &amp;lbrack;Properties Panel&amp;rbrack; 에셋 이름 및 에셋 축소판이 있는 [속성] 패널 제목의 새 디자인
* &amp;lbrack;속성 패널(&amp;r); 필터 레이어가 이제 사전 설정을 지원합니다.
* 이미지 가져오기 레이어에서 &amp;lbrack;속성 패널&amp;rbrack;을 선택하고 이미지 미리 보기를 마우스 오른쪽 버튼으로 클릭하여 Photoshop에서 이미지를 편집합니다
* &amp;lbrack;Adobe Bridge&amp;rbrack; Adobe Bridge에서 에셋을 검색하면 해당 에셋의 위치에서 Bridge가 실행됩니다
* &amp;lbrack;Adobe Photoshop&amp;rbrack; Adobe Photoshop에서 편집하면 Photoshop에서 이미지를 편집할 준비가 된 상태로 열립니다
* &amp;lbrack;Adobe Photoshop&amp;rbrack; Adobe Photoshop에 저장할 때마다 편집된 이미지가 Sampler에 다시 로드됩니다.
* &amp;lbrack;Substance 3D Designer&amp;rbrack; Adobe Substance 3D Designer에서 보낸 에셋이 에셋 패널의 &quot;내 에셋&quot; 섹션에 직접 도착합니다
* &amp;lbrack;내보내기&amp;rbrack; Adobe Substance 3D Painter 및 Adobe Substance 3D Stager으로 에셋을 바로 보내기
* &amp;lbrack;내보내기&amp;rbrack; Adobe Substance 3D Painter으로 재질 및 환경 조명 보내기
* &amp;lbrack;내보내기&amp;rbrack; 환경 조명을 Adobe Substance 3D Stager으로 보내기
* &amp;lbrack;렌더링&amp;rbrack; 이제 새 질감 속성이 지원되고 3D로 렌더링됨
* &amp;lbrack;렌더링&amp;rbrack; 광택 지원 추가(광택 색상, 광택 불투명도 및 광택 거칠음)
* &amp;lbrack;렌더링&amp;rbrack; 코팅 지지체 추가(코팅 색상, 코팅 거칠기, 일반 코팅, Specular level 코팅 및 IOR 코팅)
* &amp;lbrack;렌더링&amp;rbrack; 비등방성 지원 추가(비등방성 레벨 및 비등방성 각도)
* &amp;lbrack;렌더링&amp;rbrack; Specular edge color 지원 추가
* &amp;lbrack;렌더링&amp;rbrack; 채널 설정 패널에서 이러한 새 속성을 활성화합니다
* &amp;lbrack;Rendering&amp;rbrack; Beta에서 새로운 실시간 엔진(2021) 렌더러 소개
* &amp;lbrack;Rendering&amp;rbrack; 뷰어 설정 패널에서 두 렌더러 버전 간 전환
* &amp;lbrack;Rendering&amp;rbrack; 실시간 엔진(2021) 렌더러는 투명도, 흡수 및 분산 재질 속성을 지원합니다
* &amp;lbrack;Rendering&amp;rbrack; 실시간 엔진(2021) 렌더러에는 환경 조명에서 그림자를 계산하는 새로운 방법이 도입되었습니다.
* &amp;lbrack;Rendering&amp;rbrack; 실시간 엔진(2021) 렌더러는 환경 조명의 조도를 실시간으로 계산합니다
* &amp;lbrack;Shader Settings Panel&amp;rbrack; 특정 재료 셰이더 매개 변수를 조정하기 위한 새로운 셰이더 설정 패널
* &amp;lbrack;Shader Settings Panel&amp;rbrack; 새 매개 변수(표준 비율, Height 비율, Height 레벨, 방출 강도, IOR, 코트 표준 강도 및 코트 IOR)
* &amp;lbrack;Shader Settings Panel&amp;rbrack; 실시간 엔진 2021에 대한 특정 매개 변수(서브서피스 스캐터링, 스캐터링 거리, 빨강 이동 및 레일리 스캐터링)
* &amp;lbrack;Shader Settings Panel&amp;rbrack; 설정 값은 에셋별로 저장됩니다
* &amp;lbrack;뷰어 설정 패널(&amp;rbrack;)에서 기본 환경 조명에 대한 미리 보기를 추가했습니다.
* &amp;lbrack;뷰어 설정 패널(&amp;rbrack;)에서 기본 메시에 대한 미리 보기를 추가했습니다.
* &amp;lbrack;뷰어 설정 패널(&amp;rbrack; 새 환경 불투명도 매개 변수
* &amp;lbrack;뷰어 설정 패널(&amp;rbrack; 새 환경 흐림 효과 매개 변수(Realtime Engine 2021 렌더러에만 해당)
* &amp;lbrack;Localization&amp;rbrack; 독일어 및 프랑스어의 새로운 번역
* &amp;lbrack;Content&amp;rbrack; 새로운 기본 스타터 재질
* &amp;lbrack;내용&amp;rbrack; 새 기본 환경 조명
* &amp;lbrack;Content&amp;rbrack; 모든 필터가 업데이트, 정리 및 최적화되었습니다.
* &amp;lbrack;Content&amp;rbrack; 조정 필터가 여러 개의 필터로 분할되었습니다
* &amp;lbrack;내용&amp;rbrack; 새로운 명도/대비 필터
* &amp;lbrack;내용&amp;rbrack; 새로운 색조/채도 필터
* &amp;lbrack;내용&amp;rbrack; 새로운 활기 필터
* &amp;lbrack;내용&amp;rbrack; 새로운 선명 효과 필터
* &amp;lbrack;내용&amp;rbrack; 새로운 표준/Height 조정
* &amp;lbrack;내용&amp;rbrack; 새 패널 필터
* &amp;lbrack;내용&amp;rbrack; 새 스머지 필터
* &amp;lbrack;Content&amp;rbrack; New Weaves filter
* &amp;lbrack;내용&amp;rbrack; 새 뒤틀기 변형 필터
* &amp;lbrack;Content&amp;rbrack; AO 필터에 대한 새 Height
* &amp;lbrack;Content&amp;rbrack; 새로운 일반 Height 필터
* &amp;lbrack;Content&amp;rbrack; Color Replace - 새로 지원되는 채널(광택, 코팅, 비등방성 등)에서 바꾸기
* &amp;lbrack;Content&amp;rbrack; 색상 변형 - 변경할 색상을 정확하게 선택하는 수동 모드
* &amp;lbrack;Content&amp;rbrack; 타일링 - 이음새 컷을 시각화하는 옵션
* &amp;lbrack;Content&amp;rbrack; 타일링 - 완벽한 타일링을 위해 잘린 이음새를 페인팅하는 옵션
* &amp;lbrack;Content&amp;rbrack; 일치 - 색상 및 거칠기에 맞는 재질을 추가하는 옵션
* &amp;lbrack;Content&amp;rbrack; 일치 - 이제 다른 이미지의 색상과 일치하도록 이미지에서 작동합니다
* &amp;lbrack;내용&amp;rbrack; 환경 조명 - 새로운 색온도 필터
* &amp;lbrack;내용&amp;rbrack; 환경 조명 - 새 노출 필터
* &amp;lbrack;내용&amp;rbrack; 환경 조명 - 새로운 노출 미리 보기 필터
* &amp;lbrack;콘텐츠&amp;rbrack; 환경 조명 - 새 Nadir Patch 필터
* &amp;lbrack;콘텐츠&amp;rbrack; 환경 조명 - 새 Nadir Extract 필터
* &amp;lbrack;내용&amp;rbrack; 환경 조명 - 새 조명 필터(구, 선, 모양, 평면)
* &amp;lbrack;내용&amp;rbrack; 환경 조명 - 새 파노라마 패치 필터
* &amp;lbrack;내용&amp;rbrack; 환경 조명 - 새로운 수평선 곧게 필터
* &amp;lbrack;콘텐츠&amp;rbrack; 환경 조명 - 새로운 HDR 병합 필터

**알려진 문제:**

* &amp;lbrack;Realtime Engine 2021&amp;rbrack; 레이아웃 변경, 응용 프로그램 충돌
* &amp;lbrack;Realtime Engine 2021&amp;rbrack; 대규모 계산, 응용 프로그램 충돌
* &amp;lbrack;Panels&amp;rbrack; MacOS - 고정 해제된 패널이 모든 애플리케이션 앞에 있음
* &amp;lbrack;Widgets&amp;rbrack; Transform 및 Position 위젯이 사라질 수 있습니다. 레이어를 숨기거나 숨김 해제하여 표시합니다.
* &amp;lbrack;Export&amp;rbrack; 환경 조명의 SBSAR 내보내기는 32비트 심도 정밀도를 손실합니다.
* &amp;lbrack;에셋 패널&amp;rbrack; 폴더를 열 때 에셋 강조 표시
* &amp;lbrack;등록 정보 패널&amp;rbrack; 매개 변수를 재설정해도 콤보 상자 UI가 재설정되지 않음
* &amp;lbrack;지역화&amp;rbrack; 언어 변경은 다시 만들어질 때까지 프로젝트 패널에 영향을 주지 않습니다

## 버전 2

### 2.3.2 (2020.3.2) 버미첼리

*(릴리스: 2021년 2월 23일)*

**추가됨:**

* &amp;lbrack;Localization&amp;rbrack; 일본어 지원

**고정:**

* 자수 필터에서 재질을 비틀면 자수 이미지가 손실됩니다.

**알려진 문제:**

* 고해상도 이미지에서 [이미지를 재료로](AI 기반)를 사용하는 속도가 느려질 수 있습니다
* 내용 인식 채우기 필터의 고해상도는 느립니다
* 슬라이더에서 특정 값을 입력할 때 혼수 또는 점을 무시할 수 있습니다
* 동일한 재질 레이어 스택의 2배 저장이 불가능

### 2.3.1 (2020.3.1) 버미첼리

*(릴리스: 2020년 12월 17일)*

**추가됨:**

* &amp;lbrack;엔진&amp;rbrack; Substance 엔진 업데이트
* 특정 기능을 비활성화하는 &amp;lbrack;Application&amp;rbrack; 환경 변수
* &amp;lbrack;내용&amp;rbrack; 색상 대체 - 새로운 고급 분할 옵션
* &amp;lbrack;Content&amp;rbrack; 바닥 타일 - 새로운 패턴 및 옵션 사용 가능
* &amp;lbrack;Content&amp;rbrack; 자수 - 필터 전체 개조
* &amp;lbrack;Content&amp;rbrack; 조정 - 새 금속성 매개변수 + 불투명도 안전 변형 교정

**고정:**

* &amp;lbrack;Layers&amp;rbrack;에서 동일한 사용자 정의 필터를 두 번 가져올 수 없습니다.
* &amp;lbrack;Layers&amp;rbrack; 브러시 도구로 이미지 입력을 사용할 수 없습니다.
* &amp;lbrack;Export&amp;rbrack; .jpeg 대신 .jpg로 내보내기
* &amp;lbrack;UI&amp;rbrack; 시작 화면 이미지 크레딧 업데이트
* &amp;lbrack;UI&amp;rbrack; 메뉴의 보이지 않는 구분 기호 수정
* &amp;lbrack;UI&amp;rbrack; 라디오 버튼이 잘릴 때 도구 설명이 표시됨
* &amp;lbrack;UI&amp;rbrack; 오타: 스타터 재질
* &amp;lbrack;Application&amp;rbrack; 자산 이름의 UTF-8 문자가 작동하지 않습니다.
* &amp;lbrack;Localization&amp;rbrack; 중국어 로케일에 대한 이탤릭체 글꼴 스타일 비활성화
* &amp;lbrack;Localization&amp;rbrack; 지역화된 문자열이 2줄로 분할됨
* &amp;lbrack;Localization&amp;rbrack; 폴더 이름을 조정하고 너무 길면 생략 부호로 대체합니다
* &amp;lbrack;Localization&amp;rbrack; 천 단위 구분 기호가 있는 형식 번호
* &amp;lbrack;Localization&amp;rbrack; Localize 날짜 및 시간 표시
* &amp;lbrack;Localization&amp;rbrack; Windows에서 색상 피커 지역화
* &amp;lbrack;Content&amp;rbrack; Transform - 안전한 변환이 활성화되면 법선이 45°마다 올바르게 회전합니다.
* &amp;lbrack;Content&amp;rbrack; 표면 부조 - 퍼린 프랙탈 노이즈(고급 노이즈)의 타일링 문제 수정
* &amp;lbrack;Content&amp;rbrack; Brickwall 패턴 - 16비트 Height 입력
* &amp;lbrack;내용&amp;rbrack; 재질 아이콘 렌더링 - Specular 반사 문제
* &amp;lbrack;내용&amp;rbrack; 색상 변형 - 색상 입력과 결과 간 색상 이동 없음
* &amp;lbrack;내용&amp;rbrack; 색상 변형 - 성능 업데이트

**알려진 문제:**

* 고해상도 이미지에서 [이미지를 재료로](AI 기반)를 사용하는 속도가 느려질 수 있습니다
* 내용 인식 채우기 필터의 고해상도는 느립니다
* 슬라이더에서 특정 값을 입력할 때 혼수 또는 점을 무시할 수 있습니다
* 동일한 재질 레이어 스택의 2배 저장이 불가능

### 2.3.0 (2020.3.0) 버미첼리

*(릴리스: 2020년 10월 26일)*

**추가됨:**

* &amp;lbrack;Image to Material&amp;rbrack; NVIDIA RTX 3000 시리즈 지원
* &amp;lbrack;Image to Material&amp;rbrack; 형상 세부 정보를 제어하는 새로운 매개변수
* &amp;lbrack;이미지를 재료로&amp;rbrack; 거칠기를 제어하는 새로운 매개 변수
* &amp;lbrack;Image to Material&amp;rbrack; 흐림 강도를 제어하는 새로운 매개변수
* &amp;lbrack;Thumbnails&amp;rbrack; Substance Designer의 PBR 렌더러를 기반으로 하는 새 썸네일 생성기
* &amp;lbrack;Thumbnails&amp;rbrack; 기본 재질 및 아틀라스를 업데이트하여 해당 썸네일을 포함합니다.
* &amp;lbrack;Thumbnails&amp;rbrack; .sbsar 파일의 축소판(있는 경우)을 검색합니다.
* &amp;lbrack;Thumbnails&amp;rbrack; 환경 설정에서 축소판 품질 변경
* &amp;lbrack;엔진&amp;rbrack;이(가) Substance 엔진 버전 8로 업데이트됨
* &amp;lbrack;Localization&amp;rbrack; 중국어 현지화
* &amp;lbrack;UI&amp;rbrack; 시험적 별색 선택기
* &amp;lbrack;Content&amp;rbrack; 새 환경 맵 - Studio 06
* &amp;lbrack;Content&amp;rbrack; Atlas Generator 필터 추가
* &amp;lbrack;내용&amp;rbrack; Atlas Splitter 필터 추가
* &amp;lbrack;내용&amp;rbrack; 버려진 검 추가 필터
* &amp;lbrack;내용&amp;rbrack; 지문 추가 필터
* &amp;lbrack;내용&amp;rbrack; Scratches 추가 필터
* &amp;lbrack;Content&amp;rbrack; 표면 부조 필터 추가(Height 변조 필터 대체)
* &amp;lbrack;내용&amp;rbrack; 뒤틀기 필터 추가
* &amp;lbrack;내용(&amp;r); 반전 추가 필터
* &amp;lbrack;내용&amp;rbrack; 색상화 필터 추가
* &amp;lbrack;내용&amp;rbrack; 대체 색상 필터 추가
* &amp;lbrack;Content&amp;rbrack; Transform - 특정 채널에서 변형을 비활성화할 수 있는 가능성을 추가합니다
* &amp;lbrack;Content&amp;rbrack; 변환 - 안전 변환이 활성화되면 회전 추가
* &amp;lbrack;Content&amp;rbrack; 색상 변형 - 색상을 배포하는 방법을 선택하기 위한 분할 옵션 추가

**고정:**

* &amp;lbrack;Layers&amp;rbrack; 여러 실행 취소/다시 실행 작업을 수행할 때 UI를 올바르게 업데이트
* &amp;lbrack;Layers&amp;rbrack; 여러 실행 취소/다시 실행 작업을 수행할 때 충돌 방지
* &amp;lbrack;Layers&amp;rbrack; Image to Material(AI Powered)을 로그와 함께 사용할 때 충돌 발생: 잘못된 장치 서수
* &amp;lbrack;Filters&amp;rbrack; NVIDIA 그래픽 카드 탐지 개선 NVidia 특정 기능
* 애플리케이션을 닫을 때 &amp;lbrack;Application&amp;rbrack;가 충돌함
* &amp;lbrack;Application&amp;rbrack; MacOS에서 VRAM 양 감지 수정
* &amp;lbrack;내보내기&amp;rbrack; 일부 내보내기 사전 설정이 누락되는 경우가 있습니다
* &amp;lbrack;내용&amp;rbrack; 유화 효과 - 변위 진폭이 높은 Height 범위 수정
* &amp;lbrack;Content&amp;rbrack; Make It Tile Advanced - 내보낼 때 빛바랜 색상 없음
* &amp;lbrack;Content&amp;rbrack; Make It Tile Advanced - AO가 너무 강할 때 기본 색상의 흰색 마스크
* &amp;lbrack;Content&amp;rbrack; 조정 - 이제 이미지에서 작동합니다(scan1, ...)

**알려진 문제:**

* 고해상도 이미지에서 [이미지를 재료로](AI 기반)를 사용하는 속도가 느려질 수 있습니다
* 내용 인식 채우기 필터의 고해상도는 느립니다
* 슬라이더에서 특정 값을 입력할 때 혼수 또는 점을 무시할 수 있습니다
* 동일한 재질 레이어 스택의 2배 저장이 불가능

### 2.2.1 (2020.2.1) 우동

*(릴리스: 2020년 7월 21일)*

**추가됨:**

* &amp;lbrack;Layers&amp;rbrack; Image to Material(AI 기반)의 메모리가 부족할 때 앱 오류 메시지가 표시됨

**고정:**

* &amp;lbrack;Layers&amp;rbrack; Image to Material(AI 기반)이 Specular/광택 워크플로우에서 작동하지 않음
* &amp;lbrack;Layers&amp;rbrack;에서 Image to Material(AI 기반)을 사용하는 동안 비디오 메모리가 부족하면 충돌합니다.
* 스택을 열 때 &amp;lbrack;Layers&amp;rbrack; 디스크 캐시가 표시에 사용되지 않음
* &amp;lbrack;Layers&amp;rbrack; Nvidia RTX 8000 감지
* &amp;lbrack;Layers&amp;rbrack; 스플래터 입력 외부로 레이어를 이동할 수 없는 경우가 있습니다
* 스택에 스택을 삽입할 때 &amp;lbrack;Layers&amp;rbrack; 디스크 캐시가 사용되지 않음
* &amp;lbrack;Layers&amp;rbrack; 일부 채널 사용은 사용되지 않지만 계산됩니다.
* 이미지를 가져올 때 때때로 &amp;lbrack;Layers&amp;rbrack; 빈 출력이 생성됩니다
* &amp;lbrack;2D 보기&amp;rbrack; 그리기 모드 활성 블록 팬 및 확대/축소를 사용하여 다른 레이어로 전환
* &amp;lbrack;Content&amp;rbrack; Snow - 일반 맵의 8비트 문제
* &amp;lbrack;Content&amp;rbrack; 포장 패턴 - 일반 맵에서 8비트 문제
* &amp;lbrack;Content&amp;rbrack; 이퀄라이저 - 일반 맵에서 8비트 문제
* &amp;lbrack;Content&amp;rbrack; 자갈 생성기 - 일반 맵에서 8비트 문제
* &amp;lbrack;Content&amp;rbrack; 바닥 타일 - 불투명도 및 Specular level 처리
* &amp;lbrack;내용&amp;rbrack; 블렌더 사이클에서 내보내기 사전 설정 종료 - 표준 맵 반전
* &amp;lbrack;Content&amp;rbrack; Image to Material(AI 작동)로 거대한 이미지의 문제를 수정하십시오.
* &amp;lbrack;Application&amp;rbrack; 데이터베이스 오류에서 &quot;백업 및 다시 시작&quot;을 선택할 때 충돌 발생
* &amp;lbrack;Application&amp;rbrack; 동일한 자산을 빠르게 클릭하면 충돌이 발생합니다.
* &amp;lbrack;Application&amp;rbrack; 종료 시 드문 충돌 발생
* 시작 화면에 파일을 놓을 때 &amp;lbrack;Application&amp;rbrack;이 충돌합니다.
* &amp;lbrack;응용 프로그램&amp;rbrack; 손상된 환경 파일이 로드되면 충돌이 발생합니다.
* &amp;lbrack;Application&amp;rbrack; 렌더링된 에셋을 빠르게 전환할 때 드물게 충돌이 발생합니다.
* &amp;lbrack;Application&amp;rbrack; 에셋을 계산하는 동안 종료할 때 멈춤
* &amp;lbrack;Application&amp;rbrack; macos에서 시작할 때 드문 충돌 발생
* 시작 후 바로 애플리케이션을 닫을 때 &amp;lbrack;Application&amp;rbrack; 교착 상태
* &amp;lbrack;렌더링&amp;rbrack; 3D 보기가 가끔 깜박임
* &amp;lbrack;UI&amp;rbrack; 색상 피커 및 임의 시드 위젯이 나머지 이동에 정렬되지 않음
* &amp;lbrack;렌더링&amp;rbrack; 잘못된 계산 시간이 표시됨
* &amp;lbrack;내보내기&amp;rbrack; 일부 내보내기 사전 설정이 누락되는 경우가 있습니다

**알려진 문제:**

* 고해상도 이미지에서 [이미지를 재료로](AI 기반)를 사용하는 속도가 느려질 수 있습니다
* 구형 NVIDIA 드라이버에서 Delighter 충돌(400.x 미만)
* 내용 인식 채우기 필터의 고해상도는 느립니다
* 슬라이더에서 특정 값을 입력할 때 혼수 또는 점을 무시할 수 있습니다
* 동일한 재질 레이어 스택의 2배 저장이 불가능

### 2.2.0 (2020.2.0) 우동

*(릴리스: 2020년 6월 15일)*

**추가됨:**

* &amp;lbrack;Create&amp;rbrack; Windows 및 Linux에서 사용할 수 있는 새 이미지-재질(AI 기반) 필터
* &amp;lbrack;Create&amp;rbrack; 비트맵을 자료로 이름을 바꿉니다(B2M).
* &amp;lbrack;이미지 가져오기&amp;rbrack; 새 재질 생성 템플릿 팝업
* &amp;lbrack;이미지 가져오기&amp;rbrack; 새로운 &quot;기본 재질 추가&quot; 옵션
* &amp;lbrack;이미지 가져오기&amp;rbrack; 재료 생성 템플릿에 추가 이미지를 드래그하여 놓을 수 있습니다.
* &amp;lbrack;이미지 가져오기&amp;rbrack; 재료 생성 템플릿에서 이미지를 제거할 수 있음
* &amp;lbrack;이미지 가져오기&amp;rbrack; 파일 이름에 따라 자동으로 가져온 비트맵에 채널 할당
* &amp;lbrack;이미지 가져오기&amp;rbrack; 표준 맵을 반전할 수 있음
* &amp;lbrack;2D 보기&amp;rbrack; 페인팅 모드 소개
* &amp;lbrack;2D View&amp;rbrack; 페인팅 타일
* &amp;lbrack;2D 보기&amp;rbrack; 브러시 색상의 회색조 값 설정
* &amp;lbrack;2D 보기&amp;rbrack; 페인팅 중 팬 및 확대/축소
* 브러시 회색 음영 값을 반전하는 &amp;lbrack;2D 보기&amp;rbrack; X 단축키
* 브러시 크기를 변경하기 위한 &amp;lbrack;2D 보기&amp;rbrack; &amp;lbrack; 및 &amp;rbrack; 단축키
* &amp;lbrack;2D 보기&amp;rbrack; Ctrl(또는 Cmd) + 마우스 휠 브러시 크기 변경
* &amp;lbrack;2D View&amp;rbrack; 이제 복제 패치를 사용할 때 소스 위치를 수정할 수 있습니다.
* &amp;lbrack;레이어&amp;rbrack; Shift+드래그하여 자동 산란 아틀라스에 놓기
* &amp;lbrack;Layers&amp;rbrack; Alt + 드래그 앤 드롭 기능이 데칼로 재질을 삽입합니다.
* &amp;lbrack;레이어&amp;rbrack; Substance Designer에서 쉽게 매트릭스 변환 노출
* &amp;lbrack;Layers&amp;rbrack; 비어 있지 않은 스택에서 텍스처를 삭제하면 올바른 채널에 자동으로 할당됩니다
* &amp;lbrack;Layers&amp;rbrack; 새로운 유형의 레이어: 복합 필터
* &amp;lbrack;매개 변수&amp;rbrack; Substance 문자열 입력 지원
* &amp;lbrack;UI&amp;rbrack; 팝업 및 메뉴에 대한 그림자 추가
* 마우스 오른쪽 버튼 클릭 옵션(지우기, 복사, 붙여넣기)이 있는 &amp;lbrack;UI&amp;rbrack; 새 색상 위젯
* 페인팅 도구 옵션이 있는 &amp;lbrack;UI&amp;rbrack; 새 이미지 위젯
* &amp;lbrack;UI&amp;rbrack; 이미지 위젯에서 가져온 이미지 위에 페인팅할 수 있음
* &amp;lbrack;렌더링&amp;rbrack; 새 기본 카메라 위치
* &amp;lbrack;Export&amp;rbrack; Substance 파일을 Substance Designer 2020.1.2(10.1.2)용으로 내보냅니다.
* &amp;lbrack;성능&amp;rbrack; 응용 프로그램 시작 시간 향상
* &amp;lbrack;성능&amp;rbrack; 비동기 작업 처리 개선
* &amp;lbrack;성능&amp;rbrack; 레이어 추가, 제거 또는 이동 시 레이어 스택 성능 향상
* &amp;lbrack;성능&amp;rbrack; Image to Material(AI 지원)이 RTX GPU에서 더 빠르게 실행됩니다
* &amp;lbrack;Content&amp;rbrack; 새로운 메시: 여성 티셔츠, 남성 티셔츠, 신발
* &amp;lbrack;내용&amp;rbrack; 새로운 혼합 모드 - 채널별 혼합
* &amp;lbrack;Content&amp;rbrack; 불투명도는 두 개의 새로운 매개 변수(Height 위치 및 Height 비율)로 Height 교정을 혼합합니다.
* &amp;lbrack;Content&amp;rbrack; Height 혼합 모드에서 Height 조정 추가
* &amp;lbrack;내용&amp;rbrack; 사용자 정의 마스크 혼합에서 Height 정보 사용 옵션
* &amp;lbrack;내용&amp;rbrack; 새로운 원근 교정 도구
* &amp;lbrack;Content&amp;rbrack; 패턴 생성기 - 패턴을 반전하는 매개 변수를 추가합니다.
* &amp;lbrack;Content&amp;rbrack; 패턴 생성기 - 새 매개변수 추가 재료 세부 정보 무시
* &amp;lbrack;Content&amp;rbrack; 새로운 데칼 필터
* &amp;lbrack;내용&amp;rbrack; 새 이끼 필터
* &amp;lbrack;내용&amp;rbrack; 새 균열 필터
* &amp;lbrack;내용&amp;rbrack; 새 PBR 유효성 검사 필터
* &amp;lbrack;Content&amp;rbrack; 새로운 바닥 타일 필터
* &amp;lbrack;내용&amp;rbrack; 새 퀼트 스티치 필터
* &amp;lbrack;Content&amp;rbrack; Atlas Scatter - 페인팅 옵션을 활성화하려면 사용자 정의 마스크 입력 추가
* &amp;lbrack;Content&amp;rbrack; Dirt - 페인팅 옵션을 활성화하려면 사용자 정의 마스크 입력 추가
* &amp;lbrack;Content&amp;rbrack; CLO 내보내기 사전 설정
* &amp;lbrack;Content&amp;rbrack; VStitcher 내보내기 사전 설정
* &amp;lbrack;Content&amp;rbrack; Unity HDRP 사전 설정 디테일 맵 내보내기

**고정:**

* &amp;lbrack;Layers&amp;rbrack; 가져온 이미지가 너무 많이 로드됩니다.
* &amp;lbrack;Layers&amp;rbrack; 스택 맨 아래에 복제 패치를 생성할 때 충돌합니다.
* &amp;lbrack;Layers&amp;rbrack; 스택 아래쪽에 재질을 추가하면 불안정해집니다
* 이미지 가져오기 후 필터링이 제대로 작동하지 않는 &amp;lbrack;Layers&amp;rbrack;
* 사용자 정의 필터를 사용하여 프로젝트 간에 워크플로우를 전환할 때 &amp;lbrack;Layers&amp;rbrack; workflow_type 값이 업데이트되지 않음
* &amp;lbrack;Layers&amp;rbrack; 선택된 레이어가 없을 때 &quot;레이어 제거&quot; 버튼 비활성화
* 복제 패치가 포함된 에셋을 로드할 때 &amp;lbrack;Layers&amp;rbrack;가 충돌함
* &amp;lbrack;Layers&amp;rbrack; Normal to Height 필터가 MacOS에서 충돌함
* &amp;lbrack;Application&amp;rbrack; 환경 맵을 앞뒤로 로드할 때 충돌 발생
* 일부 그래픽 태블릿 드라이버 설치 시 &amp;lbrack;Application&amp;rbrack; 성능 문제 발생
* &amp;lbrack;Application&amp;rbrack; EXR 32비트 파일 가져오기가 검정색임
* 에셋을 로드 및 언로드할 때 &amp;lbrack;Application&amp;rbrack;이 충돌합니다.
* &amp;lbrack;응용 프로그램&amp;rbrack; 탐색에서 작성으로 전환할 때 충돌이 발생합니다.
* 재질 저장 시 &amp;lbrack;Application&amp;rbrack; 대상 컬렉션이 현재 프로젝트에서 가져온 것이 아님
* &amp;lbrack;응용 프로그램&amp;rbrack; 백업 수정 및 다시 시작
* &amp;lbrack;이미지 가져오기&amp;rbrack; 회색 음영 이미지를 올바르게 가져오기
* &amp;lbrack;Content&amp;rbrack; 새로운 매트릭스 처리를 위한 새로운 필터
* &amp;lbrack;Content&amp;rbrack; 가져온 사용자 정의 필터는 빠른 액세스 막대에 표시됩니다
* &amp;lbrack;Content&amp;rbrack; 타일 만들기 고급 필터로 색상 이동 수정
* &amp;lbrack;성능&amp;rbrack; 색상 대화 상자를 여는 속도가 느려 현재 레이어를 다시 계산합니다
* &amp;lbrack;UI&amp;rbrack; 키보드 단축키가 작동하지 않는 경우가 있습니다.
* &amp;lbrack;2D 보기&amp;rbrack; 내용 인식 채우기를 사용하려면 처음 한 번 클릭을 사용할 필요가 없습니다.
* 로컬 디스크의 &amp;lbrack;Resources&amp;rbrack; 폴더는 제거 후에도 계속 업데이트됩니다
* &amp;lbrack;Resources&amp;rbrack; 파일 시스템에서 연결된 폴더를 삭제해도 삭제되지 않음
* &amp;lbrack;Export&amp;rbrack; 사용자 정의 내보내기 사전 설정의 사용자 정의 사용은 내보내지지 않습니다
* &amp;lbrack;내보내기&amp;rbrack; 경로에 특수 문자가 있는 .sbsar 파일 내보내기가 실패합니다

**알려진 문제:**

* 이미지를 재료로 반복 재계산(AI 작동)하면 충돌(메모리 부족)이 발생할 수 있습니다
* Delighter를 반복적으로 재계산하면 충돌(메모리 부족)이 발생할 수 있습니다.
* 고해상도 이미지에서 [이미지를 재료로](AI 기반)를 사용하는 속도가 느려질 수 있습니다
* VRAM이 낮은 GPU에서 Image to Material(AI 기반)을 사용하면 충돌(메모리 부족)이 트리거될 수 있습니다
* Image to Material(AI 작동)은 PBR Specular/광택에서 사용할 수 없음
* 구형 NVIDIA 드라이버에서 Delighter 충돌(400.x 미만)
* 내용 인식 채우기 필터의 고해상도는 느립니다
* 슬라이더에서 특정 값을 입력할 때 혼수 또는 점을 무시할 수 있습니다
* 동일한 재질 레이어 스택의 2배 저장이 불가능

### 2.1.1 (2020.1.1) 티라미수

*(릴리스: 2020년 4월 1일)*

**추가됨:**

* &amp;lbrack;프로젝트&amp;rbrack; 메타데이터 내보내기 및 가져오기
* &amp;lbrack;Application&amp;rbrack; Ctrl+S가 이제 탐색에 사전 설정을 저장합니다.
* &amp;lbrack;성능&amp;rbrack; 최대 2k 해상도에 대해 저장된 재질을 다시 계산하는 대신 렌더링 캐시를 사용합니다

**고정:**

* &amp;lbrack;UI&amp;rbrack; 뷰포트의 고정 컴퓨팅 표시기
* &amp;lbrack;UI&amp;rbrack; 슬라이더에 음수 값 입력이 수정되었습니다.
* &amp;lbrack;UI&amp;rbrack; 콤보 상자: 키보드 화살표 및 스크롤 막대가 이제 작동함
* &amp;lbrack;UI&amp;rbrack; 2D 보기에서 &quot;재질 출력&quot; 및 &quot;레이어 입력&quot; 간에 전환할 때 선택한 채널을 유지합니다
* &amp;lbrack;Layers&amp;rbrack; 기본 재질에서 사용자 정의 채널을 추가할 때 발생하는 충돌 수정
* &amp;lbrack;Layers&amp;rbrack; 레이어 조작 시 충돌
* &amp;lbrack;Layers&amp;rbrack; 사용자 정의 채널은 저장된 재질과 함께 표시되지 않습니다
* &amp;lbrack;Application&amp;rbrack; 에셋을 가져올 때 발생하는 드문 충돌 수정
* &amp;lbrack;응용 프로그램(&amp;r); 종료 시 충돌
* 이제 사전 설정을 전환할 때 &amp;lbrack;Application&amp;rbrack; 콤보 상자에 올바른 값이 표시됩니다.
* &amp;lbrack;Export&amp;rbrack; 이름이 Enscape 사전 설정으로 Enscape Revit로 변경됨
* &amp;lbrack;내보내기&amp;rbrack; 내보내기 사전 설정을 제거한 후 가져오기가 작동합니다.
* &amp;lbrack;내보내기&amp;rbrack; 내보내기 시 충돌
* &amp;lbrack;Rendering&amp;rbrack; 기본 색상이 16비트 반부동 형식일 때 렌더링을 고정합니다.
* &amp;lbrack;프로젝트&amp;rbrack; 손상된 패키지를 가져올 때 충돌하지 않음
* &amp;lbrack;Project&amp;rbrack; Create를 연 적이 없는 경우 2019.1.4에서 2.x.x로 마이그레이션 처리
* &amp;lbrack;프로젝트&amp;rbrack; 동일한 프로젝트를 두 번 가져올 때 발생하는 충돌 수정
* &amp;lbrack;프로젝트&amp;rbrack; 프로젝트를 가져올 때 충돌 수정
* &amp;lbrack;Resources&amp;rbrack; 이전 버전에서 가져온 사용자 정의 필터 작동
* 같은 이름의 &amp;lbrack;Resources&amp;rbrack; Materials가 더 이상 서로 지워지지 않음
* &amp;lbrack;Resources&amp;rbrack; 로컬 폴더 연결 시 충돌
* &amp;lbrack;Resources&amp;rbrack; Starter Materials 사용자가 만든 폴더는 다시 시작한 후 더 이상 제거되지 않습니다
* &amp;lbrack;Inspire&amp;rbrack; 재료/수집 드롭 영역을 수정하고 저장되지 않은 재료를 사용하는 경우 경고 메시지를 추가합니다

**알려진 문제:**

* 내용 인식 채우기 필터의 고해상도는 느립니다
* 하나의 재질에 여러 개의 흐림 효과를 사용하는 것은 권장되지 않습니다
* 구형 NVIDIA 드라이버에서 Delighter 충돌(400.x 미만)
* 슬라이더에서 특정 값을 입력할 때 혼수 또는 점을 무시할 수 있습니다

### 2.1.0 (2020.1.0) 티라미수

*(릴리스: 2020년 3월 12일)*

**추가됨:**

* &amp;lbrack;Export&amp;rbrack; 사전 설정 선택 내보내기를 통해 렌더러 및 게임 엔진을 위한 텍스처를 압축합니다
* &amp;lbrack;내보내기&amp;rbrack; 사전 설정을 Unreal Engine 4로 내보내기
* &amp;lbrack;Export&amp;rbrack; 사전 설정을 Unity 표준으로 내보내기
* &amp;lbrack;내보내기&amp;rbrack; 사전 설정을 Unity HDRP로 내보내기
* &amp;lbrack;내보내기&amp;rbrack; 사전 설정을 블렌더 주기/이벤트로 내보내기
* &amp;lbrack;내보내기&amp;rbrack; 사전 설정을 Arnold 5로 내보내기
* &amp;lbrack;내보내기&amp;rbrack; 사전 설정을 Corona 렌더러로 내보내기
* &amp;lbrack;내보내기&amp;rbrack; 사전 설정을 Enscape로 내보내기
* &amp;lbrack;내보내기&amp;rbrack; 사전 설정을 Keyshot 9로 내보내기
* &amp;lbrack;내보내기&amp;rbrack; 사전 설정을 Redshift로 내보내기
* &amp;lbrack;내보내기&amp;rbrack; 사전 설정을 Vray Next로 내보내기
* &amp;lbrack;내보내기&amp;rbrack; 사전 설정을 Lens Studio로 내보내기
* &amp;lbrack;내보내기&amp;rbrack; 사전 설정을 Spark AR Studio로 내보내기
* &amp;lbrack;Export&amp;rbrack; 사전 설정을 PBR 금속 거칠기에서 PBR Specular 광택으로 내보내기
* &amp;lbrack;내보내기&amp;rbrack; 새 내보내기 UI
* &amp;lbrack;내보내기&amp;rbrack; 내보내기 설정 기억
* &amp;lbrack;내보내기&amp;rbrack; 사용자 정의 내보내기 사전 설정 가져오기 및 관리
* &amp;lbrack;내보내기&amp;rbrack; 사용자 정의 내보내기 사전 설정을 삭제하고 바꿉니다
* &amp;lbrack;내보내기&amp;rbrack; 사용자 정의 내보내기 사전 설정 이름 바꾸기
* &amp;lbrack;내보내기&amp;rbrack; 기본 내보내기 해상도를 현재 해상도로 설정합니다.
* &amp;lbrack;Export&amp;rbrack; 내보내기 위치에 하위 폴더를 만들 선택 사항을 추가합니다
* 기존 파일을 바꾸기 전에 &amp;lbrack;Export&amp;rbrack; 경고 메시지
* &amp;lbrack;Application&amp;rbrack; 새 버전 번호 매기기 체계
* &amp;lbrack;Application&amp;rbrack; 실행 시 작성 열기 및 랩 순서 변경
* &amp;lbrack;시작 화면&amp;rbrack; 새 시작 배너
* &amp;lbrack;프로젝트&amp;rbrack; 실행 시 마지막 프로젝트 열기
* &amp;lbrack;UI&amp;rbrack; 새 콤보 상자 스타일
* &amp;lbrack;2D view&amp;rbrack; 2d 뷰에 포커스를 맞추는 단축키
* &amp;lbrack;Filters&amp;rbrack; Substance 그래프의 alchemist::parameterVisibility 태그에 대한 지원이 추가되었습니다.
* &amp;lbrack;Filters&amp;rbrack;에는 워크플로우에 따라 매개 변수 가시성을 관리하기 위한 전역 조정이 있습니다.
* &amp;lbrack;Resources&amp;rbrack; 구성 파일로 리소스 및 링크된 폴더를 설정하는 새로운 명령줄 옵션
* &amp;lbrack;버전 검사기&amp;rbrack; 버전 검사 구성
* &amp;lbrack;Content&amp;rbrack; 새로운 스타터 재질
* &amp;lbrack;Content&amp;rbrack; Bitmap to Material - 금속 채널을 정의할 가능성을 추가합니다(균일, 사용자 정의 이미지 가져오기, 색상 선택)
* &amp;lbrack;Content&amp;rbrack; 조정 - PBR Specular/광택 워크플로우 지원 추가
* &amp;lbrack;Content&amp;rbrack; Atlas Scatter - 새 매개 변수

**고정:**

* &amp;lbrack;프로젝트&amp;rbrack; 동일한 프로젝트를 두 번 가져올 때 충돌함
* &amp;lbrack;Project&amp;rbrack; 프로젝트를 여러 번 가져오고 열 때 충돌하는 문제 수정
* 명명되지 않은 재질을 로드할 때 &amp;lbrack;Application&amp;rbrack;이 충돌합니다.
* &amp;lbrack;Application&amp;rbrack; 파일을 다시 가져올 때 누락된 파일 인식
* &amp;lbrack;응용 프로그램 &amp;rbrack; 종료 시 임의 충돌 수정
* &amp;lbrack;Application&amp;rbrack; Create에서 재료를 언로드할 때 드물게 발생하는 충돌 수정
* &amp;lbrack;Application&amp;rbrack; UI 컨트롤 사용 시 임의 충돌 수정
* &amp;lbrack;Application&amp;rbrack; Windows 10에서 로그 파일을 데스크톱으로 내보내는 문제 수정
* 만들기에서 &amp;lbrack;UI&amp;rbrack; 내보내기 패널을 열 때 패널의 크기가 올바르지 않음
* &amp;lbrack;UI&amp;rbrack; 한 번의 클릭으로 프로젝트 열기
* &amp;lbrack;UI&amp;rbrack; 최소 및 최대 슬라이더 값을 올바르게 설정
* &amp;lbrack;UI&amp;rbrack; ID 대신 채널 사용 레이블 표시
* &amp;lbrack;UI&amp;rbrack; 재질을 클릭하면 항상 면변형 패널이 열리거나 닫힙니다
* &amp;lbrack;UI&amp;rbrack; 숨겨진 레이어 색상 수정
* &amp;lbrack;UI&amp;rbrack; 시작 화면 버튼 개선
* &amp;lbrack;Layers&amp;rbrack; 불필요한 비용 감소
* 복제 패치를 사용할 때 &amp;lbrack;Layers&amp;rbrack;가 충돌합니다.
* &amp;lbrack;Layers&amp;rbrack; 이미지 가져오기 레이어를 선택해도 더 이상 컴퓨트가 트리거되지 않습니다.
* &amp;lbrack;레이어&amp;rbrack; 복제 패치 및 내용 인식 채우기 레이어가 선택되었을 때 더 이상 다시 계산되지 않음
* &amp;lbrack;채널 설정&amp;rbrack; 이제 사용 활성화 또는 비활성화는 렌더링을 트리거합니다.
* &amp;lbrack;Resources&amp;rbrack; 라이브러리의 스택을 대량 클릭할 때 멈춤 방지
* 이전에 추가한 연결된 폴더를 다시 추가할 때 &amp;lbrack;Resources&amp;rbrack; Performance hit
* &amp;lbrack;Resources&amp;rbrack; 삭제된 .sbsar 파일을 열려고 할 때 발생하는 충돌 수정
* &amp;lbrack;Performance&amp;rbrack; 해당 매개변수에 액세스하기 위해 재료를 로드하지 않도록 합니다.
* &amp;lbrack;Performance&amp;rbrack; 프로젝트 또는 작성된 자료에서 사용되는 경우에만 에셋을 백업합니다.
* &amp;lbrack;Export&amp;rbrack; 내보내기 대기열의 고정 재질을 건너뛰거나 잘못된 매개 변수로 내보내는 경우가 있습니다.
* &amp;lbrack;2D 보기&amp;rbrack; 팬 및 확대/축소 복원됨
* &amp;lbrack;내용&amp;rbrack; 쪽매 패턴은 주변 오클루전 채널을 고려합니다.
* &amp;lbrack;Content&amp;rbrack; Paint - 사용자 정의 마스크를 활성화할 때 마스크 입력 표시
* &amp;lbrack;Content&amp;rbrack; Stonewall 패턴 - 표준 맵에서 가능한 밴딩 효과 제거
* &amp;lbrack;내용&amp;rbrack; Height 변조 - 2d 보기에서 이중 기본 색상 항목 수정

**알려진 문제:**

* 내용 인식 채우기 필터의 고해상도는 느립니다
* 하나의 재질에 여러 개의 흐림 효과를 사용하는 것은 권장되지 않습니다
* 구형 NVIDIA 드라이버에서 Delighter 충돌(400.x 미만)
* 슬라이더에서 특정 값을 입력할 때 혼수 또는 점을 무시할 수 있습니다

## 버전 1

### 1.1.4 (2019.1.4) 참깨

*(릴리스: 2020년 1월 30일)*

**추가됨:**

* &amp;lbrack;Resources&amp;rbrack; 리소스 폴더를 지울 때 확인 프롬프트

**고정:**

* &amp;lbrack;Layers&amp;rbrack; 아래 또는 위에 있는 둘 이상의 레이어로 레이어 이동
* &amp;lbrack;Create&amp;rbrack; 우수한 성능을 위한 충분한 VRAM 예산 할당

**알려진 문제:**

* 많은 리소스를 가져오면 Substance Alchemist 속도가 느려질 수 있습니다
* 내용 인식 채우기 필터의 고해상도는 느립니다
* 하나의 재질에 여러 개의 흐림 효과를 사용하는 것은 권장되지 않습니다
* 구형 NVIDIA 드라이버에서 Delighter 충돌(400.x 미만)
* 슬라이더에서 특정 값을 입력할 때 혼수 또는 점을 무시할 수 있습니다
* Height에 표준 필터가 MacOS에서 충돌할 수 있음

### 1.1.3 (2019.1.3) 참깨

*(릴리스: 2020년 1월 28일)*

**추가됨:**

* &amp;lbrack;워크플로&amp;rbrack; 다중 워크플로 지원
* &amp;lbrack;Workflow&amp;rbrack; PBR Specular 광택 워크플로우 지원
* &amp;lbrack;워크플로우&amp;rbrack; 새 채널 설정 패널
* 프로젝트 생성 시 &amp;lbrack;Workflow&amp;rbrack; Workflow 선택
* &amp;lbrack;채널 설정&amp;rbrack; 특정 채널 계산 활성화/비활성화
* &amp;lbrack;채널 설정&amp;rbrack; 현재 자료에서 사용할 수 있는 사용자 정의 채널 목록 표시
* &amp;lbrack;채널 설정&amp;rbrack; 필요한 경우 사용자 정의 채널 자동 계산
* &amp;lbrack;채널 설정&amp;rbrack; 사용자 정의 채널의 강제/블록 계산
* &amp;lbrack;Layers&amp;rbrack; Atlas Scatter 및 스플래터 필터에서 재료 입력 자리 표시자의 새로운 UI
* &amp;lbrack;Layers&amp;rbrack; 필터의 이미지 입력 매개 변수는 레이어 아래에 지정할 수 있습니다.
* &amp;lbrack;Layers&amp;rbrack; 일부 레이어가 최신 상태가 아닐 때 알림을 표시합니다.
* &amp;lbrack;Layers&amp;rbrack; 알림을 통해 오래된 레이어의 최신 버전으로 업데이트할 수 있습니다.
* 프로젝트 생성 시 &amp;lbrack;프로젝트&amp;rbrack; 새 메타데이터 필드
* &amp;lbrack;Inspire&amp;rbrack; 생성된 변형은 프로젝트에 따라 다릅니다.
* &amp;lbrack;2D View&amp;rbrack; 레이어 입력, 레이어 출력 및 재질 출력 간 전환
* &amp;lbrack;시작 화면&amp;rbrack; 가져오기 프로젝트(.alch) 추가 옵션
* &amp;lbrack;환경 설정&amp;rbrack; 캐시 위치 및 분석 개인정보 설정을 지정하는 새 환경 설정 창
* &amp;lbrack;UI&amp;rbrack; 새 UI 단추
* &amp;lbrack;성능&amp;rbrack; 병렬화 시스템의 전반적인 개선
* &amp;lbrack;성능&amp;rbrack; 재료 계산 수 최적화
* &amp;lbrack;엔진&amp;rbrack; Substance 엔진 업데이트
* &amp;lbrack;프레임워크&amp;rbrack; Qt 5.13으로 업그레이드
* &amp;lbrack;MacOS&amp;rbrack; macOS Catalina 지원의 글로벌 개선 사항
* &amp;lbrack;내용&amp;rbrack; 조정 필터 - 표준 강도 및 반전 매개 변수

**고정:**

* 레이어를 삭제할 때 &amp;lbrack;Layers&amp;rbrack; 이미지 입력 매개 변수 설정 해제
* &amp;lbrack;Layers&amp;rbrack; 복제 패치 레이어를 추가할 때 충돌 수정
* &amp;lbrack;Layers&amp;rbrack; 다른 레이어 스택 재질에 레이어 스택 재질을 혼합할 때 일부 충돌 수정
* 이제 내보낼 &amp;lbrack;내보내기&amp;rbrack; 채널 선택이 준수됩니다.
* &amp;lbrack;Resources&amp;rbrack; 리소스 패널에서 탐색할 때 충돌하지 않음
* &amp;lbrack;Resources&amp;rbrack; 손상된 Substance 파일을 가져올 때 충돌 수정
* &amp;lbrack;Resources&amp;rbrack; 큰 폴더를 로드할 때 충돌 수 줄이기
* &amp;lbrack;Thumbnail&amp;rbrack; Thumbnail 계산으로 인터페이스가 고정되지 않음
* &amp;lbrack;이미지 가져오기&amp;rbrack; 응용 프로그램 전체에서 지원되는 이미지 유형 균일화
* &amp;lbrack;Preset&amp;rbrack; SBSAR에서 사전 설정을 만들 때 설명을 저장
* &amp;lbrack;Inspire&amp;rbrack; 이미지 드래그 앤 드롭 수정
* &amp;lbrack; 응용 프로그램 &amp;rbrack; 종료 시 충돌 수정
* &amp;lbrack;Application&amp;rbrack; 자료를 내보낼 때 종료 시 충돌 수정
* &amp;lbrack;UI&amp;rbrack; 수정 및 개선 사항
* &amp;lbrack;UI&amp;rbrack; 임시 에셋 이름을 &quot;저장되지 않은 재질&quot;로 바꾸기
* &amp;lbrack;Content&amp;rbrack; 전체 업데이트 및 모든 필터 정리

**알려진 문제:**

* 많은 리소스를 가져오면 Substance Alchemist 속도가 느려질 수 있습니다
* 내용 인식 채우기 필터의 고해상도는 느립니다
* 하나의 재질에 여러 개의 흐림 효과를 사용하는 것은 권장되지 않습니다
* 구형 NVIDIA 드라이버에서 Delighter 충돌(400.x 미만)
* 슬라이더에서 특정 값을 입력할 때 혼수 또는 점을 무시할 수 있습니다
* Height에 표준 필터가 MacOS에서 충돌할 수 있음

### 1.1.2 (2019.1.2) 참깨

*(릴리스: 2019년 12월 11일)*

**추가됨:**

* &amp;lbrack;레이어&amp;rbrack; 저장 및 다른 이름으로 저장 옵션은 레이어 스택 도구 모음의 인터페이스를 통해 액세스할 수 있습니다.
* &amp;lbrack;Resources&amp;rbrack; [리소스] 패널에서 더 명확한 탐색 경로를 통해 폴더 탐색
* &amp;lbrack;Resources&amp;rbrack; 모든 상위 폴더에 액세스하려면 뒤로 유지 버튼을 누릅니다.
* &amp;lbrack;Resources&amp;rbrack; 가져온 재질 다시 로드 추가 옵션을 사용하여 최신 버전으로 업데이트합니다
* &amp;lbrack;Layers&amp;rbrack; 이미지 가져오기 레이어에서 이미지를 변경할 가능성
* &amp;lbrack;Layers&amp;rbrack; 이미지를 채널로 정의할 수 있는 가능성(기본 색상, 표준, Height 등) 이미지 가져오기 레이어에서
* &amp;lbrack;Content&amp;rbrack; Substance Source에서 새 atlas 요소 산란을 위한 새 Atlas Scatter 필터
* &amp;lbrack;내용&amp;rbrack; 새로운 유화 효과 필터
* &amp;lbrack;Content&amp;rbrack; 기본 색상 및 표준 맵에서 Height, 주변 오클루전 및 거칠기를 생성하는 새로운 채널 생성 필터

**고정:**

* &amp;lbrack;UI&amp;rbrack; 레이어 스택 도구 모음에서 도구 설명 다시 활성화
* &amp;lbrack;UI&amp;rbrack; 슬라이더 값에 2개의 소수점을 입력할 때 발생하는 문제 수정
* &amp;lbrack;성능&amp;rbrack; 재료 간 빠르게 전환 시 충돌 수정
* &amp;lbrack;내보내기&amp;rbrack; 내보내기 종료 전에 다른 재질로 전환해도 더 이상 충돌이 발생하지 않습니다
* &amp;lbrack;Resources&amp;rbrack; 컨텍스트 메뉴는 재료를 마우스 오른쪽 버튼으로 클릭하면 재료 위에 표시됩니다.
* &amp;lbrack;Layers&amp;rbrack; 레이어 스택이 비어 있을 때 &#39;여기를 클릭&#39; 링크가 작동합니다.
* Alchemist에서 만든 재질인 경우 조정 패널에서 저장 버튼을 제거합니다(&amp;lbrack; 사전 설정&amp;rbrack;)
* &amp;lbrack;Tweak&amp;rbrack; Alchemist에서 생성된 자료일 때 표시되는 정보 메시지
* &amp;lbrack;뷰 포트(&amp;r); Specular level 텍스처의 기본값이 0.04로 수정됨
* &amp;lbrack;파일 메뉴&amp;rbrack; 수정 후 저장 및 다른 이름으로 저장 옵션 이름 변경
* &amp;lbrack;Engine&amp;rbrack; 가져오기 중 일부 SBSAR 파일의 충돌을 방지하기 위해 Substance 엔진 버전을 업데이트합니다.
* &amp;lbrack;Content&amp;rbrack; 타일링 필터가 주변 오클루전 채널에서 작업 중입니다
* &amp;lbrack;Content&amp;rbrack; 자르기 필터가 주변 오클루전 채널에서 작동함
* &amp;lbrack;Content&amp;rbrack; 물 필터가 Height 맵의 이득을 수정합니다.
* &amp;lbrack;Content&amp;rbrack; 불투명도 혼합 모드에서 위쪽 재질의 타일링 수정
* 불투명도 혼합 모드에서는 상단 재질의 &amp;lbrack;Content&amp;rbrack; Height이 유지됩니다
* &amp;lbrack;Content&amp;rbrack; 천공 필터에서 사용자 정의 마스크, 사용자 정의 패턴 또는 비율 맵을 추가할 수 있음
* &amp;lbrack;Content&amp;rbrack; Height 변조 필터는 Height 및 표준 맵을 16비트로 강제 적용합니다.
* &amp;lbrack;Content&amp;rbrack; 조정 필터는 Height 및 표준 맵을 16비트로 강제 적용합니다.

**알려진 문제:**

* 많은 리소스를 가져오면 Substance Alchemist 속도가 느려질 수 있습니다
* 내용 인식 채우기 필터의 고해상도는 느립니다
* 하나의 재질에 여러 개의 흐림 효과를 사용하는 것은 권장되지 않습니다
* 구형 NVIDIA 드라이버에서 Delighter 충돌(400.x 미만)
* 슬라이더에서 특정 값을 입력할 때 혼수 또는 점을 무시할 수 있습니다
* Height에 표준 필터가 MacOS에서 충돌할 수 있음

### 1.1.1 (2019.1.1) 참깨

*(릴리스: 2019년 11월 26일)*

**추가됨:**

* &amp;lbrack;Blend&amp;rbrack; 새로운 불투명도 혼합 모드
* &amp;lbrack;엔진&amp;rbrack; 새 Substance 엔진 버전

**고정:**

* &amp;lbrack;Layers&amp;rbrack; 아직 계산 중인 레이어를 삭제하는 동안 충돌 수정
* &amp;lbrack;Layers&amp;rbrack; 맨 아래 레이어를 제거하는 동안 충돌 수정
* &amp;lbrack;Layers&amp;rbrack; 재료 이름에 특수 문자가 포함된 경우 충돌 수정
* &amp;lbrack;Layers&amp;rbrack; 위젯을 사용하는 모든 필터의 계산 중지
* &amp;lbrack;레이어&amp;rbrack; 복제 패치 및 내용 인식 채우기 필터를 사용하는 동안 충돌 방지
* &amp;lbrack;Layers&amp;rbrack; 튄 입력 슬롯에 필터를 드래그하여 드롭하는 동안 충돌 수정
* &amp;lbrack;Resources&amp;rbrack; 로컬 폴더를 연결하거나 Substance Alchemist에서 리소스를 가져오는 동안 충돌 수정
* &amp;lbrack;Collection&amp;rbrack; 재료 간 빠르게 전환하는 동안 충돌 수정
* &amp;lbrack;UI&amp;rbrack; 값이 null이거나 뷰포트의 타일링, 변위 슬라이더에서 유효하지 않은 동안 충돌 수정
* &amp;lbrack;Inspire&amp;rbrack; Inspire 탭에 액세스하는 동안 발생하는 충돌 수정
* &amp;lbrack;Inspire&amp;rbrack; 방금 저장된 레이어 스택 재질에 영감을 주는 동안 충돌 수정
* &amp;lbrack;성능&amp;rbrack; 대용량 Substance 재질 및 필터(타일링) 계산 속도 향상
* &amp;lbrack;도움말&amp;rbrack; 내보내기 로그 파일 수정
* &amp;lbrack;내용&amp;rbrack; 임의화 필터는 모든 채널에서 작동합니다.
* &amp;lbrack;Content&amp;rbrack; 다중 각도 워크플로는 모든 스캔을 고려합니다.
* &amp;lbrack;Content&amp;rbrack; AO 혼합 교정 혼합
* &amp;lbrack;내용&amp;rbrack; 곡률 혼합 교정 혼합
* &amp;lbrack;내용&amp;rbrack; 색상 ID 혼합 교정 혼합
* &amp;lbrack;내용&amp;rbrack; 사용자 정의 마스크 혼합 교정 혼합
* &amp;lbrack;Content&amp;rbrack; 거칠기 수정을 위한 조정 필터 수정
* &amp;lbrack;Content&amp;rbrack; 사용자 정의 일반 기본 재질 업로드를 위한 수정 채널 필터
* &amp;lbrack;Content&amp;rbrack; 엠보싱 필터의 사용자 정의 가져오기 패턴 수정

**알려진 문제:**

* 하나의 재질에 여러 개의 흐림 효과를 사용하는 것은 권장되지 않습니다
* 구형 NVIDIA 드라이버에서 Delighter 충돌(400.x 미만)
* 슬라이더에서 특정 값을 입력할 때 혼수 또는 점을 무시할 수 있습니다
* Height에 표준 필터가 MacOS에서 충돌할 수 있음

### 1.1.0 (2019.1.0) 참깨

*(릴리스: 2019년 11월 4일)*

**추가됨:**

* &amp;lbrack;프로젝트&amp;rbrack; 프로젝트 생성
* &amp;lbrack;프로젝트&amp;rbrack; 프로젝트 데이터가 포함된 .alch 파일 형식 소개
* &amp;lbrack;프로젝트&amp;rbrack; 컬렉션 및 해당 자료가 포함된 .alch 프로젝트를 내보냅니다
* &amp;lbrack;프로젝트&amp;rbrack; .alch 프로젝트 가져오기
* &amp;lbrack;프로젝트&amp;rbrack; 최근 프로젝트 열기
* &amp;lbrack;시작 화면&amp;rbrack; 시작 화면이 시작 시 표시됩니다.
* &amp;lbrack;시작 화면&amp;rbrack; 시작 화면에서 프로젝트 만들기
* &amp;lbrack;시작 화면&amp;rbrack; 시작 화면의 모든 프로젝트 목록에 액세스
* &amp;lbrack;시작 화면&amp;rbrack; 설명서, 정보 팝업 및 라이센스 관리에 액세스하는 빠른 링크
* &amp;lbrack;파일 메뉴&amp;rbrack; 파일 메뉴 통합
* &amp;lbrack;파일 메뉴&amp;rbrack; 파일 탭의 프로젝트 명령과 레이어 스택의 저장에 액세스
* &amp;lbrack;파일 메뉴&amp;rbrack; 편집 탭에서 실행 취소 및 재실행 명령에 액세스합니다.
* &amp;lbrack;파일 메뉴&amp;rbrack; 이전 도움말 메뉴가 도움말 탭 아래의 파일 메뉴에서 이동되었습니다.
* &amp;lbrack;Layers&amp;rbrack; 레이어 스택의 새로운 아키텍처
* &amp;lbrack;Layers&amp;rbrack; 레이어 스택의 새로운 UI
* &amp;lbrack;레이어&amp;rbrack; 도구 모음에서 직접 혼합 모드를 선택합니다
* &amp;lbrack;Layers&amp;rbrack; 블렌드 매개변수와 재료 매개변수에 개별적으로 액세스
* &amp;lbrack;Layers&amp;rbrack; 레이어 스택에 있는 스플래터 필터의 전용 입력에 재질을 직접 추가합니다
* &amp;lbrack;Layers&amp;rbrack; 이미지 가져오기 레이어에서 직접 스캔 순서 변경
* &amp;lbrack;뷰 포트(&amp;r); 카메라 시야의 제어
* &amp;lbrack;Viewport&amp;rbrack; 정사영 또는 원근 카메라 간 전환 가능
* &amp;lbrack;뷰포트(&amp;rBrack; 각 채널의 비트 심도 및 해상도 표시
* &amp;lbrack;Resources&amp;rbrack; 기본 재질이 기본값마다 열립니다.
* &amp;lbrack;Cache&amp;rbrack; 썸네일 캐시 폴더를 찾습니다.
* &amp;lbrack;Cache&amp;rbrack; 렌더링 캐시 폴더를 찾습니다.
* &amp;lbrack;Panels&amp;rbrack; 재료 설정 패널이 일시적으로 숨겨집니다.
* &amp;lbrack;워크플로&amp;rbrack; Specular/광택 일시 비활성화
* &amp;lbrack;MacOS&amp;rbrack; Catalina OS 버전 공증
* &amp;lbrack;Content&amp;rbrack; Delighter 필터의 새 버전
* &amp;lbrack;내용&amp;rbrack; 새 이미지 내용 인식 채우기 필터
* &amp;lbrack;Content&amp;rbrack; 새로운 질감 내용 인식 채우기 필터
* &amp;lbrack;Content&amp;rbrack; 변형 필터에는 안전한 변형 옵션이 있습니다.

**고정:**

* 새로운 UI 및 아키텍처 릴리스에서는 생성과 관련된 이전의 모든 버그가 현재 유효하지 않습니다.
* 툴팁이 상단 표시줄의 아이콘을 숨기지 않음 (3D, 2D, 2D/3D)
* &amp;lbrack;Content&amp;rbrack; 스플래터 필터는 전체 Height 맵이 있는 Atlas를 수락합니다.
* &amp;lbrack;Content&amp;rbrack; 변환 필터는 이미지(scan1, scan2,...)에서 작동합니다.

**알려진 문제:**

* 하나의 재질에 여러 개의 흐림 효과를 사용하는 것은 권장되지 않습니다
* 구형 NVIDIA 드라이버에서 Delighter 충돌(400.x 미만)
* 슬라이더에서 특정 값을 입력할 때 혼수 또는 점을 무시할 수 있습니다
* Height에 표준 필터가 MacOS에서 충돌할 수 있음

## 베타

### 0.8.1 베타 퀴노아

*(릴리스: 2019년 8월 19일)*

**추가됨:**

* 시작 관리자에서 프로젝트 Substance Alchemist으로 Substance Source 에셋을 보내는 기능

**고정:**

* &amp;lbrack;Create&amp;rbrack; 일부 필터는 빠른 접근자에는 나열되지만 필터 패널에는 나열되지 않았습니다
* &amp;lbrack;MacOS&amp;rbrack; 종료 시 일부 충돌 수정

**알려진 문제:**

* 하나의 재질에 여러 개의 흐림 효과를 사용하는 것은 권장되지 않습니다
* 구형 NVIDIA 드라이버에서 Delighter 충돌(400.x 미만)
* Delighter 단계의 빠른 가시성 전환은 권장하지 않습니다
* 이미지 가져오기 레이어의 [속성] 패널에 TIF 이미지가 표시되지 않습니다
* 슬라이더에서 특정 값을 입력할 때 혼수 또는 점을 무시할 수 있습니다
* Height에 표준 필터가 MacOS에서 충돌할 수 있음
* macOS에서 종료할 때도 임의로 충돌할 수 있음

### 0.8.0 베타 퀴노아

*(릴리스: 2019년 8월 8일)*

**추가됨:**

* &amp;lbrack;Resources&amp;rbrack; 로컬 디스크의 재질 폴더를 연결하고 미러링합니다.
* &amp;lbrack;Resources&amp;rbrack; 재질 폴더 및 하위 폴더를 찾아봅니다.
* &amp;lbrack;Resources&amp;rbrack; 전체 화면에서 리소스를 확인하려면 별도의 창에서 재질 리소스 패널을 분리합니다.
* &amp;lbrack;리소스&amp;rbrack; 폴더 및 하위 폴더 탐색을 지원하는 새 리소스 패널 레이아웃
* &amp;lbrack;Resources&amp;rbrack; Breadcrum을 사용하여 폴더 탐색
* &amp;lbrack;Resources&amp;rbrack; 마우스 오른쪽 단추를 통해 액세스할 수 있는 동기화 옵션으로 로컬 폴더를 강제 동기화합니다.
* &amp;lbrack;Resources&amp;rbrack; 마우스 오른쪽 단추를 통해 액세스할 수 있는 연결 해제 옵션으로 로컬 폴더의 연결을 끊습니다.
* &amp;lbrack;Manage&amp;rbrack; Substance 파일의 포함된 태그 표시
* &amp;lbrack;Manage&amp;rbrack; 재질에 대한 태그 추가, 편집 및 삭제
* &amp;lbrack;Manage&amp;rbrack; 재질 평가
* &amp;lbrack;Layers&amp;rbrack; 지원 파노라마 출력
* &amp;lbrack;Layers&amp;rbrack; 이미지 가져오기 레이어에서 이미지 입력을 삭제할 수 있습니다
* &amp;lbrack;Layers&amp;rbrack; 새로 추가된 레이어의 자동 선택
* &amp;lbrack;Layers&amp;rbrack; 레이어 삭제 후 아래 레이어의 자동 선택
* &amp;lbrack;UX&amp;rbrack; 다른 실습실로 전환할 때 왼쪽 패널의 가시성 유지
* &amp;lbrack;UX&amp;rbrack; 비어 있지 않은 레이어 스택에서 이미지를 가져올 때 기본 레이어를 만들거나 재질 워크플로우 팝업을 열지 마십시오
* &amp;lbrack;UI&amp;rbrack; 새 텍스트 필드 스타일
* &amp;lbrack;UI&amp;rbrack; 새로운 SearchBox 스타일
* &amp;lbrack;UI&amp;rbrack; 새 패널 헤더 스타일
* &amp;lbrack;UI&amp;rbrack; 새로운 사용 중 표시기 스타일
* &amp;lbrack;UI&amp;rbrack; 새 레이어 스택 배경 스타일
* &amp;lbrack;UI&amp;rbrack; Adobe Clean 글꼴 사용
* &amp;lbrack;UI&amp;rbrack; 색상 입력 매개 변수의 스포이드 아이콘 제거 자리 표시자
* &amp;lbrack;성능&amp;rbrack; 사용 중 표시기 최적화
* &amp;lbrack;내용&amp;rbrack; 새 패턴 생성기 필터
* &amp;lbrack;내용&amp;rbrack; 새로운 흐림 효과 필터

**고정:**

* &amp;lbrack;Inspire&amp;rbrack; 10개 이상의 색상을 사용할 때 충돌 수정
* &amp;lbrack;2D 보기&amp;rbrack; 2D 보기의 채널 목록에서 스크롤 막대 수정
* &amp;lbrack;Viewer&amp;rbrack; 2의 전력이 아닌 환경 맵을 가져올 때 충돌 수정
* &amp;lbrack;Content&amp;rbrack; 엠보싱 및 천공 필터의 사용자 정의 패턴에 대한 PNG 가져오기 수정
* &amp;lbrack;내보내기&amp;rbrack; 일반 수정 및 채널당 16비트 Height 내보내기
* 이름이 같은 두 개의 사전 설정이 있는 재질을 가져올 때 무한 루프 수정
* 기본 재질 레이어에서 긴 파일 경로 표시 수정

**알려진 문제:**

* 하나의 재질에 여러 개의 흐림 효과를 사용하는 것은 권장되지 않습니다
* 구형 NVIDIA 드라이버에서 Delighter 충돌(400.x 미만)
* Delighter 단계의 빠른 가시성 전환은 권장하지 않습니다
* 이미지 가져오기 레이어의 [속성] 패널에 TIF 이미지가 표시되지 않습니다
* 슬라이더에서 특정 값을 입력할 때 혼수 또는 점을 무시할 수 있습니다
* Height에 표준 필터가 MacOS에서 충돌할 수 있음
* macOS에서 종료할 때 임의로 충돌할 수 있음

### 0.7.0 베타 페퍼

*(릴리스: 2019년 6월 13일)*

**추가됨:**

* &amp;lbrack;Filters&amp;rbrack; 스페이스바를 눌러 빠르게 필터에 액세스
* &amp;lbrack;Filters&amp;rbrack; 필터를 관리하고 찾아보고 가져올 수 있는 새로운 전용 패널
* &amp;lbrack;Metadata&amp;rbrack; 재질을 마우스 오른쪽 버튼으로 클릭하여 메타데이터를 봅니다.
* &amp;lbrack;Metadata&amp;rbrack; 재질을 마우스 오른쪽 버튼으로 클릭하여 디스크에서 해당 위치를 확인합니다.
* &amp;lbrack;슬라이더&amp;rbrack; Ctrl을 눌러 슬라이더를 위로 가져갈 때 Animate
* &amp;lbrack;Sliders&amp;rbrack; P를 눌러 슬라이더 애니메이션을 중지하고 다시 시작합니다.
* &amp;lbrack;내보내기&amp;rbrack; SBSAR 내보내기는 Substance Source 지침을 따릅니다.
* &amp;lbrack;License&amp;rbrack; 환경 변수를 사용하여 Substance Alchemist 활성화
* &amp;lbrack;UX&amp;rbrack; 파일 대화 상자가 마지막으로 선택한 파일 경로를 기억합니다.
* &amp;lbrack;UX&amp;rbrack; 폴더 대화 상자가 마지막으로 선택한 폴더 경로를 기억합니다.
* &amp;lbrack;UI&amp;rbrack; 리소스 업데이트 패널 UI
* &amp;lbrack;UI&amp;rbrack; 검색 막대 UI 업데이트
* &amp;lbrack;UI&amp;rbrack; 새 재질 만들기 아이콘이 업데이트됨
* &amp;lbrack;도움말&amp;rbrack; URL이 substance3d.com 도메인으로 업데이트됩니다.
* 이제 &amp;lbrack;Mesh&amp;rbrack; 천 메시를 사용할 수 있습니다.
* &amp;lbrack;Content&amp;rbrack; 새로운 부식 필터
* &amp;lbrack;콘텐츠&amp;rbrack; 새로운 산소 공급 필터
* &amp;lbrack;내용&amp;rbrack; 새 이끼 필터
* &amp;lbrack;내용&amp;rbrack; 새 Dust 필터
* &amp;lbrack;내용&amp;rbrack; 새로운 임계값 패턴 필터
* &amp;lbrack;Content&amp;rbrack; 새로운 스톤월 패턴 필터
* &amp;lbrack;Content&amp;rbrack; 새로운 나무 마무리 필터
* &amp;lbrack;Content&amp;rbrack; 새로운 메탈 마무리 필터
* &amp;lbrack;내용&amp;rbrack; 새 Snow 필터
* &amp;lbrack;내용&amp;rbrack; 새로운 임의화 필터
* &amp;lbrack;Content&amp;rbrack; 이제 기본 재질 필터에서 직접 텍스처를 가져올 수 있습니다

**고정:**

* 레이어 스택을 저장할 때 충돌 해결
* 환경 회전 슬라이더에서 1보다 큰 값을 추가할 수 있습니다.
* 블렌드 레이어가 블렌드 레이어에서 재질 레이어로 앞뒤로 변환되면 블렌드 매개 변수를 잃지 마십시오
* 동일한 레이어 스택의 변형을 여러 번 생성할 때 중복 수정
* 재질을 다시 열 때 Alchemist은 슬라이더의 수정된 범위(최소 및 최대)를 기억합니다

**알려진 문제:**

* 하나의 재질에 여러 개의 흐림 효과를 사용하는 것은 권장되지 않습니다
* 구형 NVIDIA 드라이버에서 Delighter 충돌(400.x 미만)
* Delighter 단계의 빠른 가시성 전환은 권장하지 않습니다
* 사용자 정의 환경 가져오기가 검은색으로 바뀔 수 있음
* 이미지 가져오기 레이어의 [속성] 패널에 TIF 이미지가 표시되지 않습니다
* 슬라이더에서 특정 값을 입력할 때 혼수 또는 점을 무시할 수 있습니다
* Height에 표준 필터가 MacOS에서 충돌할 수 있음

### 0.6.1 베타 오렌지

*(릴리스: 2019년 6월 13일)*

**추가됨:**

* 최신 Substance Designer 버전과 호환되도록 &amp;lbrack;엔진&amp;rbrack; Substance 엔진 업데이트
* &amp;lbrack;License&amp;rbrack; 첫 번째 설치에 대한 라이선스 폴더 업데이트
* &amp;lbrack;Layers&amp;rbrack; 언제든지 레이어 스택을 다시 로드하여 사용자 정의 필터를 업데이트합니다.

**고정:**

* &amp;lbrack;데이터 호환성&amp;rbrack; 업그레이드 시 데이터 손상을 제한하는 예방 수정

**알려진 문제:**

* 하나의 재질에 여러 개의 흐림 효과를 사용하는 것은 권장되지 않습니다
* 구형 NVIDIA 드라이버에서 Delighter 충돌(400.x 미만)
* Delighter 단계의 빠른 가시성 전환은 권장하지 않습니다
* 사용자 정의 환경 가져오기가 검은색으로 바뀔 수 있음
* 이미지 가져오기 레이어의 [속성] 패널에 TIF 이미지가 표시되지 않습니다
* 슬라이더에서 특정 값을 입력할 때 혼수 또는 점을 무시할 수 있습니다

### 0.6.0 베타 오렌지

*(릴리스: 2019년 4월 18일)*

**추가됨:**

* &amp;lbrack;Metadata&amp;rbrack; 전용 탭에서 재질 메타데이터를 보고 채웁니다.
* &amp;lbrack;Collection&amp;rbrack; 검색 결과에서 직접 모음을 만듭니다
* &amp;lbrack;미디어 게시&amp;rbrack; 컬렉션 보드 내보내기
* &amp;lbrack;UX&amp;rbrack; Ctrl+Z를 눌러 조정 변경 또는 이미지 가져오기의 실행을 취소합니다.
* &amp;lbrack;UX&amp;rbrack; Ctrl+Shift+Z를 눌러 조정 변경 또는 이미지 가져오기를 다시 실행합니다.
* &amp;lbrack;UI&amp;rbrack; 새 스타일의 새 아이콘
* 탭 전환을 더 잘 처리하기 위한 새로운 세션 관리자(&amp;lbrack; Performance&amp;rbrack; New Session Manager)
* 이미지 가져오기 레이어를 더 빠르게 여는 &amp;lbrack;성능&amp;rbrack;
* &amp;lbrack;Content&amp;rbrack; 새 금속 일반 재료
* &amp;lbrack;Content&amp;rbrack; 새로운 녹 자료
* &amp;lbrack;Content&amp;rbrack; New Stone 일반 재료
* &amp;lbrack;Content&amp;rbrack; 엠보싱 필터 업데이트
* &amp;lbrack;Content&amp;rbrack; 자수 필터 업데이트
* &amp;lbrack;내용&amp;rbrack; 페인트 필터 업데이트
* &amp;lbrack;Content&amp;rbrack; Delighter 필터 업데이트

**고정:**

* &amp;lbrack;Content&amp;rbrack; 물 필터가 Specular/광택 작업 과정에서 작동함
* 활성화 팝업에서 회색 음영 라디오 버튼 수정
* 코마 문자가 포함된 파일 허용
* 팝업 창에서 작은 글꼴 문제 해결
* 일부 NVIDIA 카드의 FXAA 매개 변수와 충돌하여 발생하는 투명도 UI 문제 해결
* 슬라이더에 값을 입력한 후 필드의 초점을 제거합니다.
* 충돌의 감소를 위해 신호기에 최소 VRAM 용량을 할당합니다.
* 애플리케이션 창 크기 조정 시 창 고정 문제 해결
* 평가되는 동안 레이어 스택을 삭제할 때의 충돌 문제를 해결했습니다.

**알려진 문제:**

* 하나의 재질에 여러 개의 흐림 효과를 사용하는 것은 권장되지 않습니다
* 구형 NVIDIA 드라이버에서 Delighter 충돌(400.x 미만)
* Delighter 단계의 빠른 가시성 전환은 권장하지 않습니다
* 사용자 정의 환경 가져오기가 검은색으로 바뀔 수 있음
* 이미지 가져오기 레이어의 [속성] 패널에 TIF 이미지가 표시되지 않습니다
* 슬라이더에서 특정 값을 입력할 때 혼수 또는 점을 무시할 수 있습니다

### 0.5.4 베타 나초

*(릴리스: 2019년 3월 26일)*

**고정:**

* &amp;lbrack;Stack&amp;rbrack; 스플래터 레이어를 제거할 때 충돌이 발생합니다.
* 응용 프로그램 충돌 시 &amp;lbrack;Data&amp;rbrack; 자산 데이터베이스가 손상됨
* 자산 데이터베이스가 손상된 경우 &amp;lbrack;Data&amp;rbrack; Substance Alchemist을 시작할 수 없습니다.
* Substance 재질을 가져올 때 임의 충돌

**알려진 문제:**

* 하나의 재질에 여러 개의 흐림 효과를 사용하는 것은 권장되지 않습니다
* 구형 NVIDIA 드라이버에서 Delighter 충돌(400.x 미만)
* Delighter 단계의 빠른 가시성 전환은 성능에 영향을 줍니다.
* 사용자 정의 환경 가져오기가 검은색으로 바뀔 수 있음
* 이미지 가져오기 레이어의 [속성] 패널에 TIF 이미지가 표시되지 않습니다
* 슬라이더에서 특정 값을 입력할 때 혼수 또는 점을 무시할 수 있습니다
* 저장할 기본 컬렉션은 비워 둘 수 있습니다.

### 0.5.3 베타 나초

*(릴리스: 2019년 3월 19일)*

**추가됨:**

* 리소스 패널에서 재질 이름으로 검색
* 브러시 크기 시각화가 적용된 &amp;lbrack;UI&amp;rbrack; 복제 도구의 새로운 UI
* &amp;lbrack;UI&amp;rbrack; 숨겨진 단계 선택 및 삭제
* &amp;lbrack;UI&amp;rbrack; 새 텍스트 필드 UI
* &amp;lbrack;도움말&amp;rbrack; Substance Source, Substance share 및 Substance 아카데미 웹 사이트 액세스
* &amp;lbrack;Content&amp;rbrack; 생성기 및 atlas가 있는 새로운 기본 재질
* &amp;lbrack;Content&amp;rbrack; 비트맵-재질 업데이트
* &amp;lbrack;콘텐츠&amp;rbrack; Dirt 업데이트
* &amp;lbrack;콘텐츠&amp;rbrack; 녹 업데이트
* &amp;lbrack;Content&amp;rbrack; 새로운 엠보싱 필터
* &amp;lbrack;Content&amp;rbrack; 새로운 자수 필터
* &amp;lbrack;Content&amp;rbrack; 새 침식 필터
* &amp;lbrack;Content&amp;rbrack; 새로운 자갈 생성기
* &amp;lbrack;내용&amp;rbrack; 새 페인트 필터
* &amp;lbrack;내용&amp;rbrack; 새 쪽매 패턴 필터
* &amp;lbrack;Content&amp;rbrack; 새로운 포장 패턴 필터
* &amp;lbrack;내용&amp;rbrack; 새 천공 필터
* &amp;lbrack;Content&amp;rbrack; 새로운 스플래터 필터
* &amp;lbrack;Content&amp;rbrack; 새로운 섬유 마모 필터
* &amp;lbrack;내용&amp;rbrack; 새 변환 필터

**고정:**

* &amp;lbrack;Viewport&amp;rbrack; X에 x2 타일링이 있는 구 메시
* &amp;lbrack;Viewport&amp;rbrack; 사용자 환경을 로드할 때 충돌함
* &amp;lbrack;뷰 포트(&amp;rbrack; 환경 맵에서도 이제 노출 값을 사용하고 있습니다.
* &amp;lbrack;뷰포트(&amp;r)rbrack; 단축키가 카메라 각도를 재설정하지 않음
* &amp;lbrack;Export&amp;rbrack; SBS 내보내기가 최신 Substance Designer 2018.3.3에서 작동합니다.
* &amp;lbrack;Export&amp;rbrack; SBSAR 내보내기는 Substance Source 재질과 동일한 지침을 따릅니다.
* &amp;lbrack;UI&amp;rbrack; 스크롤 막대를 드래그할 수 있음
* 폴더 및 파일 경로에서는 특수 문자가 지원됩니다
* 자료를 저장할 때 썸네일이 다시 생성됩니다.

**알려진 문제:**

* 하나의 재질에 여러 개의 흐림 효과를 사용하는 것은 권장되지 않습니다
* 구형 NVIDIA 드라이버에서 Delighter 충돌(400.x 미만)
* Delighter 단계의 빠른 가시성 전환은 성능에 영향을 줍니다.
* 사용자 정의 환경 가져오기가 검은색으로 바뀔 수 있음
* 이미지 가져오기 레이어의 [속성] 패널에 TIF 이미지가 표시되지 않습니다
* 슬라이더에서 특정 값을 입력할 때 혼수 또는 점을 무시할 수 있습니다
* 저장할 기본 컬렉션은 비워 둘 수 있습니다.

### 0.5.2 베타 나초

*(릴리스: 2019년 3월 7일)*

**추가됨:**

* 높은 프로필 GPU 감지 및 사용

**고정:**

* 회전 매개 변수에 적절한 슬라이더 위젯이 있음
* 재질을 드래그하여 놓을 때 파랑 색상 선의 가시성 수정
* 첫 번째 레이어 아래에 재질을 놓을 때 재질 혼합 수정
* 사용자 정의 이미지 경로가 설정되지 않은 경우에만 이미지 입력을 플러그로 지정

**알려진 문제:**

* 파일 경로에 특수 문자가 있으면 재질이 저장되지 않음
* 하나의 재질에 여러 개의 흐림 효과를 사용하는 것은 권장되지 않습니다
* 구형 NVIDIA 드라이버에서 Delighter 충돌(400.x 미만)
* Delighter 단계의 빠른 가시성 전환은 성능에 영향을 줍니다.
* 자체 환경을 로드할 때 충돌 발생

### 0.5.1 베타 나초

*(릴리스: 2019년 3월 4일)*

**고정:**

* 충돌 보고서, 버그 보고서 및 라이선스 팝업 수정

**알려진 문제:**

* 하나의 재질에 여러 개의 흐림 효과를 사용하는 것은 권장되지 않습니다
* 구형 NVIDIA 드라이버에서 Delighter 충돌(400.x 미만)
* Delighter 단계의 빠른 가시성 전환은 성능에 영향을 줍니다.
* 자체 환경을 로드할 때 충돌 발생

### 0.5.0 베타 나초

*(릴리스: 2019년 2월 28일)*

**추가됨:**

* &amp;lbrack;레이어 스택&amp;rbrack; 레이어 순서 변경
* &amp;lbrack;레이어 스택&amp;rbrack; 숨겨진 레이어 삭제
* &amp;lbrack;레이어 스택&amp;rbrack; 원하는 위치에서 바로 재질 가져오기
* &amp;lbrack;레이어 스택&amp;rbrack; 새 필터 매개 변수 유형으로 재료 입력
* &amp;lbrack;Performance&amp;rbrack; Substance 엔진 예산이 더 나은 성능을 위해 동적입니다.
* &amp;lbrack;Performance&amp;rbrack; 특히 MacOS에서 더 나은 OpenGL 성능
* &amp;lbrack;Data&amp;rbrack; 새 버전이 출시된 후 더 빠른 데이터 업그레이드
* &amp;lbrack;Content&amp;rbrack; Windows 7 및 Windows 8에서 사용 가능한 AI Delighter
* rtx GPU에서 사용 가능한 &amp;lbrack;Content&amp;rbrack; AI Delighter

**고정:**

* 애플리케이션을 종료할 때 발생할 수 있는 충돌 수정
* 큰 컬렉션을 내보낼 때 내보내기 팝업이 더 빠르게 열립니다

**알려진 문제:**

* 하나의 재질에 여러 개의 흐림 효과를 사용하는 것은 권장되지 않습니다
* 구형 NVIDIA 드라이버에서 Delighter 충돌(400.x 미만)
* Delighter 단계의 빠른 가시성 전환은 성능에 영향을 줍니다.
* 자체 환경을 로드할 때 충돌 발생

### 0.4.0 베타 머핀

*(릴리스: 2019년 1월 17일)*

**추가됨:**

* &amp;lbrack;컬렉션을 Substance 아카이브(sbsar) 내보내기(&amp;r)
* &amp;lbrack;컬렉션을 sbs(Substance 파일) 내보내기
* 내보내기 패널에 내보내기 대기열 표시(&amp;lbrack; Export&amp;rbrack; Export queue)
* &amp;lbrack;Export&amp;rbrack; 내보내기 전에 컬렉션 또는 재질 이름 지정
* &amp;lbrack;Data&amp;rbrack; Ctrl+Shift+S를 눌러 자료로 저장
* &amp;lbrack;Data&amp;rbrack; Ctrl+S를 눌러 재질을 저장합니다.
* &amp;lbrack;Data&amp;rbrack; 컬렉션 및 재질은 여러 버전에서 호환됩니다.
* &amp;lbrack;Data&amp;rbrack; 최신 필터로 재질 레이어 스택 업데이트
* &amp;lbrack;Data&amp;rbrack; 가져온 사용자 정의 필터의 핫 리로드
* &amp;lbrack;UI&amp;rbrack; 뷰포트에서 컴퓨팅 중에 시각적 피드백
* &amp;lbrack;UI&amp;rbrack; 새 버튼 스타일
* &amp;lbrack;UI&amp;rbrack; 저장 팝업에 활성 컬렉션의 이름이 표시됩니다.
* &amp;lbrack;UI&amp;rbrack; 이미지 가져오기 레이어의 소스 이미지 수정
* 이제 &amp;lbrack;Content&amp;rbrack; 사용자 정의 사용이 지원됩니다.
* &amp;lbrack;Content&amp;rbrack; 이미지 입력 매개 변수에서 더 많은 이미지 형식이 지원됩니다.
* &amp;lbrack;Content&amp;rbrack; Make It Tile Advanced라는 이름의 새로운 타일링 필터
* &amp;lbrack;Content&amp;rbrack; 물 필터 업데이트

**고정:**

* [재질로 비트맵]으로 Specular/광택 작업 과정 처리

**알려진 문제:**

* 하나의 재질에 여러 개의 흐림 효과를 사용하는 것은 권장되지 않습니다
* 구형 NVIDIA 드라이버에서 Delighter 충돌(400.x 미만)
* RTX GPU 카드에서는 Delighter가 지원되지 않음
* Delighter 단계의 빠른 가시성 전환은 성능에 영향을 줍니다.

### 0.3.1 베타 Lasagna

*(릴리스: 2018년 12월 17일)*

**고정:**

* 10가지 색상 추출 충돌로 색상 변형 생성
* 방금 저장한 레이어 스택이 충돌하여 색상 변형 생성
* Substance Alchemist 버전 업데이트 팝업에서 잘못된 링크

**알려진 문제:**

* [비트맵을 재질로]에서 [Specular/거칠음] 작업 과정을 처리하지 않음
* 하나의 재질에 여러 개의 흐림 효과를 사용하는 것은 권장되지 않습니다
* 구형 NVIDIA 드라이버에서 Delighter 충돌(400.x 미만)
* Delighter 단계의 빠른 가시성 전환은 성능에 영향을 줍니다.

### 0.3.0 베타 Lasagna

*(릴리스: 2018년 12월 12일)*

**추가됨:**

* &amp;lbrack;내보내기&amp;rbrack; 새 내보내기 팝업
* &amp;lbrack;내보내기&amp;rbrack; 전체 컬렉션 내보내기
* &amp;lbrack;내보내기&amp;rbrack; 선택한 형식으로 비트맵을 내보냅니다
* &amp;lbrack;내보내기&amp;rbrack; 선택한 해상도로 비트맵을 내보냅니다
* &amp;lbrack;내보내기&amp;rbrack; 선택한 채널만 내보내기
* &amp;lbrack;Export&amp;rbrack; 내보내기의 추정 크기 미리 보기
* &amp;lbrack;내보내기&amp;rbrack; 내보내기 전에 디스크에서 사용 가능한 크기를 미리 봅니다
* 마우스 오른쪽 버튼을 클릭하여 액세스할 수 있는 컬렉션의 &amp;lbrack;UX&amp;rbrack; 작업
* &amp;lbrack;UX&amp;rbrack; Inspire에서 이미지 또는 에셋 설정 해제 허용
* &amp;lbrack;UX&amp;rbrack; Substance Alchemist이 최대로 실행됩니다.
* &amp;lbrack;Assets&amp;rbrack; 다음 버전에서 영구적인 유지를 위해 자료를 저장하는 새로운 방법
* &amp;lbrack;도움말&amp;rbrack; 도움말 메뉴를 통해 온라인 설명서에 액세스
* &amp;lbrack;성능&amp;rbrack; Substance Alchemist을 사용하여 만든 복합 재질에 대한 더 빠른 색상 변형
* &amp;lbrack;성능&amp;rbrack; 실습실 전환 시 메모리 누수 감소
* &amp;lbrack;Content&amp;rbrack; 재질 물리적 크기 진단을 위한 크기 검사기
* &amp;lbrack;Content&amp;rbrack; 이탈리아 Venice Mosaic 타일 재질 업데이트
* &amp;lbrack;Content&amp;rbrack; 모스 스플래터 업데이트

**고정:**

* 재질을 저장할 때 더 이상 기본 이름이 없음
* 재료를 저장하고 Substance Alchemist을 다시 열면 필터 매개변수가 손실됩니다
* &amp;lbrack;Content&amp;rbrack; AO 및 곡률 혼합을 위한 하단과 상단 논리에서 수정

**알려진 문제:**

* 이전 버전으로 만든 재질은 새 버전에서 사용할 수 없습니다.
* [비트맵을 재질로]에서 [Specular/거칠음] 작업 과정을 처리하지 않음
* 하나의 재질에 여러 개의 흐림 효과를 사용하는 것은 권장되지 않습니다
* 구형 NVIDIA 드라이버에서 Delighter 충돌(400.x 미만)
* Delighter 단계의 빠른 가시성 전환은 성능에 영향을 줍니다.

### 0.2.0 베타 Kiwi

*(릴리스: 2018년 11월 9일)*

**추가됨:**

* 뷰어 설정은 한 세션에서 다른 세션으로 저장됩니다
* 재질 설정은 한 세션에서 다른 세션으로 저장됩니다
* 속성 패널의 빠른 로드
* &amp;lbrack;Log&amp;rbrack; 도움말 메뉴를 통해 로그 파일 내보내기
* &amp;lbrack;UI&amp;rbrack;새 슬라이더 스타일
* &amp;lbrack;UI&amp;rbrack;사전 설정 및 비틀기 패널 병합
* &amp;lbrack;UI&amp;rbrack;새 축소판 스타일
* 변위, 타일링 및 그림자 설정은 뷰포트에서 직접 액세스할 수 있습니다
* &amp;lbrack;Content&amp;rbrack; 새로운 기본 재질
* &amp;lbrack;Content&amp;rbrack; 모스 스플래터 업데이트
* &amp;lbrack;Framework&amp;rbrack; Substance 엔진 프레임워크 업데이트

**고정:**

* Labs를 전환하여 레이어 스택을 삭제한 것은 수정되었습니다.
* 뷰포트에 표시된 로드 시간 값이 정확합니다.
* 재료 워크플로우 기본 채널이 올바르게 초기화됨
* 사용자 정의 메시 가져오기 비활성화
* 비트맵 내보내기
* &amp;lbrack;MacOS&amp;rbrack; 닫기 Substance Alchemist에 &quot;강제 종료&quot;가 필요할 수 있습니다.

**알려진 문제:**

* 이전 버전으로 만든 재질은 새 버전에서 사용할 수 없습니다.
* 하나의 재질에 여러 개의 흐림 효과를 사용하는 것은 권장되지 않습니다
* 구형 NVIDIA 드라이버에서 Delighter 충돌(400.x 미만)
* Delighter 단계의 빠른 가시성 전환은 성능에 영향을 줍니다.

### 0.1.1 베타 잼

*(릴리스: 2018년 10월 24일)*

**추가됨:**

* 이제 BaseColor Delighter 사용 가능
* 도움말 메뉴를 통해 Substance Alchemist 정보에 액세스
* 새로운 버전의 Substance Alchemist을 사용할 수 있을 때 알림 받기
* 콘솔이 더 이상 Windows에 표시되지 않습니다.
* 새 축소판 스타일
* 전체 화면에서 &amp;lbrack;MacOS&amp;rbrack; Substance Alchemist 설정 가능
* &amp;lbrack;Filter&amp;rbrack; 두 재질 간의 혼합을 관리하는 사용자 정의 마스크 가져오기
* &amp;lbrack;Filter&amp;rbrack; Control Moss scale
* &amp;lbrack;필터&amp;rbrack; 복제 패치 업데이트

**고정:**

* 매개 변수 목록에 입력된 이미지에 이미지를 추가하면 출력이 업데이트됩니다.
* 사용자 정의 필터 가져오기에 검정색 앰비언트 오클루전과 검정색 불투명도가 추가되지 않음

**알려진 문제:**

* 이전 버전으로 만든 재질은 새 버전에서 사용할 수 없습니다.
* &amp;lbrack;MacOS&amp;rbrack; 닫기 Substance Alchemist에 &quot;강제 종료&quot;가 필요할 수 있습니다.
* 하나의 재질에 여러 개의 흐림 효과를 사용하는 것은 권장되지 않습니다
* 구형 NVIDIA 드라이버에서 Delighter 충돌(400.x 미만)
* Delighter 단계의 빠른 가시성 전환은 성능에 영향을 줍니다.
* 재질 내보내기가 충돌할 수 있음

### 0.1.0 베타 아이스크림

*(릴리스: 2018년 10월 17일)*

**추가됨:**

* 4가지 혼합 유형을 사용한 재질 혼합(Height 혼합, 샘플 혼합, 곡률 혼합, AO 혼합)
* 레이어 스택 재계산을 최적화하는 캐싱 메커니즘 도입
* 뷰포트에 표시되는 경우 Inspire에서 재질 자동 선택
* 재질 설정 패널에서 중앙 집중화된 일반 형식
* 자르기 및 타일링 위젯 컨트롤(-90xB0,+90xB0, 정사각형 만들기 등) 청소하는 중
* 새 Snow 필터

**고정:**

* 패널 UI 정리
* 창 및 패널 크기 조정 시 뷰포트가 깜박임
* 저장하면 레이어 스택이 다시 계산되지 않음
* 인터페이스의 에셋 이름은 그래프 이름 대신 레이블을 사용합니다

**알려진 문제:**

* 레이어 가시성을 빠르게 전환하여 레이어 늘이기
* 초점이 카메라 각도를 재설정합니다.
