# blog-management
Java + 디자인 패턴_블로그 게시물 관리 프로그램

## 프로젝트 소개
**디자인 패턴을 활용한 블로그 게시물 관리 시스템입니다.**

## 개발 기간
- 23.08.03 - 23.08.23

### 개발 환경

---
- Java
- IDE: Intellij

### 사용한 디자인 패턴

---
1. 데코레이터 패턴

    블로그 게시물 관리 시스템의 여러 기능들인
    **댓글 기능, 좋아요 기능, 태그 기능** 구현


2. 팩토리 패턴

    각 유형의 게시물(일반 글, 이미지 게시물, 동영상 게시물) 객체를
    생성하는 기능을 구현하기 위해 사용

    클라이언트 코드에서는 팩토리 클래스에 객체 생성 역할을 위임


3. 커맨드 패턴
    
    게시물에 대한 **저장, 삭제 기능**에 대한 실행을 커맨드 클래스에 캡슐화