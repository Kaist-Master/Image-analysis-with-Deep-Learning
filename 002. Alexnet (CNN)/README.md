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

## 추가할 사항

- 코드 : PyTorch 
  - v1 : Train만을 이용하여 predict (Training all dataset with batch)  
  - v2 : kfold를 이용하여 predict 
  - v3 : Use utilization package in https://dacon.io/competitions/official/235591/codeshare/1288?page=1&dtype=recent&ptype=pub

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
