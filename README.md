# ARTI402 – Deep Learning Labs

This repository contains my completed lab assignments for the ARTI402 Deep Learning course.

## Lab 1 – Neural Network Fundamentals

This lab covers:

- Neurons, weights, and biases
- Dense layers
- Matrix multiplication
- Forward propagation
- Building a basic neural network using NumPy

**Notebook:** [arti402_lab1_2240005619.ipynb](arti402_lab1_2240005619.ipynb)

## Lab 2 – Activations, Loss, and Network Learning

This lab covers:

- ReLU, sigmoid, and softmax activation functions
- Dense-layer implementation
- Categorical cross-entropy loss
- Numerical derivatives and gradient descent
- Backpropagation and the chain rule
- Training a neural network using NumPy

**Notebook:** [arti402_lab2_2240005619.ipynb](arti402_lab2_2240005619.ipynb)

## Lab 3 – CNN Architecture: The Four Building Blocks

This lab covers:

- Implementing convolution and ReLU
- Implementing max pooling and flattening
- Tracking tensor shapes and counting parameters
- Extracting features using frozen Sobel filters
- Training a fully connected classification head
- Comparing raw pixels with CNN features on shifted images
- Exploring how pooling affects translation invariance

The raw-pixel model achieved 100% training accuracy but only 33.3% test accuracy. The CNN pipeline with global max pooling achieved 100% accuracy on both sets using 15 trained dense-layer parameters.

**Notebook:** [arti402_Lab3_2240005619.ipynb](arti402_Lab3_2240005619.ipynb)

## Tools Used

- Python
- NumPy
- Matplotlib
- Jupyter Notebook
