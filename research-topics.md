# 마키나락스가 고민하는 문제들 

- Catastrophic forgetting을 극복하고 지속적으로 학습 가능한 온라인 딥러닝 모델 및 알고리즘을 만들 수 있을까?
  - Novel/Anomaly 정보가 없거나 극도로 적을 때 Novelty/Anomaly Detection 모델의 성능은 어떻게 평가할 수 있을까?
  - 온라인 환경에서 데이터의 양이 늘어남에 따라 모델 학습의 Regularization을 자동으로 조정하는 방법은 무엇일까? (Dynamic adjustment 방안)
  - 기존에 학습된 결과로부터 잘못된 레이블 정보를 효과적으로 폐기 학습 (manifold unlearning) 할 수 있는 방법은 무엇일까?
- 지도, 비지도, 준지도 딥러닝을 기반으로 이상 탐지(Novelty/Anomaly Detection)를 수행할 수 있는 효과적인 방안은 무엇일까? State-of-the-art (SOTA) 성능은 어떠하며, 이를 뛰어넘을 수 있는 방법은?
  - 모델 학습에 있어 불확실한 레이블 값 (Noisy label)의 효과적인 처리 방안은 무엇일까?
  - 극심한 레이블 불균형 데이터 셋 (Extreme class imbalance) 상황에서 어떻게 하면 효과적으로 딥러닝 모델을 학습하고 이상 탐지 및 분류에 활용할 수 있을까?
  - 온라인 환경에서 레이블 데이터양이 증가함에 따라 비지도에서 준지도로, 준지도에서 지도학습 방식으로 자연스럽게 전환할 수 있는 방법은 무엇일까?
- Multi-modality를 갖는 Multi-context 데이터를 효과적으로 모델링 할 수 있는 단일 딥러닝 모델을 만들 수 있을까?
- Data Scientist가 좀 더 빠르고 효과적으로 데이터를 분석할 수 있도록 Exploratory Data Analysis (EDA)를 체계화하는 방안은 무엇일까? 과연 어디까지 자동화할 수 있을까?
- 강화 학습을 활용하여 개선할 수 있는 산업 최적화 문제들을 어떤 것들이 있을까? (예: 데이터 센터, 자동 운송 시스템 최적화 등)
- 딥러닝 모델의 추론(Inference)에 대한 적절한 불확실성(Uncertainty) 측정 방법은 무엇일까? (베이지안 딥러닝?)
