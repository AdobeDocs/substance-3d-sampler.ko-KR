---
helpx_url: 'https://helpx.adobe.com/kr/substance-3d-sampler/getting-started/system-requirements.html'
breadcrumb-title: ''
description: Substance 3D Sampler의 시스템 요구 사항을 검토하여 하드웨어와 소프트웨어가 호환성 표준을 충족하는지 확인하십시오.
helpx_creative_field: ''
helpx_description: Sampler > Getting Started > System requirements
helpx_experience_level: ''
helpx_learn_topic: ''
helpx_tags: ''
title: 시스템 요구 사항
user-guide-description: ''
user-guide-title: ''
source-git-commit: cd61972eaf1567863dc8c3549a1c90c84ffee825
workflow-type: tm+mt
source-wordcount: '595'
ht-degree: 0%

---


# 지원되는 시스템

다음은 애플리케이션에서 지원하는 하드웨어 및 시스템 목록입니다.

>[!WARNING]
>
> 다음 Nvidia 드라이버는 Sampler 실행 시 안정성을 유발하는 것으로 알려져 있습니다.
>
> * 610.47
>
> 이러한 버전은 사용하지 않는 것이 좋습니다. 더 최신 버전을 사용하거나 더 최신 버전이 없는 경우 이전 버전을 사용하는 것이 좋습니다.

## Windows

|  | 최소 | 권장 | 최적 |
| --- | --- | --- | --- |
| **OS** | Windows 11 64비트 버전 23H2 | Windows 11 64비트 버전 24H1 | Windows 11 64비트 버전 24H2 |
| **CPU** | Intel Core i5 AMD Ryzen 5 | Intel Core i7 AMD Ryzen 7 | Intel Core i9 AMD Ryzen 9 |
| **GPU** | NVIDIA GeForce RTX 2060 Super NVIDIA Quadro RTX 4000 AMD Radeon RX 5700 XT AMD Radeon Pro W5700 | NVIDIA GeForce RTX 3080 NVIDIA Quadro RTX A4000 AMD Radeon RX 6800 XT AMD Radeon Pro W7700 | NVIDIA GeForce RTX 4090 NVIDIA Quadro RTX 5000 Ada Generation AMD Radeon RX 7900 XTX AMD Radeon Pro W7800 |
| **VRAM** | 8GB | 16GB | 24GB |
| **RAM** | 16GB | 32GB | 64GB |
| **저장소** | 30GB의 사용 가능한 공간이 있는 SSD | 50GB의 사용 가능한 공간이 있는 SSD | 70GB의 사용 가능한 공간이 있는 SSD |

### macOS

|  | 최소 | 권장 | 최적 |
| --- | --- | --- | --- |
| **OS** | macOS 13 벤투라 | macOS 소노마 | macOS 타호 |
| **CPU** | Apple | Apple | Apple M4 Pro |
| **GPU** | Apple | Apple | Apple M4 Pro |
| **RAM** | 24GB | 32GB | 64GB |
| **저장소** | 30GB의 사용 가능한 공간이 있는 SSD | 50GB의 사용 가능한 공간이 있는 SSD | 70GB의 사용 가능한 공간이 있는 SSD |

### 리눅스

| 기업 | 증기 |
| --- | --- |
| RHEL 8 <br>RHEL 9 | Ubuntu 22.04 |

>[!NOTE]
>
> 시스템이 위의 시스템 요구 사항을 충족하지만 여전히 성능이 낮은 경우 Sampler에서 잘못된 GPU를 사용하고 있을 수 있습니다.
>
> NVIDIA GPU를 사용하는 경우 [이 페이지의 지침에 따라 Sampler에서 사용하는 GPU를 변경하십시오](../technical-support/configuration/nvidia-driver-settings.md).

## 일반 권장 사항

* 편안한 환경에서 작업하려면 해상도가 1 MegaPixel보다 크고 1280 픽셀보다 넓은 모니터를 사용하는 것이 좋습니다.
* 대부분의 Substance 앱은 RHEL8/9 호환을 위해 OpenSSL 1.1.1을 사용합니다. 최신 OpenSSL 버전을 사용하는 시스템의 경우 수동으로 제공해야 합니다.

## 지원되지 않는 구성

**Windows**

* 가상 컴퓨터가 지원되지 않습니다.
* Windows Server가 지원되지 않습니다.

**Mac**

* 공식 Apple 구성만 지원됩니다.
* eGPU는 현재 지원되지 않으며 안정성 문제가 있을 수 있습니다.

**Linux**

* Linux의 Mesa 드라이버는 지원되지 않습니다.

**모든 플랫폼**

* 통합 GPU는 x86-64(Intel, AMD) CPU에서 지원되지 않습니다.
* 그래픽 드라이버에 대한 Sampler 호출을 차단하는 서드파티 소프트웨어와 함께 Sampler을 사용하는 것은 지원되지 않습니다. 이러한 소프트웨어에는 다음이 포함됩니다.
  * 색 보정, 카메라 효과 등을 적용하는 리셰이더와 같은 후처리 인젝터입니다.
  * 사용자 정의 십자선, GPU 성능 지표, 비디오 스트리밍용 스킨 등의 화면 오버레이...

## 최소 GPU 드라이버 버전

다음은 응용 프로그램을 문제 없이 실행하는 데 필요한 최소 GPU 드라이버 버전 목록입니다. 이 목록은 새 버전이 출시될 때마다 변경될 수 있습니다.

새 드라이버를 다운로드하려면 [GPU에 오래된 드라이버가 있음](https://experienceleague.adobe.com/en/docs/substance-3d-painter/using/technical-support/technical-issues/gpu-issues/gpu-has-outdated-drivers)을 참조하십시오.

| OS | NVIDIA | AMD | Intel |
| --- | --- | --- | --- |
| **Windows** | GeForce 551.86 Quadro/RTX 538.33 | Radeon 23.8.1 Radeon Pro / FirePro 24.q2 | 31.0.1015590 |
| **Linux** | 525.116.04 이상 *또는* 535.54.03 이상 | Radeon 23.20 Pro 23.Q3 | 지원되지 않음 |

>[!NOTE]
>
> **Mac OS**&#x200B;에서 GPU 드라이버는 운영 체제에서 제공됩니다. 최신 드라이버에 액세스하려면 최신 버전의 OS로 업데이트하십시오.

## 언어

소프트웨어 인터페이스는 다음 언어로 제공됩니다.

* 영어
* 독일어
* 프랑스어
* 일본어
* 한국어
* 중국어
* 이탈리아어
* 포르투갈어
* 스페인어
