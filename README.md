# PredictPriceSeoulAPT

- 프로젝트 개요: 이 레포지토리는 서울 지역 아파트 가격을 예측하기 위한 데이터 분석 및 모델링 과정을 담고 있습니다. 데이터 전처리, 탐색적 데이터 분석(EDA), 모델링 등의 단계로 구성되어 있으며, 각 단계별 코드와 결과를 포함하고 있습니다.

## 사용 기술
- Python: 데이터 처리 및 분석
- Pandas: 데이터 프레임 조작 및 관리
- NumPy: 수치 연산
- Matplotlib/Seaborn: 데이터 시각화
- Scikit-learn: 머신러닝 모델링
- geopy: 좌표를 위경도로 변환

## 디렉토리 및 파일 설명
- EDA/: 탐색적 데이터 분석을 위한 노트북과 스크립트.
- Modeling/: XGBoost 와 transformer(BERT), RandomForest 등 예측에 필요한 모델링 코드.
- PreprocessingCode/: 데이터 생성부터 데이터 전처리(이상치제거, 파생변수 생성), 데이터 시각화(EDA)까지의 코드.
- RANDOMSAMPLING/: 데이터 샘플링 관련 코드. 
- 좌표추출/: 서울 내 상가 및 역의 좌표 데이터를 위경도로 변환하는 코드.
