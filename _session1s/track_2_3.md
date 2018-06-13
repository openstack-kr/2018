---
layout: session1
order: 6
title: "넷마블의 Cloud 환경에서의 보안과 네트워크 성능 보안 (xFW), DPDK OVS"
track: Track 2
time: "15:20 ~ 15:50"
duration: 30분
speakers:
  - name: 이창재
    org: 넷마블
    desc: 
    image: ../assets/imgs/unknown.png
---

## 개요

Cloud 환경의 보안은 항상 중요한 운영 요소입니다. 물리 방화벽 하단에 구성되어 있는 Cloud 환경의 경우 VM간 차단이 없고 특히, 동일 Host 내부의 VM 간 차단은 더 어렵습니다. 이 세션에서는 netmarble에서 구현하고 운영하고 있는 Virtual 방화벽을 소개합니다. 또한, 가상 방화벽으로 인해 저하되는 성능을 DPDK OVS 의 성능 개선으로 '보안과 성능' 두가지 목적을 달성한 사례를 소개드립니다.

이 세션에서는 아래와 같은 내용을 포함할 예정입니다.
* 넷마블 Virtual 방화벽(xFW) 소개 (openflow 등)
* DPDK OVS 성능 개선 (emc hit, multi queue 등)
