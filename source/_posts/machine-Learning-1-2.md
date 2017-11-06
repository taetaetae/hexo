---
title: 모두를 위한 딥러닝 강좌 정리 Lec 01~02
date: 2017-11-06 17:36:18
categories: tech
tags:
  - machine-learning
---
모두를 위한 딥러닝 강좌 정리 Lab01~02
<!-- more -->
> 맘 맞는 사람들끼리 머신러닝인지 러닝머신인지 머싱러닌 인지 러닌머싱 인지 스터디를 시작하였고, 그참에 김성훈 교수님께서 감사하게도 유투브 강의를 보기로 결정, 제대로 공부 해보고자 따로 정리를 블로깅 해본다.

# # Lec-1 : 기본적인 Machine Learning 의 용어와 개념 설명
- 머신러닝이란 무엇인가?
  - 정확한 프로그래밍이 제한되는 경우가 있다.
  - 프로그램이 데이터를 학습해서 배울수 있도록 능력을 갖게끔 하는 프로그래밍
- 머신러닝의 학습방법 종류 (머신러닝이 학습하는..)
  - Supervised learning (지도학습)
    - 정해진 데이터(Training data set)를 가지고 학습하는 방법 (레이블이 정해져있다.)
    - ex
      - 여러 이미지를 주고 강아지일까, 고양이 일까 확인 (이미지 묶음을 주고 학습)
      - Image labeling, Email spam filter, Predicting exam score
  - Unsupervised learning (비지도학습)
    - 데이터는 있지만 레이블이 정해지지 않았다. 
    - ex : 뉴스 그룹핑, Word clustering
- Type of Supervised learning (지도학습의 종류)
  - regression : 정해진 범위 내에서 값을 찾는 방법
  - binary clasfication : pass / non-pass (둘중 하나)
  - multi-label clasfication : 등급을 주는 방법
- 용어 정리
  - Tensor : array 또는 list 로서 다차원 자료형
  - Rank : 배열의 차원을 나타냄
  ```
  예 )
  483 : rank 0
  [1.1, 2.2, 3.3] : rank 1
  [[1,2,3], [4,5,6], [7,8,9]] : rank 2
  [[[2],[4],[6]], [[8],[10],[12]], [[14],[16],[18]]] : rank 3
  ```
  - Shape : Python 리스트 / 정수형 튜플 또는 TensorShape class로 표현 할 수 있음
  - Data types : 말그대로 데이터 타입, 정수냐 소수냐 등등
  ---
# # Lec-2 : Linear Regression의 Hypothesis 와 cost 설명
- x(데이터), y(결과) 가 주어지면 그래프를 그리며 어떤 기울기가 맞는 기울기 일까(추측) 학습하는것이 Linear Regression
![](Linear_Regression.png)
- Cost function : 임의로 세운 가설과 현재 데이터 set과 얼마나 다른가를 확인
- 결국 머신러닝으로 해야하는 목표 : Cost 를 최소화 해야 근접한 값을 얻을수 있다.
![](cost_function.png)

--- 
- 참고
  - 모두를 위한 딥러닝 : https://www.youtube.com/channel/UCML9R2ol-l0Ab9OXoNnr7Lw
  - 윈도우/텐서플로우 설치 : http://aileen93.tistory.com/58