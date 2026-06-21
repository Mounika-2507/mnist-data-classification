# mnist-data-classification
# MNIST Handwritten Digit Classification using TensorFlow

## Project Overview

This project implements a Deep Learning model for handwritten digit recognition using the MNIST dataset. The model is built using TensorFlow and Keras and is trained to classify handwritten digits from 0 to 9.

## Dataset

The MNIST dataset consists of:

* 60,000 training images
* 10,000 testing images
* Grayscale images of size 28×28 pixels
* 10 output classes (digits 0–9)

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* TensorFlow Datasets (TFDS)

## Model Architecture

* Input Layer: 28×28 grayscale images
* Flatten Layer
* Dense Layer (200 neurons, ReLU activation)
* Dense Layer (200 neurons, ReLU activation)
* Output Layer (10 neurons, Softmax activation)

## Training

* Optimizer: Adam
* Loss Function: Sparse Categorical Crossentropy
* Epochs: 5

## Results

* Test Accuracy: 97%
* Successfully classified handwritten digits from 0–9.
* Generated predictions on unseen test images.
* Compared predicted digits with actual labels.

## Sample Prediction

The trained model predicts the digit with the highest probability using the Softmax output layer.

Example:

Predicted Digit: 7

Actual Digit: 7

## Learning Outcomes

* Data preprocessing and normalization
* Building neural networks using TensorFlow/Keras
* Model training and evaluation
* Prediction on unseen data
* Understanding Softmax classification

## Future Improvements

* Convolutional Neural Networks (CNN)
* Hyperparameter tuning
* Confusion Matrix visualization
* Model deployment using Flask or Streamlit

