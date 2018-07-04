---
layout: session1
order: 7
title: "FreeIPA 이용한 SSO"
track: Track 4
time: "15:50 ~ 16:20"
duration: 30분
speakers:
  - name: 송상준
    org: 서진디에스에이
    desc: "
	      1999년 부터 Novell eDirectory Server부터 시작하여 Netscape Directory Server(LDAP)서버 구축을 시작하여
	      현재 전세계 존재하는 모든 Directory Server(LDAP)를 구축 컨설팅하는 일을 담당하고 있습니다. LDAP구축 뿐만
	      아니라 LDAP연동할 수 있는 모든 S/W를 발굴하여 이를 연동할 수 있는 방법을 제시해 드리고 있습니다.
	      최근에는 Cloudera Hadoop을 LDAP에 계정/그룹 연동하는 작업을 하였고, 다음 연동 소프트웨어로 OpenShift, Kubernetes
	      ,Keystone을 고민해 보고 있습니다.
	      "
    image: ../assets/imgs/송상준.jpg
materials:
  - https://www.slideshare.net/openstack_kr/openinfra-days-korea-2018-track-4-freeipa-sso
---

## 개요

1. FreeIPA 구성
2. FreeIPA 이용방안(OS계정통합, Windows AD 연동: Sync or Trust) : 동영상 데모
3. Kerberos를 이용한 SSH/ApacheWeb Single Sing On : 동영상 데모
4. FreeIPA ->Identity Provier(Idp)->Apache(mod_auth_mellon:SAML) 연동 방안
