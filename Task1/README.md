# Image Classification with CIFAR-10 Dataset
This project involves image classification using the CIFAR-10 dataset. The goal is to classify images into one of the following categories: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck. We use a Convolutional Neural Network (CNN) model employing the TensorFlow library for this task.

## Introduction
Image classification is a common task in computer vision. In this project, we use the CIFAR-10 dataset, which contains 60,000 32x32 color images in 10 different classes. Our objective is to build and train a CNN model to accurately classify these images.

## Dataset
The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. There are 50,000 training images and 10,000 test images.

## Model Architecture
We use a Convolutional Neural Network (CNN) for this image classification task. The architecture includes:

* Convolutional layers
* Max Pooling layers
* Fully connected layers - Dense layer
* Dropout for regularization

## Example of CNN for image classification
![CCN_cifar10](https://github.com/Vinit21592/ShadowFox-AIML-Internship/assets/78821357/452a3d8a-c7f2-48ac-802b-f8f7f7188c1b)

## Results
Running 20 epochs with batch-size 32 we are able to achieve accuracy of 78.66% and validation accuracy of 73.18%. To improve accuracy we can increase epochs.
