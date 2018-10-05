# Neural Networks and Deep Learning

## Week 1 Introduction to Deep Learning

## What is a neural network
![](ImageNotes/Week1_1.png)

Note: Each of the neurons of hidden layer takes all four input features. Given enough training examples with both x and y, neural networks are remarkably good at figuring out functions that accurately map from x to y. 

## Supervised Learning with Neural Networks
![](ImageNotes/Week1_2.png)

## Why is Deep Learning taking off?
![](ImageNotes/Week1_3.png)

Note: The algorithm development makes NN runs faster. e.g. Switching from Sigmoid to Relu will make gradient descent much faster. Slope of sigmoid close to 0 at some parts which will make gradient to be 0. This will result in parameters changes very slow. But if use Relu as activation function, the gradient equals to 1 for all positive values. So the gradient is much less likely to gradually shrink to 0. 

## Week 2 Neural Networks Basics
![](ImageNotes/Week2_1.png)

## Week 3 Shallow Neural Networks
![](ImageNotes/Week3_1.png)

Note: Use small values to initialize the weights work good when using sigmoid or tanh as activation function. But won't make difference for ReLU and Leaky ReLU since the slope is always 1 when z>0.

## Week 4 Deep Neural Network
![](ImageNotes/Week4_1.png)
