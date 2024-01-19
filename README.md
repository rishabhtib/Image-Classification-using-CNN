# Image-Classification-using-CNN

# Overview
This repository contains a simple implementation of a Convolutional Neural Network (CNN) for image classification using PyTorch. The network architecture consists of two convolutional layers followed by fully connected layers. The CNN is designed for the MNIST dataset, a commonly used benchmark for handwritten digit recognition

# Requirements
Python 3.x<br>
pytorch

# Architectrure
The CNN architecture consists of the following layers:<br>
<br>
Conv1: 1 input channel, 6 output channels, kernel size 5x5, stride 1, padding 1<br>
MaxPool1: 2x2 kernel, stride 2<br>
Conv2: 6 input channels, 16 output channels, kernel size 5x5, stride 1, padding 1<br>
MaxPool2: 2x2 kernel, stride 2<br>
Fully Connected Layers: 5x5x16 input features, 120 output features; 120 input features, 84 output features; 84 input features, 10 output features<br>
