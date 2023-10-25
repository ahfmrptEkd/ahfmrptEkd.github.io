---
title: "[Git Hub] 블로그 세팅"
categories: # 복수로 가능하다 하지만 1개로 설정
    - Git Blog
tags:        # 태그는 복수로 설정 해도 괜찮다
    - setting
sidebar:   
    nav: "counts"
last_modified_at: 2023-10-25T00:00:00-00:30
typora-root-url: ../..
sidebar:
    nav: "counts"
---

<br>

# [Git Hub] blog setting 블로그 세팅

# Config setting
---

  

  

- 폴더 안에는 테마의 설정을 관리하는  _config.yml 이 있다.
  - 기본 설정들을 관리하는 파일이다.

  

  



## 스킨 (테마) 바꾸기

![image-20231025190045973](/images/2023-10-25-blog-setting/image-20231025190045973.png)

- _config.yml 파일 안에  위 항목은 블로그 전체적인 스킨 바꿀 수 있다. 
  - minimal mistakes의 제작자가 만든 스킨들로 10개 중에 골라 " " 안에 넣으면 된다.

  

<br/>

---

<br>

## 페이지 세팅



![image-20231025192223363](/images/2023-10-25-blog-setting/image-20231025192223363.png)

- locale = 지역 

  - 한국의 경우 "ko-KR" 을 이용하면 된다.

- title = 브라우저의 탭부분에 나타나는 이름

  - 엄연히 masthead_title과는 다른 것. (통일 추천해)

    ![image-20231025190945411](/images/2023-10-25-blog-setting/image-20231025190945411.png){: .align-center}

- subtitle = 부 제목 같은 역할

  ![image-20231025191253824](/images/2023-10-25-blog-setting/image-20231025191253824.png){: .align-center}

- name = 소유주의 이름

- description = 페이지의 부연설명

- url = 블로그의 url

  - 이 부분은 링크의 모든 루트 역할을 하므로 꼭 틀리지 않게 확인해야 한다.

- repository = 블로그의 기반이 되는 레포지토리를 넣어준다.

- logo = 탭에서의 아이콘 모양을 담당
- masthead_title = 블로그 상단에 표기되는 이름
- breadcrumbs = 상단의 표기되는 포스팅의 경로? 같은것을 표기한다.![image-20231025194035100](/images/2023-10-25-blog-setting/image-20231025194035100.png)
- words_per_minutes = 글을 읽는데 소요되는 시간을 표기 한 것.

![image-20231025192259458](/images/2023-10-25-blog-setting/image-20231025192259458.png){: .align-center}

---



<br>

### logo 넣기

![image-20231025194238745](/images/2023-10-25-blog-setting/image-20231025194238745.png){: .align-center}

나는 내 logo.png를 assets 폴더에 따로 넣어서 경로를 위와 같이 설정을 해주었다.

- 경로는 루트(깃 블로그 폴더)을 기준으로 설정해주면 된다.

  - 깃 블로그 폴더 안에 바로보이는 공간이 루트 공간
    - 그 안에 보이는 폴더 assets에 넣었다.

  ![image-20231025194507840](/images/2023-10-25-blog-setting/image-20231025194507840.png){: .align-center}

---

<br>



##  Site Author

![image-20231025192715041](/images/2023-10-25-blog-setting/image-20231025192715041.png)

- 블로그의 프로필에 해당하는 부분이다.

- author

  - 이 부분에서 프로필들을 채워 넣어준다.
  - name = 이름
  - avatar = 프로필의 사진이 될 부분
  - bio = 간단한 나의 설명
  - location = 지역을 의미한다.
  - links = 하이퍼 링크 만들 수 있는 부분
    - 원하는 링크의 이름을 label에 적고
    - url 에 링크를 달아놓을 수 있다.  (아이콘은 추후에 블로그에 포스팅할 예정)

---

<br>

## Defaults

<img src="/images/2023-10-25-blog-setting/image-20231025194816123.png" alt="image-20231025194816123" style="zoom:80%;" />{: .align-center}

- _config.yml에는 default 설정들이 있는데 이 부분들은 **page 와 post** 에 기본설정으로 줄 수 있는 공간이다.
- 페이지의 설정은 페이지 클래스 안에 포스트는 포스트 클래스 안에 설정한다. (사실 type으로 구분 된다.)

---

<br>

### 날짜 표기

- "show_date: " 를 적어주면, 포스트의 작성일자가 보이게 된다.

#### 날짜 표기 방법

![image-20231025195118940](/images/2023-10-25-blog-setting/image-20231025195118940.png)

날짜 표기는 위 사진의 포맷팅을 참고하면 되지만, 그냥 전형적인

``` date_format: "%Y-%m-%d"``` 을 사용해도 무방하다.

---

```
개인 공부 기록용 블로그입니다.
틀린 부분은 댓글로 소통 & 지적 해주시면 감사하겠습니다!!!
```



