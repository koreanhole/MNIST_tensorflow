# MNIST_tensorflow

MNIST image data를 사용하여 tensorflow로 convolution neural network를 설계하고 test data에 대한 예측 정확도를 99.6%까지 높혔다.

사용된 기법
  1. batch normalization 적용
  2. 1개의 hidden layer(256개의 노드 사용)
  3. 3개의 convolution layer(각각 32, 64, 128개의 filter 갯수)
  4. 0.7 hidden layer dropout, 0.5 convolution layer dropout
  5. AdamOptimizer사용
  
결과
  ![epoch_accuracy_graph](https://user-images.githubusercontent.com/54267479/73365792-3101b080-42f0-11ea-81df-53d67dcc3bea.png)
  
