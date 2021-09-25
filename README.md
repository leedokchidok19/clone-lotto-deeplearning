# clone-lotto-deeplearning
로또 번호 딥러닝

# 로또 번호 예측
+ 데이터 수집
  - 동행 복권-1회차부터 현재 회차까지   
    csv 파일로 범주형 데이터화
+ 데이터 전처리-원 핫인 코딩 처리
  - [원-핫 인코딩(One-Hot Encoding)](https://wikidocs.net/22647)
+ 모델 구성-LSTM(RNN 계열)
  - 시계열 데이터, 자연어 데이터 처리 등에   
    사용되는 딥러닝 모델   
    예) 날씨, 주식 등에 사용되는 데이터    
    혹은 자연어 데이터처럼 이전 데이터가  
    다음 데이터에 영향을 주는 형태의 데이터 처리에    
    사용되는 딥러닝 모델입니다   
    즉, 로또 번호도 이전 번호가 다음 번호랑   
    연관이 있을 거라는 가정하에 이전 번호들을 분석해서 다음 데이터를 예측
+ 모델 입출력 정의 - 지도학습
  - 지도학습 정의   
    지도학습이란 문제와 정답을 줘서 모델을 학습    
    이전 회차 당첨 번호를 주고 다음 회차 번호를 정답으로 학습

---
# Reference
[로또 예측 사이트](https://animalface.site/lotto)    
참고 동영상 : [조코딩 유튜브 채널](https://www.youtube.com/watch?v=3G3zExNItj0)   
참고 문헌:
+ [김태영님 블로그](https://tykimos.github.io/2020/01/25/keras_lstm_lotto_v895/)    
+ [딥 러닝을 이용한 자연어 처리 입문](https://wikidocs.net/book/2155)
