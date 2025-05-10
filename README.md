# 고객 이탈 예측 모델 📉
해당  프로젝트는 Telco 고객 데이터를 활용하여 고객이 이탈할지 여부를 예측하는 머신러닝 모델을 구현합니다.

## 🔍 프로젝트 개요

- 탐색적 데이터 분석 (EDA)
- 전처리 및 범주형 변수 인코딩
- 머신러닝 모델 학습 및 성능 비교
  - 로지스틱 회귀
  - K-Nearest Neighbor (KNN)
  - Ridge 분류기

## 📁 폴더 구조
customer-churn-prediction/
├── data/ # 원본 및 전처리된 데이터
├── eda.ipynb # 탐색적 데이터 분석 및 전처리
├── modeling.ipynb # 모델 학습 및 평가
├── .gitignore
├── requirements.txt # (선택) 사용한 패키지 목록
└── README.md

## 📈 사용한 모델

- 로지스틱 회귀 (Logistic Regression)
- K-최근접 이웃 (KNN, k=5)
- Ridge 분류기

## ⚙️Tech Stack

- Python (pandas, scikit-learn, joblib)
- JupyterLab
- Git/GitHub

## ✅ 모델 성능 예시

| 모델명             | 정확도 (Accuracy) |
|--------------------|------------------|
| Logistic Regression| 0.7989           |
| KNN                | 0.7463           |
| Ridge              | 0.7939           |

## 💻 실행 방법

1. 레포지토리를 클론합니다.
2. `data/` 폴더에 데이터셋 CSV 파일을 넣습니다.
3. `eda.ipynb`를 실행하여 전처리를 수행합니다.
4. `modeling.ipynb`를 실행하여 모델을 학습하고 평가합니다.

## 🙋‍♂️ 작성자

- GitHub: [SeungwooKim525](https://github.com/SeungwooKim525)
