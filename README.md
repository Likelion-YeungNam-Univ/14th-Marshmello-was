<h1>🌸 품결</h1>

<p align="center">
  <img
    width="100%"
    alt="품결 대표 이미지"
    src="https://github.com/user-attachments/assets/d343422c-3416-4ba1-92c3-65cfa0314e00"
  />
</p>

> ## 🖇️ https://www.marshrnello.cloud

---

## 🌷 서비스 소개

튼살 관리 정보는 많지만,<br />
**“지금 나에게 무엇이 필요한지”를 판단하는 일은 여전히 사용자의 몫입니다.**

품결은 사용자가 매번 정보를 찾고 자신의 상태를 판단하는 대신,<br />
임신 주차와 피부 변화, 관리 기록을 지속적으로 연결해 **오늘 해야 할 케어를 제안합니다.**

매일의 체크인을 통해 피부 변화를 기록하고, 케어카드로 관리 행동을 안내하며,<br />
이전 케어에 대한 피드백을 다음 관리에 반영합니다.

즉, 품결은 한 번의 질문에 답하는 서비스가 아니라<br />
**기록 → 케어 → 피드백 → 다음 케어가 이어지는 임신 기간의 지속적인 피부 관리 서비스**입니다.

---

## 🔎 Problem

<img
  width="100%"
  alt="문제 정의"
  src="https://github.com/user-attachments/assets/93681a4b-dae0-43d4-845f-bf1f595cca6b"
/>

<img
  width="100%"
  alt="페인포인트"
  src="https://github.com/user-attachments/assets/c02464c6-2acb-4e68-a8cf-d94574307b77"
/>

<br />

---

## 💡 Solution

### 01. 정보를 찾는 대신, **오늘 해야 할 케어를 제안합니다**

임신 주차와 현재 피부 상태를 바탕으로 필요한 정보를 선별하고,<br />
단순한 정보 제공에 그치지 않고 **오늘 바로 실천할 수 있는 케어 행동으로 연결합니다.**

→ `흩어진 정보 속 판단 불가` 해결

### 02. 매일의 변화를 기록해 **관리해야 할 순간을 놓치지 않게 합니다**

피부 사진과 바디맵, 체크인 기록을 지속적으로 쌓아<br />
사용자가 스스로 알아채기 어려운 피부 변화를 확인할 수 있도록 합니다.

기록된 상태를 바탕으로 **오늘 어떤 부위를 더 신경 써야 하는지 케어카드로 안내**해,<br />
“지금 관리해야 할까?”를 혼자 판단해야 하는 부담을 줄입니다.

→ `관리 시점을 놓치는 불안` 해결

### 03. 관리의 결과보다 **꾸준히 이어온 과정을 보여줍니다**

매일의 피부 상태뿐 아니라 케어 실천과 피드백까지 함께 기록하고,<br />
이를 다음 케어에 반영해 **사용할수록 나에게 맞는 관리 흐름을 만들어갑니다.**

월간 기록을 통해 피부 변화만 보는 것이 아니라<br />
**내가 얼마나 꾸준히 관리해왔는지도 확인할 수 있도록 해**,<br />
신체 변화에 대한 불안을 관리의 성취감으로 전환합니다.

→ `자존감 하락으로 이어지는 정서적 부담` 해결

---

## ✨ Key Features

<img
  width="100%"
  alt="주요 기능 1"
  src="https://github.com/user-attachments/assets/dc2834cc-9d86-4baa-bfb6-13bf42caff77"
/>
<img
  width="100%"
  alt="주요 기능 2"
  src="https://github.com/user-attachments/assets/2995aab3-50c9-4ac0-b461-ce0463c75a1f"
/>
<img
  width="100%"
  alt="주요 기능 3"
  src="https://github.com/user-attachments/assets/b49b711f-1d55-401f-8103-e18c8d17f34f"
/>

### 주요 기능 요약

| 기능 | 설명 |
| --- | --- |
| Google 로그인 | OAuth 기반으로 간편하게 로그인하고 사용자 프로필을 관리합니다. |
| 오늘의 체크인 | 사진, 신체 부위별 피부 상태, 메모와 감정을 기록합니다. |
| 맞춤 케어카드 | 체크인 결과를 바탕으로 오늘 실천할 피부 관리 행동을 안내합니다. |
| 기록 및 타임라인 | 날짜별 체크인 기록과 사진을 캘린더와 타임라인에서 확인합니다. |
| 월간 리포트 | 체크인 기록과 관리 흐름을 바탕으로 월간 상태와 관리 성취도를 확인합니다. |
| 케어 콘텐츠 | 임신 중 피부 관리에 필요한 콘텐츠와 단계별 마사지 가이드를 제공합니다. |
| 마이페이지 | 출산 예정일과 사용자 정보를 수정하고 계정 및 고객 지원 메뉴를 이용합니다. |

---

## 🛠 Tech Stack

