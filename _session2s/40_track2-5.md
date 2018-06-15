---
layout: session2
order: 4-5
title: KubeMonkey를 통한 Chaos Engineering 실전 운영하기
track:
  - Room E6
time: "14:20 ~ 14:50"
duration: 30분
speakers:
  - name: 윤석찬
    org: Korea Chaos Engineering Community
    desc: 현재, 한국 카오스 엔지니어링 커뮤니티(http://facebook.com/groups/chaosengkorea/) 운영자이면서 AWS 테크니컬 에반젤리스트로 클라우드 기술을 전파하며 개발자들이 클라우드를 활용할 수 있도록 지원하는 역할을 하고 있다. 웹 개발자로 인터넷 업계에 투신해 스타트업 CTO, 오픈 소스 커뮤니티 리더 및 IT분야 블로거 등 다양한 역할을 수행했고, 다음커뮤니케이션에서 연구개발 부서 리더 및 오픈 API 플랫폼 에반젤리스트로서 API 플랫폼 구축 및 외부 개발자 지원을 담당했다.
    image: ../assets/imgs/윤석찬.jpg 
---

## 개요
카오스 엔지니어링(Chaos Engineering)이란 프로덕션 서비스의 각종 장애 조건을 견딜 수 있는 시스템의 신뢰성을 확보하기 위해 분산 시스템을 실험 하고 배우는 분야입니다. 즉, 개발자들이 현실 세계에서 발견되는 시스템 장애를 미리 탐지하여 복원성 높은 아키텍처를 구성하는 방법을 공유합니다.클라우드 컴퓨팅의 발전과 데브옵스 방법론을 기반으로 자동화를 통해 좀 더 쉽게 개발자들이 직접 분산 시스템을 통제된 환경에서 실험을 하는 동안 나오는 결과를 관찰함으로써 현실에서 실제 행동 방법을 배울 수 있습니다. 본 세션에서는 카오스 엔지니어링의 기본 개념과 함께 Kubernetes용 Chaos Tool인 KubeMonkey를 통해 무작위로 클러스터의 포드를 삭제하여 장애 복구 서비스 아키텍처를 검증하는 방법을 설명합니다.