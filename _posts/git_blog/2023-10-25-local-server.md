---
title:  "[Git Hub] Local server"
author_profile: false # 내 프로필을 보여줄지 말지.
categories:  # 복수로 가능하다 하지만 1개로 설정
  - Git Blog
tags:        # 태그는 복수로 설정 해도 괜찮다.
  - local server 
last_modified_at: 2023-10-25T00:00:00-00:20   # 마지막 수정일
sidebar: 
    nav: "counts"
---

# Local Server에 적용하기

  

  

  

## Update gem 파일

- 이전 두 글에서 서버 생성과 이미지를 올리는 방법을 배웠다면, 이번에는 올린 것들을 실제 서버에서는 어떻게 적용이 되었는지 확인하는 것을 할 것이다.

  

- 우리는 저번에 cmd에 ```gem install jekyll bundle ```   명령어를 이용해 지킬과 번들을 설치 했다.
  - 이제 설치한 번들안에 들어 있는 플러그인들을 설치해줘야 한다.
    1. 먼저 cmd의 경로를 블로그 폴더로 이동한다.
    2.  ```bundle install``` 를  cmd에 명령어를 입력해준다.



  

  

---

  

  

## Local server 구동

- 이젠 우리가 적용한 것들을 확인할 서버를 구동한다.

  1. 명령어로 ```bundle exec jekyll server```  를 명령어를 입력한다.

     - 위 명령어는 로컬 서버를 구동하는 명령어

       ![image-20231025173825171](/images/2023-10-25-local-server/image-20231025173825171.png)
     

  2. 정상 구동이 된다면 서버가 돌고 있다는 글을 볼 수 있다.
     ![image-20231025174005058](/images/2023-10-25-local-server/image-20231025174005058.png)

       

       

     - 하지만 가끔 오류가 있다.

     - 이렇게  'webrick'이 없다는 오류가 뜬다면

       -> ```bundle add webrick```을 명령어 에 입력 해준다.

       <img src="/images/2023-10-25-local-server/image-20231025174127355.png" alt="image-20231025174127355" style="zoom:150%;" />

     - 이제 그럼  다시 서버 구동 명령어를 입력해준다. 그럼 정상으로 작동할 것이다.

  

  



그럼 이제 우리가 로컬 파일에 입력하는 것들은 실시간으로 로컬 서버에 적용되는 모습을 볼 수 있다.

---

```
개인 공부 기록용 블로그입니다.
틀린 부분은 댓글로 소통 & 지적 해주시면 감사하겠습니다!!!
```
