# 머신러닝 분류/회귀 예측 분석 프로젝트 기록

- 2023.12.26(화) ~ 진행 중
- 사용 데이터 : 캐글, 데이콘, 빅데이터 콘테스트 등
- 모델 구분 : 분류(Classification), 회귀(Regression) 등

---

### 1. [머신러닝] 캐글 - 주택 가격 예측 프로젝트 : 회귀(Regression)

- **개요**
    - 주택 가격 예측 프로젝트로 주택 관련 6개의 변수 중 Price(주택 가격)을 타겟으로 예측함.

- **데이터셋**
    - Housing Price Prediction Dataset → [링크](https://www.kaggle.com/datasets/muhammadbinimran/housing-price-prediction-data)

- **분석일**
    - 2023.12.26(화)

- **분석 결과(code)**
    - ml_regression/housing_price_predict.ipynb -> [링크](https://github.com/datasbb/machine-learning-project/blob/main/ml_regression/housing_price_predict.ipynb)

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

- **코드 상세 설명**
     - https://blog.naver.com/databb/223303981394

---