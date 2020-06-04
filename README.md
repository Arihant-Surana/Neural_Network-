# Neural_Network-
This is a basic 2 Layer Neural_Network. It consists of 1 Hidden layer and 1 Output Layer. 

# What’s a Neural Network?
Most introductory texts to Neural Networks brings up brain analogies when describing them. Without delving into brain analogies, I find it easier to simply describe Neural Networks as a mathematical function that maps a given input to a desired output.
Neural Networks consist of the following components
# Basic layout:
An input layer, x
An arbitrary amount of hidden layers
An output layer, ŷ
A set of weights and biases between each layer, W and b
A choice of activation function for each hidden layer, σ. In this tutorial, we’ll use a Sigmoid activation function.

Naturally, the right values for the weights and biases determines the strength of the predictions.
The process of fine-tuning the weights and biases from the input data is known as training the Neural Network.
# Forward and backpropogation:
Each iteration of the training process consists of the following steps:
Calculating the predicted output ŷ, known as feedforward
Updating the weights and biases, known as backpropagation
# Caluculus involved :
In the calculation of backpropoogation we use Chain rule of the derivatives. 
