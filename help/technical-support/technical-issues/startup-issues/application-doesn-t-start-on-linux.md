---
helpx_url: "https://helpx.adobe.com/kr/substance-3d-sampler/technical-support/technical-issues/startup-issues/application-doesn-t-start-on-linux.html"
breadcrumb-title: ''
description: Linux에서 Substance 3D Sampler 시작 문제를 해결하여 애플리케이션 실행 문제 및 오류 메시지를 해결하는 방법에 대해 알아보십시오.
helpx_creative_field: ""
helpx_description: Sampler > Technical Support > Technical Issues > Startup issues > Application doesnt start on Linux
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Linux에서 응용 프로그램이 시작되지 않음
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '108'
ht-degree: 0%

---


# Linux에서 응용 프로그램이 시작되지 않음

터미널에서 다음 오류 메시지와 함께 Linux에서 응용 프로그램을 시작할 수 없습니다.

```
error while loading shared libraries: libicui18n.so.50
```


이는 라이브러리 ICU([유니코드용 국제 구성 요소](http://site.icu-project.org/))가 없거나 설치된 버전이 너무 최신임을 의미합니다. 응용 프로그램에는 버전 50이 필요합니다.

이 문제를 해결하려면 패키지 관리자에서 버전 50을 설치하거나, **/usr/lib64**&#x200B;에 설치할 때 누락된 버전을 [수동으로 다운로드](http://mirror.centos.org/centos/7/os/x86_64/Packages/libicu-50.2-4.el7_7.x86_64.rpm)하십시오.
