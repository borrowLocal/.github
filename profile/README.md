## 📌 프로젝트 개요

**바로로(borrowLocal)**

  사용자가 필요한 물건을 가까운 지역에서 손쉽게 대여하고 반납할 수 있도록 설계된 지역 기반 대여 서비스입니다. 

* 개발 기간: 2025.03 ~ 2025.06 (약 3개월)
* 참여 인원: 프론트엔드 1명, 백엔드 2명

## 🎯 주요 기능

* 회원 관리: 회원가입, 로그인, 회원정보 수정, 회원탈퇴
* 물품 관리: 물품 등록, 대여 및 반납
* 이용 내역 조회
* 즐겨찾기 기능 (물품 즐겨찾기 추가/삭제)
* 대여 후기 작성 및 관리
* 카테고리/사용자 위치/검색 기반 필터링

## 🛠️ 기술 스택

### Frontend

* React 19, React Router DOM 7
* Axios
* CSS (모듈 방식, 파일 분리 import)
  
### Backend

* Spring Boot
* Swagger API Docs

### Tools

* Notion, Figma

## 🖥️ 실행 방법

### Frontend

```bash
cd frontend
npm install
npm start
```

### Backend

```bash
cd backend

```

## 📂 레포지토리 구조

* [frontend 레포](https://github.com/borrowLocal/frontend)
* [backend 레포](https://github.com/borrowLocal/backend-SpringBoot)

## 📸 구현 화면
👉 자세한 구현 화면은 [프론트엔드 레포지토리](https://github.com/borrowLocal/frontend) README를 참고해주세요.

## 🧑‍🤝‍🧑 팀 소개 & 역할

- [프론트엔드 A](https://github.com/pyqvv)  
  전체 UI 설계 및 구현, CSS 스타일링, 백엔드 API 연동

- [백엔드 A](https://github.com/Ss-HhJin)  
  대여/반납, 신고/리뷰, 물품 관리, 이메일 기능 구현, Swagger API 문서 작성

- [백엔드 B](https://github.com/Ubokchi)  
  ERD 설계 및 DB 구조 정의, 회원 관리 기능 구현


## 🚀 배포 주소

* API 문서: 

## ⚡ 트러블슈팅 & 개선점

* **문제**: Spring Boot 프로젝트에서 Swagger UI 접근 시 500 내부 서버 오류 발생

  * **해결**: Swagger 라이브러리 버전 업그레이드 (pom.xml 내 swagger 의존성 버전 변경 2.7.0 및 재빌드)

### 앞으로의 개선점

* 사용자 인증 강화: 비밀번호 암호화 및 강력한 비밀번호 정책 도입
* 알림 기능: 반납 기한 등을 알려주는 리마인더 제공
* 커뮤니케이션 기능: 유저 간 대여 거래를 지원하는 1:1 채팅
* 결제 기능: 실제 결제 서비스와의 연동

