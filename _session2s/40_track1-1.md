---
layout: session2
order: 4-1
title: "워크샵: 실 업무에 사용해보는 Kubernetes"
rowspan: 3
track:
  - Room E5
time: "13:20 ~ 13:50" # for 2nd column
duration: 1시간 30분
speakers:
  - name: 공진기
    org: IBM
    desc: "
백/프론트 개발, 서버, 네트워크, 하드웨어, 인지신경과학까지 새롭고 신기한건 배워보고 구현해봐야 직성이 풀린다.
전자동화 구매대행 스타트업을 창업 경험을 토대로, 지금은 한국 IBM 의 테크니컬 에반젤리스트로 PaaS, Container, DevOps, Blockchain, IoT 등 혼자 알기 아까운 신기술을 다른 사람들에게 알리고 있다.
          "
    image: ../assets/imgs/공진기.png
---

## 개요 
Kubernetes 로 당장 실서비스를 제공한다면 어떤걸 공부해야 할까요? 내 컨테이너를 도메인에 어떻게 연결하고 인증서를 설정할지, 롤링 업데이트와 보안 설정은 어떻게 해야 할지, 기존 서버 관리자와 개발자의 입장에서 Kubernetes 의 고급 기능들을 실시간 시연을 통해 알아봅니다.
 
다음과 같은 운영 시나리오를 통해 실제 서비스 운영에 필요한 Kubernetes 기능들을 확인할 예정입니다.
 
1. "컨테이너를 띄웠는데 32504 포트 말고 https://www.mycompany.com/ 로 연결하고 싶어요."
    * Ingress 를 통한 서비스별 도메인/패스 컨트롤, SSL 인증서 관리
2. "업데이트한 홈페이지는 어떻게 배포하죠?
    * 무정지 Rollout / Rollback 및 Deployment 버전 관리하기
3. "사용자가 많아져서 서비스가 느려져요!"
    * Load balancing 과 확장(scaling), 서비스 디스커버리
4. "디비 비밀번호는 어디에 저장하나요?"
    * 환경설정과 보안정보 저장 및 접근
5. "Kubernetes 고급 관리에 대해 알고 싶어요."
    * 노드간 네트워크 트래픽 관리
    * K8s 환경의 로깅 & 모니터링
    * 스토리지 선택과 관리
 
### 참석자
Docker 와 K8s 기본 내용을 공부해오시면 좋습니다. 오전 Room E5의 "K8s: User Groups 공동 워크샵 I" "Kubernetes User Group: Kubernetes for Beginner" 과정을 추천드립니다.
