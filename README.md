# Health Check Data Analysis

건강검진 데이터를 활용해  
LDL 콜레스테롤, BMI, 음주 여부와 수축기 혈압 간 관계를  
통계 분석을 통해 검증한 프로젝트입니다.

---

# Project Overview

콜레스테롤 수치가 높을수록 혈압도 높아질까?  
이 질문에서 출발해 건강 지표 간 관계를 통계적으로 분석했습니다.

특히 LDL 콜레스테롤이 혈압과 실제로 유의미한 관계를 가지는지 검증하고  
BMI 및 음주 여부와 혈압 간 관계도 함께 분석했습니다.

---

# Dataset

국가건강검진 데이터 샘플  

- 약 2,000건 데이터 사용
- LDL, 수축기 혈압, 음주 여부, BMI 등 주요 건강 지표 활용
- LDL 결측치 제거 후 최종 분석 데이터 구성

---

# Analysis Process

1. 데이터 전처리  
   - 결측치 제거  
   - LDL 이상치 범위 보정  

2. 파생 변수 생성  
   - BMI 계산  

3. 정규성 검정  
   - Shapiro-Wilk Test 수행  

4. 상관 분석  
   - Spearman Correlation  

5. 집단 평균 비교  
   - Welch t-test  
   - ANOVA

---

# Key Insight

- LDL 콜레스테롤 수치와 수축기 혈압 간 **유의미한 상관관계는 확인되지 않았습니다.**

- 반면 **BMI는 수축기 혈압과 통계적으로 유의미한 관계를 보였습니다.**

→ 건강 위험 요인은 단일 지표보다  
**복합적인 건강 지표의 상호작용 속에서 나타날 가능성이 있습니다.**

---

# Portfolio

📄 프로젝트 포트폴리오 PDF

[health-check-data-analysis.pdf](./health-check-data-analysis.pdf)
