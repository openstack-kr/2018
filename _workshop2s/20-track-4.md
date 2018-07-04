---
layout: workshop2
order: 2
title: "핸즈온 워크샵: 서버리스가 컨테이너를 만났을 때"
track:
  - Room E4
time: "13:00 ~ 14:50"
duration: 1시간 50분
speakers:
  - name: 유정협 (Justin Yoo)
    org: Mexia Consulting
    desc: 
    image: ../assets/imgs/유정협.png
materials:
  - https://www.slideshare.net/openstack_kr/openinfra-days-korea-2018-day-2-e4
---

## 제목
- 한글: "서버리스가 컨테이너를 만났을 때"
- English: "When Serverless Meets Containers"

## 개요
애저 펑션을 비롯한 서버리스 아키텍처의 가장 큰 특징중 하나는 바로 운영 환경에 대한 걱정을 덜어낸다는 데 있습니다. 반면에 컨테이너 기술은 어떻게 하면 운영 환경을 좀 더 편리하게 구성할 수 있을까에 대한 고민의 결과입니다. 어떻게 보면 서버리스와 컨테이너는 정 반대의 길을 걸어간다고 볼 수도 있는데요, 사실은 같은 곳을 지향하고 있다고 봐도 무방합니다.

이 세션에서는 애저 펑션과 같은 대표적인 서버리스 플랫폼이 어떻게 컨테이너 환경에서 배포 및 설치가 이루어지는지 알아보고 실제로 간단한 애저 펑션 앱을 개발한 후 도커 컨테이너를 통해 애저 클라우드로 배포하는 방법에 대해 처음부터 끝까지 한 호흡으로 다루어 보고자 합니다.

이 세션이 끝난 후 참가자들은 애저 펑션과 같은 서버리스 아키텍처/플랫폼에 대한 이해와 더불어, 도커 컨테이너를 통해 서버리스 플랫폼을 구성하고 배포하는 방법에 대해 알 수 있습니다. 또한 이러한 전체적인 과정을 모두 CI/CD 파이프라인 안에서 해결하는 방법에 대해 배우게 됩니다.

## 안내

핸즈온 워크샵은 행사 등록하신 분들에 한해서 참석 가능하며, 최대 80명까지만 참석하실 수 있습니다.
사전 등록시 신청을 받을 예정이며, 또한 행사 당일에도 선착순으로 신청을 추가로 받을 예정입니다.

- 레벨: 초급
- 사전 준비: 노트북 (윈도우/맥/리눅스 무관). 단, 윈도우의 경우 윈도우 10 Fall Creators Update (1709) 이상 설치
- 사전 조건: Azure 서비스에 대해 들어는 봤다. 서버리스가 뭔지 들어는 봤다. 컨테이너가 뭔지 들어는 봤다.
- 유의 사항: Azure 섭스크립션이 필요합니다. https://azure.microsoft.com/ko-kr/free/. 참가자들이 인터넷을 사용할 수 있어야 합니다.

### 공통 ###

* [Visual Studio Code](https://code.visualstudio.com/#alt-downloads)
* [Azure CLI](https://docs.microsoft.com/ko-kr/cli/azure/install-azure-cli)
* [Azure Functions CLI](https://github.com/Azure/azure-functions-core-tools)
* [Azure 무료 구독](https://azure.microsoft.com/ko-kr/free/)
* [GitHub 계정](https://github.com)
* [Docker Hub 계정](https://hub.docker.com)
* [AppVeyor 계정](https://ci.appveyor.com)


### 윈도우 ##

* [.NET Core SDK 2.1 for Windows](https://www.microsoft.com/net/download/windows)
* [Windows Subsystem for Linux (WSL): Ubuntu](https://docs.microsoft.com/ko-kr/windows/wsl/install-win10)
* [Docker for Windows](https://docs.docker.com/docker-for-windows/install/)
* [Docker 와 WSL 연결](https://blog.aliencube.org/ko/2018/04/11/running-docker-and-azure-cli-from-wsl/)

> *NOTE*: WSL 에도 리눅스용 .NET Core SDK 와 Azure CLI 를 설치해야 합니다.


### 맥 ###

* [.NET Core SDK 2.1 for Mac](https://www.microsoft.com/net/download/macos)
* [Docker for Mac](https://docs.docker.com/docker-for-mac/install/)


### 리눅스 ###

* [.NET Core SDK 2.1 for Linux](https://www.microsoft.com/net/download/linux)
* [Docker](https://www.docker.com/community-edition#/download)

## Abstract
One of benefits using serverless architecture is "no need to worry about infrastructure management". On the other hands, container technology is about "no need to worry about setting up infrastructure". They are two different directions of evolving cloud services. Now, they get together and play together. Actually they get along each other quite seamlessly.

At the end of this session, audiences will learn 1) why we need containers for serverless applications, 2) how this is possible in Azure Functions, and 3) how to deploy Azure Functions with a Docker container.

