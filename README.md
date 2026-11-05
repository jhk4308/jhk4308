# Jung Hyun Kim

![Header](https://capsule-render.vercel.app/api?type=waving&height=200&text=Welcome%20to%20My%20GitHub!&fontAlign=40&fontAlignY=40&color=gradient)

<div align="center">


[![Open Portfolio](https://img.shields.io/badge/Portfolio%20열기-3A57D3?style=for-the-badge&logo=githubpages&logoColor=white)](https://jhk4308.github.io/)
[![PDF](https://img.shields.io/badge/PDF%20다운로드-111946?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://jhk4308.github.io/assets/portfolio-kim-junghyun.pdf)

</div>

---

## 👋 About Me

**지표를 신뢰 가능하게 만드는 데이터 분석가 김정현입니다.**  
Raw data 가공과 EDA로 데이터 품질을 먼저 잡고,  
의사결정에 쓸 수 있는 지표와 대시보드로 만드는 일을 합니다.  
공모전·해커톤·부트캠프에서 8개 프로젝트를 수행했고, 그중 데이터톤 프로젝트로 대상을 받았습니다.

**핵심 역량**  
· 데이터 정제·품질 관리: 결측·이상치 기준 설계, 단위·명칭 표준화, 정보 누수 차단  
· 예측 모델링: Feature Engineering, 앙상블, 시계열 예측 (ML/DL)  
· 대시보드 구축: Tableau, Streamlit, Dash  
· DB 정합성 검증: 분석 데이터와 DB·API 명세 1:1 대조, AWS RDS·Supabase(PostgreSQL) 적재

---

## 🧠 Skills

### 💻 Languages & Libraries
![Python](https://img.shields.io/badge/Python-3776AB.svg?&style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1.svg?&style=for-the-badge&logo=postgresql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458.svg?&style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243.svg?&style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E.svg?&style=for-the-badge&logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C.svg?&style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00.svg?&style=for-the-badge&logo=tensorflow&logoColor=white)

### ⚙️ Tools & Databases
![Tableau](https://img.shields.io/badge/Tableau-E97627.svg?&style=for-the-badge&logo=tableau&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B.svg?&style=for-the-badge&logo=streamlit&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1.svg?&style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/Supabase-3ECF8E.svg?&style=for-the-badge&logo=supabase&logoColor=white)
![AWS](https://img.shields.io/badge/AWS%20RDS-527FFF.svg?&style=for-the-badge&logo=amazonrds&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000.svg?&style=for-the-badge&logo=vercel&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757.svg?&style=for-the-badge&logo=anthropic&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032.svg?&style=for-the-badge&logo=git&logoColor=white)

---

## 💼 Projects

### 📦 StockPilot, 해외 소싱 재고 위험·승인 웹 서비스
**2026.10 | LS 부트캠프 바이브코딩 팀 프로젝트(3인)**  
- 재고 소진 예상일이 입고 예정일 + 여유일보다 빠르면 위험으로 판정하는 규칙을 SQL 뷰로, 요청·승인 순서를 DB 함수로 구현
- Supabase PostgreSQL 표 10개와 RLS 설계, DB 통합 시험 167개 검증 (팀 전체 자동 시험 396개 통과), Vercel 배포
- 경계 사례를 넣은 **가상 시나리오 20개**에서 기존 규칙 1개, 새 규칙 7개 검출

### ⚡ 1시간 뒤 전력 예측 및 피크 사전경보 관제 대시보드
**2026.09 – 10 | 제6회 K-인공지능 제조데이터 분석 경진대회 (팀 3인)**  
- 시간 표기 이상 48건 복원, 6,168시간 결측 0건으로 정제, 셧다운 구간 분리
- LSTM+TCN 앙상블로 RMSE 8.67kW 달성 (전주 같은 시각 기준선 대비 30.0% 감소), Dash 관제 화면 구현

### 🔌 설비 상태 15분 후 예측 및 변압기 예지보전 대시보드
**2026.09 | LS 부트캠프 데이터 분석 프로젝트 (팀 3인)**  
- 센서 5종을 15분 단위로 통합(27,607행 × 63열), 미래 기후값 배제로 정보 누수 차단
- 15분 선행 예측 R² 절연유 온도 0.969, 역률 0.961, 왜형률 0.907

### 🏪 전통시장 가격 정보 비대칭 해소: 물가 대시보드와 정책 제안
**2026.04 – 05 | 서울특별시 빅데이터 경진대회 (팀 3인)**  
- 3개년 원본 319,296건을 317,455행 · 22열로 정제, 품목별 변동계수(CV)에 Z-Score를 차등 적용한 4단계 이상치 기준 설계
- 지역·시장별 물가지수 Tableau 대시보드 단독 구현

### ♿ 장애인 체육 시설·종목 편중 분석과 맞춤형 추천 앱
**2025.08 – 12 | 국민체육진흥공단 공모전 (DA 1 · BE 2 · FE 1)**  
- 장애유형–종목 연관성 Cramér's V 0.417 확인, 추천 기준 수립
- API 명세와 분석 데이터 1:1 대조 후 AWS RDS에 적재해 앱과 연동

### 💳 지역 간 소비 불균형 해소를 위한 카드 결제 데이터 분석
**2025.07 – 08 | 부산 DIVE 해커톤 (DA 1 · BE 1 · FE 1 · PM 1)**  
- 수백만 건 카드 데이터를 Chunk 단위로 처리, 소비 집중도 지수 설계, K-means로 상권 특성 정의
- 시간대별 쿠폰·리워드 전략과 ‘스팟 정복 챌린지’ 기획

### 🔬 만성질환 예측 및 대시보드 서비스 · 🏆 데이터톤 프로젝트 대상
[![GitHub Repo](https://img.shields.io/badge/Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jhk4308/health-survey-disease-prediction)

**2024.12 – 2025.01 | 멋쟁이사자처럼 데이터 분석 3기 (팀 4인)**  
- 국민건강영양조사 258개 컬럼에서 분석 대상 선정, 가족 ID 역추적으로 가족력 결측 보완
- 다중 출력 모델 + Conv1d 딥러닝 Soft Voting 앙상블, AUC 고혈압 0.9357 · 당뇨 0.9328 · 이상지질혈증 0.8257
- CSV 업로드 기반 Streamlit 예측 대시보드 구현

### 🛍️ 백화점 거래 데이터 기반 고객 결혼 여부 예측
[![GitHub Repo](https://img.shields.io/badge/Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jhk4308/department-store-marriage-prediction)

**2024.10 – 11 | 멋쟁이사자처럼 파이널 프로젝트 (팀 4인)**  
- 구매 시간·요일·상품군·브랜드·지점·환불 패턴으로 파생변수 설계, 스태킹·평균·가중평균 앙상블 비교
- Kaggle Private Score 0.741859, CV·Public·Private 비교로 검증 방식 개선 필요성 도출

---

## 📫 Contact

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jhk2858@gmail.com)
[![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)](https://www.notion.so/Jung-Hyun-Kim-b170ecdbdebe48b0b4c79ce6e7a2335f)
[![Portfolio](https://img.shields.io/badge/Portfolio-3A57D3?style=for-the-badge&logo=githubpages&logoColor=white)](https://jhk4308.github.io/)
