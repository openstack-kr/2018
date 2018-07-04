---
layout: session2
order: 6
title: "GPU on Kubernetes"
track:
  - Room E5
time: "16:10 ~ 16:50"
duration: 40분
speakers:
  - name: 이종철 책임
    org: LG CNS
    desc: "LG CNS에 입사한 이후 15년간 개발 프레임워크 및 도구를 만들어 왔습니다.
           2년전 부터는 클라우드 기술인 OpenStack 및 Kubernetes에 대한 구축 및 기술지원을
           담당하고 있습니다."
    image: ../assets/imgs/이종철.jpg
materials:
  - https://www.slideshare.net/openstack_kr/openinfra-days-korea-2018-day-2-e5-gpu-on-kubernetes
---

## 개요

LG CNS에서는 Deep Learning 서비스를 준비하고 있으며, 이는 Kubernetes
기반으로 만들고 있습니다.
이번 발표에서는 먼저 beta로 제공되고 있는 Kubernetes GPU 기능에 대해 간단하게
살펴보고, 향후 제공될 기능 로드맵에 대해 공유하겠습니다.
이후, 저희가 서비스 검증을 위해 진행한, AI 어플리케이션의 성능 및 NVidia Tesla
GPU 모델별 호환성 확인을 공유하도록 하겠습니다.