

# Adaline and Perceptron Algorithm Implementation

This repository contains a Python implementation of the Adaline (Adaptive Linear Neuron) and perceptron algorithm, as described in the book "Fundamentals of Neural Networks" by Fausett [1].

## Table of Contents

- [Introduction](#introduction)
- [Dependencies](#dependencies)

## Introduction

The Adaline algorithm is a simple machine learning algorithm used for binary classification. It adjusts its weights and bias to minimize the squared error between the predicted and actual outputs. This implementation demonstrates how to train an Adaline model and visualize its decision boundary.

The Perceptron is one of the simplest machine learning algorithms used for binary classification. It aims to find a linear decision boundary that can separate two classes of data points. The algorithm learns by adjusting its weights and bias during training to correctly classify data points.

Madaline, short for "Multiple Adaline," is a neural network model based on the McCulloch-Pitts neuron with linear activation. This algorithm is designed for binary classification tasks and is known for its simplicity and effectiveness in linearly separable problems.
Madaline consists of two layers: an input layer and an output layer. It employs multiple Adaline units in the output layer, each responsible for a particular classification decision boundary. During training, Madaline adjusts the weights and biases of these Adaline units to minimize classification errors.
## Dependencies

This implementation requires the following dependencies:

- Python (>= 3.6)
- NumPy (for numerical operations)
- Matplotlib (for data visualization)

You can install these dependencies using the following commands:

```bash
pip install numpy matplotlib
```

[1] Fausett L. V. (1994). Fundamentals of neural networks : architectures algorithms and applications. Prentice-Hall.
