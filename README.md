# boston-housing-regression

# 🏠 Boston Housing 회귀 분석 보고서

이 프로젝트는 Boston Housing 데이터를 기반으로  
주택 중위가격(`medv`)을 다양한 변수 조합으로 예측한 회귀 분석 실습입니다.

## 📁 파일 설명

- `Boston_Regression_Analysis.ipynb`: 전체 분석 코드가 포함된 노트북
- `heatmap.png`, `histogram.png`, `residuals.png`: 시각화 이미지
- `README.md`: 프로젝트 요약 및 사용 방법 안내

## 📊 회귀 모델 요약

| 회귀 모델                 | 결정계수 (R²) | AIC 값 |
|---------------------------|----------------|---------|
| medv ~ rm                 | 0.484          | 3350    |
| medv ~ lstat              | 0.544          | 3287    |
| medv ~ crim               | 0.151          | 3602    |
| rm + lstat + ptratio      | **0.679**      | **3114** |

## ✅ 주요 결과

- `rm`, `lstat`, `ptratio`를 포함한 모델이 가장 성능이 좋았음
- 단변량보다 다변량 모델의 예측력이 훨씬 높음
- 잔차 플롯을 통해 선형회귀 가정을 잘 만족하는지도 확인함

## 🧪 실행 방법

1. Google Colab 또는 JupyterLab에서 `.ipynb` 파일 열기
2. 상단부터 셀을 순서대로 실행

---

📌 본 분석은 조별 실습 과제로 제출되었으며, 변수 조합 실험과 성능 비교를 중심으로 작성되었습니다.
