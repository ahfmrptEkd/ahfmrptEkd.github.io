---
title:  Image uploading w/ Typora
author_profile: false # 내 프로필을 보여줄지 말지.
categories: 카테고리 # 복수로 가능하다 하지만 1개로 설정
    - Git Blog
tags:       태그 # 태그는 복수로 설정 해도 괜찮다
    - Image
sidebar:   
    nav: "counts"
---

![Tortoise_Fred](../images/2023-10-24-image upload/Tortoise_Fred.jpg)

# 준비물

- Typora



Typora는 마크다운 기반의 글쓰기 보조 서비스입니다.

​	노션에 익숙한 저로써는 노션처럼 글을 쓸 수 있게 해주는 Typora를 이용했습니다.

Typora는 이미지 삽입및 글 편집을 편하게 하기에 쓰는 편입니다.



# 쓰는 법



1. 먼저 Typora를 맞는 OS에 따라 설치를 한다.

2.  Typora를 Git Clone한 폴더를 열어 폴더를 봅니다.

   <img src="../images/2023-10-24-image upload/image-20231024212115354.png" alt="image-20231024212115354" style="zoom: 80%;" />



3.  그리고 환경 설정으로 들어가

   - 이미지 탭에서

      <img src="../images/2023-10-24-image upload/image-20231024212312915.png" alt="image-20231024212312915" style="zoom: 80%;" />

     - 위의 그림이 기본 설정에서 바뀐 점은 파일 경로가 바뀌었습니다.

       ./${filename} 에서 점을 추가 위에 images/ 파일에 넣을 것이다 라는 의미로

       ../images/${filename}으로 설정할 수 있습니다.

     - images 는 꼭 images가 아니라 원하는 이름으로 폴더를 만들어 주면 된다.
