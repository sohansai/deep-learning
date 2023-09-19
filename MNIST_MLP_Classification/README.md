# MNIST Multilayer Perceptron (MLP) Classification

This folder focuses on classifying handwritten digits from the MNIST dataset using a Multilayer Perceptron (MLP) neural network. The MNIST dataset consists of a large number of labeled images of handwritten digits (0-9), making it a classic benchmark for image classification tasks.

## Overview

The project includes the following key components:

1. Data Loading and Preprocessing: The MNIST dataset is acquired using TensorFlow, and the images are preprocessed by reshaping and normalizing them to prepare them for input to the MLP model.

1. Model Architecture: An MLP neural network is defined using the TensorFlow Keras API. The model consists of an input layer, two hidden layers with ReLU activation functions, and an output layer with softmax activation.

1. Training: The MLP model is trained on the training data using categorical cross-entropy loss and the Adam optimizer. The training process involves multiple epochs, and the progress is monitored.

1. Evaluation: The trained model's performance is evaluated on the test dataset, providing insights into its accuracy and generalization.

## Files

  MNIST_MLP_Classification.ipynb: A Jupyter Notebook containing the Python code for this project.

## Results

The project aims to achieve accurate classification of handwritten digits using the MLP model. After running the code, you can expect to see metrics such as test loss and accuracy, which provide insights into the model's performance.

## Requirements

    Python 3.x
    Jupyter Notebook
    TensorFlow (for deep learning)

## Acknowledgments

  The MNIST dataset is sourced from TensorFlow, a widely used deep learning library.
  
  TensorFlow: https://www.tensorflow.org/
