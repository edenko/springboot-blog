<h1 align="center">Welcome to springboot-blog 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-0.5.0-blue.svg?cacheSeconds=2592000" />
  <img alt="License" src="https://img.shields.io/badge/License-MIT-yellow.svg"/>
</p>

> Springboot simple blog project
> (현재 local 동작 상태, AWS EC2 세팅 중, AWS RDS 연결 중)

## Requirements
* Java 17.0
* Springboot 2.1.7
* JUnit4
* JPA
* JSP

## Skills
* JUnit : 테스트 자동화
* Lombok : 코드 간략 표현
* JPA Auditing : 생성 및 수정 시간 관리
<!-- * Dirty Checking : Update시 쿼리를 날리지 않음
* OAuth 2.0 : 구글 및 네이버 로그인 -->

## App Structure
```bash
node-express/
├── package-lock.json
├── package.json
├── server.js
├── router
│   ├── main.js
└── views
    ├── chat.ejs
    └── write.ejs
```

## List of API Endpoints
```sh
+--------+-------------------------+
  Method | URI
+--------+-------------------------+
  GET    | /
  GET    | /login
  POST   | /login
  GET    | /write
  POST   | /add
  GET    | /list
  DELETE | /delete
  GET    | /detail/id
  GET    | /edit/id
  PATCH  | /edit/id
+--------+-------------------------+
```

## Features
* 블로그 기능 (Posts)
  * 게시글 조회
  * 게시글 등록
  * 게시글 수정
  * 게시글 삭제
* Spring Security
  * OAuth2 Client 사용하지 않고 Kakao login 구현

<!-- ## Screens -->

## Author
👤 **HaYoung Ko**

* Github: [@edenko](https://github.com/edenko)
* email: goodeden3@gmail.com
