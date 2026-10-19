# 김대영 | Backend Developer

Java와 Spring Boot를 중심으로 백엔드 개발을 공부하고 있습니다.  
기능 구현을 넘어 동시성, 데이터 정합성, 메시징, 장애 대응과 같은
실제 서비스의 문제를 이해하고 해결하는 데 관심이 있습니다.

## Tech Stack

- Java, Spring Boot, Spring Security, JPA
- MySQL, Redis
- Kafka
- Docker, AWS, GitHub Actions

## Projects

### ResourceHub
공유 자원 예약 및 관리 서비스

- 비관적 락을 활용한 예약 동시성 제어
- Redis Cache-Aside 및 캐시 정합성 처리
- Kafka 기반 비동기 이벤트 처리
- Transactional Outbox Pattern
- AWS 배포 및 CI/CD 구축

[Repository](https://github.com/eodud9/resource-hub)

### JWT Token Revocation under Storage Failure
Redis 기반 JWT 폐기 검증 시스템의 장애 대응 전략 비교 연구

- Fail-Open / Fail-Closed
- DB Fallback / DB Verification
- Redis 장애 및 Redis-MySQL 불일치 시나리오
- k6 기반 성능·보안성·가용성 비교 실험

[Repository](https://github.com/eodud9/jwt-revocation-research)
