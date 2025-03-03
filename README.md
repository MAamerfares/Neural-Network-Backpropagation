# Neural Network Implementation in PyTorch

This project contains a simple neural network model implemented using PyTorch. The neural network is a feedforward model with 2 input neurons, 2 hidden layers, and 2 output neurons. The weights and biases of the network are initialized based on values provided in a given image. The network performs a forward pass and computes the mean squared error (MSE) loss, then updates the weights using gradient descent.

## Model Description

- **Architecture**:
  - **Input Layer**: 2 input neurons
  - **Hidden Layer 1**: 2 neurons with sigmoid activation
  - **Hidden Layer 2**: 2 neurons with sigmoid activation
  - **Output Layer**: 2 output neurons with sigmoid activation

- **Weights and Biases**:
  - The weights and biases are manually initialized based on values provided in the image. These values are used in the forward propagation of the neural network.

## Files

- `neural_network.py`: Contains the code for the model implementation and training process.

## Dependencies

This code uses the following Python libraries:

- **PyTorch**: Used for building and training the neural network.
  You can install it by running:

  ```bash
  pip install torch
