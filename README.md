<div align="center">

<img width="100%" src="./header_skyline.png" alt="Juhwan Kim · AI Service Engineer" />

<p align="center">
  <strong>AI Service Engineer&nbsp;·&nbsp;AX Engineer</strong><br/>
  <code>LLM Agent</code> · <code>RAG</code> · <code>MSA</code> · <code>Computer Vision</code>
</p>

<br/>

<a href="mailto:jkwltx177@gmail.com"><img src="https://img.shields.io/badge/Email-0C0D64?style=flat-square&logo=gmail&logoColor=white" /></a>
<a href="https://github.com/jkwltx177"><img src="https://img.shields.io/badge/GitHub-0C0D64?style=flat-square&logo=github&logoColor=white" /></a>
<a href="https://velog.io/@jkwltx177"><img src="https://img.shields.io/badge/Blog-0C0D64?style=flat-square&logo=velog&logoColor=white" /></a>

</div>

<img src="./assets/h_stack.svg" width="100%" alt="Tech Stack"/>

#### AI / ML
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logo=yolo&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

#### Backend · Infra
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)

#### Frontend · App
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=for-the-badge&logo=react&logoColor=black)

#### Foundation
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white)
<br/><sub>C++: 자료구조·알고리즘 집중 학습 · OpenGL 3D 렌더링 팀 프로젝트(<a href="https://github.com/jkwltx177/cg-opengl-maze">cg-opengl-maze</a>)</sub>

<img src="./assets/h_projects.svg" width="100%" alt="Featured Projects"/>

<sub>카드의 숫자는 전부 실측·집계값입니다.</sub>

<img src="./assets/h3_qapilot.svg" width="100%" alt="QApilot · Agentic AI 기반 통합 테스트 자동화 시스템"/>

> SKALA AI 서비스 개발 팀 프로젝트 **최우수상(1위)** · 6인 팀 **기술 리드**(오케스트레이터·Agent 설계·백엔드·테스트 대상 시스템 전체) · SKT 차세대 시스템(NOVA)을 개발하는 SK AX 현업 조직 발주

코드베이스와 요구사항 문서(PRD·정책·약관)를 읽어 **E2E 테스트 시나리오(TS·TC·TV)를 자동 생성**하고, Playwright로 **UI-API-DB 3-Tier를 교차 검증**하는 Agentic AI 시스템입니다. 장애 시 원인 후보(Top-N)·수정 코드·담당자를 제안하고, 요구사항 추적(RTM)·HITL 승인까지 통합 테스트 전 과정을 자동화합니다.

<img src="./assets/stats_qapilot.svg" width="100%" alt="결함 판정 정확도 96.6% · LLM 호출 비용 93% 절감 · 골든셋 224 TC 전수 실측 (요구사항 커버리지 100%)"/>

- 시나리오 생성을 TS·TC·TV Agent로 분리해 컨텍스트 폭주·할루시네이션 완화 ($0.21→$0.0144, usage_metadata 실측 · 요구사항 커버리지 100% · 테스트 코드 정확도 89.2%)
- 실행 불가(SKIPPED)·검증 축 부재(UNVERIFIED)를 분리하는 **판정 분류 체계**를 직접 정의. '확인되지 않은 성공'이 지표를 오염시키지 않게 설계
- 테스트 대상 시스템 **Mini-BSS**(통신 BSS MSA: FastAPI×2 + Vue 3 16화면 + PostgreSQL·MariaDB, 의도적 결함 7종)까지 단독 설계·구현

`LangGraph`(9 Agent · 8 Tool) · `FastAPI` · `Spring Boot` · `React`+`Vite` · `Playwright` · `tree-sitter` · `Qdrant` · `BGE-M3` · `Celery`/`Redis` · `PostgreSQL`+`S3`

