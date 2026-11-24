# 통신 서비스 고객 이탈 예측 및 주요 요인 분석

## 1. 프로젝트 소개

본 프로젝트는 IBM Telco Customer Churn 데이터를 활용하여 통신 서비스 고객의 이탈 여부를 예측하고, 고객 이탈에 영향을 미치는 주요 요인을 분석하는 프로젝트입니다.

데이터 탐색 및 시각화를 통해 고객의 특성을 파악하고, 다양한 머신러닝 분류 모델을 적용하여 예측 성능을 비교하였습니다.

## 2. 프로젝트 목표

- 통신 서비스 고객 데이터의 특성 및 분포 파악
- 고객 이탈 여부와 관련된 주요 요인 분석
- 머신러닝 모델을 활용한 고객 이탈 예측
- 모델별 예측 성능 비교 및 분석

## 3. 사용 데이터

- 데이터명: IBM Telco Customer Churn
- 데이터 유형: 통신 서비스 고객 정보
- 데이터 크기: 7,043개 행, 21개 열 (원본 데이터 기준)

## 4. 사용 기술 및 라이브러리

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost

## 5. 머신러닝 모델

본 프로젝트에서는 다음 네 가지 모델을 사용하였습니다.

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. XGBoost

## 6. 주요 분석 결과

- Logistic Regression: Accuracy 0.8038
- Decision Tree: Recall 0.6150, F1-score 0.6085
- Random Forest: Feature Importance 분석
- XGBoost: ROC-AUC 0.8398

Feature Importance 분석 결과, tenure, TotalCharges, MonthlyCharges 및 계약 유형 등이 고객 이탈 예측에 중요한 변수로 나타났습니다.

## 7. 프로젝트 파일

- `통신서비스_고객이탈_예측_분석.ipynb`: 데이터 탐색, 시각화, 전처리, 머신러닝 학습 및 성능 평가를 포함한 분석 노트북

## 8. 데이터 출처

IBM Telco Customer Churn Dataset

[IBM Sample Data - Telco Customer Churn](https://community.ibm.com/community/user/businessanalytics/blogs/steven-macko/2019/07/15/telco-customer-churn-1113)
