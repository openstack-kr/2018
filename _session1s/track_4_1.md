---
layout: session1
order: 4
title: "Grafana를 이용한 OpenStack 클라우드 성능 모니터링"
track: Track 4
time: "13:50 ~ 14:20"
duration: 30분
speakers:
  - name: 임재민
    org: 고려대학교
    desc: 
    image: ../assets/imgs/unknown.png
materials:
  - https://www.slideshare.net/openstack_kr/openinfra-days-korea-2018-track-4-grafana-openstack-104161634
---

## 개요

클라우드 수준의 성능 모니터링 도구인 Grafana를 이용해서 오픈스택과 연동한 경험을 나누고 이를 스텔라 프로젝트에 적용할 수 있는 방안을 소개함. Grafana는 오픈스택에서 사용할 수 있는 오픈소스 모니터링 도구이고, 스텔라 프로젝트는 고려대학교에서 진행중인 클라우드 환경의 성능 보장 방법을 연구하는 프로젝트임. 
첫번째로, Grafana-오픈스택 연동한 경험을 공유하고자 함. Grafana와 오픈스택 연동 아키텍처를 소개하고 필요성, 연동할 때 고려할 사항, 기능 등에 내용을 정리함. 
두번째로, 고려대학교에서 진행중인 스텔라 프로젝트에서 I/O 성능 보장하기 위한 Grafana-오픈스택-스텔라 통합 아키텍처를 설명하고 연동을 통해 클라우드 수준의 성능 모니터링 및 동적인 성능을 조절 방법을 설명함.
마지막으로, Grafana 설치부터 테스트 과정까지 얻은 경험을 토대로 오픈스택 환경에서 Grafana를 사용할 때 얻는 장점과 단점을 비교하고 공유할 계획임. 특히 모니터링 할 대상을 추가하는 관점에서 다룰 예정임.