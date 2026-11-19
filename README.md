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

The raw-pixel model achieved 100% training accuracy and 33.3% test accuracy. The CNN pipeline with global max pooling achieved 100% accuracy on both sets using 15 trained dense-layer parameters.

**Notebook:** [ARTI402_Lab3_2240005619.ipynb](ARTI402_Lab3_2240005619.ipynb)

## Lab 4 – Recurrent Networks: RNN, LSTM, and GRU

This lab covers:

- Implementing RNN and LSTM cells from scratch using NumPy
- Running a recurrent cell over a sequence and tracking its hidden state
- Comparing parameter counts for RNN, GRU, and LSTM
- Training a classifier on the final hidden states of frozen RNN and LSTM models
- Testing how sequence length and forget-gate bias affect memory

At 40 time steps, the RNN achieved 27.5% test accuracy and the LSTM achieved 94.2%. The LSTM’s accuracy dropped to 79.2% at 80 steps.

**Notebook:** [ARTI402_Lab4_2240005619.ipynb](ARTI402_Lab4_2240005619.ipynb)

To rerun Lab 4, place the lab’s `arti402_figures.py` file in the same folder as the notebook.

## Tools Used

- Python
- NumPy
- Matplotlib
- Jupyter Notebook
