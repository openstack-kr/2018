---
layout: session1
order: 8
title: "CephFS with OpenStack Manila based on Bluestore and Erasure Code"
track: Track 3
time: "16:30 ~ 17:00"
duration: 30분
speakers:
  - name: 유장선
    org: 네이버
    desc: 
    image: ../assets/imgs/유장선.gif
materials:
  - https://www.slideshare.net/openstack_kr/openinfra-days-korea-2018-track-3-cephfs-with-openstack-manila-based-on-bluestore-and-erasure-code
---

## 개요

네이버에서는 Ceph Storage 를 도커 컨테이너의 Persistent Storage 로 활용하기 위한 다양한 연구를 진행하고 있습니다. 이를 위해 OpenStack 의 일부 프로젝트만 도입하여 Composable Infrastructure 형태로 구축을 진행하고 있습니다. 이미 Ceph RBD 와 OpenStack Cinder를 연동하여 Block Storage 를 도커 컨테이너에 제공을 하고 있으며, 현재 CephFS 와 OpenStack Manila 를 연동하여 Shared FS 제공하기 위한 작업을 진행하고 있습니다.

본 세션에서는 CephFS 의 성능 및 안정성 테스트, Kolla 를 통한 CephFS 배포, OpenStack Manila 연동, BlueStore 및 Erasure Code 를 도입하게된 배경, Multiple MDS 적용, Ceph Fuse 와 Kernel Mount 비교 등 구축하면서 발생된 여러 이슈들과 이를 어떻게 해결하였는지 다양한 정보를 공유드리도록 하겠습니다.
