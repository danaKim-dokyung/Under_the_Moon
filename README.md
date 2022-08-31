
# 월하합작: 전국 8도 명주를 찾아서


1. 프로젝트 개요
    - 한국 전통주 온라인 판매가 허용됨에 따라 전통주 수요가 증가함
    - 또한, 코로나19 거리두기로 인해 Home술, 혼술은 선택이 아닌 필수가 됨
    - 이에 따라 만 19세 이상 회원에 한해 판매가 이루어지는 온라인 전통주 쇼핑몰 서비스를 기획함
    
2. 설계의 주안점 (프로젝트 결과 탭을 참조해주세요!)
    - Git 커밋메세지 및 Naming 컨벤션을 설정한다.
    - 개발프로세스로는 칸반을 사용한다.
    - 오픈소스를 활용한다.
    - MVC 패턴으로 개발한다.
    - Spring Security로 권한을 관리한다.

3. 프로젝트 진행 기간
    - 2021-1-12 ~ 2021-02-09 : 총 29일
    
4. 월하합작 팀의 Workspace  <a href="https://angry-capacity-44d.notion.site/FINAL-Project-10356e5988474b5fa69612ca56c19e7f">바로가기</a>
    
    
<br/> <br/> 

## 1. 기술 스택


1. Backend 
    - Tomcat 8.5
    - Spring MVC
    - Spring Security
    - MyBatis
    - Java11

1. Database
    - Oracle - SQLDeveloper
    
2. Server 
    - AWS

1. Frontend
    - Javascript
    - Jquery
    - JSTL
    - Gson

1. Collaboration tool 
    - Git and Github
    - Notion
    - Slack
    - Figma


<br/> <br/> 

## 2. ERD 명세서



- 상세 보기를 원하시면 아래 Url을 참고해주세요.
    ![Untitled](https://user-images.githubusercontent.com/83184270/184530044-5e15923d-c3fd-43c0-9f44-f528a6a2f11d.png)

    [https://www.erdcloud.com/d/wdNtYArwPCWpBgcAj](https://www.erdcloud.com/d/wdNtYArwPCWpBgcAj)
    

<br/> <br/> 


## 3. 담당 주요 구현 기능



1. 회원가입
- Ajax 통신을 통한 휴대폰 인증 기능
- 휴대폰 인증 기능
    - 오픈소스 문자 전송 API 활용
- 생년월일 정규표현식

2. 문의 기능
- User 권한 사용자
    - 1:1 문의기능 작성 시 본인 작성 게시글만 조회
    - 게시글 상세 조회는 Ajax로 구현
    - 게시글 삭제
- Admin 권한 사용자
    - 전체 문의글 조회
    - 게시글 삭제
    - 답변 작성
    - 답변 삭제

3. 오픈 소스 활용
- 휴대폰 인증 구현 시 문자 전송 API 활용
- 지역별 전통주 종류 개수를 카카오지도 API 를 활용해 클러스터로 나타냄

<br/> <br/> 

## 4. 프로젝트 결과


1) 월하합작 프로젝트 

- [http://3.37.11.69/](http://3.37.11.69/)

2) Git 커밋메세지와 Naming 컨벤션을 설정한다.  


![Untitled](https://user-images.githubusercontent.com/83184270/184530166-44d5f9ad-ae31-41fb-a949-286a81041279.png)



- 컨벤션에 관한 자세한 사항은 아래 Notion 페이지를 참고해주세요!

3) 개발프로세스로는 칸반을 사용한다. 

- 자세한 사항은 월하합작팀 Notion 을 통해 확인하실 수 있습니다.

4) 오픈소스를 활용한다. 

- 휴대폰 문자 전송 API
    - 회원가입 시 사용자의 휴대폰 번호가 유효한지 검증하는 로직을 구현함
    - 아이디 찾기 시 휴대폰 인증을 통해 본인확인 하는 로직을 구현함
- 카카오결제 API
    - 결제 시 카카오결제와 일반 카드 결제로 구분해서 구현함
- 카카오지도 API
    - 지역별 전통주 입점 수량을 클러스터로 지도에 나타냄
    
<br/> <br/> 


## 5. 참고 사항



월하합작 팀의 컨벤션 및 회의록 등, 개발 세부 진행사항을 확인하고 싶다면 

아래 Notion 링크를 참조해주세요 ! 

- 월하합작: 전국 8도 명주를 찾아서, <a href="https://angry-capacity-44d.notion.site/FINAL-Project-10356e5988474b5fa69612ca56c19e7f">Notion 바로가기</a>

<br/> <br/> 
