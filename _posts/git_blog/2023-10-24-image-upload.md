---
title: "2. Image uploading w/ Typora"
author_profile: true # 내 프로필을 보여줄지 말지.
categories: # 복수로 가능하다 하지만 1개로 설정
    - Git Blog
tags:        # 태그는 복수로 설정 해도 괜찮다
    - Image
sidebar:   
    nav: "counts"
typora-root-url: ../
---



# 준비물

- Typora



Typora는 마크다운 기반의 글쓰기 보조 서비스입니다.

​	노션에 익숙한 저로써는 노션처럼 글을 쓸 수 있게 해주는 Typora를 이용했습니다.

Typora는 이미지 삽입및 글 편집을 편하게 하기에 쓰는 편입니다.

![Tortoise_Fred](/images/2023-10-24-image-upload/Tortoise_Fred.jpg)
# 쓰는 법



1. 먼저 Typora를 맞는 OS에 따라 설치를 한다.

2.  Typora를 Git Clone한 폴더를 열어 폴더를 봅니다.

   



3.  그리고 환경 설정으로 들어가

   - 이미지 탭에서![image-20231025105347798](/images/2023-10-24-image-upload/image-20231025105347798.png)

      - 위의 그림이 기본 설정에서 바뀐 점은 파일 경로가 바뀌었습니다.

       ./${filename} 에서 점을 추가 위에 images/ 파일에 넣을 것이다 라는 의미로

       ../images/${filename}으로 설정할 수 있습니다.

     - images 는 꼭 images가 아니라 원하는 이름으로 폴더를 만들어 주면 된다.

   
   
## 오류 
   
   
   
   -  하지만 카테고리를 우리가 추가하면서 이미지가 깨지게 되는 경우가 있다.
   
     - 무언가 경로가 꼬이면서 상대경로 만으로는 표시가 안되는 것이다.

   ![image-20231025105014289](/images/2023-10-24-image-upload/image-20231025105014289.png)



   - 그렇다면? 어떻게 해결하면 되는 것인가?
   
     1.  먼저 이미지 하이퍼 링크에서 ../을 빼주면, typora에서는 깨져보일 수 있으나, 페이지에서는 잘 보이는게 보인다.

![image-20231025104640643](/images/2023-10-24-image-upload/image-20231025104640643.png)



​	2. 우리 페이지 설정 부분에서 "typora-root-url: ../" 을 추가해 준다.

   ![image-20231025105529517](/images/2023-10-24-image-upload/image-20231025105529517.png)

