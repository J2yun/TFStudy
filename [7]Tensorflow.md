# 7강 - Application & Tips
## Learning rate
- Gradient (기울기)  
- Good and Bad  
![](https://user-images.githubusercontent.com/47270758/62682374-f715b880-b9f6-11e9-85db-ad0a31283539.PNG)  
- Annealing the learning rate  
![RR_an](https://user-images.githubusercontent.com/47270758/62683407-4f4dba00-b9f9-11e9-9c9f-7119c08e4001.PNG)

## Data preprocessing
- Feature Scaling - Normalization
- Noisy Data (쓸모없는 데이터)

## Overfitting
- Set a features 
  1. Get more training data
  2. Smaller set of features (차원 줄이기) - (PCA)
  ![PCAcode](https://user-images.githubusercontent.com/47270758/62683807-4f01ee80-b9fa-11e9-9244-b58ee1955871.PNG "PCA 알아보기")
  3. Add additional features
- Regularization (Add term to loss)  
![Regularization](https://user-images.githubusercontent.com/47270758/62684256-40680700-b9fb-11e9-917f-fa655c3c8a02.PNG)
- Solutions
  1. Feature Nomalization - 특징 정교화
  2. Regularization - 정교화
  3. More data (Data Augmentation)
  4. Dropout (0.5 id common)
  5. Batch Normalization

# L2_Loss 함수 
