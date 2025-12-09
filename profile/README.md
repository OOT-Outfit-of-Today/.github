# OOT (Outfit of Today)

> **옷의 새로운 여정, 오늘 당신이 이어주세요!**

---

## 1. 팀원 소개

| | | | |
|---|---|---|---|
| **팀원** | **역할** | **담당 기능" | **기술 스택** |
| 지나 | Backend | 인증/인가, 사용자 관리, 판매글, 채팅, 결제 | Spring Security, JWT, WebSocket, Toss Payments |
| 병수 | Backend | 옷장 관리, 옷 등록, 추천, 위치 검색, 대시보드 | Spring Batch, Redis, Kakao Maps API |

---

## 2. 프로젝트 개요

**개발 기간:** 2025년 10월 13일 ~ ✓

`OOT(Outfit of Today)`는 사용자가 **디지털 옷장을 관리**하고, **중고 의류를 거래**할 수 있는 플랫폼입니다.

자주 입지 않는 옷의 기부 또는 판매를 추천하여 의류 순환을 통해 환경 보호에 기여합니다.

### 주요 특징
- **회원 기반 서비스**: 옷장 관리, 중고 거래는 회원 전용 기능
- **비회원 접근**: 공개 옷장 및 중고 거래 게시물 조회 가능
- **직거래 기반**: 모든 중고 거래는 사용자 간의 직거래 방식
- **독립적 거래**: 옷장 서비스를 이용하지 않아도 거래 참여 가능

---

## 3. 주요 기술 스택

### **애플리케이션**
![Java](https://img.shields.io/badge/Java%2017-007396?style=for-the-badge&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring%20Data%20JPA-6DB33F?style=for-the-badge&logo=spring&logoColor=white)

### **인증 및 보안**
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)

### **메시징 및 비동기 처리**
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=for-the-badge&logo=socketdotio&logoColor=white)

### **데이터베이스**
![MySQL](https://img.shields.io/badge/MySQL%208.0-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### **CI/CD**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

### **클라우드 및 모니터링**
![AWS EC2](https://img.shields.io/badge/AWS%20EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white)
![AWS RDS](https://img.shields.io/badge/AWS%20RDS-527FFF?style=for-the-badge&logo=amazonrds&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS%20S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-F46800?style=for-the-badge&logo=grafana&logoColor=white)

### **External API**
![Google OAuth](https://img.shields.io/badge/Google%20OAuth-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Kakao Maps](https://img.shields.io/badge/Kakao%20Maps-FFCD00?style=for-the-badge&logo=kakao&logoColor=black)
![Toss Payments](https://img.shields.io/badge/Toss%20Payments-0064FF?style=for-the-badge&logo=v&logoColor=white)

### **협업 도구**
![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)
![Swagger](https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white)

---

## 4. 서비스 플로우

1. **옷장 생성 및 옷 등록**  
   사용자가 디지털 옷장을 생성하고 보유 중인 옷을 등록합니다.

2. **착용 기록 추적**  
   옷을 착용할 때마다 기록이 자동으로 업데이트됩니다.

3. **미착용 옷 자동 감지**  
   1년 이상 입지 않은 옷을 배치 작업으로 자동 감지합니다.

4. **판매/기부 추천**  
   감지된 옷에 대해 판매 또는 기부를 추천합니다.

5. **거래 진행**  
   사용자 간 직거래 또는 기부를 통해 의류를 순환시킵니다.

---

## 5. 시스템 아키텍처

> 추후 아키텍처 다이어그램 추가 예정

---

## 6. ERD

> 추후 ERD 다이어그램 추가 예정

---

## 7. API 명세

- **Swagger UI**: [개발 서버 Swagger](http://3.36.121.187:8080/api/swagger-ui/index.html)

---

## 8. 레포지터리 구조

| Repository | 설명 |
|------------|------|
| **OOT-Outfit-of-Today** | 메인 서버 애플리케이션 (Auth, User, Closet, Clothes, SalePost, Chat 등 핵심 도메인) |
| **OOT-Batch** | 통계 집계, 추천 데이터 전처리, 정기 작업 등을 수행하는 배치 서버 |
| **OOT-Common** | 공통 DTO, 유틸, 도메인·에러 코드 등 공유 모듈 |
| **OOT-Monitoring** | 로그/메트릭 수집, 대시보드 설정 등 모니터링 관련 레포 |

---

## 9. 주요 기능

### 🔐 인증/인가
- 일반 로그인 및 소셜(구글) 로그인 지원
- 멀티 디바이스 로그인 관리 (최대 5개)

### 👔 옷장 관리
- 디지털 옷장 생성 및 옷 등록
- 착용 기록 자동 업데이트
- 1년 이상 미착용 옷 자동 감지 및 추천

### 🛍 판매글
- 중고 의류 거래 게시글 작성 및 관리
- 카테고리·상태·키워드 기반 검색

### 💬 채팅
- 판매자와 구매자 간 1:1 실시간 채팅

### 📍 위치 기반 기부처 검색
- 반경 5km 이내 의류 기부처 실시간 검색 (Kakao Map API)

### 📊 대시보드
- 사용자 및 관리자용 통계 집계 및 시각화
- Redis 캐싱을 통한 빠른 응답

---

## 📮 Contact

- **프로젝트 기간**: 2025년 10월 13일 ~ 2025년 11월 18일
- **팀 노션**: [OOT 팀 노션](https://www.notion.so/teamsparta/6-OOT-2862dc3ef5148073a3fbcf5014ebf307)
- **Swagger API**: [개발 서버 Swagger](http://3.36.121.187:8080/api/swagger-ui/index.html)
- **GitHub Organization**: https://github.com/OOT-Outfit-of-Today
