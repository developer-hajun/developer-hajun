# 👋 Hi there! I'm Hajun

### 🧑‍💻 Backend Developer & Database Engineer  
- 안정적인 서비스를 추구합니다.  
- 항상 사용자의 관점에서 개발합니다.  
- 기술을 공부할 때는 원리까지 깊게 파고듭니다.  
- 증상을 덮는 수정보다 **구조적 원인 진단**, 사후 패치보다 **설계 단계의 예방**을 중시합니다.

---

## 💼 Career

| Period | Company | Role |
|--------|---------|------|
| 2026.10 ~ | **현대오토에버 (Hyundai AutoEver)** | 신입 입사 |

---

## 🎓 Education

| Period | Organization | Detail |
|--------|--------------|--------|
| - | 동아대학교 | 컴퓨터공학 졸업 |
| - | SSAFY (삼성 청년 SW·AI 아카데미) 14기 | Java 트랙 수료 |

---

## 🛠️ Tech Stack

**Languages & Frameworks**  
<img src="https://img.shields.io/badge/Python-181717?style=flat-square&logo=Python&logoColor=white"/> 
<img src="https://img.shields.io/badge/C++-181717?style=flat-square&logo=C%2B%2B&logoColor=white"/> 
<img src="https://img.shields.io/badge/Java-181717?style=flat-square&logo=Java&logoColor=white"/> 
<img src="https://img.shields.io/badge/Kotlin-181717?style=flat-square&logo=Kotlin&logoColor=white"/> 
<img src="https://img.shields.io/badge/Spring-181717?style=flat-square&logo=Spring&logoColor=white"/> 
<img src="https://img.shields.io/badge/Spring Security-181717?style=flat-square&logo=Spring%20Security&logoColor=white"/> 
<img src="https://img.shields.io/badge/MyBatis-181717?style=flat-square&logo=MyBatis&logoColor=white"/> 
<img src="https://img.shields.io/badge/QueryDSL-181717?style=flat-square&logo=QueryDSL&logoColor=white"/> 
<img src="https://img.shields.io/badge/Django-181717?style=flat-square&logo=Django&logoColor=white"/> 
<img src="https://img.shields.io/badge/React-181717?style=flat-square&logo=React&logoColor=white"/> 
<img src="https://img.shields.io/badge/Vue.js-181717?style=flat-square&logo=Vue.js&logoColor=white"/> 

**Database & Cache**  
<img src="https://img.shields.io/badge/MySQL-181717?style=flat-square&logo=MySQL&logoColor=white"/> 
<img src="https://img.shields.io/badge/PostgreSQL-181717?style=flat-square&logo=PostgreSQL&logoColor=white"/> 
<img src="https://img.shields.io/badge/Redis-181717?style=flat-square&logo=Redis&logoColor=red"/> 
<img src="https://img.shields.io/badge/Elasticsearch-181717?style=flat-square&logo=Elasticsearch&logoColor=white"/> 

**Cloud & DevOps**  
<img src="https://img.shields.io/badge/Amazon EC2-181717?style=flat-square&logo=Amazon-EC2&logoColor=white"/> 
<img src="https://img.shields.io/badge/Amazon S3-181717?style=flat-square&logo=Amazon-S3&logoColor=white"/> 
<img src="https://img.shields.io/badge/Docker-181717?style=flat-square&logo=Docker&logoColor=white"/> 
<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/> 

---

## ⚒️ Tools

<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/>  <img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=Notion&logoColor=white"/>  <img src="https://img.shields.io/badge/Anaconda-44A833?style=flat-square&logo=Anaconda&logoColor=white"/>  <img src="https://img.shields.io/badge/IntelliJ IDEA-000000?style=flat-square&logo=IntelliJ-IDEA&logoColor=white"/>  

---

## 🚀 Projects

### 🔎 자연어 기반 부동산 매물 검색 시스템 (개인)
- 필터 직접 선택 방식 대신 **자연어로 매물을 검색**하는 RAG 기반 시스템
- 키워드 1차 필터링 후 **Pgvector + HNSW 인덱싱** 벡터 유사도 검색
- `Spring AI` `Spring Boot` `MyBatis` `PostgreSQL` `Pgvector`

