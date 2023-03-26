## DACON: Basic 전화 해지 여부 분류 AI 경진대회

1️⃣ 데이터 로드

2️⃣ EDA(Exploratory Data Analysis)
- 기술통계값 확인
- 히스토그램 시각화
- label값 countplot 시각화
- 변수 간 상관계수 분석 및 결측값 확인
- 이상치 확인 및 제거

3️⃣ 데이터 분할
- X_train, X_valid, y_train, y_valid로 분할

4️⃣ Feature Engineering
- 파생변수 생성
- 데이터 구간화
- 로그 변환
- RobustScaler 사용

5️⃣ 모델 선택 및 학습
- XGBClassifier
- LGBMClassifier

6️⃣ 모델 평가 및 성능 향상
- RandomSearchCV를 이용하여 하이퍼파라미터 튜닝
- 교차 검증(cross-validation)
- 평가기준: Macro F1 Score
