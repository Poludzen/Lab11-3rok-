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

## First example: CIFAR 10 Classification task
Source of example: https://colab.research.google.com/drive/1LXQpqk0WpracGLCpprtONjvI8p6ftCW2?usp=sharing
### Overview: 
CIFAR10 task is shown in this example: cifar10 dataset consists of 60000 32x32 colour images in 10 classes. 
The 10 different classes represent airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships, and trucks. 
There are 6,000 images of each class, and they are already compressed. 
In this code we have a convolutional neural network, that build with tensorflow(keras) framework.
This neural network consists of 4 convolutional layers, dense layers,
some regularization layers(Dropout,BatchNormalization) and MaxPool layers
After fiting with this network , that is shown that neural network really works ( accuracy of a network on a test dataset and one prediction on example)
### Why it is important?
This dataset is one of the most important in the history of the development of computer vision in 2010-2020, it appears in many articles and is one of the basic ones when testing the performance of neural network architectures
### Why they compressed to 32x32? 
To optimize resources (memory, time). Also, wide format pictures do not always contain the necessary information in a large number of pixels.
### Dataset example:
##### Truck:
![alt text](https://github.com/Poludzen/Lab11-3rok-/blob/main/images/truckexample.jpg?raw=true "Truck")
##### Dog:
![alt text](https://github.com/Poludzen/Lab11-3rok-/blob/main/images/dogexample.jpg?raw=true "Dog")
### Fit, predict, report
Neural network was fit on 10 epochs, after that some predictions were done:
##### Prediction 1(Ship was given , and ship was predicted)
![alt text](https://github.com/Poludzen/Lab11-3rok-/blob/main/images/pred_exampl1.jpg?raw=true "Ship")
##### Prediction 2(Frog was given, and frog was predicted)
![alt text](https://github.com/Poludzen/Lab11-3rok-/blob/main/images/pred_exampl2.jpg?raw=true "Frog")

Also, classification report was calculated on test dataset
Accuracy on test is 0.7262
##### Classification report and Accuracy 
![alt text](https://github.com/Poludzen/Lab11-3rok-/blob/main/images/score.jpg?raw=true "Score")
