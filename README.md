# LDL, BMI, 음주 여부와 혈압 간 관계 분석
Statistical Analysis of Health Indicators Using Health Check Data

건강검진 데이터를 활용해 LDL 콜레스테롤, BMI, 음주 여부와  
수축기 혈압 간 관계를 통계 분석을 통해 검증한 프로젝트입니다.

---

## Project Overview

콜레스테롤 수치가 높을수록 혈압도 높아질까?  
이 질문에서 출발해 건강 지표 간 관계를 통계적으로 분석했습니다.

LDL 콜레스테롤, BMI, 음주 여부와 수축기 혈압 간 관계를  
Spearman 상관 분석, Welch t-test, ANOVA 등을 통해 검증했습니다.

---

## Dataset

국가건강검진 데이터 샘플  

- 약 2,000건 데이터 사용
- LDL 결측치 제거 후 분석 데이터 구성
- 주요 변수: LDL, 수축기 혈압, BMI, 음주 여부

---

## Analysis Methods

- Shapiro-Wilk normality test
- Spearman correlation analysis
- Welch t-test
- ANOVA

---

## Key Insight

LDL 콜레스테롤은 혈압과 직접적인 상관관계를 보이지 않았지만,
BMI는 수축기 혈압과 유의미한 관계를 보였습니다.

이는 혈압과 관련된 건강 지표를 해석할 때
단일 변수보다는 여러 건강 지표를 함께 고려할 필요가 있음을 시사합니다.

---

## Portfolio

📄 View Full Portfolio  
- Portfolio PDF: [health-check-analysis.pdf](./health-check-data-analysis-portfolio.pdf)
---

## Project Structure

```
health-check-analysis
│
├ README.md
└ health-check-analysis.pdf
```
