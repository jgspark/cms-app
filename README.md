## CMS (Contents Management System)

게시판, 레이아웃, 모듈과 같은 기능을 모아둔 웹 프레임워크이다.<br/>
CMS를 사용하면 클릭 한번으로 사이트를 만들 수 있다.<br/>
게시판 관련 기능 같은 기본적인 작업을 자동화시키기 때문에 웹 사이트 제작에 드는 시간이 많이 감소된다.<br/>
그만큼 개발속도로 빨라진다.<br/>
기본적으로 파일/썸네일/캐시/등 프레임워크 단위의 도구가 있기 때문에 새로운 기능을 만들 때도 간단하게 구현이 가능하다.<br/>

-------

## Runbook 

- clone 

git clone --recurse-submodules https://github.com/Gon-Zo/cms-app.git
 
## 개발환경 

###### `Spring Boot 2.3.x` `Java8` `Intellij` `Spring Security` `JPA` 

##### `Postgresql` `Logback` `Gradle` `React` `Webpack` `Git`

-------

## 구현기능 
 1. 회원 기능
    - 구글 로그인
    - 페이스북 로그인
2. 게시판 CMS 기능
    - 게시글 관리 (조회,삭제)
    - 댓글 관리 (조회,삭제)
    - 게시판 관리 (조회,생성,수정,삭제)
3. 기본 게시판 기능
    - [번호, 제목, 내용, 글쓴이, 시간, 조회수] 정보를 가진 게시글
    - 등록, 수정, 삭제 기능 및 권한 처리(내가 쓴 글만 수정, 삭제 가능)
    - 글자 수 제한(10000자)
    - 이미지(jpg, png, gif) 업로드 기능
    - 임시 저장 기능
    - 좋아요
    - 댓글 글자 수 제한(140자)
    - 계증형 댓글 기능(대댓글 까지)
4. 보안 (tag,script 입력 필터링)
5. 관리 페이지 
    - 큰 카테고리 / 작은 카테고리 관리
    - 게시판 관리 
    - 댓글 관리 
    - 유저 관리 


-------

#### 출처
* CMS 정의 : [https://namu.wiki/w/CMS](https://namu.wiki/w/CMS)