| Category | Technology | Usage |
| --- | --- | --- |
| Language / Framework | Java 17, Spring Boot 4.1.0 | 백엔드 애플리케이션과 REST API 구성 |
| Security | Spring Security, OAuth2 Client, Google OIDC | 세션 기반 로그인, 인증·인가, CSRF 및 CORS 처리 |
| Persistence | Spring Data JPA, Hibernate, PostgreSQL 18.4 | 도메인 데이터 영속화와 관계형 데이터 관리 |
| Migration | Flyway | 스키마 버전 관리와 케어 행동 초기 데이터 구성 |
| AI | OpenAI Java SDK | 케어카드와 월간 리포트의 구조화된 문구 생성 |
| Image Analysis | ONNX Runtime | 자체 ONNX 모델을 이용한 피부 이미지 분석 |
| Object Storage | AWS SDK for Java, Amazon S3 | 원본 이미지 저장과 Presigned URL 발급 |
| API Documentation | springdoc-openapi, Swagger UI | REST API 명세 생성과 프런트엔드 연동 지원 |
| Build / Test | Gradle, JUnit 5, H2 | 빌드 자동화와 단위·통합·HTTP 테스트 |
| Infrastructure | AWS EC2, Docker, Docker Compose, GHCR | 컨테이너 기반 실행과 운영 환경 구성 |
| CI/CD | GitHub Actions | 테스트, 이미지 검증·게시 및 EC2 배포 자동화 |

---

## 🏗 Architecture

> 아키텍처 이미지 교체 예정

<!--
<img
  width="100%"
  alt="품결 백엔드 아키텍처"
  src="https://github.com/Likelion-YeungNam-Univ/14th-Marshmello-was/blob/master/marshmello-backend-architecture-corrected.png?raw=true"
/>
-->

품결 백엔드는 **Spring Boot 기반 REST API**로, 기능별 도메인과 외부 시스템 연동을 분리한 구조를 사용합니다.

- 클라이언트 요청은 AWS EC2의 Docker 컨테이너에서 실행되는 Spring Boot 애플리케이션이 처리합니다.
- Google OIDC 로그인 결과를 서버 세션으로 관리하고 Spring Security에서 인증·인가, CSRF, CORS 정책을 적용합니다.
- 도메인 서비스는 Spring Data JPA를 통해 PostgreSQL에 데이터를 저장하며 Flyway가 스키마와 초기 데이터를 관리합니다.
- 업로드된 피부 이미지는 EC2 내부의 ONNX 모델로 분석하고 원본 파일은 Amazon S3에 저장합니다.
- 케어카드와 월간 리포트는 도메인 데이터와 OpenAI API의 구조화된 응답을 조합해 생성합니다.
- GitHub Actions가 테스트와 컨테이너 검증을 수행하고, 검증된 이미지를 GHCR에 게시한 뒤 EC2에 배포합니다.

---

## 🗂 ERD

> ERD 이미지가 준비되면 아래 주석의 `ERD_IMAGE_URL`을 GitHub 이미지 URL로 교체하고 주석을 해제해 주세요.

<!--
<p align="center">
  <img width="100%" alt="품결 백엔드 ERD" src="ERD_IMAGE_URL" />
</p>
-->

### Entity별 핵심 기능

#### `User` · `SocialAccount` — 사용자와 인증 계정

- Google OIDC의 공급자·사용자 식별자를 내부 사용자와 연결합니다.
- 최초 로그인 시 사용자와 소셜 계정을 생성하고, 이후 로그인에서는 기존 계정을 조회합니다.
- 닉네임과 출산 예정일 등 프로필을 조회·수정하며 회원 탈퇴 시 연결된 데이터를 함께 정리합니다.

#### `Image` · `ImageAnalysis` — 피부 이미지 저장과 분석

- 최대 10MB의 피부 이미지를 받아 ONNX 모델로 분석합니다.
- 감지된 이미지의 분석 점수를 저장하고 원본 이미지는 Amazon S3에 보관합니다.
- 인증된 사용자에게 본인 이미지의 제한된 시간 동안 유효한 Presigned URL을 발급합니다.

#### `CheckIn` · `BodyDiary` — 일일 체크인

- 사용자별 하루 한 번의 체크인에 감정, 케어 달성 여부, 일기와 분석 완료 이미지를 연결합니다.
- 신체 부위별 튼살 여부와 메모를 함께 저장해 날짜별 기록을 구성합니다.
- 월별 감정 기록, 체크인 수, 달성 수와 가장 자주 기록한 신체 부위를 집계합니다.

#### `Action` · `CareCard` · `UserActionFeedback` — 맞춤 케어카드

- 이미지 분석 점수에 맞는 검증된 케어 행동 후보를 조회합니다.
- 사용자가 남긴 행동별 도움 점수를 다음 후보 선택에 반영합니다.
- 선택된 행동과 근거를 OpenAI 구조화 응답과 결합해 체크인별 케어카드를 생성합니다.

#### `Report` — 월간 리포트

- 종료된 월의 체크인과 이미지 분석 점수를 날짜순 추세 데이터로 구성합니다.
- 누적된 변화 데이터를 기반으로 OpenAI가 생성한 월간 요약을 저장합니다.
- 사용자와 월 조합의 리포트를 한 번만 생성하고 월 단위로 조회합니다.

