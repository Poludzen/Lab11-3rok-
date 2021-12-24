# Lab11-3rok-
1) First example :https://colab.research.google.com/drive/1LXQpqk0WpracGLCpprtONjvI8p6ftCW2?usp=sharing
CIFAR10 task is shown in this example: cifar10 dataset consists of 60000 32x32 colour images in 10 classes. 
The 10 different classes represent airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships, and trucks. 
There are 6,000 images of each class, and they are already compressed. 
In this code we have a convolutional neural network, that build with tensorflow(keras) framework.
This neural network consists of 4 convolutional layers, dense layers,
some regularization layers(Dropout,BatchNormalization) and MaxPool layers
After fiting with this network , that is shown that neural network really works ( accuracy of a network on a test dataset and one prediction on example)
2) Second example: https://colab.research.google.com/drive/1r-c6UTkJEQx3Pi-Hl9q_MoveIF_0h03M?usp=sharing#scrollTo=Fgo7WgPS7ihR
EMNIST62 task is shown in this example: emnist62 dataset consists of 700000 grayscale images in 62 classes.
The 62 different classes represent characters : 0-9, a-z, A-Z
In this code we have a convolutional neural network, that build with pyTorch framework.
This neural network consists of 2 convolutional layers(one with regulaizer), Dense layers, 
some regularization layer(Dropout) and MaxPool layer
After fiting with this network , that is shown that neural network really works ( accuracy of a network on a test dataset and one prediction on example)
