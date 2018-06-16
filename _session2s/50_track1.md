---
layout: session2
order: 5
title: "CEPH 운영자를 위한 Object Storage Performance Tuning"

track:
  - Room E5
time: "15:20 ~ 16:00"
duration: 40분
speakers:
  - name: 한승진
    org: netmarble
    desc: 
    image: ../assets/imgs/unknown.png
---

## 개요

hyper converged infra structure의 요구사항이 증가함에 따라 CEPH의 활용도는 더 높아지고 있습니다. 특히 최근 빅데이터와 어플리케이션에 유연하게 대응 가능한 object storage에 대한 니즈는 더 높아지고 있습니다. 이 세션에서는 실제 ceph의 radosgw를 통해 object storage를 구축하고 운영한 엔지니어의 입장에서 Object Storage를 실제 구축/운영 할 때 도움을 줄 수 있는 성능 튜닝 포인트를 공유할 예정입니다. 포함할 topic은 아래와 같습니다.

* Erasure Coded Pool Tuning
* Filestore vs Bluestore
* HDD Index Pool vs SSD Index Pool
* RGW Bottleneck?
* cluster 크기에 따른 RGW 비율
* Cache Tier 성능 테스트
* CAS (Cache Acceleration Software)