---

## 🚀 Getting Started

### 1. 저장소 클론

```bash
git clone https://github.com/Likelion-YeungNam-Univ/14th-Marshmello-was.git
cd 14th-Marshmello-was
```

### 2. 사전 요구사항

- Java 17
- PostgreSQL 18.x
- 전체 기능 사용 시 Google OIDC 클라이언트, Amazon S3 버킷, OpenAI API 키

### 3. 로컬 데이터베이스 준비

PostgreSQL에 애플리케이션이 사용할 데이터베이스와 사용자를 생성합니다. 애플리케이션 시작 시 Flyway가 필요한 스키마와 초기 데이터를 적용합니다.

```sql
CREATE USER marshmello WITH PASSWORD 'your-local-password';
CREATE DATABASE marshmello OWNER marshmello;
```

### 4. 환경 변수 설정

아래 값은 예시입니다. 실제 비밀 값은 저장소에 커밋하지 마세요.

```bash
export SPRING_DATASOURCE_URL=jdbc:postgresql://127.0.0.1:5432/marshmello
export SPRING_DATASOURCE_USERNAME=marshmello
export SPRING_DATASOURCE_PASSWORD=your-local-password

export OIDC_ISSUER_URI=https://accounts.google.com
export OIDC_CLIENT_ID=your-client-id
export OIDC_CLIENT_SECRET=your-client-secret
export APP_CORS_ALLOWED_ORIGINS=https://your-frontend.example.com
export APP_LOGIN_SUCCESS_URL=https://your-frontend.example.com

export AWS_REGION=ap-northeast-2
export AWS_S3_BUCKET=your-bucket-name
export OPENAI_API_KEY=your-openai-api-key
```

S3 또는 OpenAI 설정을 생략하면 해당 연동 기능은 사용할 수 없지만 애플리케이션은 대체 구현으로 기동할 수 있습니다.

### 5. 애플리케이션 실행

```bash
./gradlew bootRun --args='--spring.profiles.active=local'
```

기본 서버 주소는 `http://localhost:8080`이며, 로컬 프로필에서는 Swagger UI를 `http://localhost:8080/swagger-ui/index.html`에서 확인할 수 있습니다.

---

## 📜 Scripts

| Command | Description |
| --- | --- |
| `./gradlew bootRun --args='--spring.profiles.active=local'` | 로컬 프로필로 백엔드 애플리케이션을 실행합니다. |
| `./gradlew test` | 전체 테스트를 실행합니다. |
| `./gradlew clean build` | 테스트를 포함한 전체 빌드를 수행합니다. |
| `./gradlew bootJar` | 실행 가능한 Spring Boot JAR를 생성합니다. |
| `docker build --build-arg BUILD_ID=local -t marshmello-was:local .` | 로컬 Docker 이미지를 생성합니다. |

---

## 👥 Team

| BE / Leader | BE | FE | FE | FE | P&D |
| :---: | :---: | :---: | :---: | :---: | :---: |
| <img src="https://github.com/6rmkhj.png" width="100" height="100" alt="김형준" /> | <img src="https://github.com/psj-1228.png" width="100" height="100" alt="박성준" /> | <img src="https://github.com/Pdar124.png" width="100" height="100" alt="박다래" /> | <img src="https://github.com/parkjinacosmos.png" width="100" height="100" alt="박진아" /> | <img src="https://github.com/Hengjju.png" width="100" height="100" alt="정형주" /> | <img src="https://github.com/22320139-code.png" width="100" height="100" alt="최혜선" /> |
| [김형준](https://github.com/6rmkhj) | [박성준](https://github.com/psj-1228) | [박다래](https://github.com/Pdar124) | [박진아](https://github.com/parkjinacosmos) | [정형주](https://github.com/Hengjju) | [최혜선](https://github.com/22320139-code) |

---

## 📝 Commit Convention

[Conventional Commits](https://www.conventionalcommits.org/) 형식을 사용합니다.

```text
<type>: <subject>
```

| Type | 설명 |
| --- | --- |
| `feat` | 새로운 기능 추가 |
| `fix` | 버그 수정 |
| `refactor` | 기능 변화가 없는 코드 구조 개선 |
| `style` | 코드 동작에 영향을 주지 않는 포맷 변경 |
| `docs` | 문서 추가 또는 수정 |
| `test` | 테스트 추가 또는 수정 |
| `chore` | 패키지, 설정 등 기타 작업 |
| `revert` | 이전 커밋 되돌리기 |
| `merge` | 브랜치 병합 |

### 작성 규칙

- `type`은 영문 소문자로 작성합니다.
- 제목은 변경 내용을 명확하고 간결하게 작성하며 마침표를 붙이지 않습니다.
- 하나의 커밋에는 하나의 논리적인 변경만 포함합니다.
- 상세 설명이 필요하면 제목 다음에 빈 줄을 두고 본문을 작성합니다.

---

## License

이 프로젝트는 [MIT License](./LICENSE)를 따릅니다.
