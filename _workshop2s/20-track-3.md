---
layout: workshop2
order: 2
title: "GKE 딥다이브: Initial Service Deployment and Advanced Cluster Management"
track:
  - Room E3
time: "13:00 ~ 14:50"
duration: 1시간 50분
speakers:
  - name: 이민구
    org: CTO, Shakr (Google Cloud Platform User Group)
    desc: "
	      Shakr에서 개발과 관련된 여러 가지 업무를 하고 있지만, DevOps와 컨테이너 기반 애플리케이션 배포 및 운영에 특히 관심이 많아 여러 국내 Google Cloud 행사에서 Kubernetes와 관련된 주제로 이야기를 나누었습니다. 2014년부터 Shakr.com의 프로덕션 환경에서 컨테이너를 사용하고 있고, 현재는 대부분의 클라우드 워크로드를 Google Kubernetes Engine으로 마이그레이션 하여 운영중입니다.
	      "
    image: ../assets/imgs/이민구.jpg

---

## 개요

처음 GKE를 사용하기 시작하면 난해할 수 있는 서비스 배포, GKE 클러스터를 생성하고 여러 GCP의 서비스를 이용하여 첫 애플리케이션을 배포하는 과정까지 자세하게 살펴봅니다. 또한 애플리케이션을 배포한 이후 안정적인 서비스 운영을 위해 활용할 수 있는 클러스터 관리 테크닉을 소개합니다.

- Part 1: Initial App Deployment 13:00-13:50
- Break: 13:50-14:00
- Part 2: Advanced Cluster Management 14:00-14:50


### Part 1: Initial App Deployment

Google Kubernetes Engine에 처음 애플리케이션을 배포할 때, 어디부터 시작해야 하는지, 클러스터를 생성하고 설정할 때 주의할 점은 무엇인지 난해한 경우가 많습니다. 또한 Google Cloud에서 제공하는 여러 서비스를 적절히 활용하려고 해도 사용 사례나 튜토리얼을 찾아보는 것에도 한계가 있기 마련입니다. 

본 세션의 첫 번째 파트에서는 소스 코드 호스팅 및 협업 애플리케이션인 GitLab CE Omnibus를 Google Kubernetes Engine(GKE)에 배포하는 예시를 통해 적당히 규모가 있는 애플리케이션을 GKE에 배포하는 전략을 알아봅니다. 또한 PostgreSQL과 Redis를 GKE에 직접 호스팅하는 대신, Google Cloud에서 매니지드 형태로 제공하는 서비스인 Cloud SQL과 Cloud Memorystore 인스턴스를 각각 생성하고, GKE 내에서 각각의 서비스에 연결하는 방법을 자세하게 설명합니다. 

- 필요 이해도: 컨테이너에 대한 이해와 통상적인 애플리케이션 배포 과정에 대한 이해를 전제로 진행되고, Google Cloud SDK와 Kubernetes CLI를 사용하므로 커맨드 라인 도구의 사용에 능숙한 경우 세션의 내용을 보다 쉽게 이해하실 수 있습니다.


### Part 2: Advanced Cluster Management

Kubernetes에는 분산 시스템을 구축하고 관리하는 것을 도와주는 다양한 기능이 있지만, 워낙 많은 사용 사례에 대비하다보니 어떤 기능이 있는지를 쉽게 간과하고 넘어가는 경우가 많습니다.

두 번째 파트에서는 클러스터와 애플리케이션을 보다 효율적으로 관리할 수 있도록 도와주는 여러 가지 리소스와 기능을 소개합니다. Google Cloud 서비스와 연동되어 Service Account 프로비저닝을 GKE 내에서 관리할 수 있게 도와주는 Service Broker, 한 번 실행되거나 시간대에 맞춰 자동으로 실행되는 CronJob, 애플리케이션의 SLO(Service Level Objective)를 유지하기 위한 Affinity 및  Pod Disruption Budget에 대해 알아봅니다.

- 필요 이해도: Kubernetes에 애플리케이션을 배포해 보고 관리해 보신 경험이 있는 분에게 적합합니다. Part 1을 듣고 이어서 들으셔도 무방합니다.
