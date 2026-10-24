# 김대영 | Backend Developer

제가 가진 기술로 사람들의 하루에 더 많은 웃음을 더하는 개발자를 지향합니다.

Java와 Spring Boot를 중심으로 백엔드 시스템을 개발하고 있습니다.  
단순히 기능을 구현하는 것을 넘어, 실제 사용자가 안정적으로 사용할 수 있는 서비스를 만드는 데 관심이 있습니다.

이를 위해 동시성, 데이터 정합성, 메시징, 장애 대응과 같은 실제 서비스에서 발생할 수 있는 문제를 고민하고 해결하며 백엔드 개발 역량을 쌓아가고 있습니다.

## Tech Stack

**Backend**
- Java, Spring Boot, Spring Security, JPA

**Database & Messaging**
- MySQL, Redis, Kafka

**Frontend**
- React, TypeScript, Next.js

**Infra**
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

- Fail-Open / Fail-Closed 전략 비교
- DB Fallback / DB Verification 전략 구현
- Redis 장애 및 Redis-MySQL 불일치 시나리오 검증
- k6 기반 성능·보안성·가용성 비교 실험

[Repository](https://github.com/eodud9/jwt-revocation-research)
