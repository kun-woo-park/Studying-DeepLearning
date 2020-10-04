# Studying-DeepLearning
본 Repo는 DeepLearning을 공부한 내용을 간단하게 정리한 Repo이다. 각 챕터별로 동일한 이름을 가진 jupyter notebook file에 해당 챕터 내용에 대한 example code를 작성해 두었다. (ex. 1-1.Gradient_descent_MSE.ipynb)

## 1.Gradient descent
머신러닝의 핵심은 주어진 입력에 대해 의도된 출력이 매칭되는 함수를 도출해 내는 것이다. 가장 간단한 예시로 Y=aX 꼴의 X, Y 데이터 셋이 있을때 해당 함수를 유추하는 것은 a의 값을 유추해 내는 것과 같다. 이를 유추해 내는 가장 대표적인 알고리즘이 Gradient descent 알고리즘이다. Gradient descent 알고리즘은 임의의 a값을 지정해 Y_predicted를 계산 한 뒤 그 계산값을 이용해 실제 Y_target 값에 가깝게 수렴하도록 계산이 진행된다. 이 과정은 먼저 Y_predicted를 주어진 loss function(ex. L2norm)을 사용해 Y_target과의 loss를 계산하고, 이 loss가 최저점이 되는 지점을 찾기 위해 loss의 a(weight)에 대한 변화율을 현재의 a에서 뺀 값을 이후 스텝의 a로 채택한다. 이 알고리즘을 그래프로 간략화 하면 다음과 같다.

### Gradient descent algorithm
img

## 2.Pytorch, the python-based scientific computing package
Pytorch는 python환경을 기반으로 제공되는 Deep learning research platform이다. Pytorch는 Deep learning에 필수적인 함수들 말고도 Deep learning에 도움이 되는 다양한 모듈들을 지원한다. 가장 대표적으로 Pytorch는 Autograd를 지원하는데, 이는 Tensor의 자동미분(ex. Backpropagation)

## 3.Regression and Classification

## 4.Advanced CNN


