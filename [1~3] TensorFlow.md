# 1강
## What is ML?
- Machine learning (머신러닝)

## Supervised/Unsupervied learning learning
- regression 
- binary classification  
- muti-label classification

# 2강
## Regression
- 회귀 >> 전체평균으로 돌아가려 한다(?)
## Linear Regression
- 데이터를 잘 대변하는 직선의 방정식을 찾는 것  
![Linear Regression](https://upload.wikimedia.org/wikipedia/commons/3/3a/Linear_regression.svg)
## Hypothesis - Which hypothesis is better?
- Hypotheis : H(x) = Wx + b  
- Cost : cost(W.b:) = 1/m * 시그마(H(x) - y)^2  
- Cost - 실제 데이터와 선형 가설 데이터와 의 차이  
- Cost의 총합이 작을 수록 유리함  
- Goal : Minimize cost!!

# 2강 실습
- cost = tf.reduce_mean(tf.square(hypothesis - y_data))  
- tf.reduce_mean() : 차원 감소?  
- tf.square() : 제곱
## Gradient descent (경사 하강 알고리즘)
- minimize cost(W,b)  
- A.assign_sub(B) : A= A - B

# 3강 -How to minmize cost?
## Gradient descent algorithm
1. 추정을 통한 값 예측
2. W,b 지속적 업데이트 > cost 최소화 방향으로 
3. cost 최소화 판단까지 반복

# 3강 실습 
# import numpy?
-numpy.linspace
