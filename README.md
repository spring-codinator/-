# 프로젝트

## ⚙️ 개발 환경(Development Environment)

|---|---|
| 운영체제 | Windows 10 64bit |
| 개발도구 | Intellij Ultimate, Gradle |
| 프레임워크 | Spring Boot 2.7.0, Spring Security(OAuth2.0) |
| 개발 언어 | Java 11 |
| 데이터베이스 | Maria DB Server |
| 버전 관리 | Github, Git |
| 배포 및 운영 | Ubuntu 20.04 LTS, Docker, Github Actions |

## 📝 요구사항 분석(Requirements analysis)
관리자(Master)
* 한명의 관리자는 여러명의 회원을 조회할 수 있다.
* 
회원(User)
* 회원 가입을 할 수 있다.
  *  
* 기존 회원은 회원 탈퇴를 할 수 있다.
* 로그인을 할 수 있다.
* 소셜 로그인을 할 수 있다.
팀(Team)
게시판(Board)
* 작성자는 게시글에 대한 작성, 수정, 삭제가 가능하다.
* 관리자는 게시글에 대한 작성, 수정, 삭제가 가능하다.
  *  
* 작성자에 작성한 회원의 이름이 표시된다.
* 글을 작성한 시간이 표시된다.
* 관리자와 회원은 댓글을 작성할 수 있다.
* 게시물을 삭제하면 달려있는 댓글들이 모두 삭제된다.
* 한명의 회원은 여러개의 게시판을 작성할 수 있다.
* 제목, 내용, 이미지를 올릴 수 있다.

공지사항(Notice)
* 관리자는 공지사항에 대한 수정과 삭제가 가능하다.
* 작성자에 관리자가 표시된다.
* 글을 작성한 시간이 표시된다.
* 제목, 내용, 이미지를 올릴 수 있다.
* 한명의 관리자는 여러개의 공지사항을 작성할 수 있다.

## 📝 도메인 모델 분석(Domain Model Analysis)

관리자(Master)
회원(User)
팀(Team)
게시판(Board)
