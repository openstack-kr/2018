---
layout: session2
order: 1
title: "Invited Talk: A Day in the Java Developer’s Life, with a Taste of Kubernetes"
rowspan: 2
track:
  - Room E5
time: "09:30 ~ 09:55" # for column 2
duration: 50분
speakers:
  - name: "Arun Gupta (Principal Open Source Technologist)"
    org: AWS
    desc: "
Arun Gupta is a Principal Open Source Technologist at Amazon Web Services. He focuses on everything open source, containers and serverless at AWS. He is responsible for the CNCF strategy within AWS, and participates at CNCF Board and technical meetings actively. He has built and led developer communities for 12+ years at Sun, Oracle, Red Hat and Couchbase. Prior to that he led engineering teams at Sun and is a founding member of the Java EE team.

He has extensive speaking experience in more than 40 countries on myriad topics and is a JavaOne Rock Star for four years in a row. Gupta also founded the Devoxx4Kids chapter in the US and continues to promote technology education among children. An author of several books on technology, an avid runner, a globe trotter, a Java Champion, a JUG leader, NetBeans Dream Team member, and a Docker Captain, he is easily accessible at @arungupta.
          "
    image: ../assets/imgs/Arun.jpg
---

## Overview

Deploying your Java application in a Kubernetes cluster could feel like Alice in Wonderland. You keep going down the rabbit hole and don’t know how to make that ride comfortable. This no-slide and code-only session will explain how a Java application consisting of different microservices can be deployed in a Kubernetes cluster. Specifically, it will explain the following: 

-Show a Java application with three microservices 
-How this application is packaged as a Docker image 
-Create Kubernetes manifests 
-How Helm charts are created and hosted in a Helm repository 
-Test in a local environment such as minikube 
-Attach debugger (may need to find out if tooling exists in this area) 
-Install Istio in k8s, show service visibility 
-Install k8s on AWS -Migrate application from a local cluster to a cluster in the Cloud 
-Setup deployment pipeline -Use an Alexa skill to scale the application 
-Change application, show A/B using Istio
