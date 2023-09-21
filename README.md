# Deep-Learning-Approaches-to-RUL-Prediction-of-Lithium-ion-Batteries

## NMC-LCO 18650 배터리 RUL 예측

####    0.<span style="color: red;"> Hawaii Natural Energy Institute에서 공개한 실제 NMC-LCO 18650 배터리 시험 데이터를 활용해서 데이터 분석을 진행함
    
####    1. <span style="color: red;"> 배터리 RUL에 영향을 주는 여러 인자들 중 충방전 할때 변화하는 값들의 의미를 이해하였고, 실제 분석도 진행했음 </span>
    
    
####    2. <span style="color: red;">   데이터를 확인 결과 이상치가 많이 있었는데, 이를 해결하기 위해 통계적 방법을 적용함 </span>

    
    
#### 3. 실제 현업에서도 여러 가지 이유로 이상치가 나올 수 있음. 대표적인 것들이 노이즈, 센서 이상, 데이터 계측 시스템 이상 등이 있음
   - 이러한 상황에 대비하여 통계적 접근을 통해 데이터를 지우거나, 현업 지식을 사용하는 것이 중요하단 것을 알았음

#### 4. 또한, 데이터들간의 상관성 분석을 진행하였는데, 상관성이 높은 데이터들이 있었음. 이럴 때도 여러 가지 판단 요건에 의해 데이터를 가공함 (실제로 연관이 있는지, 데이터의 형태는 어떤지, 현업 지식으로 판단하였을 때 실제로 연관성이 서로 있는 데이터인지 등 종합적인 판단이 필요함)

   

#### 5. <span style="color: red;"> 또한 회귀 머신러닝 알고리즘을 사용하여 모델을 구축하였고, 배터리 RUL을 측정하였음. 선형 회귀는 분류와 다른 평가 지표를 사용하는데, 그 중 R^2, RMSE 평가 지표에서 각각 95%, 76 정도의 성능을 보임. RUL을 잘 예측하는 모델을 만들 수 있었음 </span>
