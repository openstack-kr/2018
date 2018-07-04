---
layout: session1
order: 3
title: "Kubernetes 환경에서의 Volume 배포와 데이터 관리의 유연성 확보(실 테스트 사례 공유)"
track: Track 1
time: "13:20 ~ 13:50"
duration: 30분
speakers:
  - name: 김진학 부장
    org: NetApp
    desc: "
	      한국 NetApp에서 클라우드 비즈니스에 대한 컨설팅 및 Pre-Sales를 지원하고
          있으며, OpenStack에서 Data 저장소를 필요로 하는 여러 프로젝트들(Cinder, Manila,
          Swift)에 대한 전문지식을 보유하고 있습니다. 또한 최근 컨테이너 기반 기술의 성장에
          따라, 관련 비즈니스에 대한 지원을 하고 있습니다.
	      "
    image: ../assets/imgs/김진학.jpg
  - name: 장다성 선임
    org: LG CNS
    desc: "
	      LG CNS 에서 Infra Architect 로 근무하며, OpenStack 플랫폼 구축 및
          유지보수를 하였으며, 컨테이너 서비스 제공을 위한 kubernetes 환경의 컨테이너
          플랫폼 구축 및 설계를 지원하고 있습니다.
	      "
    image: ../assets/imgs/장다성.jpg
materials:
  - https://www.slideshare.net/openstack_kr/openinfra-days-korea-2018-track-1-kubernetes-volume
---

## 개요

Container는 상태 비 저장 어플리케이션에 유용합니다. 그렇지만, Container 기술이
성숙 해짐에 따라 엔터프라이즈 환경에서 상태 저장 어플리케이션에 대한 요구가 점점
증가하고 있습니다. 이번 공동 발표 세션에서는, Kubernetes 환경에서 상태 저장
어플리케이션을 배포하고 운영하는데 따른 challenge를 알아보고, 이를 극복하는
방안을 실제 테스트 사례를 기반으로 전달 합니다.
테스트 사례는, NetApp의 Trident plug-in을 이용하여 컨테이너를 위한 볼륨의 배포
자동화 및 서비스 연속성을 제공하기 위한 테스트 결과를 공유 합니다.