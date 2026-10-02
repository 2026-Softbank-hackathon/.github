# 🌸 Team camellia

**SoftBank Hackathon 2026 · AI 원클릭 멀티 환경 배포 시스템**

> **One Action, Infinite Clouds.** 로컬 웹앱 소스를 올리면 AI 가 분석해 IR(앱 명세) 로 만들고, 같은 이미지로 AWS와 온프레미스에 원클릭 배포한다.

---

## 🚀 메인 프로젝트

**[Auto-Deployment-System](https://github.com/2026-Softbank-hackathon/Auto-Deployment-System)** — Fastify + Zod + pg-boss + Terraform + Cloudflare

- 데모 콘솔: https://console.camellia-deploy.app
- 데모 영상: *(제출 전 추가 예정)*

---

## 📊 심사 제출 자료

### 1. 소스 코드
- GitHub: https://github.com/2026-Softbank-hackathon/Auto-Deployment-System

### 2. 설계 문서·논의 메모
- **Notion 팀 공간**: https://www.notion.so/term1_team_camellia-6958bee9ada483d1815c01c831afcb3a
  - 📋 기능 명세 최신본 (109개)
  - 🔌 API 명세 최신본 (49개)
  - 📜 Discussion Log — 일자별 논의 과정 (9/27~10/3)
  - 결정 기록 `docs/decisions.md` (D-01 ~ D-69, 대안·근거 포함)

### 3. 발표 자료
- **중간발표 (10/3)**: Notion `📊 중간발표 자료` *(링크 추가 예정)*
- **최종발표 (10/4)**: 미작성

---

## 🏗 핵심 아키텍처

![전체 아키텍처](https://raw.githubusercontent.com/2026-Softbank-hackathon/Auto-Deployment-System/main/docs/architecture_overall_v5.5.svg)

**4 종 다이어그램** ([docs/](https://github.com/2026-Softbank-hackathon/Auto-Deployment-System/tree/main/docs)):
- [전체 아키텍처 v5.5](https://raw.githubusercontent.com/2026-Softbank-hackathon/Auto-Deployment-System/main/docs/architecture_overall_v5.5.svg)
- [AWS 배포 상세](https://raw.githubusercontent.com/2026-Softbank-hackathon/Auto-Deployment-System/main/docs/architecture_deploy_aws_v5.5.svg)
- [온프레미스 배포 상세](https://raw.githubusercontent.com/2026-Softbank-hackathon/Auto-Deployment-System/main/docs/architecture_deploy_onprem_v5.5.svg)
- [환경 전환 상세](https://raw.githubusercontent.com/2026-Softbank-hackathon/Auto-Deployment-System/main/docs/architecture_env_switch_v5.5.svg)

---

## 💡 와우 포인트

| | 내용 | 심사 매핑 |
|---|---|---|
| 1 | **원클릭 배포** — 소스 zip → AI 분석 → 1회 빌드 → 두 환경 동시 배포 | 완성도 · AI |
| 2 | **환경 전환** — AWS ↔ 온프레미스 CF DNS CNAME 1 API call · TTL 1초 · 15분 롤백 유예 | 클라우드 활용 · 독창성 |
| 3 | **같은 digest** — ECS · Lambda · S3 · 온프레미스 Docker 모두 하나의 이미지 | 이식성 |
| 4 | **운영 가시화** — `/ops` 대시보드 (큐 · 워커 heartbeat · AI 비용 · CD 기록) | 운영 수준 인프라 |
| 5 | **다국어 콘솔** — AI 설명 1 호출로 한국어·일본어 구조화 출력 | AI 효율 |

---

## 👥 팀 구성

| 역할 | GitHub | 담당 |
|---|---|---|
| PM · 분석 · IR · 발표 | [@Pionia5375](https://github.com/Pionia5375) | 이정 |
| 운영 대시보드 · CD · 로깅 | [@csh1668](https://github.com/csh1668) | 조서현 |
| 보안 · 비용 청구 | [@awj1052](https://github.com/awj1052) | 안우진 |
| 빌드 · 프로비저닝 · Terraform | [@gpffh20](https://github.com/gpffh20) | 신은영 |
| 프론트엔드 | [@minseong99](https://github.com/minseong99) | 김민성 |
| 검증 · Agent · 헬스체크 | [@kmsdevdata-sketch](https://github.com/kmsdevdata-sketch) | 김민서 |

---

## 📅 일정

- **10/3 (토) 10:00** — 중간 제출 (소스 · 설계 · 발표 자료 링크)
- 10/3 10:30~14:00 — 현장 개발
- 10/3 14:00~17:00 — 중간 발표 (3분 + Q&A 4분)
- **10/4 (일) 13:00** — 최종 제출 (발표 언어 + 통역 스크립트)
- 10/4 15:00~16:30 — 최종 발표 (5분)

---

**심사 기준**: 완성도·데모 30 / 클라우드 활용 30 / 팀 개발 20 / 독창성 10 / AI 10
