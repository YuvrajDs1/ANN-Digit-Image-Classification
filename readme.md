## 🧠 Handwritten Digit Classification using ANN

This project demonstrates how to build and train a simple Artificial Neural Network (ANN) using TensorFlow/Keras to classify handwritten digits from the MNIST dataset.

### 📌 Project Overview

The MNIST dataset is a classic benchmark dataset in machine learning, consisting of 70,000 images of handwritten digits (0–9). This project uses a basic feedforward neural network (ANN) to recognize these digits with high accuracy.

The ANN is implemented using the Keras Sequential API and achieves an accuracy of ~98% on the test set.

### 🔧 Tech Stack

Python

TensorFlow / Keras

NumPy

Pandas

Matplotlib

Scikit-learn

### 🧪 Dataset

MNIST – A dataset of 60,000 training and 10,000 testing grayscale images (28x28 pixels) of handwritten digits (0-9).

The dataset is loaded directly using:

from tensorflow.keras.datasets import mnist
