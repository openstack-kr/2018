---
layout: session1
order: 9
title: "Zuul v3 - OpenStack 인프라 코드로 CI/CD 살펴보기"
track: Track 3
time: "17:00 ~ 17:30"
duration: 30분
speakers:
  - name: 최영락
    org: OpenStack Korea User Group
    desc: "
          현재 오픈스택 한국 커뮤니티 3기 회장을 맡아 활동 중입니다. OpenStack 번역을 시작으로 한 문서화, 버그 수정, 커뮤니케이션 경험을 바탕으로 국제화팀 프로젝트 리더로 약 1년간 활동하였습니다. 현재는 공개SW개발자센터 (KOSSLAB) 글로벌 오픈프론티어 5기 (파트타임)
		  에 참여하고 있으며, OpenStack 번역 및 관련 인프라 작업을 시간날 때 꾸준히 하고 있습니다.
		  "
    image: ../assets/imgs/최영락.png
materials:
  - https://www.slideshare.net/openstack_kr/openinfra-days-korea-2018-track-3-zuul-v3-openstack-cicd
---

## 개요

Zuul은 프로젝트 게이팅 및 관련된 프로젝트에 초점을 맞추어 지속적인 통합, 전달 및 배포 시스템을 구동하는 프로그램으로, OpenStack Foundation에 의해 호스팅되는 CI/CD를 위한 별개의 프로젝트입니다.
본 세션에서는 Zuul v3에 대해 설명하고, OpenStack 인프라팀이 관리하는 코드 저장소에 있는 project-config, system-config, openstack-zuul-jobs 내용을 기반으로
번역 및 문서 관련 작업에 대한 Ansible 플레이북을 통해 OpenStack 프로젝트에서 CI/CD를 어떻게 활용하는지 살펴봅니다.