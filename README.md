# 안녕하세요 👋

안녕하세요, 김대영입니다.  
제가 가진 기술로 사람들의 하루에 더 많은 웃음을 더하는 개발자를 지향합니다.

단순히 코드를 작성하는 것을 넘어, **사람들에게 필요한 문제를 발견하고 기술로 해결하는 일**에 가치를 두고 있습니다.  
더 나은 방법과 새로운 가능성을 고민하며, 아이디어를 구현하는 데 필요한 기술이라면 주저하지 않고 배우고 도전합니다.

## Tech Stack

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%234479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/apachekafka-%23231F20.svg?style=for-the-badge&logo=apachekafka&logoColor=white)

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Next JS](https://img.shields.io/badge/Next-%23000.svg?style=for-the-badge&logo=next.js&logoColor=white)

![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23232F3E.svg?style=for-the-badge)

## Projects

### 1. ResourceHub
**공유 자원 예약 및 관리 백엔드 시스템**

- Spring Security와 JWT 기반 인증·인가 구현
- 비관적 락을 통한 예약 동시성 제어
- Redis Cache-Aside 및 트랜잭션 커밋 이후 캐시 무효화
- Kafka, Transactional Outbox, Consumer 멱등성 및 Retry/DLT 구현
- Docker와 AWS 기반 배포 및 GitHub Actions CI/CD 구성

**Tech Stack:** Java, Spring Boot, MySQL, Redis, Kafka, Docker, AWS

[GitHub Repository](https://github.com/eodud9/resource-hub)

### 2. JWT Revocation Research
**Redis 기반 JWT 폐기 검증의 장애 대응 및 데이터 일관성 비교 연구**

- Fail-Open, Fail-Closed, DB Fallback, DB Verification 전략 설계·구현
- Redis 장애와 Redis–MySQL 불일치 상황을 구분한 E1~E4 실험 수행
- Redis 장애 시 DB Fallback으로 정상 토큰 요청 성공률 100%, 폐기 토큰 오허용률 0% 관찰
- DB Verification으로 데이터 불일치 시 폐기 토큰 오허용률 0% 달성, 성능 비용 정량 분석

**Tech Stack:** Java, Spring Boot, MySQL, Redis, Docker, k6

[GitHub Repository](https://github.com/eodud9/jwt-revocation-research)

### 3. Connected Vehicle Backend Platform
**차량 데이터 수집 및 운행 상태 관리를 위한 백엔드 플랫폼 — 개발 진행 중**

- 차량별 API Key 인증과 사용자 JWT 인증 체계 분리
- Telemetry 수집 및 최신 차량 상태 조회
- 시동 상태 변화에 따른 운행 세션 관리
- 배터리·온도·주행 이상 이벤트 처리
- 향후 부하 측정과 병목 분석을 바탕으로 아키텍처 개선 예정

**Tech Stack:** Java, Spring Boot, Spring Security, JPA, MySQL

[GitHub Repository](https://github.com/eodud9/connected-vehicle-platform)
