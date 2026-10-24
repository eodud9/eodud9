# 안녕하세요 👋

안녕하세요, 김대영입니다.  
제가 가진 기술로 사람들의 하루에 더 많은 웃음을 더하는 개발자를 지향합니다.

단순히 코드를 작성하는 것을 넘어, **사람들에게 필요한 문제를 발견하고 기술로 해결하며 세상에 기여하는 일**에 가치를 두고 있습니다.  
현재의 방식에 머무르기보다 더 나은 방법과 새로운 가능성을 고민하고, 아이디어를 실제로 구현하는 데 필요한 기술이라면 주저하지 않고 배우고 도전합니다.

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
