해당 데이터는 기존 전처리를 완료한 데이터이며, 도서 현장에서 바로 써먹는 데이터 분석 with 파이썬으로 실습해봅니다.
다양한 탐색적 데이터분석과 시각화요소, 그리고 알고리즘에 따른 모델링을 학습합니다.

# Chick-Growth

## 병아리 성장 데이터 분석

### 프로젝트 목표
병아리의 성장 및 관련 사항 분석하고, 양계장 비즈니스에 적용하기 위한 분류 및 예측


#### 1. 몇 마리가 부화했고, 부화율은 얼마나 될까요?
- 간단한 기본 통계 분석
- bar

#### 2. 부화한 병아리들의 몸무게는 얼마일까요?
- 분포도 확인
- histogram, boxplot, Kernel Density Plot

#### 3. 사료 제조사별 성능 차이가 있을까요?
평균 몸무게 비교 하며 정규분포와 가설검정을 진행합니다. <br>
- 분포도 확인
- 정규분포여부 및 가설검정p-value값 
- boxplot, scipy

#### 4. 병아리 성장에 영향을 미치는 요소는 무엇일까요? 
상관분석을 진행합니다.<br>
- 상관계수
- Heatmap

#### 5. 병아리의 몸무게를 예측할 수 있을까요?
회귀분석을 진행합니다. <br>
1) 단순선형 회귀분석<br>
   - 결과 해석 
   - scatter , 잔차 histogram 
2) 다중 회귀분석 <br>
   - 후진소거법으로 진행 
   - 결과 해석
   - 다중공선성 확인
   - 잔차 histogram
3) 비선형 회귀분석 <br>
   - 분포도 확인 
   - 결과 해석
   - scatter plot 
   - 독립변수x의 세제곱
   - 결과 해석
   - scatter plot

#### 6. 병아리의 성별을 구분할 수 있을까요? 
로지스틱 회귀 분석(예측으로 분류)을 진행합니다. 
- 분포도 확인 
- scatter , histplot, boxplot, 
- 로지스틱 회귀 분석 
- 결과 해석
- 로지스틱 회귀모델 (분류알고리즘) 성능평가
   - 정오분류표 
   - 분류 리포트(정확도,정밀도,민감도)
   - ROC 커브 
   - AUC 계산 

#### 7. 병아리의 품종을 구분할 수 있을까요? (분류) 
1. Naive Bayes Classification
2. KNN
3. Decision Tree<br>

#### 8. 병아리의 품종을 구분할 수 있을까요? (앙상블)
1. Bagging
2. Boosting (AdaBoost, GBM : Gradient Boosting Machine 경사하강법)
3. Random Forest (Bagging을 적용한 의사결정나무 Decision Tree)
4. SVM Support Vector Machine
5. XGBoost
6. XGBoost 하이퍼 파라미터 튜닝 (그리드 서치) 
7. 분류 알고리즘 결과 정리 