**[skala-QApilot](https://github.com/skala-QApilot)** · **[SUT](https://github.com/skala-QApilot/system-under-test)**

<img src="./assets/h3_baggin.svg" width="100%" alt="baggin&#39; · 자율 논문 리서치·평가·보고서 생성 AI Agent"/>

> SKALA 미니 프로젝트 · 논문 평가 파이프라인(paper-service) 구현 · 챗봇 서비스 단독 개발

하루 ~14,000편 쏟아지는 논문을 **자동 수집·평가·한국어 요약**하고 사내 문서와 연결하는 MSA 플랫폼입니다. Sakana.ai *The AI Scientist*의 평가 코드를 직접 분석(리서치 문서 단독 작성)해 서비스 파이프라인으로 이식했습니다.

<img src="./assets/stats_baggin.svg" width="100%" alt="프로젝트 평가 94.8점 · 논문당 LLM 비용 30% 절감 · 팀 내 최다 커밋 47/90"/>

- 논문 평가(AIRA): 데스크 리젝션(gpt-4o-mini) → **Reviewer 3인 앙상블 + Self-Reflection + Area Chair 메타리뷰**(GPT-4o) → 점수 ≥ 5.0만 요약·적재. 싼 판정에서 비싼 판정으로 계층화해 논문당 API 호출 7회 억제
- arXiv 수집 → Kafka 이벤트 → 평가 → ChromaDB RAG → 사내 문서 비교 보고서 스트리밍

`Spring Cloud`(Eureka·Gateway·JWT) · `FastAPI`×5 · `Vue 3` · `Kafka` · `MariaDB` · `ChromaDB` · Docker 12컨테이너

**[Repository](https://github.com/jkwltx177/baggin)**

<img src="./assets/h3_airport.svg" width="100%" alt="A!rport · 사내 AI 에이전트 스토어"/>

> SKALA 웹 서비스 개발 미니 프로젝트(4인) · AI 에이전트 파이프라인 설계 · RAG 임베딩 · 웹서비스 통합(WebSocket/Kafka) · 워크스페이스 프론트

직원이 카탈로그에서 AI 에이전트를 구독하면 부서 예산으로 **노드 단위 사용량 과금**(Kafka 이벤트 → billing)이 이뤄지는 사내 에이전트 마켓플레이스입니다. 첫 입점 상품으로 투자심사 멀티에이전트를 탑재했습니다.

<img src="./assets/stats_airport.svg" width="100%" alt="LangGraph 11노드 파이프라인 · Spring Cloud MSA 7서비스 · HITL 체크포인트 5개"/>

- Supervisor 라우팅 → 병렬 fan-out 분석(기술·시장·경쟁사) → **LLM-as-Judge 재시도 루프**(실패한 에이전트만 부분 재실행, 최대 3회) → 투자 판정 → PDF 보고서
- FastAPI **WebSocket으로 노드 실행 로그를 실시간 스트리밍**하는 3-Panel 워크스페이스

`Spring Cloud`(Eureka·Gateway·OAuth2/JWT·Billing) · `Vue 3` · `FAISS`+`BGE-M3` 로컬 RAG(캐시 히트 시 웹검색 생략)

**[Repository](https://github.com/jkwltx177/airport-agent-store)**

<img src="./assets/h3_ecu.svg" width="100%" alt="ECU Quality System (Smart Glass) · 차량 ECU 품질 진단 멀티모달 AI MSA"/>

> SKALA 미니 프로젝트 · 4인 팀 · 초기 아키텍처·API 명세 설계 · AI 파이프라인 통합 · 백엔드 · 배포 인프라

스마트글래스를 쓴 현장 엔지니어의 음성·사진을 **STT(faster-whisper) → Vision(GPT-4V) → 고장확률·잔여수명 예측(LGBM/XGB/TCN) → 정비 매뉴얼 RAG 조치 가이드**로 잇는 차량 ECU 진단 시스템입니다 (OBD 표준 진단코드 DTC 기반).

<img src="./assets/stats_ecu.svg" width="100%" alt="발표 평가 2위 · 팀 내 최다 커밋 47/95 · NGINX 카나리 90/10 배포"/>

- 전체 디렉토리 구조·API 명세(A~F)를 초기 설계하고 LangGraph 멀티모달 오케스트레이션·하이브리드 RAG(FAISS 벡터+RDB 유사사례)를 통합. PR 통합 게이트 역할(머지 9건 중 5건)
- **GitHub Actions CI → Harbor → ArgoCD GitOps → NGINX 카나리** 배포를 프로젝트 종료 후 자발적 심화 학습으로 실클러스터에 단독 구축. PVC multi-attach 등 운영 트러블슈팅 커밋이 그 기록

`FastAPI` · `Spring Boot`(JWT) · `Vue 3`/`TS` · `FAISS` · `MariaDB` · `K8s`/`ArgoCD`

**[Repository](https://github.com/jkwltx177/smart-glass-ai-system)**

<details>
<summary><b>More Projects (펼쳐보기)</b></summary>

<br/>

| 프로젝트 | 설명 | 핵심 기술 |
|---|---|---|
| **[CareerPilot](https://github.com/jkwltx177/careerpilot)** | Claude Code를 **취준 전담 AI 컨설턴트**로 만드는 오픈소스 템플릿 (1인). 채용 전문가 스탠스 · **위키형 파일 메모리**(회사별 status/연대기/규칙 이원화) · **멀티에이전트 워크플로우 5종**(기업 리서치·자소서 적대 검토·코테 복기·기획 검증·공고 스윕) · 로컬 코테 저지 · 관제탑 대시보드. 실제 대기업 지원 캠페인 한 시즌 운영으로 검증 | Claude Code · Multi-Agent Workflow |
| **[Startup-Invest-Agent](https://github.com/jkwltx177/startup-invest-agent)** | 반도체·AI 스타트업 투자심사 멀티에이전트 (4인). 파이프라인 설계·한국어 RAG(BGE-m3-ko)·**LLM은 척도 추출, 판정은 결정론적 Scorecard/Gate로 분리** | LangGraph · FAISS · pdfplumber |
| **[LGES vs CATL Agent](https://github.com/jkwltx177/lges-vs-catl-analysis)** | 배터리 산업 전략 비교 AI Agent (4인). 데이터 정제·SWOT 구조화(Refine) 단계 설계, 출처 보존 Structured Output | LangGraph · Chroma · Pydantic |
| **[MOAA](https://github.com/jkwltx177/2025-1-Mobile-computing-MOAA)** | 기프티콘 자동 정리 앱 (4인 **조장**). **ML Kit 온디바이스 OCR·바코드** 추출 파이프라인·중복 등록 방지 설계, 유저 인터뷰부터 배포까지 전 과정 | React Native · ML Kit |
| **[Ræm (raemctrl)](https://github.com/jkwltx177/raemctrl)** | 졸업전시 AI 심리 투사 검사(HTP) 키오스크. 플로피·프린터·OBS 통합 제어, **전시 3일 449명(로그 실측) 무중단 운영** · 캡스톤디자인 경진대회 **장려상** | Python · Pygame · OBS WebSocket |
| **[TrendPilot](https://github.com/jkwltx177/trendpilot-kbeauty-agent)** | K뷰티 글로벌 진출 전략 B2B 에이전트 (2인 · RAG 실습 팀 평가 2위). 제품 사진 1장 → 규제 RAG·트렌드 분석 → 전략 PDF·광고 에셋 | GPT-4o · DALL·E 3 · ChromaDB |
| **[Artifiction](https://github.com/jkwltx177/artifiction)** | 명화 딥페이크·스타일 트랜스퍼 전시 (캡스톤 I, 3인 팀 개발 담당). GTX 1660 Ti 단일 노트북에서 스타일 모델 3종 학습·서빙, 품질과 시간의 트레이드오프 설계 | InsightFace · Fast Style Transfer · Unity |
| **[cg-opengl-maze](https://github.com/jkwltx177/cg-opengl-maze)** | C++/OpenGL 고정 파이프라인 **1인칭 3D 미로 게임 + SOR 모델러** (4인). 카메라·맵·**AABB 충돌 처리** 담당, LOD·텍스처 맵핑·스카이박스 직접 구현 | C++ · OpenGL(GLUT) |
| **[박쥐피플](https://store.onstove.com/ko/games/4128)** | Unity/C# 게임. 캐릭터 스위칭·맵·무기 스왑 구현, **스토브 퍼블리싱 완수** | Unity · C# |

</details>

<img src="./assets/h_research.svg" width="100%" alt="Research Experience"/>

<img src="./assets/h3_cislab.svg" width="100%" alt="중앙대학교 CISLAB · 학부연구생 (AI·백엔드) · 2024.10 ~ 2025.10"/>

- **LeNet-5 → ResNet → Vanilla Transformer**를 PyTorch로 밑바닥부터 구현·스크래치 학습 (Multi-GPU 영한 번역 성능 검증)
- 웹 플랫폼 MVP **백엔드 개발**: `FastAPI` · `SQLAlchemy ORM` · `MySQL`
- 딥러닝 논문 스터디 진행

<img src="./assets/h_awards.svg" width="100%" alt="Awards, Education, Certifications"/>

**Awards**
- **SKALA AI 서비스 개발 팀 프로젝트 최우수상 (1위)** · SK AX
- **2025 SW·AI 캡스톤디자인 경진대회 장려상** · 중앙대학교 SW교육원

**Education**
- **SK AI Leader Academy (SKALA)** 수료 · SK AX (2026.01 ~ 2026.06)
- **중앙대학교** 예술공학대학 컴퓨터예술학부 졸업 (2020.03 ~ 2026.08)

**Certifications**
- **SQLD** (SQL 개발자) · 한국데이터산업진흥원, 2026.03

<img src="./assets/h_stats.svg" width="100%" alt="GitHub Stats"/>

<div align="center">

<img height="170" src="https://streak-stats.demolab.com/?user=jkwltx177&hide_border=true&background=0C0D64&ring=8AB4FF&fire=8AB4FF&currStreakNum=FFFFFF&currStreakLabel=FFFFFF&sideNums=FFFFFF&sideLabels=FFFFFF&dates=C9D1FF&stroke=8AB4FF" />

</div>

<div align="center">
<br/>

<img width="100%" src="./header_minimal.png" alt="" />

</div>
