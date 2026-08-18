---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/getting-started/activation-and-licenses.html"
breadcrumb-title: ''
description: 애플리케이션 사용을 시작하고 모든 기능에 액세스하기 위해 Substance 3D Sampler에 대한 라이선스를 활성화 및 관리하는 방법에 대해 알아봅니다.
helpx_creative_field: ""
helpx_description: Sampler > Getting Started > Activation and licenses
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: 활성화 및 라이선스
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '455'
ht-degree: 1%

---


# 활성화 및 라이선스

이 페이지에서는 Sampler 사용을 시작할 수 있도록 라이선스를 활성화하고 관리하는 방법에 대한 정보를 제공합니다.

## 애플리케이션 유형별 활성화 프로세스

활성화 프로세스는 Sampler을 구매했거나 액세스할 수 있는 위치에 따라 다릅니다.

| 응용 프로그램 유형 | 활성화 프로세스 |
| --- | --- |
| Creative Cloud 데스크톱 | [HelpX 설명서](https://helpx.adobe.com/support/substance-3d-sampler.html)의 전용 페이지를 참조하십시오.문제가 있는 경우 [Creative Cloud 설명서](https://helpx.adobe.com/creative-cloud/user-guide.html)에서 추가 답변을 제공할 수 있습니다. |
| 증기 | Steam 라이브러리에서 직접 제품을 실행합니다. |
| Substance 3D 독립형 | 아래에 설명된 활성화 프로세스를 참조하십시오. |

## 활성화 단계

### 활성화 마법사

![](../assets/activation-wizard.png){width="350px"}

세 가지 옵션을 사용할 수 있습니다.

* **이 제품 평가**: 레거시 평가판을 더 이상 사용할 수 없습니다. 대신 각 Substance 3D 응용 프로그램에 대해 [여기](https://www.adobe.com/creativecloud/3d-augmented-reality.html) 또는 Creative Cloud 데스크톱을 사용하여 30일 체험판을 시작할 수 있습니다. 각 체험판은 다른 Substance 3D 애플리케이션과 별개이므로 한 번에 하나씩 또는 모두 시도해 볼 수 있습니다.
* **라이선스 파일을 사용하여 활성화**: 2022년 9월 30일 이전에 [Substance 3D 웹 사이트](https://store.substance3d.com/user)의 계정 페이지에서 다운로드한 라이선스 파일(**\*.key**)로 제품을 활성화하십시오.
* **내 계정을 사용하여 활성화**: 기존 Substance 계정은 더 이상 활성화에 사용할 수 없습니다. [Substance 계정에 대한 자세한 내용은 여기에서 확인할 수 있습니다](https://helpx.adobe.com/substance-3d/unlisted/faq-end-of-life-accounts.html).

>[!WARNING]
>
> 활성화 마법사를 사용하여 라이선스 파일을 설치하려면 관리자로 Sampler을 실행하고 안티바이러스를 일시적으로 비활성화해야 합니다.

### 수동 활성화

**license.key** 파일을 다음 폴더에 넣어 Sampler을 수동으로 활성화할 수 있습니다.

<table data-preserve-html="true"><colgroup> <col/> <col/> <col/> <col/> </colgroup><tbody><tr><th>플랫폼</th><th>버전</th><th colspan="2">경로</th></tr><tr><td rowspan="4"><strong>Windows</strong></td><td rowspan="2"><strong>3.0</strong> 이상</td><td colspan="1">앱 데이터(로컬)</td><td colspan="1">C:\Users\[사용자 이름]\AppData\Local\Adobe\Adobe Substance 3D Sampler</td></tr><tr><td colspan="1">앱 데이터(로밍)</td><td colspan="1">C:\Users\[사용자 이름]\AppData\Roaming\Adobe\Adobe Substance 3D Sampler</td></tr><tr><td rowspan="2">레거시</td><td colspan="1">앱 데이터(로컬)</td><td colspan="1">C:\Users\[사용자 이름]\AppData\Local\Allegorithmic\Substance Alchemist</td></tr><tr><td colspan="1">앱 데이터(로밍)</td><td colspan="1">C:\Users\[사용자 이름]\AppData\Roaming\Allegorithmic\Substance Alchemist</td></tr><tr><td rowspan="2"><strong>Mac</strong></td><td colspan="1"><strong>3.0</strong> 이상</td><td colspan="2">/Users/[사용자 이름]/Library/Application Support/Adobe/Adobe Substance 3D Sampler</td></tr><tr><td colspan="1">레거시</td><td colspan="2">/Users/[사용자 이름]/Library/Application Support/Allegorithmic/Substance Alchemist</td></tr><tr><td rowspan="2"><strong>리눅스</strong></td><td colspan="1"><strong>3.0</strong> 이상</td><td colspan="2">/home/[사용자 이름]/.local/share/Adobe/Adobe Substance 3D Sampler</td></tr><tr><td>레거시</td><td colspan="2">/home/[사용자 이름]/.local/share/Allegorithmic/Substance Alchemist</td></tr></tbody></table>

>[!NOTE]
>
> 위에서 언급한 경로의 일부 디렉터리는 기본적으로 숨겨져 있을 수 있습니다. 파일 탐색기에서 경로를 수동으로 입력하거나 숨겨진 파일을 표시하여 확인합니다.

>[!NOTE]
>
> 파일이 **license.key**(으)로 호출되었는지 확인하세요. 그렇지 않으면 응용 프로그램에서 파일을 찾을 수 없습니다.

### 환경 변수

Sampler에서 **license.key** 파일에 대해 확인하는 위치를 [환경 변수](../pipeline-and-integrations/environment-variables.md)(으)로 재정의할 수 있습니다.
