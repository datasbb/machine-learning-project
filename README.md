# 머신러닝 분류/회귀 예측 분석 프로젝트 기록

- 2023.12.26(화) ~ 진행 중
- 사용 데이터 : 캐글, 데이콘, 빅데이터 콘테스트 등
- 모델 구분 : 분류(Classification), 회귀(Regression) 등

---

### 1. [머신러닝] Kaggle - 주택 가격 예측 프로젝트 : 회귀(Regression)

- **개요**
  - 주택 가격 예측 프로젝트로 주택 관련 6개의 변수 중 Price(주택 가격)을 타겟으로 예측함.

- **데이터셋**
  - [Housing Price Prediction Dataset](https://www.kaggle.com/datasets/muhammadbinimran/housing-price-prediction-data)

- **분석 결과(code)**
  - [ml_regression/housing_price_predict.ipynb](https://github.com/datasbb/machine-learning-project/blob/main/ml_regression/housing_price_predict.ipynb)
  - [코드 상세 설명 - Blog](https://blog.naver.com/databb/223303981394)

- **데이터 변수**
  - `SquareFeet` : 평방미터(평수)
  - `Bedrooms` : 침실(수)
  - `Bathrooms` : 욕실(수)
  - `Neighborhood` : 동네 유형(Rural, Suburb, Urban)
  - `YearBuilt` : 건설 연도
  - `Price` : 주택 가격

- **사용한 모델**
  - 선형회귀 : LinearRegression, Lasso
  - 앙상블모델 : RandomForestRegressor, GradientBoostingRegressor, xgboost
  - 거리 기반 : k-NN

- **성능 평가 지표**
  - R-Squared, RMSE
  
---

### 2. [머신러닝] Kaggle - 약물 투입 결과 예측 (분류, Classification)

- **개요**
  - 약물 투입 결과 예측 분류 프로젝트로 약물을 투입한 사람의 나이/성별, 약물 투입 결과를 나타내는 3개 변수, 분류 클래스인 약물 타입(5 Class)이 변수로 주어짐. 

- **데이터셋**
  - [Drug Classification](https://www.kaggle.com/datasets/prathamtripathi/drug-classification)

- **분석 결과(code)**
  - [ml_classification/drug_classify.ipynb](https://github.com/datasbb/machine-learning-project/blob/main/ml_classification/drug_classify.ipynb)
  - [코드 상세 설명 - Blog](https://blog.naver.com/databb/223311358149)

- **데이터 변수**
  - `Age` : 나이
  - `Sex` : 성별
  - `BP` : 혈압 수준 (Blood Pressure Levels)
  - `Cholesterol` : 콜레스테롤 수준
  - `Na_to_K` : 체내 나트륨과 칼륨 비율 (전해질 균형, Na to Potassium Ration)
  - `Drug` : 약물 타입

- **사용한 모델**
  - 앙상블모델 : RandomForestRegressor

- **성능 평가 지표**
- accuracy, precision, recall, f1-score
  
---