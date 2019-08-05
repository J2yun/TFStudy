# 4강 - Multi-variable linear regression
## Hypothesis
- H(x) = Wx + b  
  -> H(x1,x2 , ... , xn) = w1x1 + w2x2 + ... + wnxn +b
## Cost Fuction
-cost(W,b) : 1/m * 시그마(H(x1,x2,x3)-y)^2
## Matrix
- 행 * 열  
- H(x) = X*W

# 5강 - Logistic Regression
## what is logistic regression?
- Classification  
  - ex) pass/fail, spam/not spam, real/fake -> [0,1]
- Logstic vs Linear  
  -shoe size, the number of workers VS time, heigt, weight
## Hypothesis Representation
- hypothesis = tf.sigmoid(z)
> 여기부터골때리네
> 대충 알겠는데 거지같다 다음시간은 클래스가 추가되네 오바다  
> 무적권 다시들어라

# 6강 - Softmax Regression
![](https://user-images.githubusercontent.com/47270758/62478373-ec380980-b7e5-11e9-9cd5-153d667101ed.PNG "softmax")
## Multinomial classification
##Cost function
