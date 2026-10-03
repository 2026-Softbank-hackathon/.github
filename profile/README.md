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

---

<div align="center">

**Team Camellia · SoftBank Hackathon 2026**

</div>
