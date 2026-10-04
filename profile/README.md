<div align="center">

# ☁️ 2026 소프트뱅크 해커톤 ☁️

---

### “One Action, Infinite Clouds.”

로컬 웹앱을 분석하고 필요한 인프라까지 직접 구성해  
AWS와 온프레미스 환경에 배포하는 **AI 원클릭 배포 시스템, Camellia**

</div>

<br />

## 🌺 TEAM Camellia

コロの引っ越し(코로의 이사) 는 기존 PaaS 위에 애플리케이션만 올리는 서비스가 아닌 업로드된 애플리케이션을 분석한 뒤 하나의 배포 명세를 기반으로 **VPC·ALB·ECS 등 실제 인프라를 직접 생성**하고, 컨테이너 빌드부터 AWS·온프레미스 배포와 검증까지 자동화합니다.

> **Upload → Analyze & IR → Build → Plan & Approve → Provision → Deploy → Verify**

<br />

<div align="center">

## 🛠️ Tech Stack

### 🖥️ Frontend

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

### ⚙️ Backend & Orchestration

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=for-the-badge&logo=fastify&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge&logo=zod&logoColor=white)

### 📦 Build & Registry

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![BuildKit](https://img.shields.io/badge/BuildKit-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Docker Buildx](https://img.shields.io/badge/Docker_Buildx-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Railpack](https://img.shields.io/badge/Railpack-131415?style=for-the-badge)
![Amazon ECR](https://img.shields.io/badge/Amazon_ECR-FF9900?style=for-the-badge)

### ☁️ Infrastructure & Deployment

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Amazon ECS Fargate](https://img.shields.io/badge/Amazon_ECS_Fargate-FF9900?style=for-the-badge&logo=amazonecs&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare_DNS_%26_Tunnel-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)

### 🗄️ Data, Queue & Storage

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![pg-boss](https://img.shields.io/badge/pg--boss-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Amazon S3](https://img.shields.io/badge/Amazon_S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)

### 🤖 AI & Analysis

![Anthropic Claude](https://img.shields.io/badge/Anthropic_Claude-191919?style=for-the-badge&logo=anthropic&logoColor=white)

### 🧪 Quality & CI/CD

![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)
![pnpm](https://img.shields.io/badge/pnpm-F69220?style=for-the-badge&logo=pnpm&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

</div>

<br />

<br />

<table align="center">
  <tr>
    <td align="center" rowspan="2" width="110">
        <img
          src="../assets/coro.png"
          width="78"
          alt="코로"
        />
    </td>
    <td width="390">
      <sub><strong>TEAM CAMELLIA</strong></sub>
      <br />
      <strong>コロの引っ越し</strong>
      <sub>코로의 이사</sub>
      <br />
      <sub>On-Prem Agent · 로컬 환경을 배포 대상으로 연결합니다.</sub>
    </td>
    <td align="center" width="210">
      <a href="https://github.com/2026-Softbank-hackathon/Auto-Deployment-System/releases/latest">
        <img
          src="https://img.shields.io/github/v/release/2026-Softbank-hackathon/Auto-Deployment-System?filter=onprem-agent-*&display_name=tag&style=flat-square&label=latest%20release&color=238636"
          alt="Latest On-Prem Agent release"
        />
      </a>
      <br />
      <sub>
        <a href="https://github.com/2026-Softbank-hackathon/Auto-Deployment-System/releases/latest">
          릴리스 노트 및 체크섬 →
        </a>
      </sub>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <img
        src="https://img.shields.io/badge/macOS-arm64_%7C_x64-000000?style=flat-square&logo=apple&logoColor=white"
        alt="macOS arm64 and x64"
      />
      &nbsp;
      <img
        src="https://img.shields.io/badge/Windows_10%2F11-x64-0078D4?style=flat-square&logo=windows11&logoColor=white"
        alt="Windows 10 and 11 x64"
      />
      &nbsp;
      <img
        src="https://img.shields.io/badge/Docker-Desktop-2496ED?style=flat-square&logo=docker&logoColor=white"
        alt="Docker Desktop"
      />
    </td>
  </tr>
</table>

<br />

## 🚀 Deployment Flow

1. 소스 업로드
2. 스택 분석 및 배포 IR 생성
3. 배포 대상 선택·확정
4. 단일 컨테이너 이미지 빌드 및 digest 고정
5. Terraform 인프라 계획 생성·승인
6. 실제 인프라 프로비저닝
7. AWS ECS Fargate 또는 온프레미스 Docker 환경에 애플리케이션 배포
8. 연속 헬스체크를 통한 배포 검증 및 결과 기록
9. 배포 완료 URL 제공

<br />

## 🖥️ 상황별 화면

코로(コロ)가 앱을 새 집으로 옮겨 주는 과정을 상황마다 순서대로 보여 줍니다. 말풍선은 서버가 남긴 단계 로그와 헬스체크 현황을 그대로 말합니다.

### ☁️ AWS 에 처음 배포

ZIP 을 올리면 분석해서 배포 명세(IR)를 만들고, 이미지를 한 번 빌드해 AWS 로 옮깁니다.

<table>
  <tr>
    <td width="33%"><img src="../assets/screens/flow-aws-1.png" alt="이미지 빌드" /><br /><sub>① 분석 결과로 배포 명세를 만들고 집(이미지)을 짓습니다.</sub></td>
    <td width="33%"><img src="../assets/screens/flow-aws-2.png" alt="AWS 로 배포" /><br /><sub>② 집을 비행기에 싣고 구름(AWS)으로 옮깁니다. 새 컨테이너가 켜지는 과정을 숫자로 알려 줍니다.</sub></td>
    <td width="33%"><img src="../assets/screens/flow-aws-3.png" alt="배포 완료" /><br /><sub>③ 검증을 통과하면 LIVE 표지가 붙습니다.</sub></td>
  </tr>
</table>

### 🏠 온프레미스에 처음 배포

같은 방식으로 빌드한 이미지를, 서버에 설치한 On-Prem Agent 가 받아 실행합니다.

<table>
  <tr>
    <td width="33%"><img src="../assets/screens/flow-onprem-1.png" alt="이미지 빌드" /><br /><sub>① 이미지를 빌드합니다. AWS 와 같은 이미지를 씁니다.</sub></td>
    <td width="33%"><img src="../assets/screens/flow-onprem-2.png" alt="에이전트가 배포" /><br /><sub>② 에이전트 로봇이 이미지를 받아 서버에서 컨테이너를 켭니다.</sub></td>
    <td width="33%"><img src="../assets/screens/flow-onprem-3.png" alt="배포 완료" /><br /><sub>③ 서버 옆에 집이 자리 잡고 LIVE 가 됩니다.</sub></td>
  </tr>
</table>

### 🪂 AWS → 온프레미스 전환

ZIP 을 다시 올리지 않고 버튼 하나로 옮깁니다. 같은 이미지를 쓰므로 분석과 빌드를 건너뜁니다.

<table>
  <tr>
    <td width="33%"><img src="../assets/screens/flow-to-onprem-1.png" alt="전환 준비" /><br /><sub>① 온프레미스에 자리를 준비합니다. 검증이 끝날 때까지는 AWS 가 계속 서비스합니다.</sub></td>
    <td width="33%"><img src="../assets/screens/flow-to-onprem-2.png" alt="낙하산으로 이동" /><br /><sub>② 집이 낙하산을 타고 구름에서 서버 옆으로 내려옵니다.</sub></td>
    <td width="33%"><img src="../assets/screens/flow-to-onprem-3.png" alt="전환 완료" /><br /><sub>③ LIVE 표지가 온프레미스로 옮겨 갑니다.</sub></td>
  </tr>
</table>

### ✈️ 온프레미스 → AWS 전환

<table>
  <tr>
    <td width="33%"><img src="../assets/screens/flow-to-aws-1.png" alt="전환 준비" /><br /><sub>① 비행기를 조립합니다. 그동안 온프레미스가 계속 서비스합니다.</sub></td>
    <td width="33%"><img src="../assets/screens/flow-to-aws-2.png" alt="AWS 로 이동" /><br /><sub>② 집을 싣고 구름(AWS)으로 날아갑니다.</sub></td>
    <td width="33%"><img src="../assets/screens/flow-to-aws-3.png" alt="전환 완료" /><br /><sub>③ LIVE 표지가 AWS 로 옮겨 갑니다.</sub></td>
  </tr>
</table>

### ⏪ 롤백

<table>
  <tr>
    <td width="33%" valign="top"><img src="../assets/screens/flow-rollback-0.png" alt="되돌릴 버전 고르기" /><br /><sub>① 지금 서비스 중인 버전 상자에서 되돌릴 버전을 고릅니다.</sub></td>
    <td width="33%" valign="top"><img src="../assets/screens/flow-rollback-1.png" alt="되돌리는 중" /><br /><sub>② 창고의 예전 이미지를 다시 씁니다. 빌드는 건너뜁니다.</sub></td>
    <td width="33%" valign="top"><img src="../assets/screens/flow-rollback-3.png" alt="롤백 완료" /><br /><sub>③ 이전 버전이 다시 LIVE 가 됩니다.</sub></td>
  </tr>
</table>

### 🚨 온프레미스 장애 → AWS 자동 복구

온프레미스에 문제가 생기면 대기 중인 AWS 배포로 서비스 주소를 자동으로 돌립니다.

<table>
  <tr>
    <td width="33%"><img src="../assets/screens/14-failover-1-alarm.png" alt="온프레미스 장애 감지" /><br /><sub>① 온프레미스의 불이 꺼지고 코로가 놀랍니다.</sub></td>
    <td width="33%"><img src="../assets/screens/14-failover-2-board.png" alt="비행기에 탑승" /><br /><sub>② 비행기가 집과 코로를 태웁니다.</sub></td>
    <td width="33%"><img src="../assets/screens/14-failover-3-fly.png" alt="AWS 로 이동" /><br /><sub>③ 구름 위 AWS 로 날아가 복구를 마칩니다.</sub></td>
  </tr>
</table>

<details>
<summary><b>더 보기</b> — 화면 전체 모습 (진행 · 검증 · 결과 · 실패 · 서버리스 · 앱 상세 · 대시보드 · 운영)</summary>

<br />

<table>
  <tr>
    <td width="50%"><img src="../assets/screens/03-aws-deploy.png" alt="배포 진행 화면" /><br /><sub><b>배포 진행 화면</b> · 단계 칩, 경과 시간, 장면, 로그 · 분석 탭.</sub></td>
    <td width="50%"><img src="../assets/screens/05-verify.png" alt="검증 단계" /><br /><sub><b>검증</b> · 헬스체크가 3회 연속 통과해야 서비스 주소를 연결합니다.</sub></td>
  </tr>
  <tr>
    <td><img src="../assets/screens/06-result.png" alt="배포 결과 화면" /><br /><sub><b>배포 완료</b> · 서비스 주소와 걸린 시간, 단계별 소요 시간.</sub></td>
    <td><img src="../assets/screens/11-failed.png" alt="배포 실패 화면" /><br /><sub><b>실패</b> · 실패 원인과 오류 코드를 보여 주고 바로 재배포할 수 있습니다.</sub></td>
  </tr>
  <tr>
    <td><img src="../assets/screens/10-serverless-result.png" alt="서버리스 배포 결과" /><br /><sub><b>서버리스</b> · 같은 이미지를 AWS Lambda 로 배포한 결과.</sub></td>
    <td><img src="../assets/screens/08-app-detail.png" alt="앱 상세 화면" /><br /><sub><b>앱 상세</b> · 재배포 · 환경 전환 · 서버리스 전환 · 롤백을 한 곳에서.</sub></td>
  </tr>
  <tr>
    <td><img src="../assets/screens/12-dashboard.png" alt="대시보드" /><br /><sub><b>대시보드</b> · 앱마다 지금 어디서 서비스 중인지 한눈에.</sub></td>
    <td><img src="../assets/screens/13-ops.png" alt="운영 화면" /><br /><sub><b>운영</b> · 작업 큐와 워커, 플랫폼 서버, AI 사용량.</sub></td>
  </tr>
</table>

</details>

<br />

## ✨ 핵심 기능

| 기능 | 설명 |
|---|---|
| **원클릭 배포** | ZIP 을 올리고 연결을 고르면 분석부터 검증까지 이어서 진행합니다. |
| **AI 분석과 배포 명세(IR)** | 규칙으로 스택 · 포트를 찾고, 못 찾은 칸은 AI 가 채워 하나의 배포 명세로 만듭니다. |
| **한 번 빌드, 여러 환경** | 이미지는 한 번만 만들고 AWS 에도 온프레미스에도 같은 이미지를 씁니다. |
| **AWS 배포 형태 3가지** | 컨테이너(ECS Fargate) · 서버리스(Lambda) · 정적 사이트(S3). |
| **온프레미스 배포** | 서버에 설치한 On-Prem Agent 가 이미지를 받아 Docker 로 실행합니다. |
| **검증 후 주소 연결** | 헬스체크 3회 연속 통과 뒤에 서비스 주소를 새 버전에 연결합니다. |
| **재배포 · 롤백 · 환경 전환** | ZIP 을 다시 올리지 않고 버튼으로. 분석과 빌드를 건너뜁니다. |
| **자동 장애 복구** | 온프레미스 장애 시 대기 중인 AWS 배포로 자동 전환합니다. |
| **실패 진단** | 실패 원인과 오류 코드, AI 진단을 보여 줍니다. |
| **한국어 · 日本語** | 화면 전체를 두 언어로 제공합니다. |

<br />

## 🏗️ Architecture

<div align="center">
  <img src="https://raw.githubusercontent.com/2026-Softbank-hackathon/Auto-Deployment-System/main/docs/architecture_overall_v5.4.1.svg" alt="전체 아키텍처" width="90%" />
</div>

<br />

## 📈 측정 결과

실제 서비스 API 와 실제 AWS · 온프레미스 런타임에서 13개 시나리오, 배포 61건을 측정했습니다 (2026-10-02).

| 시나리오 | 전체 소요 시간 (중앙값) |
|---|---:|
| AWS 신규 이미지 배포 | 2.03분 |
| AWS 동일 이미지 재배포 | 20.32초 |
| 온프레미스 신규 이미지 배포 | 27.26초 |
| 온프레미스 → AWS 전환 | 26.55초 |
| AWS → 온프레미스 전환 | 19.00초 |

전체 결과: [성능 · 복원력 테스트 보고서](https://github.com/2026-Softbank-hackathon/Auto-Deployment-System/tree/main/docs/performance-results/20261002-comprehensive)

<br />

## 👥 Team

| 역할 | 이름 | 담당 |
|---|---|---|
| Frontend | | 웹 콘솔 |
| Backend | | API · 배포 파이프라인 |
| Infra | | Terraform 프로필 · 플랫폼 |
| On-Prem Agent | | 에이전트 · Cloudflare 연동 |

<br />

## 🔗 Repository

- [Auto-Deployment-System](https://github.com/2026-Softbank-hackathon/Auto-Deployment-System) — 배포 플랫폼 전체 (API · Worker · Web · On-Prem Agent · Terraform)

---

<div align="center">

**Team Camellia · SoftBank Hackathon 2026**

</div>
