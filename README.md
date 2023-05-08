# Neural Network Basics

This repository provides an implementation of a neural network from scratch in Python. It includes an explanation of how neural networks work, with a focus on forward propagation and backpropagation.

## Neural Network Overview

A neural network is a machine learning model inspired by the human brain. It consists of interconnected layers of artificial neurons called nodes or units. These nodes process input data and generate output predictions.

### Forward Propagation

Forward propagation is the process of passing input data through the neural network to obtain predictions. It involves the following steps:

1. **Input Layer**: The input data is fed into the neural network.

2. **Hidden Layers**: The input data is transformed and processed by a series of hidden layers. Each hidden layer applies a weighted sum of the inputs and passes it through an activation function.

3. **Output Layer**: The final hidden layer's outputs are passed to the output layer, which produces the predicted values.

### Backpropagation

Backpropagation is the process of updating the weights of the neural network based on the error between the predicted output and the actual output. It involves the following steps:

1. **Loss Calculation**: The error between the predicted output and the actual output is calculated using a loss function, such as mean squared error or cross-entropy loss.

2. **Gradient Calculation**: The gradients of the loss function with respect to the network's weights are computed using the chain rule of calculus.

3. **Weight Update**: The weights are updated using an optimization algorithm, such as gradient descent, by moving in the opposite direction of the gradients to minimize the loss.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/zillur-av/neural-network.git
   ```
2. Run `neural-network.ipynb`

