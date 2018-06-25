---
layout: session1
order: 9
title: "Ceph Storage, PaaS 로 서비스/운영하기"
track: Track 4
time: "17:00 ~ 17:30"
duration: 30분
speakers:
  - name: 하현
    org: 네이버
    desc: 
    image: ../assets/imgs/하현.jpg
---

## 개요

네이버는 PASTA라고 하는 InHouse PaaS 시스템를 갖추고 있습니다. PASTA에는 컴퓨팅, 스토리지, 모니터링, 보안/인증 플랫폼등의 다양한 PaaS 컴포넌트가 통합되어 있어 개발자가 원하는 시점에 바로 사용할 수 있습니다. Ceph Storage 또한 PASTA의 메인 컴포넌트로 언제든 필요시 제공받을 수 있도록 구성되어 있습니다.

본 발표에서는 먼저 네이버가 Ceph Storage를 어떻게 PaaS 형태로 서비스하고 있는지에 대해 
실제 Use Case를 중심으로 소개합니다. 그리고 이를 위해 네이버에서 구축한 Openstack 및 타 오픈소스들과의 연동 아키텍처 살펴보고, Ceph Storage 를 지난 1년간 PaaS 로 운영해 오면서 겪었던 Openstack kolla를 통한 무중단 업그레이드 경험, 운영 노하우/trouble shooting/튜닝 포인트 등에 대해서 실제 사례를 통해 설명드리겠습니다.