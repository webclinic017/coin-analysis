# 코인 데이터 분석 프로젝트

> 바이낸스 카테고리 중 크게 3가지 분야에서 미래 가능성이 있는 코인 착출을 위한 분석

## 데이터 출처
- Coinmarketcap  [🔗Link](https://coinmarketcap.com/)
- Binance  [🔗Link](https://www.binance.com/)

## 분석 대상
- ETH
- BTH
- KP3R
- KP4R

## 단위
- 1시간, 24시간, 7일, 90일, 1년, 전체
- 금일봉 그래프와 단위 맞춰서 비교

## 업데이트 내역
- 개별의 가격 데이터 분석
  - 2022.02.03 : 기본 Facebook Prophet 모델 적용 [🔗Code Link](https://github.com/HwayoungYoon/coin-analysis/blob/main/%EA%B0%9C%EB%B3%84%EC%9D%98_%EA%B0%80%EA%B2%A9_%EA%B7%B8%EB%9E%98%ED%94%84%EB%A1%9C_%EC%A0%84%EB%A7%9D_%EC%98%88%EC%B8%A1_%EB%8D%B0%EC%9D%B4%ED%84%B0_%EA%B5%AC%EB%B6%84ver.ipynb)
  - 2022.02.06 : 데이터를 분할하지 않고 모두 사용, flexibility, 연간 계절성, 주간 계절성 고려 [🔗Code Link](https://github.com/HwayoungYoon/coin-analysis/blob/main/%EA%B0%9C%EB%B3%84%EC%9D%98_%EA%B0%80%EA%B2%A9_%EA%B7%B8%EB%9E%98%ED%94%84%EB%A1%9C_%EC%A0%84%EB%A7%9D_%EC%98%88%EC%B8%A1_%EB%8D%B0%EC%9D%B4%ED%84%B0_%ED%86%B5%ED%95%A9ver.ipynb)
  - 2022.02.06 : 예측의 상한선과 하한선을 포함한 결과 그래프 출력 [🔗Code Link](https://github.com/HwayoungYoon/coin-analysis/blob/main/%EA%B0%9C%EB%B3%84%EC%9D%98_%EA%B0%80%EA%B2%A9_%EA%B7%B8%EB%9E%98%ED%94%84%EB%A1%9C_%EC%A0%84%EB%A7%9D_%EC%98%88%EC%B8%A1_%EB%8D%B0%EC%9D%B4%ED%84%B0_%ED%86%B5%ED%95%A9%26%EA%B3%84%EC%A0%88%EC%84%B1_%EC%A0%9C%EA%B1%B0ver.ipynb)
  - 2022.06.16 : 그래프로 최적의 flexibility 값 탐색, 정확도 값을 포함하는 가격 예측 그래프 출력 [🔗Code Link](https://github.com/HwayoungYoon/coin-analysis/blob/main/%EA%B0%9C%EB%B3%84%EC%9D%98_%EA%B0%80%EA%B2%A9_%EA%B7%B8%EB%9E%98%ED%94%84%EB%A1%9C_%EC%A0%84%EB%A7%9D_%EC%98%88%EC%B8%A1_%EC%BD%94%EC%9D%B8%EB%A7%88%EC%BC%93%EC%BA%A1_%EC%B6%9C%EB%A0%A5ver.ipynb)
- 모멘텀
  - 2022.09.08 : 기본 모멘텀 전략 적용 [🔗Code Link](https://github.com/HwayoungYoon/coin-analysis/blob/main/Quant_Momentum_all.ipynb)

## To-Do
- 트위터 언급량과의 상관관계 분석
- 모멘텀 고도화
- 밸류 적용
- ARIMA, LSTM 모델 적합
- 미국 국채, ETP 등과의 상관관계 분석
