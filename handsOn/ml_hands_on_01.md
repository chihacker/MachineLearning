# Hands On #1

## 머신러닝 분류
### 머신러닝 분류1
#### Supervised learning
훈련 데이터에 label 이 포함된 학습 ( 학습 데이터에 답이 있다. )
  * K-Nearest Neighbors
  * Linear Regression
  * Logistic Regression
  * Support Vector Machines
  * Decision Tree, Random Forests
  * Neural networks

#### Unsupervised learning
훈련 데이터에 레이블이 없다
* Clustering
  - K-means
  - Hierarchical Custer Analysis
  - Expectation Maximization
- Visualization, Dimensionality reduction
  - Principal Component Analysis
  - Kernel
* Association rule learning

#### Semisupervised learning
레이블이 있는것과 없는게 섞여 있다.
ex> 구글 포토

#### Reinforcement learning
action 에 대해 reward 와 penalty 를 부여 하여 학습 시키는 것
ex> 알파고

### 머신러닝 분류2
#### Batch learning
데이터 전부를 학습
#### Incremental learning(Mini-batch)
데이터를 순차적으로 학습

### 머신러닝 분류3
#### Instance-based learning
기존 사례와의 유사도
#### model-based learning
샘들들의 모델을 만들어 예측

## 머신러닝 도전과제
* Sampling nosie
* Sampling bias
* 품질이 낮은 데이터
* 관련없는 특성 제거 ( feature engineering )
  - feature selection, feature extraction
- overfitting
  - 파라미터가 적은 모델 선택
  - 훈련 데이터의 특성 수 축소
  - 모델에 제약 조건 추가 ( hyperparameter )
  - 더 많은 훈련 데이터
  - noise 제거 ( 오류데이터 수정 및 이상치 제거 )
- Underfitting
  - 모델 파라미터가 많은 강력한 모델 선택
  - 더 좋은 데이터의 특성 추가
  - 모델의 제약 완화

## 테스트와 검증
* train set 과 test set
  - 보통 데이터를 8:2 로 가름
- cross-validation
  - 데이터를 서브셋으로 나눠서 훈련 테스트 반복
