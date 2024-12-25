# 회귀 앙상블을 이용한 집 값 예측

##  프로젝트 개요  
이 프로젝트는 다양한 피처(특징)와의 관계를 분석하여 **집값(Price)**을 예측하는 회귀 앙상블 모델을 개발하는 데 중점을 둡니다.  
다중 회귀 모델과 앙상블 기법을 활용해 예측 성능을 향상시키는 것을 목표로 합니다.

---

##  주요 기능
- **데이터 전처리:**  
  결측치 처리
- **특징 선택:**  
  Price에 가장 영향을 미치는 주요 피처를 선택.
- **회귀 앙상블 모델 구현:**  
  - 단일 회귀 모델(Linear Regression, polynomial Regression, K-nearest-neighbor-regression)
  - 앙상블 적용 (평균 앙상블, voting 앙상블)
- **모델 성능 평가:**  
  MSE, R2와 같은 지표들을 통한 예측 모델의 성능 평가.

---

## 데이터 출처
“House Prices Regression” dataset,Kaggle.
데이터 생산자: Malak Al-Aabiad
분석에 사용한 케글 데이터 URL
https://www.kaggle.com/datasets/malakalaabiad/house-prices-regression