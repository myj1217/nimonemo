# NIMONEMO

✔ N잡을 희망하는 직장인 이용자들이 취미를 부업화하고 일정한 소득을 얻게 하는 플랫폼 서비스 입니다. <br>
✔ 직장인 이용자들이 곧 작은 사업자가 되어 소상공인 서포트 프로젝트를 함께 진행하고 있습니다. <br>

📽 시연 영상 : 추후 제공 예정입니다. <br>

<br>

## 1. 제작 기간 & 참여 인원

- 2024.03.05~2024.03.25
- 4명

<br>

## 2. 기술 스택

- Java 17
- Spring Boot 3.2.3
- Spring Web MVC 6.1.5
- Spring Security 3.2.4
- Spring data JPA 3.2.4
- MySQL 8.0.3

- react 18.2.0
- react-redux 9.1.0
- reduxjs/toolkit 2.2.1
- tensorflow-models/mobilenet 2.1.1
- tailwindcss 3.4.1

<br>

## 3. 주요 기능

| 상품 이미지 분석 서비스

- 검색을 원하는 이미지를 업로드하면 이미지를 분석하여 키워드 추출 후 검색까지 자동으로 진행

| 챗봇 서비스

- 사용자가 원하는 정보를 키워드만 입력해도 챗봇에서 관련 답변을 제공하여 사용자에게 보다 빠른 정보 제공

| 커뮤니티 서비스

- 검색에도 원하는 상품을 찾지 못할 경우 커뮤니티 게시판에 공유하여 사용자들끼리 정보를 공유하는 공간 제공
- 게시글을 등록, 조회, 수정, 삭제할 수 있으며 이미지 또한 게시글 안에서 함께 등록, 조회, 수정, 삭제 할 수 있습니다.

| 회원관리 서비스

- 회원 가입, 탈퇴가 가능합니다.
- 이메일을 통해 로그인하며, 회원 정보 수정이 가능합니다.
- 회원가입 시 입력한 이메일로 인증코드를 발송하여 비밀번호 찾기 기능을 이용할 수 있습니다.

<br>

## 4. 개체-관계 모델(ERD)

![erd](https://github.com/myj1217/nimonemo/assets/76141799/29cdc16b-aa85-4b72-a3ea-a1bde367a836)

## 5. 개발 팀 소개

| 조민영 (Team Leader, https://github.com/myj1217)

- 메인 페이지 구현
- 상품리스트 페이지 및 등록, 조회, 수정, 삭제 기능 구현
- 장바구니 페이지 및 선택 상품 주문 기능 구현

| 김경목 (https://github.com/0221kmac)

- 회원가입, 로그인, 마이페이지, 회원정보 수정 페이지 및 기능 구현
- 로그인, 로그아웃, 소셜로그인 기능 구현
- 토큰 검증을 통한 계정 데이터베이스 구현
- 상품 검색 및 결과창 페이지 구현
- 페이지 정보 상단바, 챗봇 버튼, 스크롤업 버튼 구현
- 권한 확인 페이지, 404 Error 페이지 구현

| 박광휘 (https://github.com/jy02145709)

- BasicMenu 페이지 구현
- 상품 이미지 분석 기능 구현
- 챗봇 기눙 구현
- 고객센터 페이지 구현
- 월간 아티스트 페이지 구현
- 회원가입, 로그인, 마이페이지 페이지 구현
- 로딩 페이지 구현

| 천하늘 (https://github.com/soundspeedskye)

- 커뮤니티 게시판 등록, 조회, 수정, 삭제 페이지 및 기능 구현
- 결제 기능 구현
- 결제창, 주문화인 모달 창 페이지 구현
- 문서작업 일체
