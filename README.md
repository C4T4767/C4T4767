# 안녕하세요 👋

문제를 직접 해결하는 **백엔드/자동화 지향 개발자**를 목표로 학습하고 있습니다.  
Java & Spring 기반 백엔드 개발을 중심으로, Docker · Kubernetes · Jenkins · GitHub Actions 같은 **배포/자동화 흐름**에도 관심이 많습니다.

<p align="center">
  <a href="https://solved.ac/profile/ssssssafy">
    <img src="http://mazassumnida.wtf/api/v2/generate_badge?boj=ssssssafy" alt="Solved.ac Profile" />
  </a>
</p>

## Links

- **GitHub**: [C4T4767](https://github.com/C4T4767)
- **Service**: ~~[peekle.today](https://peekle.today)~~
- **BOJ / solved.ac**: [`ssssssafy`](https://solved.ac/profile/ssssssafy)

## About Me

- **Java / Spring** 기반 백엔드 개발에 집중하고 있습니다.
- 반복되는 불편을 그냥 넘기지 않고, **자동화 가능한 구조**로 바꾸는 것을 좋아합니다.
- 팀 프로젝트에서는 구현뿐 아니라 **이슈 관리, 협업 방식, 운영 흐름**까지 함께 봅니다.
- 꾸준한 알고리즘 문제 풀이를 통해 **문제 해결력과 구현력**을 쌓고 있습니다.

## Featured Projects

### [지구본 (ZIGU-BON)](https://github.com/suspicious-people/zigubon)
전 세계 최신 이슈를 3D 지구본 위에서 탐색하고, 국가별 이슈·AI 요약·개인화 추천·챗봇/음성 명령을 하나의 흐름으로 연결한 **AI 기반 글로벌 이슈 시각화 서비스**입니다.

- **수상 이력**: SSAFY 공통 프로젝트에서 **반 2위 팀**으로 선정되어 **프로젝트 우수상** 수상 (`삼성전자주식회사`, 2026.05.21)
- `frontend / backend / ai-service / infra`로 구성된 **monorepo 프로젝트**
- **Frontend**: Next.js 16, React 19, TypeScript, Three.js 기반 3D 지구본 UI
- **Backend**: Java 21, Spring Boot 3.5, JPA, OAuth2/JWT, PostgreSQL / Redis 연동
- **AI Server**: FastAPI 기반 뉴스 수집, 이슈 클러스터링, 요약, Q&A, 의도 분석 처리
- **Data Pipeline**: 국가별 뉴스 수집, 임베딩, 클러스터링, 이슈 생성 흐름 설계
- **Infra / Automation**: Docker, Nginx, GitLab CI/CD 기반 배포 및 운영 환경 구성

### [오트밀 (Auto-Trading-for-Meals)](https://github.com/ant-rescue-team/Auto-Trading-for-Meals)
나만의 투자 전략을 만들고, 백테스트로 검증한 뒤, 한국투자증권 API 기반 실거래까지 연결하는 **한국 주식 자동매매 플랫폼**입니다.

- **수상 이력**: SSAFY 공통 프로젝트에서 **반 2위 팀**으로 선정되어 **프로젝트 우수상** 수상 (`삼성전자주식회사`, 2026.03.30)
- `frontend / backend`로 구성된 **monorepo 프로젝트**
- **Frontend**: Next.js 16, React 19, TypeScript, Tailwind CSS, Recharts 기반 대시보드·차트 UI
- **Backend**: Java 21, Spring Boot 3.4, JPA, QueryDSL, Spring Security, OAuth2/JWT 기반 API 서버
- **Trading**: 한국투자증권 API 연동, 자동매매 세션 시작/중지/재개, 주문 재시도 및 체결 활동 로그 처리
- **Backtesting**: 전략 조건 기반 백테스트 요청, SSE 기반 진행률 스트리밍, 수익률·이벤트·종목 인사이트 조회
- **Market Data**: KOSPI/KOSDAQ 종목 데이터, 실시간 시세, 캔들 차트, 보조지표, 재무제표/투자지표 제공
- **AI / Automation**: Gemini 기반 전략 추천·챗봇, DART/pykrx 기반 종목·재무 데이터 시드 자동화
- **Infra / CI/CD**: Docker, PostgreSQL, Redis, Nginx, Jenkins Pipeline 기반 빌드·배포 환경 구성

### [힐끔힐끔코딩(Peekle)](https://github.com/Peek-a-chu/Peekle)
문제 풀이, 스터디 협업, 실시간 소통, AI 추천, Chrome Extension 자동 연동을 하나의 흐름으로 연결한 **실시간 코딩 스터디 플랫폼**입니다.

- **수상 이력**: SSAFY 공통 프로젝트에서 **반 1위 팀**으로 선정되어 **프로젝트 우수상** 수상 (`삼성전자주식회사`, 2026.02.09)
- **Service**: ~~[peekle.today](https://peekle.today)~~
- `frontend / backend / ai-server / extension`으로 구성된 **monorepo 프로젝트**
- **Frontend**: Next.js 15, TypeScript, Tailwind CSS, Shadcn/UI
- **Backend**: Java 21 기반 서버, Redis / MySQL 연동, 인증·스터디·제출·리그 등 핵심 도메인 로직 처리
- **Realtime**: WebSocket, LiveKit 기반 실시간 채팅·코드 공유·협업 기능 구현
- **AI Server**: Python 기반 문제 추천 및 임베딩 처리
- **Extension**: 백준 제출 결과와 풀이 코드를 자동 수집하는 Chrome Extension



### [Bap Time with SSAFY](https://github.com/C4T4767/baptimessafy)
SSAFY 멀티캠퍼스 10층/20층 식단 정보를 자동으로 수집·가공해 Chrome Extension에 제공하는 **운영형 자동화 프로젝트**입니다.

- **20층 식단 자동화**: Welstory API 기반으로 일일 식단 데이터를 수집하고 JSON으로 저장
- **10층 식단 자동화**: Mattermost에 업로드된 주간 식단표 PNG를 수집한 뒤, Google Gemini API로 파싱해 구조화
- **Workflow Automation**: GitHub Actions 기반 정기 실행으로 데이터 생성, 커밋, 반영까지 자동화
- **Data Standardization**: 서로 다른 입력 소스를 공통 JSON 스키마로 정규화해 Extension에서 바로 사용할 수 있도록 설계
- **Production Use**: 실제 Chrome Extension **Bap Time with SSAFY**에 연동되어 운영 중이며, 작성 시점 기준 **사용자 461명 / 평점 5.0**

## Experience

### (네이버클라우드) 클라우드 네이티브 기반 웹 풀스택 개발자 과정 | 네이버클라우드 주식회사
- **기간**: 2024.10.29 ~ 2025.05.12
- **학습 시간**: 1040시간
- **내용**
  - Spring Boot 기반 웹 서비스 개발
  - Docker / Kubernetes 오케스트레이션 실습
  - Jenkins CI/CD를 통한 **NCloud(NKS, Object Storage) 배포 자동화** 경험

## Awards & Certificates

- **SQLD** | 2025.12.12
- **리더십 상** | 네이버클라우드 | 2024.12.03
  - 팀 운영과 협업 기여를 인정받아 수상
- **우수상** | 삼성전자주식회사 | 2026.02.09
  - SSAFY 공통 프로젝트 반 1위 팀으로 선정되어 프로젝트 우수상 수상

## Tech Stack

<p>
  <img src="https://img.shields.io/badge/Java-000000?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" />
</p>

## Problem Solving

- **BOJ / solved.ac**: [`ssssssafy`](https://solved.ac/profile/ssssssafy)
- 알고리즘 문제 풀이 기록을 꾸준히 쌓고 있습니다.

## Currently

- Spring Boot / REST API / DB 설계
- Docker / Kubernetes / CI/CD / Automation
- Problem Solving on BOJ

---

작은 불편도 직접 해결해 서비스와 자동화로 바꾸는 개발자가 되려고 합니다.
