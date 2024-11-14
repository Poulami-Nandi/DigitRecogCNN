# Digit Recognition Using Convolutional Neural Network (CNN)

This repository contains a project for recognizing handwritten digits using the popular MNIST dataset and a Convolutional Neural Network (CNN). The goal is to classify grayscale images of digits (0-9) with high accuracy.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Installation](#installation)
- [Training](#training)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview
The project uses a CNN model built with TensorFlow/Keras to classify digits in the MNIST dataset. This is a standard deep learning task that provides a solid foundation for understanding neural network models applied to image classification.

## Dataset
The MNIST dataset consists of 70,000 grayscale images of handwritten digits, where each image is 28x28 pixels in size:
- **Training set**: 60,000 images
- **Test set**: 10,000 images

Each image is labeled from 0 to 9, corresponding to the digit it represents.

## Model Architecture
The model is a Convolutional Neural Network (CNN) with the following structure:
1. **Input Layer**: Accepts 28x28 grayscale images
2. **Convolutional Layers**: Extracts features from the images
3. **Pooling Layers**: Reduces spatial dimensions
4. **Fully Connected Layers**: Maps features to digit classes
5. **Output Layer**: Uses softmax activation for multiclass classification (digits 0-9)

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/digit-recognition.git
   cd digit-recognition
