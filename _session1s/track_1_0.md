---
layout: session1
order: 3
title: "Kubernetes 환경에서의 Volume 배포와 데이터 관리의 유연성 확보"
track: Track 1
time: "13:20 ~ 13:50"
duration: 30분
speakers:
  - name: 김진학
    org: NetApp
    desc: 
    image: ../assets/imgs/김진학.jpg
---

## 개요

Container는 상태 비 저장 어플리케이션에 유용합니다. 그렇지만, Container 기술이
성숙 해짐에 따라 Stateful 어플리케이션에 점점 더 많은 이점을 제공 할 수 있습니다.
이 세션에서는 Container 환경에서의 데이터 지속성에 대해 설명 합니다. 우리는
Stateful 어플리케이션에 대해 자세히 살펴보고, 배포하는 데 따른 어려움을 이해 할
것이며, 다양한 Kubernetes 기능을 활용하는 방법을 배웁니다. PersistentVolume,
PersistentVolumeClaim, StorageClasse, Quota 등을 사용하여 Stateful
어플리케이션을 배포하고 관리합니다.