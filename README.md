# 안녕하세요 👋

사용자의 불편을 발견하고, 이를 실제로 사용할 수 있는 서비스로 구현하는 개발자입니다.

Java·Spring 기반 백엔드 개발을 중심으로 React·Next.js·TypeScript를 활용한 웹 애플리케이션 개발도 경험했습니다. 기능 구현에 그치지 않고 데이터 처리, 성능 개선, 배포와 운영까지 서비스가 동작하는 전체 흐름을 이해하기 위해 노력하고 있습니다.

<p align="center">
  <a href="https://solved.ac/profile/ssssssafy">
    <img src="http://mazassumnida.wtf/api/v2/generate_badge?boj=ssssssafy" alt="Solved.ac Profile" />
  </a>
</p>

## Links

- **GitHub**: [C4T4767](https://github.com/C4T4767)
- **Previous Service**: ~~[peekle.today](https://peekle.today)~~

## About Me

- Java·Spring을 중심으로 웹 서비스의 API와 데이터 처리 기능을 개발했습니다.
- React·Next.js·TypeScript 및 Vue3·Vite 기반 프로젝트를 경험했습니다.
- 프로젝트에서 발생한 성능 문제를 분석하고 개선하는 과정에 관심이 많습니다.
- 반복되는 작업을 자동화하고 유지보수하기 좋은 구조로 개선하는 것을 좋아합니다.
- 팀 프로젝트에서는 구현뿐 아니라 역할 분담, 일정 관리와 기술적 의사결정에도 참여했습니다.
- Docker와 CI/CD를 활용해 서비스를 배포하고 운영한 경험이 있습니다.

## Featured Projects

### [지구본 (ZIGU-BON)](https://github.com/suspicious-people/zigubon)

전 세계 최신 이슈를 3D 지구본 위에서 탐색하고, 국가별 이슈·AI 요약·개인화 추천·챗봇과 음성 명령을 하나의 흐름으로 연결한 **AI 기반 글로벌 이슈 시각화 서비스**입니다.

- **수상 이력**: SSAFY 프로젝트에서 반 2위 팀으로 선정되어 프로젝트 우수상 수상
- **담당 역할**
  - Next.js·React·TypeScript·Three.js 기반 3D 지구본 인터페이스 구현
  - 중복 URL 선검증, 일괄 조회와 인덱스 적용을 통해 뉴스 처리 시간 약 78분 → 23분 단축
  - 프론트엔드·백엔드·AI 서버 간 API 명세와 데이터 형식 조율
- **Project Stack**
  - Frontend: Next.js 16, React 19, TypeScript, Three.js
  - Backend: Java 21, Spring Boot 3.5, JPA, OAuth2/JWT, PostgreSQL, Redis
  - AI Server: FastAPI 기반 뉴스 수집, 이슈 클러스터링, 요약, Q&A 및 의도 분석
  - Infra: Docker, Nginx, GitLab CI/CD
- `frontend / backend / ai-service / infra`로 구성된 monorepo 프로젝트

---

### [힐끔힐끔코딩 (Peekle)](https://github.com/Peek-a-chu/Peekle)

문제 풀이, 스터디 협업, 실시간 소통, AI 추천과 Chrome Extension 자동 연동을 하나의 흐름으로 연결한 **코딩 스터디 플랫폼**입니다.

- **수상 이력**: SSAFY 프로젝트에서 반 1위 팀으로 선정되어 프로젝트 우수상 수상
- **담당 역할**
  - 6인 팀의 팀장으로 기능 범위, 역할 분담과 개발 우선순위 조율
  - 백준 제출 이벤트를 감지해 제출 결과와 풀이 코드를 서버로 자동 연동하는 흐름 구현
  - 지원 서버 종료 후 개인 AWS 환경에 재배포해 약 3개월간 운영
- **Project Stack**
  - Frontend: Next.js 15, TypeScript, Tailwind CSS, Shadcn/UI
  - Backend: Java 21, Spring Boot, Redis, MySQL
  - Realtime: WebSocket, LiveKit
  - AI Server: Python 기반 문제 추천 및 임베딩 처리
  - Extension: Chrome Extension 기반 백준 제출 결과 및 풀이 코드 자동 수집
- `frontend / backend / ai-server / extension`으로 구성된 monorepo 프로젝트
- **Previous Service**: ~~[peekle.today](https://peekle.today)~~

---

### Twalk

여러 사용자가 여행지를 검색하고 하나의 여행 계획을 함께 작성·수정할 수 있도록 만든 **협업형 여행 계획 서비스**입니다.

- **담당 역할**
  - 여러 사용자가 하나의 여행 계획에 참여해 일정과 장소를 공동으로 관리하는 기능 구현
  - WebSocket을 활용해 일정 변경 사항이 다른 참여자의 화면에도 반영되는 이벤트 흐름 구성
  - Vue3와 Pinia를 활용한 여행 계획, 참여자 및 일정 상태 관리
  - Elasticsearch의 필드별 가중치와 사용자 클릭 데이터를 반영해 여행지 검색 결과 개선
  - Redis와 Lua Script를 활용해 동시에 발생하는 좋아요 요청을 원자적으로 처리
- **Project Stack**
  - Frontend: Vue3, Vite, Tailwind CSS, Pinia
  - Backend: Java 17, Spring Boot 3.5, MyBatis, Spring Security, JWT
  - Data: MySQL, Redis, Elasticsearch
  - Infra: Docker, KT Cloud

---

### [Bap Time with SSAFY](https://github.com/C4T4767/baptimessafy)

SSAFY 멀티캠퍼스 10층·20층 식단 정보를 자동으로 수집·가공해 Chrome Extension에 제공하는 **운영형 자동화 프로젝트**입니다.

- **담당 역할**: 기획, 개발, 배포 및 운영 1인 수행
- **20층 식단 자동화**: Welstory API 기반으로 일일 식단 데이터를 수집하고 JSON으로 저장
- **10층 식단 자동화**: Mattermost에 업로드된 주간 식단표 이미지를 수집한 뒤 Gemini API로 분석해 구조화
- **Workflow Automation**: GitHub Actions 기반 정기 실행으로 데이터 생성, 커밋과 반영 과정 자동화
- **Data Standardization**: 서로 다른 입력 소스를 공통 JSON 스키마로 정규화해 Extension에서 바로 사용할 수 있도록 설계
- **Production Use**: 실제 SSAFY 교육생을 대상으로 운영했으며 누적 사용자 500명 이상 기록
- **Project Stack**: JavaScript, HTML5, CSS3, Chrome Extension Manifest V3, Node.js, GitHub Actions, Gemini API

---

### [오트밀 (Auto-Trading-for-Meals)](https://github.com/ant-rescue-team/Auto-Trading-for-Meals)

사용자가 투자 전략을 만들고 백테스트로 검증한 뒤 한국투자증권 API 기반 실거래까지 연결할 수 있도록 만든 **한국 주식 자동매매 플랫폼**입니다.

- **수상 이력**: SSAFY 프로젝트에서 반 2위 팀으로 선정되어 프로젝트 우수상 수상
- **담당 역할**
  - 투자 전략 조건을 처리하는 백테스트 엔진 및 데이터 처리 로직 구현
  - 초기 데이터 로딩, 스냅샷 Map과 지표 캐시를 적용해 백테스트 처리 시간 약 12분 → 3분 단축
  - 한국투자증권 API를 활용한 자동매매 기능 및 주문 처리 흐름 개발
- **Project Stack**
  - Frontend: Next.js 16, React 19, TypeScript, Tailwind CSS, Recharts
  - Backend: Java 21, Spring Boot 3.4, JPA, QueryDSL, Spring Security, OAuth2/JWT
  - Data: PostgreSQL, Redis
  - Trading: 한국투자증권 API, 자동매매 세션 및 주문 처리
  - AI / Automation: Gemini 기반 전략 추천·챗봇, DART·pykrx 기반 데이터 시드 자동화
  - Infra: Docker, Nginx, Jenkins Pipeline
- `frontend / backend`로 구성된 monorepo 프로젝트

## Experience

### 삼성청년SW·AI아카데미 | 삼성 청년 SW 아카데미

- **기간**: 2025.07.01 ~ 2026.06.01
- **학습 시간**: 1,725시간
- Java·Spring 기반 백엔드 개발 및 알고리즘 학습
- React·Next.js·TypeScript 및 Vue3·Vite 기반 웹 프로젝트 수행
- 생성형 AI 연동, 실시간 통신, 데이터 처리 및 성능 개선 경험
- Redis·PostgreSQL을 활용한 저장 구조 설계
- 팀 프로젝트에서 팀장으로 역할 분담, 일정과 기술적 의사결정 조율

### (네이버클라우드) 클라우드 네이티브 기반 웹 풀스택 개발자 과정 | 네이버클라우드 주식회사

- **기간**: 2024.10.29 ~ 2025.05.12
- **학습 시간**: 1,040시간
- Java·Spring Boot 기반 웹 서비스 및 REST API 개발
- Docker 기반 애플리케이션 컨테이너화
- Jenkins를 활용한 CI/CD 파이프라인 구축
- Kubernetes와 Ncloud NKS 기반 서비스 배포
- Object Storage 연동 및 클라우드 환경 구성
- 팀 프로젝트 팀장으로 기능 범위와 개발 일정 조율

## Awards & Certificates

- **정보처리기사** | 2026.06.12
- **SQLD** | 2025.12.12
- **프로젝트 우수상** | SSAFY | 2026.05.21
  - 지구본 프로젝트, 반 2위 팀 선정
- **프로젝트 우수상** | SSAFY | 2026.03.30
  - 오트밀 프로젝트, 반 2위 팀 선정
- **프로젝트 우수상** | SSAFY | 2026.02.09
  - 힐끔힐끔코딩 프로젝트, 반 1위 팀 선정
- **리더십상** | 네이버클라우드 교육 과정 | 2024.12.03
  - 팀 운영과 협업 기여를 인정받아 수상
## Tech Stack

### Frontend

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white" />
</p>

### Backend & Data

<p>
  <img src="https://img.shields.io/badge/Java-000000?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
</p>

### Infra & Collaboration

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" />
</p>

## Problem Solving

- **BOJ / solved.ac**: [`ssssssafy`](https://solved.ac/profile/ssssssafy)

## Currently

- Java·Spring 기반 웹 서비스 개발
- React·Next.js·TypeScript 프로젝트 경험 확장
- 데이터 처리 및 성능 개선
- Docker·CI/CD 기반 배포 자동화
- BOJ 알고리즘 문제 풀이

---

작은 불편도 직접 해결해 서비스와 자동화로 바꾸는 개발자가 되려고 합니다.
