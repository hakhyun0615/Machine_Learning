# AdaBoost(Adaptive Boosting)

## 하이퍼파라미터
- n_estimators: 약한 학습기의 수
- learning_rate: 학습률
- base_estimator: 기본적으로 DecisionTree를 약한 학습기로 사용(다른 학습기도 사용 가능)

## 장단점
### 장점
- 과적합의 영향을 덜 받음
- 유연함
    - 기본 학습기에 제한이 없음
    - 손실 함수를 여러가지 사용 가능
### 단점
- 이상치에 민감
- 모든 앙상블 계열이 그렇듯이 한 입력 변수와 출력 변수간의 관계를 해석하기 어려움