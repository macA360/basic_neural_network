# basic_neural_network
Python implementation of a simple neural network designed to solve the XOR problem. The XOR (exclusive OR) problem is a classic problem in AI that demonstrates the non-linear separability of certain datasets and the need for multi-layer networks.

## Features
- Implementation of a basic feedforward neural network with a single hidden layer.
- Supports different activation functions: Sigmoid, ReLU, and Tanh.
- Utilizes backpropagation for training the network.
- Customizable network parameters including number of hidden nodes and learning rate.

## Requirements
- Python 3.x
- NumPy
- SciPy

## Installation
No specific installation is required apart from the Python environment. Ensure that NumPy and SciPy are installed. If not, they can be installed using pip:

pip install numpy scipy

## Usage
The script neural_network.py can be run directly. It will train the neural network on the XOR problem and then test the network on the same dataset to demonstrate its learning capability.

To customize the neural network, you can modify the parameters in the script:

- input_nodes: Number of input nodes (fixed at 2 for the XOR problem).
- hidden_nodes: Number of hidden nodes (default is 50, but can be changed).
- output_nodes: Number of output nodes (fixed at 1 for the XOR problem).
- learning_rate: Learning rate for the network (default is 0.6, but can be adjusted).

## Example Output
After training, the network will output its predictions for the XOR dataset:

Testing XOR function:
Input: [0, 0], Predicted Output: [[approximate value]]
Input: [0, 1], Predicted Output: [[approximate value]]
Input: [1, 0], Predicted Output: [[approximate value]]
Input: [1, 1], Predicted Output: [[approximate value]]


