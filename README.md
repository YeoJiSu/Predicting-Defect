# predictingDefect
> ### 🦠 살균기 불량 판별 최적 예측 모델 개발
> 개발 환경: [Google Colab](https://colab.research.google.com/drive/1VYaNFpjZ4k29XI5_N5IISbdFYp6q6BMO?usp=sharing) <br>
> 사용 언어: Python <br>
> 개발 기간: 2023.03.02 ~ 2023.03.14 <br>


### 🙌 비고

- 식품 살균 공정의 살균기 데이터셋을 활용하여 품질의 불량 여부를 판별하고자 함.
- **지도 학습 알고리즘**들을 활용해 각각의 모델을 만들어보고, 분류성능평가지표를 활용해 성능을 비교하고자 함.
- 알고리즘별로 예측이 잘되는 이유 혹은 잘 안되는 이유에 대한 분석을 진행함.
- 가장 성능이 좋은 모델을 찾고자 함.

### 🙌 진행
- [전과정 코드로 보기](https://github.com/YeoJiSu/Predicting-Defect/blob/main/predictingDefect.ipynb)
- [겪은 문제들과 여러 가설들을 세우면서 해결한 과정](https://github.com/YeoJiSu/Predicting-Defect/issues/3)
- [학습 결과에 대해 분석한 내용](https://github.com/YeoJiSu/Predicting-Defect/issues/4)

### 🙌 결과 요약
_랜덤포레스트 알고리즘을 사용한 모델이 가장 예측을 잘한다._

    ROC score: 0.9957
    TNR(실제 불량을 불량으로 판단할 확률): 0.9931
    TPR(실제 양품을 양품으로 판단할 확률): 0.9983

- 지도학습 알고리즘들의 성능 비교 결과

   <img src="https://user-images.githubusercontent.com/76769044/224890525-ba3f7d1e-2bfd-4d2e-90b1-adeaba7d4038.png" width="750"/>

