# 📚 개발 지식 체계 (전체 구성 초안)

소프트웨어 엔지니어로 성장하기 위한 개발 지식 체계를 정리하고 관리하기 위한 저장소입니다.
- 각 카테고리는 소프트웨어 엔지니어링을 기반으로 핵심 역량을 모듈별로 분리하여 구성
- 이론부터 설계, 구현, 운영, 협업까지 전체 흐름을 포괄

---

[1. Computer Science](#-1-computer-science)  
[2. 소프트웨어 엔지니어링](#-2-소프트웨어-엔지니어링)  
[3. 백엔드 개발](#-3-백엔드-개발)  
[4. DevOps & 인프라](#%EF%B8%8F-4-devops--인프라)  
[5. 시스템 설계 & 성능](#%EF%B8%8F-5-시스템-설계--성능)  
[6. 보안](#-6-보안)  
[7. 프론트엔드 기초](#-7-프론트엔드-기초-백엔드-관점)  
[8. 협업 & 커뮤니케이션](#-8-협업--커뮤니케이션)  
[9. 도메인 모델링 & 아키텍처](#-9-도메인-모델링--아키텍처)  
[10. 수학 & 통계](#-10-수학--통계)  

---
<br>

## 🧠 1. Computer Science

> 개발의 본질을 이해하고 문제 해결 능력을 키우기 위한 이론들로,  
> 코딩 테스트, 기술 면접, 성능 분석 및 시스템 디버깅 등에서 요구되는 역량

### 🎯 **기준**

- 개발자라면 반드시 이해하고 있어야 하는 **이론적 기반**들
    
- 언어나 프레임워크와 무관하게 공통적으로 작동하는 원리
    
### 📌 구성 의도

- 문제 해결 능력, 성능 분석, 시스템 이해의 기초
    
- 면접, 코딩 테스트, 성능 트러블슈팅 대응

### 💡 예시

- 운영체제 (프로세스, 메모리, 동기화)
    
- 네트워크 (TCP/IP, HTTP, DNS, CORS 등)
    
- 컴퓨터 구조 (CPU, 캐시, 파이프라인)
    
- 자료구조 & 알고리즘 (시간복잡도, DFS/BFS, 힙 등)
    
- 데이터베이스 이론 (정규화, 트랜잭션, 인덱스, 동시성 제어)
    
- 컴파일러 기초 (파싱, 바이트코드, 인터프리터)


<br>

---
<br>

## 🛠 2. 소프트웨어 엔지니어링

> 소프트웨어를 **체계적이고 지속 가능하게 개발하기 위한 사고 방식과 절차**들로,  
> 요구사항 분석부터 설계, 구현, 테스트, 배포, 유지보수까지의 전 과정을 포함

### 🎯 **기준**

- **프로세스 중심**: 소프트웨어 생명주기 전체를 아우르는 개발 원칙/문화/관리
    

### 📌 구성 의도

- 품질 있는 소프트웨어를 **팀으로, 지속적으로, 책임 있게** 만들기 위한 기반 역량
    
- 협업, 요구사항 분석, 테스트, 코드 품질 등 “비코딩 역량” 포함
    
### 💡 예시

- 개발 방법론 (애자일, 스크럼, TDD, DevOps 문화)
    
- 요구사항 분석 / 사용자 스토리
    
- 테스트 전략 / QA 협업
    
- 설계 원칙 (SOLID, KISS, DRY 등)
    
- 형상 관리 / Git 전략
    
- 릴리즈 & 배포 전략 (버전 전략, Blue-Green)
    
- 유지보수 전략 / 기술 부채 / 변경 영향 분석
    
- 사용자 중심 설계 / 피드백 루프
    

<br>

---
<br>

## 🌐 3. 백엔드 개발

> 웹 기반 애플리케이션의 서버 측 로직 구현을 위한 기술들로,  
> API, DB 처리, 인증, 예외 처리 등을 중심으로 구성

### 🎯 **기준**

- **웹 기반 서비스의 서버 측 개발에 필요한 전반적인 기술스택**
    

### 📌 구성 의도

- Spring을 중심으로, **백엔드 실전 구현 역량** 축적
    
- 인증, 예외 처리, REST API 설계, 파일 처리 등 포함
    
### 💡 예시

- Java / Kotlin 언어 기초
    
- Spring Boot / Spring Data / Spring Security
    
- REST API / 상태 코드 / 인증 인가
    
- 예외 처리, 로그, 트랜잭션, @Transactional
    
- 페이징 / 정렬 / 검색 / 파일 업로드
    
- API 버전 관리, 멀티모듈 설계
    
- 스케줄링 / WebSocket
    

<br>

---
<br>

## ⚙️ 4. DevOps & 인프라

> 코드가 안정적으로 배포되어 **운영 환경에서 서비스될 수 있도록** 하기 위한 인프라/운영 역량

### 🎯 **기준**

- **서비스가 배포되고 운영되는 환경을 자동화/관측/관리**하는 기술들
    

### 📌 구성 의도

- 코드만이 아니라 **실제로 서비스가 안정적으로 동작하게 만들기 위한 운영 역량**
    
- Docker, Kubernetes, AWS, CI/CD, 모니터링 포함
    
### 💡 예시

- CI/CD (GitHub Actions, ArgoCD)
    
- Docker / Dockerfile / Compose
    
- Kubernetes (Pod, Service, ConfigMap, Helm)
    
- AWS (EC2, RDS, S3, IAM, VPC)
    
- Terraform / IaC / LocalStack
    
- Secret 관리 (sealed-secret, Vault 등)
    
- GitOps / 상태 동기화
    

<br>

---
<br>

## 🏗️ 5. 시스템 설계 & 성능

> 확장성과 유지보수성을 고려한 **고수준 구조 설계 및 성능 개선 전략**으로,  
> 대규모 시스템 설계, 트래픽 대응, 장애 복원력 확보 등에서 필요한 역량

### 🎯 **기준**

- 고수준 구조 결정 및 **성능 최적화 전략**을 다루는 영역
    
- MSA, API Gateway, Rate Limit, CQRS 등 포함
    

### 📌 구성 의도

- 확장성 있고, 장애에 강하고, 유지 가능한 시스템을 만드는 역량
    
- 실무 설계/기술 면접, 트래픽 대응, 병목 분석 대응

### 💡 예시

- 아키텍처 스타일 (Monolith, MSA, Serverless)
    
- API Gateway, Load Balancer, Rate Limiting
    
- CQRS / Event Sourcing
    
- 정규화 vs 비정규화, 1:N / N:M 관계 설계
    
- 데이터 파티셔닝, 샤딩, 레플리케이션
    
- GC 튜닝 / JFR / Thread Dump 분석
    
- 부하 테스트 (k6, JMeter), 성능 지표 해석
    

<br>

---
<br>

## 🔐 6. 보안

> **안정적이고 신뢰성 있는 서비스**를 제공하기 위한 보안 역량

### 🎯 **기준**

- 서비스의 **신뢰성과 안전성 확보**를 위한 요소들
    

### 📌 구성 의도

- 애플리케이션/인증/클라우드 보안 실무 대응
    
- API 보안, HTTPS, OAuth2, IAM 등

### 💡 예시

- XSS / CSRF / SQL Injection
    
- HTTPS / TLS / 인증서 체계
    
- JWT / OAuth2 흐름
    
- IAM / 최소 권한 정책 / 비밀 키 관리
    
- CSP, 보안 헤더, CORS 정책
    

<br>

---
<br>

## 🖥 7. 프론트엔드 기초 (백엔드 관점)

> API 설계 및 통신 연동에 필요한 **클라이언트 측 지식**으로,  
> 백엔드 개발자에게도 필수적인 이해 요소

### 🎯 **기준**

- 백엔드 엔지니어가 반드시 이해해야 하는 **클라이언트 동작 원리와 통신 구조**
    

### 📌 구성 의도

- CORS, 쿠키, HTTP 흐름 등 API 설계 관점에서 필요한 클라이언트 이해
    
- 비동기 요청, 상태 관리 개념도 일부 포함

### 💡 예시

- HTTP 요청/응답 흐름 / fetch / async-await
    
- CORS / Preflight / 쿠키 처리
    
- SPA vs SSR vs SSG
    
- Form 전송 방식, 상태 관리 개념
    
- 브라우저 렌더링 원리
    

<br>

---
<br>

## 🗣 8. 협업 & 커뮤니케이션

> **팀과 함께 일하는 개발자**가 되기 위해 필요한 역량으로,  
> 코드 리뷰, 문서화, 기술 공유, 커뮤니케이션을 포함

### 🎯 **기준**

- **코드 외의 협업 역량** (PR, 회고, 기술 설명, 문서화)
    

### 📌 구성 의도

- 함께 일할 수 있는 개발자가 되기 위한 **태도와 실전 역량**
    
- 리뷰 작성, 회의 리딩, 기술 공유 등

### 💡 예시

- Git 브랜치 전략 / 커밋 메시지
    
- Pull Request 작성법 / 코드 리뷰 가이드
    
- 회의 리딩 / 비개발자 대상 기술 설명
    
- 기술 블로그 / 지식 공유 / 회고
    

<br>

---
<br>

## 🧱 9. 도메인 모델링 & 아키텍처

> **복잡한 도메인을 올바른 구조로 설계**하기 위한 철학과 기술로,  
> DDD, Clean Architecture 등 시스템의 뼈대를 다루는 역량

### 🎯 **기준**

- 복잡한 비즈니스 요구를 **정제된 도메인 모델과 구조로 설계**하는 역량
    

### 📌 구성 의도

- DDD, Clean/Hexagonal Architecture, Bounded Context 등 포함
    
- 설계 철학 + 구현 구조 연결

### 💡 예시

- Entity / Value Object / Aggregate
    
- Bounded Context / Context Mapping
    
- 유비쿼터스 언어 / Event Storming
    
- 식별자 설계 / 불변성 / 의도 중심 모델링
    
- 계층형 vs Hexagonal 구조 비교
    

<br>

---
<br>

## 📊 10. 수학 & 통계

> 성능 분석, 데이터 기반 판단, 알고리즘 이해 등에 필요한 기초 수리 역량

### 🎯 **기준**

- 성능 분석, 지표 해석, AI/데이터 응용 등에 필요한 **기초 수리 능력**
    

### 📌 구성 의도

- 로그 스케일, 평균/표준편차, Big-O 시각화 등
    
- SLI/SLO 지표, 히스토그램 기반 성능 해석 등에 활용
    
### 💡 예시

- 평균 / 표준편차 / 분산 / 히스토그램
    
- 백분위수 / 로그 스케일 / 지수적 성장
    
- Big-O 분석 / 시간 복잡도 시각화
    
- 지표 기반 성능 해석 (SLO/SLI/SLA)
    
<br>

---
