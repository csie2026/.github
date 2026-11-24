
<div align="center">

  <img src="./assets/ToPeak_bg.png" width="120" alt="ToPeak Logo" />

  # ToPeak

  ### 기록하고 즐겁게 오르는 방법

  경기도의 새로운 산을 발견하고, 산행을 기록하며 성장하는 등산 서비스

  🏆 **2026 컴퓨터정보공학부 학술제 인기상 (4등)**

  **Team FiveGuys**

  <img src="https://img.shields.io/badge/Frontend-React-61DAFB?style=flat-square&logo=react&logoColor=white" />
  <img src="https://img.shields.io/badge/Backend-Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/Database-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Infrastructure-AWS-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white" />

</div>

---

## 🏔️ 프로젝트 소개

**ToPeak**은 경기도의 다양한 산을 지역 중심으로 탐색하고,
GPS 기반 산행 기록을 점수 및 랭킹으로 연결하여
지속적인 등산 참여를 유도하는 경기도 특화 등산 서비스입니다.

등산 입문자도 주변의 산과 코스를 쉽게 발견할 수 있으며,
다양한 산을 방문하고 꾸준히 산행하는 과정에서 성취감을 느낄 수 있도록 설계하였습니다.

- 경기도 산 **140개**, 등산 코스 **420개** 데이터 구축
- 권역 및 시·군 기반의 단계적 산 탐색
- GPS 기반 산행 기록 및 활동 검증
- 산행 다양성과 빈도를 중심으로 한 점수 및 랭킹
- AWS 기반 서비스 배포 및 CI/CD 구축

### 서비스 핵심 흐름

**지역 탐색 → 산·코스 선택 → GPS 산행 → 기록 → 점수 및 랭킹 → 새로운 산 탐색**

---

## 🏆 수상 실적

| 구분 | 내용 |
| :--- | :--- |
| 대회명 | 2026 컴퓨터정보공학부 학술제 |
| 프로젝트 | ToPeak |
| 참가팀 | FiveGuys |
| 수상 | 인기상 (4등) |

---

## ✨ 주요 기능

| 기능 | 설명 |
| :--- | :--- |
| 소셜 로그인 | Google 및 Kakao OAuth 2.0 기반 로그인 |
| 지역별 산 탐색 | 경기도 4개 권역 및 시·군별 산 탐색과 검색 |
| 등산 코스 조회 | 코스 길이, 난이도, 예상 소요 시간 및 지도 제공 |
| 산행 날씨 | 기상청 단기예보 API 기반 산행 전 날씨 확인 |
| GPS 산행 기록 | 이동 경로, 거리, 활동 시간, 평균 속도 및 완등 여부 기록 |
| 등산일지 | 실제 산행 기록 기반 일지 작성 및 공개·비공개 관리 |
| 점수 및 랭킹 | 산행 다양성과 빈도 기반 점수 산정 및 사용자 순위 제공 |
| 월간 목표 | 월별 산행 횟수 및 거리 목표 설정과 달성률 확인 |
| 마이페이지 | 개인 산행 통계, 활동 기록 및 프로필 관리 |

---

## 🎯 서비스 차별성

### 지역 중심의 산 탐색

산 이름을 알고 있어야 하는 검색 방식뿐만 아니라,
경기도 권역과 시·군을 단계적으로 선택하며
새로운 산을 발견할 수 있는 탐색 환경을 제공합니다.

### 다양성과 꾸준함을 중심으로 한 경쟁

산행 속도나 산의 높이보다 다양한 산의 방문과
꾸준한 산행 활동에 가치를 부여합니다.

등산 입문자도 부담 없이 경쟁에 참여할 수 있도록
점수 및 랭킹 시스템을 설계하였습니다.

### 실제 활동과 기록의 연결

GPS 기반 산행 활동과 등산일지를 구분하여 관리하며,
저장된 활동을 기반으로 개인 통계와 점수를 산정합니다.

---

## 🛠️ 기술 스택

### Frontend

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)

### Backend

