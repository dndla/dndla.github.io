---
layout: default
title: MongoDB 생성하기
description: "MongoDB Atlas 무료버전 생성"
permalink: /database/mongo/1/
grand_parent: Database
parent: mongo
nav_order: 1
---
* 
{:toc}

MongoDB Atlas 서비스를 이용하여 DB를 생성해보려고 합니다.   

## Cluster 생성

회원 가입 후 `new project`를 클릭하여 프로젝트를 생성한 뒤
MongoDB Database 화면에서 `Build a database`를 클릭하여 DB를 생성합니다.   

<img width="1431" alt="스크린샷 2022-10-28 오후 10 55 32" src="https://user-images.githubusercontent.com/59944155/198627545-b3bcbafd-1eea-4c38-a6dc-e97bf016cf9d.png">

무료로 제공하는 공유버전 `Shared`를 선택하여 줍니다.    

<img width="1440" alt="스크린샷 2022-10-28 오후 10 59 54" src="https://user-images.githubusercontent.com/59944155/198634345-9bd7b714-4ec9-4f20-8c63-3bbb33547eb1.png">

`create` 를 클릭한 뒤 provider 와 region을 선택합니다. 
이번에 새로 생성하면서 서울이 무료버전에 추가되었더라구요, 그래서 전 서울로 선택하였습니다.

그리고 클러스터 이름을 테스트로 'dev-node'로 넣어준뒤 생성을 클릭하였습니다.   

<img width="1431" alt="스크린샷 2022-10-28 오후 11 00 25" src="https://user-images.githubusercontent.com/59944155/198632027-85e508bc-6525-4409-8d32-b73b1245aff7.png">

## User 생성

클릭하게 되면 클러스터가 생성되면서 유저를 생성할수 있도록 제공합니다. 
평상시 쓰던 username, password로 유저를 생성하여 주었습니다.   
<span style="background-color: #fff5b1">사진에는 .을 포함하였는데 username 명명규칙에 어긋나서 wooim 이라고 생성하였습니다..!</span>   

<img width="1431" alt="스크린샷 2022-10-28 오후 11 03 42" src="https://user-images.githubusercontent.com/59944155/198632005-bb67df17-b96b-4695-bd24-7a2de1bf00d3.png">


## Cluster 생성 완료

<img width="1395" alt="스크린샷 2022-10-28 오후 11 11 18" src="https://user-images.githubusercontent.com/59944155/198637185-8cef1414-15be-45c1-8e07-40f7c25115a2.png">
