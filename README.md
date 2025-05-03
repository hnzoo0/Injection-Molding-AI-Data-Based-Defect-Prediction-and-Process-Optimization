## 데이터셋 다운로드
[다운로드](https://www.kamp-ai.kr/aidataDetail?AI_SEARCH=%EC%82%AC%EC%B6%9C&page=1&DATASET_SEQ=4&EQUIP_SEL=&GUBUN_SEL=&FILE_TYPE_SEL=&WDATE_SEL=)



# 📌 프로젝트 주제

---

**[개요]** 📝

- 사출성형 공정에서 발생하는 다양한 불량 유형(쇼트숏, 플래시, 싱크마크 등)의 원인을 데이터로 분석하여 머신러닝 기반 불량 예측 모델 개발.  
- 데이터 기반으로 생산 조건 최적화 및 품질 향상을 도모.

---

**[배경]** 🔍

- 현재 제조 현장에서는 불량 선별이 대부분 작업자의 육안 검수에 의존 → 품질 편차 발생.  
- 불량 발생 원인 규명이 어렵고, 원인 파악까지 시간이 오래 걸림.  
- 불량 발생 시점에서 공정을 제어하는 것이 어려워 즉각적 대응 한계.

---

**[주제]** 🎯

- 공정 변수(온도, 압력, 시간, 속도 등)와 불량률 간 상관관계 파악.  
- 지도 학습 및 이상 탐지 기반 불량 예측 모델 개발.  
- 데이터 기반 생산조건 최적화 제안.

---

**[설명]** 🧪

사출성형 공정 데이터를 전처리 후, 변수 간 상관관계를 분석하고 머신러닝 모델로 불량 여부를 예측한다. 다양한 알고리즘을 비교해 최적 모델을 선정하며, 주요 변수 기반으로 생산조건을 최적화한다. 분석 결과는 대시보드로 시각화하여 현장 적용성을 높인다.

---

**[데이터]** 📊

- 데이터 출처: KAIST 제공 「사출성형기 AI 데이터셋」  
- 데이터 형식: CSV  
- 주요 데이터: labeled_data.csv (PassOrFail 값 포함)  
- 사출성형기에서 수집된 센서 데이터 (온도, 압력, 시간, 속도, 위치 등 총 25개 이상 변수)

---

## 🧭 프로젝트 목표

- 사출성형 공정에서 발생하는 불량품을 사전에 예측하여 품질 향상 및 불량률 감소.  
- 주요 공정 변수의 영향도 분석을 통해 최적의 생산 조건 제시.  
- 데이터 기반 품질 관리 시스템 구축 및 대시보드 제공으로 현장 작업자 대응 시간 단축.

---

## ❗ 문제 정의

- 분석 및 시각화의 중점  
    - 변수별 불량 발생 영향도 분석 (온도, 압력, 시간, 속도 등)  
    - 공정별 주요 불량 유형의 발생 원인 시각화  
    - 불량 발생 패턴과 정상 패턴 비교  

- 문제의 필요성 및 중요성  
    - 육안 검수 의존에서 벗어나 데이터 기반 품질 관리 가능.  
    - 불량 발생 원인 파악 시간 단축 → 생산성 향상.  
    - 불량률 감소로 제조 비용 절감 및 납기 안정성 확보.
 


----------------------------------------------------------------------------------------------------------------------------------------------

## Dataset Download
[download](https://www.kamp-ai.kr/aidataDetail?AI_SEARCH=%EC%82%AC%EC%B6%9C&page=1&DATASET_SEQ=4&EQUIP_SEL=&GUBUN_SEL=&FILE_TYPE_SEL=&WDATE_SEL=)

## 📌 Project Topic
[Overview] 📝

Development of a machine learning-based defect prediction model by analyzing the causes of various defect types (short shot, flash, sink mark, etc.) occurring in the injection molding process using data.
Aiming to optimize production conditions and improve quality based on data.

## [Background] 🔍

Currently, defect screening in manufacturing sites largely relies on manual visual inspection by operators → leading to quality variation.
It is difficult to identify the causes of defects, and it takes a long time to determine the root cause.
Immediate response is limited as it is difficult to control the process at the point of defect occurrence.

## [Topic] 🎯

Identifying the correlation between process variables (temperature, pressure, time, speed, etc.) and the defect rate.
Developing defect prediction models based on supervised learning and anomaly detection.
Proposing data-driven production condition optimization.

## [Explanation] 🧪

After preprocessing the injection molding process data, the correlation between variables is analyzed, and defect occurrence is predicted using a machine learning model. The optimal model is selected by comparing various algorithms, and production conditions are optimized based on key variables. Analysis results are visualized through a dashboard to enhance applicability in the field.

## [Data] 📊

Data Source: KAIST provided "Injection Molding Machine AI Dataset"
Data Format: CSV
Key Data: labeled_data.csv (Includes PassOrFail values)
Sensor data collected from the injection molding machine (Total of 25+ variables including temperature, pressure, time, speed, position, etc.)


### 🧭 Project Goals
Improve quality and reduce defect rate by predicting defects occurring in the injection molding process in advance.
Propose optimal production conditions through analysis of the influence of key process variables.
Establish a data-driven quality management system and provide a dashboard to shorten response time for field operators.

## ❗ Problem Definition
- Focus of Analysis and Visualization

  - Analysis of the influence of each variable on defect occurrence (temperature, pressure, time, speed, etc.)
  - Visualization of the causes of major defect types for each process step
  - Comparison of defect occurrence patterns and normal patterns


- Necessity and Importance of the Problem
  - Enables data-driven quality management, moving away from reliance on visual inspection.
  - Shortens the time required to identify the causes of defects → leading to productivity improvement.
  - Reduces manufacturing costs and ensures delivery stability by decreasing the defect rate.