![Java](https://img.shields.io/badge/Java_21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_4.1.1-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)

### Database & Data

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

### Infrastructure & DevOps

![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white)
![AWS RDS](https://img.shields.io/badge/AWS_RDS-527FFF?style=for-the-badge&logo=amazonrds&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Let's Encrypt](https://img.shields.io/badge/Let's_Encrypt-003A70?style=for-the-badge&logo=letsencrypt&logoColor=white)

### External API

- Kakao Maps JavaScript SDK
- Google OAuth 2.0
- Kakao OAuth 2.0
- 기상청 단기예보 API
- Web Geolocation API

---

## 🏗️ 시스템 아키텍처

<div align="center">
  <img src="./assets/ToPeak_시스템_아키텍처_최종.png" width="100%" alt="ToPeak 시스템 아키텍처" />
</div>

- React 및 TypeScript 기반 SPA
- Spring Boot 기반 REST API 서버
- OAuth 2.0 및 서버 세션 기반 인증
- Spring Security 기반 CSRF 보호 및 접근 제어
- PostgreSQL 기반 서비스 데이터 관리
- Flyway 기반 데이터베이스 스키마 및 초기 데이터 관리
- Nginx 기반 정적 파일 제공 및 리버스 프록시

---

## ☁️ AWS 배포 및 CI/CD

<div align="center">
  <img src="./assets/아키텍쳐_파이브가이즈.png" width="100%" alt="ToPeak AWS 배포 아키텍처" />
</div>

AWS 서울 리전(ap-northeast-2)을 기반으로
프론트엔드와 백엔드를 배포하고 관리형 데이터베이스를 연동하였습니다.

- Amazon EC2 기반 애플리케이션 운영
- Amazon RDS PostgreSQL 기반 데이터베이스 운영
- Nginx 및 Let's Encrypt 기반 HTTPS 환경 구축
- GitHub Actions 기반 자동 테스트 및 빌드
- Self-hosted Runner 기반 자동 배포
- 백엔드 Health Check 및 Rollback 구성
- systemd 기반 백엔드 서비스 관리

---

## 📊 데이터 구축

산림청 및 OpenStreetMap의 등산로 데이터와
Copernicus DEM 고도 자료를 활용하여
경기도 특화 등산 데이터베이스를 구축하였습니다.

| 구분 | 구축 내용 |
| :--- | :--- |
| 산 데이터 | 140개 |
| 등산 코스 데이터 | 420개 |
| 데이터 처리 | Python 기반 정제 및 가공 |
| 코스 난이도 | 고도 및 코스 길이 기반 산정 |
| 데이터 적재 | Seed SQL 및 Flyway Migration |

### 데이터 처리 과정

**원천 데이터 수집 → 데이터 정제 → 좌표·경로 가공 → SQL 생성 → PostgreSQL 적재**

### 데이터 출처

- [산림청](https://www.forest.go.kr/)
- [OpenStreetMap Contributors (ODbL)](https://www.openstreetmap.org/copyright)
- Copernicus DEM

---

## 📱 서비스 UI / UX

<div align="center">
  <img src="./assets/최종UI_파이브가이즈.png" width="100%" alt="ToPeak 서비스 최종 UI" />
</div>

---

## 📂 Repositories

ToPeak은 역할과 책임에 따라 4개의 독립된 저장소로 구성되어 있습니다.

| Repository | Description |
| :--- | :--- |
| [**FE**](https://github.com/csie2026/FE) | React 및 TypeScript 기반 프론트엔드 |
| [**BE**](https://github.com/csie2026/BE) | Spring Boot 기반 백엔드 및 REST API |
| [**DATA**](https://github.com/csie2026/DATA) | 산·등산로 데이터 수집, 정제 및 가공 |
| [**DOCS**](https://github.com/csie2026/DOCS) | 서비스 기획안, API 명세서 및 기술 문서 |

---

## 📚 프로젝트 문서

- [서비스 기획안 및 프로젝트 문서](https://github.com/csie2026/DOCS)
- [API 명세서](https://github.com/csie2026/DOCS)
- [프론트엔드 구현 및 실행 안내](https://github.com/csie2026/FE)
- [백엔드 구현 및 실행 안내](https://github.com/csie2026/BE)
- [데이터 구축 및 처리 과정](https://github.com/csie2026/DATA)

---

## 🤝 협업 및 개발 관리

- GitHub Organization 기반 저장소 관리
- GitHub Issues 기반 작업 및 이슈 관리
- 기능별 브랜치 분리
- Pull Request 기반 코드 리뷰 및 병합
- GitHub Actions 기반 테스트 및 빌드 검증
- 서비스 기획안 및 API 명세서 기반 개발

---

## 👥 Team FiveGuys

2026 컴퓨터정보공학부 학술제 프로젝트

<div align="center">

  <img src="./assets/ToPeak_bg.png" width="60" alt="ToPeak Logo" />

  **ToPeak — 기록하고 즐겁게 오르는 방법**

  Copyright © 2026 Team FiveGuys.

</div>
