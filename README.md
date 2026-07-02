<div align="center">

# 정건희 · Backend Developer

**스스로 배워 적용하고, 끝까지 완성하는 개발자**

국토교통부 GIS 공간정보 시스템을 운영하며 3천만 건 ETL 파이프라인을 구축했습니다.<br>
ArcGIS·QGIS를 독학으로 익혀 실무에 적용했고, 개인 프로젝트는 기획부터 배포·운영까지 직접 완성합니다.

[![Portfolio](https://img.shields.io/badge/Portfolio-geonhui--portfolio.rjsgmlq33.workers.dev-2455C3?style=flat-square)](https://geonhui-portfolio.rjsgmlq33.workers.dev/)
[![GitHub](https://img.shields.io/badge/GitHub-donasman-181717?style=flat-square&logo=github)](https://github.com/donasman)
[![Email](https://img.shields.io/badge/Email-rjsgmlq33%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:rjsgmlq33@gmail.com)

</div>

---

## 💪 Strengths

| | |
|---|---|
| **01 — SCALE** | 국토 데이터 **3천만 건 ETL 파이프라인** 단독 구축 — 추출부터 DB 적재까지 안정적으로 운영 |
| **02 — INTEGRITY** | UNIQUE 제약 Upsert 멱등성, 성능 인덱스 설계, 경량 JWT 직접 구현 — 깨지지 않는 데이터 흐름 |
| **03 — AI-NATIVE** | AI가 생성한 코드를 리뷰·개선하는 사이클을 스터디로 실습 — 도구가 아닌 워크플로우로 활용 |

## 🚀 Projects

### 01. 우리동네 재생정보 시스템 `실무`

> 국토교통부 도시재생 포털 백엔드 유지보수 · GIS 데이터 처리 · 대용량 ETL 구축
> **2024.09 – 2025.08** · [city.go.kr](https://city.go.kr)

- 수년간 운영된 Java Legacy + PostgreSQL 시스템을 직접 분석해 유지보수 체계 수립
- Python으로 국토토지 데이터 약 **3천만 건 ETL 파이프라인** 구축 — 추출 → 재가공 → CSV → DB 적재
- ArcGIS·QGIS를 독학으로 습득해 공간 레이어 관리 업무에 즉시 적용
- 레이어 간 위상 오류·좌표계 불일치 등 공간 데이터 품질 이슈를 QGIS 검증 도구로 확인·보정

`Java` `PostgreSQL` `Python` `ArcGIS` `QGIS` `JavaScript`

### 02. PitchLog `개인`

> 2026 FIFA 월드컵 48개국 선수 통계·경기 일정·순위표 실시간 제공 풀스택 서비스
> **2026** · [pitchlog.pages.dev](https://pitchlog.pages.dev/)

- Spring Batch 5 파이프라인 **3 Jobs / 14 Steps** + WebClient 비동기 호출로 외부 API 수집
- **3-Mode 동적 스케줄러** — IDLE → LINEUP(5분) → LIVE(10초) 자동 전환
- 13개 정규화 테이블 설계 · UNIQUE 제약 Upsert 패턴으로 배치 재실행 **멱등성 보장**
- QueryDSL 타입 안전 쿼리 + 조회 패턴 기반 성능 인덱스 6개 설계
- Next.js 14 SSG → Cloudflare Pages CDN 배포, 48개국 경로 빌드 타임 사전 생성
- API 할당량 일 7,500건 중 9%만 사용하도록 호출 주기 최적화

`Spring Boot 3` `Java 21` `Spring Batch 5` `QueryDSL` `PostgreSQL` `Next.js 14`

### 03. 사주 AI 도사 `개인`

> 사주팔자 자동 계산 + Google Gemini 기반 4개 영역 AI 명리 분석 웹 서비스
> **2026 Q1** · [vibe-product-builder.pages.dev](https://vibe-product-builder.pages.dev/)

- lunar-javascript로 양력→음력 변환 후 연·월·일·시 간지(干支) 추출, 오행 분포 시각화
- Express 프록시 서버에서만 API Key 관리 — 클라이언트 노출 원천 차단
- AbortController 중복 요청 취소 + 최대 3회 자동 재시도로 응답 안정성 확보

`Node.js` `Express 5` `MySQL` `Gemini API` `Cloudflare Pages/Workers`

### 04. 과외나무 LessonTree `팀장 · 3인`

> 과외 선생님-학생 매칭 플랫폼 — DB 설계·인증 인프라·협업 워크플로우 주도
> **2024.04 – 2024.05**

- Spring Security + JWT(HS256) + OAuth2(Google/Naver/Kakao) **3종 통합 인증** 구축
- Role 기반 URL 접근 제어 · AOP 기반 유효성 검사로 횡단 관심사 분리
- 전체 DB 스키마 설계 · GitHub Flow 브랜치 전략, PR 코드 리뷰 주도

`Java 11` `Spring Boot 2` `Security` `OAuth2` `MyBatis` `MySQL` `React 18` `AWS`

## 🛠 Tech Stack

![Java](https://img.shields.io/badge/Java_11/21-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_2/3-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Batch](https://img.shields.io/badge/Spring_Batch_5-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python_ETL-3776AB?style=flat-square&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL·PostGIS-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL_8-4479A1?style=flat-square&logo=mysql&logoColor=white)
![React](https://img.shields.io/badge/React_18-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js_14-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_S3/EC2-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

## 📚 GitHub & Study

| [Baekjun-Algorithm-Study](https://github.com/donasman) | AI-Byte-Club |
|---|---|
| 백준 알고리즘 스터디 · 5개월 (2024.12 – 2025.05) | 백엔드 실무 지식 스터디 (2026 – 진행 중) |
| 커밋 **101** · 해결 **55+** · 달성률 **93.3%** | 학습 챕터 **11** · 커밋 **15+** · Vibe Coding 기능 **6개** |
| Java + Node.js 이원 운영 — 동일 문제 두 언어 구현 | MSA·CQRS·EDA · DB 인덱스·동시성 · 인증/암호화 |
| Solved.ac `SILVER III` (rjsgmlq33) | AI 협업 개발 실습 — 생성 코드 리뷰·개선 사이클 |

## 📌 Timeline

| 기간 | 활동 |
|---|---|
| 2026 – 진행 중 | 개인 프로젝트(PitchLog · 사주 AI 도사) & AI-Byte-Club 스터디 |
| 2024.09 – 2025.08 | **국토교통부 우리동네 재생정보 시스템** — 백엔드 개발자 (계약직) |
| 2024.12 – 2025.05 | 백준 알고리즘 스터디 — Java + Node.js 이원 운영 |
| 2024.04 – 2024.05 | 과외나무 팀 프로젝트 — 팀장 (3인) |

---

<div align="center">

**함께 일할 기회를 기다립니다.**

📧 [rjsgmlq33@gmail.com](mailto:rjsgmlq33@gmail.com) · 🌐 [Portfolio](https://geonhui-portfolio.rjsgmlq33.workers.dev/) · 🐙 [github.com/donasman](https://github.com/donasman)

</div>
