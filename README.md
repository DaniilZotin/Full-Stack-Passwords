<br />
<div align="center">
  <a href="https://github.com/DaniilZotin/Spring-users-system">
    <img src="Images/usense-logo.png" alt="Logo" width="100" height="120">
  </a>

<h3 align="center" >Full stack passwords system</h3>

</div>

## Introduction
Hi, this repo has full stack project to show and analyze password.


## About the project
A system for working with passwords that has endpoints:

$\color{#55AE5B}{{GET}}$  /api/passwords/all - Show all passwords in the system<br/>
$\color{#FF0000}{{DELETE}}$ /api/passwords/delete/all - Delete all passwords<br/>
$\color{#E3C678}{{POST}}$ /api/passwords/create - Create new password<br/>

## Build with
* [![ANGULAR][ANGULAR]][ANGULAR-url]
* [![TS][TS]][TS-url]
* [![HTML][HTML]][HTML-url]
* [![CSS][CSS]][CSS-url]
* [![Spring][Spring]][Spring-url]
* [![Docker][Docker]][Docker-url]
* [![OpenJDK][OpenJDK]][Docker-url]
* [![POSTGRESQL][POSTGRESQL]][POSTGRESQL-url]

## Preview
### Detect password level
#### App
![image](https://github.com/DaniilZotin/Full-Stack-Passwords/assets/85665335/5e33cca1-4126-4385-8ba4-7a8c19102097)



### Get all passwords after login 
#### 1. Postman
![image](https://github.com/DaniilZotin/Full-Stack-Passwords/assets/85665335/74545f36-5d52-4230-a44c-7ff6b99f2e90)

#### 2. App
![image](https://github.com/DaniilZotin/Full-Stack-Passwords/assets/85665335/a029e302-80c4-48a7-b32b-04bcf0e91ac1)



### Get all passwords after login when DB do not has advertisement
#### 1. App
![image](https://github.com/DaniilZotin/Full-Stack-Passwords/assets/85665335/6361389e-5185-4b2e-94db-2ac1883e20e2)
#### 2. Postman
![image](https://github.com/DaniilZotin/Full-Stack-Passwords/assets/85665335/e41e1388-21da-45c7-aa3f-e9ad57cc7997)



## Set up
### 1. Clone the repo of backend
```sh
    https://github.com/DaniilZotin/Back-end-Spring-Analytics.git
```
### 2. Up Docker
```sh
     docker-compose up --build
```
### 3. You can use port 8094 to check app in postman
### 4. Clone the repo of frontend
```sh
    https://github.com/DaniilZotin/Front-end-React-Analytics.git
```
### 5. Build project(frontend)
### 6. Start app
```sh
    npm start
```































[Spring]: https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white
[Spring-url]: https://spring.io/projects/spring-framework

[Docker]: https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white
[Docker-url]: https://www.docker.com/

[OpenJDK]: https://img.shields.io/badge/OpenJDK-000000?style=for-the-badge&logo=openjdk&logoColor=white
[OpenJDK-url]: https://www.docker.com/

[POSTGRESQL]: https://img.shields.io/badge/postgresql-4169E1?style=for-the-badge&logo=postgresql&logoColor=white
[POSTGRESQL-url]: https://www.docker.com/

[ANGULAR]: https://img.shields.io/badge/angular-E8E8E8?style=for-the-badge&logo=angular&logoColor=black
[ANGULAR-url]: https://www.docker.com/

[TS]: https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white
[TS-url]: https://www.docker.com/

[HTML]: https://img.shields.io/badge/html-E34F26?style=for-the-badge&logo=HTML5&logoColor=white
[HTML-url]: https://www.docker.com/

[CSS]: https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white
[CSS-url]: https://www.docker.com/
