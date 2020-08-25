# Alexnet (CNN)

이미지 처리의 가장 기본적인 모델인 CNN에 대해서 정리한 자료입니다. 

## 목차 

CNN이란 무엇인지? 
- Convolution - Pooling - Fully Connected Layer 
- CNN의 Backpropagation 

CNN이 가지는 문제점 
- Gradient Vanishing 
- Gradient Exploding 

PyTorch를 이용한 실습 
- CNN_PyTorch_v1.ipynb 
  - 모든 트레인 데이터를 학습에 이용해서 예측함 
  - Train Accuracy : , Test Accuracy : 
  
- CNN_PyTorch_v2.ipynb
  - KFOLD를 이용해서 5번의 학습을 진행하고 해당 예측값을 Ensemble 
  - Train Accuracy : , Test Accuracy : 

- CNN_PyTorch_v3.ipynb
  - 학습에 유용한 파라미터들을 사용해서 코드를 개선 (https://github.com/Dacon-official/competitions/blob/master/AIFrenz_S2/1st_place/code/Model2.ipynb)
  - Train Accuracy : , Test Accuracy : 
  
## 추가할 사항

- 내용 
  - http://aikorea.org/cs231n/ 
  - parameter 계산방법 (http://taewan.kim/post/cnn/)
  - CNN의 parameter들을 설정하는 방법 (Kernel의 크기, Layer의 순서 등) 

## 참고 자료

[CNN]

1. https://medium.com/@seoilgun/cnn%EC%9D%98-stationarity%EC%99%80-locality-610166700979

2. https://www.slideshare.net/agdatalab/deep-learning-convolutional-neural-network

3. http://aikorea.org/cs231n/convolutional-networks/

4. https://www.researchgate.net/publication/326816043_FAWCA_A_Flexible-greedy_Approach_to_find_Well-tuned_CNN_Architecture_for_Image_Recognition_Problem

5. https://www.researchgate.net/figure/Model-architectures-for-the-MNIST-and-CIFAR-10-models_tbl10_324558570

6. https://ratsgo.github.io/deep%20learning/2017/04/05/CNNbackprop/

[Gradient Vanishing & Exploding] 

1. https://ayearofai.com/rohan-4-the-vanishing-gradient-problem-ec68f76ffb9b

2. http://keunwoochoi.blogspot.com/2018/01/gradients-explode-deep-networks-are.html

[Jaccobian] 

1. http://t-robotics.blogspot.com/2013/12/jacobian.html

2. https://angeloyeo.github.io/2020/07/24/Jacobian.html
