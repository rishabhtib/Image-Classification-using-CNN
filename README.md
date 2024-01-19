# Image-Classification-using-CNN
The project is based on the classification of images using CNN ob the MNIST data-set. MNIST dataset contains 60K 28x28 grayscale handwritten images of numbers ranging 0 to 9. There are 10K images for the training

# Overview
This repository contains a simple implementation of a Convolutional Neural Network (CNN) for image classification using PyTorch. The network architecture consists of two convolutional layers followed by fully connected layers. The CNN is designed for the MNIST dataset, a commonly used benchmark for handwritten digit recognition

# Requirements
Python 3.x<br>
Pytorch

# Architectrure
The CNN architecture consists of the following layers:<br>
<br>
Conv1: 1 input channel, 6 output channels, kernel size 5x5, stride 1, padding 1<br>
MaxPool1: 2x2 kernel, stride 2<br>
Conv2: 6 input channels, 16 output channels, kernel size 5x5, stride 1, padding 1<br>
MaxPool2: 2x2 kernel, stride 2<br>
Fully Connected Layers: 5x5x16 input features, 120 output features; 120 input features, 84 output features; 84 input features, 10 output features<br>

# Results
Training and testing results, including accuracy and confusion matrix, are displayed during script execution.
