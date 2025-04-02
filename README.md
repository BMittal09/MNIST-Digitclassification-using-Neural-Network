# MNIST-Digitclassification-using-Neural-Network
## Overview
This project implements handwritten digit classification using the MNIST dataset. The model is built using deep learning (Artificial Neural Networks - ANNs) to classify images of digits (0-9). The MNIST dataset consists of 70,000 grayscale images (28x28 pixels each), divided into 60,000 training images and 10,000 test images.

## Features
- Data Preprocessing

  - Normalize pixel values to the range [0,1].

  - Reshape data for model compatibility.

- Deep Learning Model

  - Fully Connected Neural Network (DNN) or Convolutional Neural Network (CNN).

  - Activation functions such as ReLU and Softmax.

  - Dropout layers to reduce overfitting.

- Training & Evaluation

  - Train the model using TensorFlow/Keras.

  - Evaluate using accuracy, loss curves, and confusion matrix.

- Prediction & Visualization

  - Display model predictions on test images.

  - Plot training accuracy/loss graphs.

## Dataset
The MNIST dataset consists of 28x28 grayscale images of handwritten digits from 0 to 9.

Load the dataset directly using Keras datasets:

## Tech Stack
Programming Language: Python

Deep Learning Framework: TensorFlow/Keras

Data Handling: NumPy, Pandas

Visualization: Matplotlib, Seaborn
