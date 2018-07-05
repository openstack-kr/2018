---
layout: session2
order: 1
title: "Invited Talk: Mesos to Kubernetes, cloud native 서비스를 위한 여정"
track:
  - Room E6
time: "09:30 ~ 09:55"
duration: 25분
speakers:
  - name: 홍석용
    org: Kakao
    desc: 
    image: ../assets/imgs/홍석용.gif
materials:
  - https://www.slideshare.net/openstack_kr/openinfra-days-korea-2018-day-2-e5-mesos-to-kubernetes-cloud-native
videos:
  - https://youtu.be/rA20Q_g6nXM
---

## 내용 

 저희 팀은 Mesos 기반의 컨테이너 서비스 플랫폼, ‘DKOS’를 3년 째 운영해오고 있습니다. 그리고 올해에는 좀 더 Cloud Native 한 서비스 운영을 위해 kubernetes Provider 를 신규 오픈하였습니다. 저희가 경험한 Mesos와 kubernetes의 운영 사례 비교를 통해 각각의 장단점과 일하는 방식의 변화에 대해서 말씀드리고자 합니다.
 또한, DKOS에서는 카카오톡 게임탭, 카카오T, 다음 메일, 뉴스, 카카오 번역(GPU) 등의 실 서비스 컨테이너들이 하루에도 수 천 개씩 서비스 중단없이 업데이트 되고 오토스케일되고 있습니다. 하지만 이러한 장점은 단순히 container orchestrator(Mesos, kubernetes…)를 도입한다고 해서 되는 것이 아니라 어플리케이션 설계 시에도 cloud native한 설계가 선행되어야 합니다. 본 세션을 통해 cloud native 어플리케이션 설계시 고려되어야 할 것들에 대해서 공유하여 DevOps가 고통 받지 않는 IT 환경을 꿈꿔보고 싶습니다.