### 🧴 향기록 (SSAFY)
- AI 향수 추천 서비스
- ML 오케스트레이션, **HNSW 인덱스 기반 벡터 유사도 검색**, Elasticsearch 초성 검색
- 팀원 중도 이탈 시 남은 업무를 재분배하고 가장 큰 비중을 직접 담당

### 🤖 HeyGent (7인)
- MSA 아키텍처 프로젝트
- **전체 시스템 설계**: MSA 구조, Spring API Gateway 인증(토큰 만료 + Redis 저장 Refresh Token 사용자 ID 일치 검증), Redis Pub/Sub, 도메인별 DB 분리 및 보상 트랜잭션
- **직접 구현**: Android/Kotlin 클라이언트 (로컬 PC WebSocket 통신, 웨어러블 연동)
- AWS 아키텍처 다이어그램 작성

### 🏛️ ForMZ (20인)
- 청년 정책 플랫폼
- `EXPLAIN ANALYZE` 진단 → **카디널리티 기준 복합 인덱스** 설계
- **Redis Cache-Aside + TTL Jittering** 적용, 응답 속도 개선 (400ms → 200ms)
- Spring Batch 기반 데이터 파이프라인
- 일정 관리 실패 경험을 피드백으로 반영해 MVP를 3단계(기능 개발 → 성능/최적화)로 재설계

### 🖐️ GESTER (6인, 팀장)
- MediaPipe 기반 Android(Kotlin) 제스처 인식으로 Windows 제어
- 레이스 컨디션 / 메모리 누수로 인한 프리징을 스레드 단일화 및 monotonic timestamp 재설계로 해결
- `AtomicBoolean` 기반 Backpressure 알고리즘, GPU Delegate 적용
- **처리 속도 27% 향상, 메모리 사용량 41% 감소**

### 💸 TrustMate (4인)
- C2C 거래 가격 예측 플랫폼, **Fair Day 수상작**
- Random Forest / Gradient Boosting / XGBoost 중 최적 모델 선택, **정확도 86%**
- ANOVA F-value 분석 (상품 상태 F=320.2)
- Long Polling → **Celery + Redis + SSE** 비동기 알림 구조로 전환, **53% 개선**
- AWS 아키텍처 다이어그램 작성

### 🏫 ThisIs (동아대학교 캠퍼스 앱)
- PHP → Java 마이그레이션

---

## 🌱 Activities

### 카카오 에코실험실 3기 (팅커벨 가든 프로젝트)
- 야행성 생태계, 빛공해(ALAN), 도시 생물다양성 주제 연구
- 인공조명 하 포식자-피식자 역학 조사, 학술 논문 분석, 환경 테마 보드게임 기획

### 도전학기제 (6개월, 지도교수와 함께)
- GIS 기반 물류 데이터 전처리 및 최적화
- Python으로 약 3만 건 데이터 전처리, 국내 좌표계 변환 후 카카오맵 시각화

---

## 📜 Certifications

| Certification | Detail |
|---------------|--------|
| 정보처리기사 | - |
| SQLD | - |
| TOEIC Speaking | IM2 |
| Claude 101 | - |

---

## 🐱 About Me

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=developer-hajun&layout=compact&theme=dark)](https://github.com/anuraghazra/github-readme-stats)

---

## 🏅 Algorithm Level

[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=dlgkwns8828)](https://solved.ac/dlgkwns8828/)

---

## 🏆 Awards

| Competition | Prize                | Date             |
|-------------|----------------------|------------------|
| Dev Day     | Encouragement Award  | August 21, 2023  |
| Fair Day    | Grand Prize          | November 14, 2024|

---

## 📫 Contact

- Email: leehajun3174@gmail.com
- Portfolio: [developer-hajun.github.io/portfolio](https://developer-hajun.github.io/portfolio/)
