# ✒ MOVA

#### 웹툰 커뮤니티, 팬아트 서비스
#### 링크: https://mo-va.site/
![mova main](https://user-images.githubusercontent.com/113073174/210253267-852c4c7d-81d4-46cf-8826-283d52110b05.png)


<br/>

## 1. 제작 기간, 맡은 역할

- 기간: 2022년 11월 30일 ~ 12월 28일

- 역할

  - 웹툰 정보 크롤링(Selenium, Chromedriver, BeautifulSoup)
  - 배포 및 운영(AWS EC2, AWS Route53, Docker, Docker compose, Gunicorn, Nginx, Postgresql)
  - 프론트 연동 및 프론트 배포 진행(AWS S3, AWS CloudFront, AWS route53)

  
## 2. 사용 기술
  
  > Backend
  
    - Python
    - Django
    - DjangoRestFramework
    - Django simple JWT
    - Dj-rest-auth
    - django-allauth
     
    
  > Database
      
    
  
    - PostgreSQL
        
    
  > Infra
  
    - AWS EC2
    - AWS Route 53
    - AWS CloudFront
    - AWS S3
    - Docker
    - Docker compose
    - Nginx
    - Gunicorn
      
    
  > Frontend
    
    - Vanilla JS
    - html
    - css
    - toast UI
        
    
  > Management
  
    - Git/Github
    - Notion
    - Slack
    
  
    
 ## 3. 주요 기능
  
- 게시글 작성/수정/삭제 및 검색 기능
- 게시글 작성/수정 시 웹툰, 게시글 카테고리 기능
- [Colorization_tool_on_web](https://github.com/yangco-le/Colorization_Tool_on_Web)을 활용한 팬아트 기능


## 4. Architecture

![mova_art](https://user-images.githubusercontent.com/113073174/210240826-dd23a2bf-212c-4128-9bfa-062a1600c7e5.png)



## 5. ERD 설계


   ![mova_erd](https://user-images.githubusercontent.com/113073174/210240686-8703f3df-64b8-4de7-94d9-28b57e5c18a8.jpg)



## 6. API 설계

  - Postman 활용하여 만든 api 명세서

    https://documenter.getpostman.com/view/24027867/2s8Z6x2Z38
    
  
## 7. 핵심 트러블 슈팅 및 피드백


### 트러블 슈팅

- 이미지 고용량 업로드 해결 문제
- 비밀번호 초기화 이메일 인증 시 url 오류
- user Delete 중 오류

### 피드백

- 소셜 로그인

[Wiki로 이동](https://github.com/marinred/MOVA_BACKEND/wiki/%ED%8A%B8%EB%9F%AC%EB%B8%94-%EC%8A%88%ED%8C%85-%EB%B0%8F-%ED%94%BC%EB%93%9C%EB%B0%B1)

 
 
 ## 9. 회고 및 느낀점
 
 - 피드백을 받으면서, 팀에서 놓치고 있었던 부분이 많았다는 생각이 들었습니다.
 - 고객들의 중점에서 불편한 것이 있지 않도록 하는 것이 제일 중요하다고 생각이 들었습니다.
 - 로컬 환경과 실제 배포 환경을 다름을 확인하고 배포 전 필요한 사항들을 확인해야겠다고 생각했습니다.
 
> [프로젝트 개발 회고 게시물](https://velog.io/@marinred/%EB%82%B4%EC%9D%BC%EB%B0%B0%EC%9B%80%EC%BA%A0%ED%94%84-%EC%B5%9C%EC%A2%85%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EC%A4%91%EA%B0%84%EB%B0%9C%ED%91%9C-K.P.T)
