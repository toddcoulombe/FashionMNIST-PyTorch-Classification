#  FashionMNIST Image Classification with PyTorch

## Overview

This project compares a Fully Connected Neural Network and a Convolutional Neural Network (CNN) on the FashionMNIST dataset using PyTorch. The objective was to evaluate how convolutional architectures improve image classification performance compared to traditional dense neural networks.

## Project Goal

The goal of this project was to compare the performance of a Fully Connected Neural Network and a Convolutional Neural Network (CNN) on the FashionMNIST dataset using PyTorch.

The project demonstrates how CNNs can automatically learn spatial features from images and improve classification accuracy compared to traditional fully connected architectures.

## Project Results

| Model | Accuracy |
|---------|---------|
| Fully Connected Neural Network | 81.5% |
| Convolutional Neural Network (CNN) | 92.0% |

**Accuracy Improvement: +10.5%**

## Dataset

- 60,000 training images
- 10,000 test images
- 28x28 grayscale images
- 10 clothing categories

## Model 1: Fully Connected Neural Network

Results:
- Accuracy: 81.5%

## Model 2: Convolutional Neural Network (CNN)

Results:
- Accuracy: 92.0%

## Technologies Used

- PyTorch
- DataLoader
- Neural Networks
- CNNs
- ReLU
- MaxPooling
- Adam Optimizer

## Key Learning

This project demonstrated that Convolutional Neural Networks (CNNs) are better suited for image classification tasks because they automatically learn spatial patterns and visual features directly from images. While the Fully Connected Neural Network achieved 81.5% accuracy, the CNN improved performance to 92.0%, highlighting the effectiveness of convolution and pooling layers for computer vision applications.

## Author

Todd Coulombe

Completed as part of the IBM AI Engineering Professional Certificate while studying neural networks, computer vision, and deep learning with PyTorch.
