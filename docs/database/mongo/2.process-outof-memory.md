---
layout: default
title: process-outof-memory 에러
description: "node 버전 변경으로 해결 (brew)"
permalink: /database/mongo/2/
grand_parent: Database
parent: mongo
nav_order: 2
---

MongoDB 설치 후 아래와 같은 에러가 발생하였다.<br/>

<img width="1138" alt="스크린샷 2022-10-29 오전 12 11 23" src="https://user-images.githubusercontent.com/59944155/198677715-cdc1f665-b867-4952-b38e-5c603d5aa09b.png">   

관련 내용을 찾아보니 node 버전 문제로 확인되어 brew를 이용하여 버전을 변경하였다.

:point_right: node 버전 확인

    node -v

:point_right: brew를 이용하여 node 버전 변경

    # 노트버전 조회
    brew search node
    # 노드 설치 
    brew install node@14
    # 노드 링크 
    brew link node@14


