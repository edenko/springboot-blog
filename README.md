<h1 align="center">Welcome to springboot-blog π</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-0.5.0-blue.svg?cacheSeconds=2592000" />
  <img alt="License" src="https://img.shields.io/badge/License-MIT-yellow.svg"/>
</p>

> Springboot simple blog project
> (νμ¬ local λμ μν, AWS EC2 μΈν μ€, AWS RDS μ°κ²° μ€)

## Requirements
* Java 17.0
* Springboot 2.1.7
* JUnit4
* JPA
* JSP

## Skills
* JUnit : νμ€νΈ μλν
* Lombok : μ½λ κ°λ΅ νν
* JPA Auditing : μμ± λ° μμ  μκ° κ΄λ¦¬
<!-- * Dirty Checking : Updateμ μΏΌλ¦¬λ₯Ό λ λ¦¬μ§ μμ
* OAuth 2.0 : κ΅¬κΈ λ° λ€μ΄λ² λ‘κ·ΈμΈ -->

## App Structure
```bash
node-express/
βββ package-lock.json
βββ package.json
βββ server.js
βββ router
β   βββ main.js
βββ views
    βββ chat.ejs
    βββ write.ejs
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
* λΈλ‘κ·Έ κΈ°λ₯ (Posts)
  * κ²μκΈ μ‘°ν
  * κ²μκΈ λ±λ‘
  * κ²μκΈ μμ 
  * κ²μκΈ μ­μ 
* Spring Security
  * OAuth2 Client μ¬μ©νμ§ μκ³  Kakao login κ΅¬ν

<!-- ## Screens -->

## Author
π€ **HaYoung Ko**

* Github: [@edenko](https://github.com/edenko)
* email: goodeden3@gmail.com
