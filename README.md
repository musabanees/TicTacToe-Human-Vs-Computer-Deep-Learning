# TicTacToe-Human-Vs-Computer-Deep-Learning
The architecture of the model is designed in such a way that it runs the Artificial Neural Network algorithm. It consists of 9 inputs. 
The activation function used is RELU activation function on all input layers. The architecture has three hidden layers, first layer having 125 neurons, second layer having 75 neurons and third layer having 25 neurons. 
RELU activation function is applied on all three layers. Output layer consists of 3 neurons. 
The activation function on the output layer is SOFTMAX activation function.
The dataset has been created, imported and has three outputs of either draw, win or lose. 
ANN is applied on the model. Possible outcomes are taken and forward passed. If winning chances are less, the arrow is propagated backwards and the best possible solution is forward passed.

## Why RELU Activtion Function
The rectified linear activation function or ReLU for short is a piecewise linear function that will output the input directly if it is positive, otherwise, it will output zero. It has become the default activation function for many types of neural networks because a model that uses it is easier to train and often achieves better performance

## Why SOFTMAX Function on the outer layer
The softmax function is a function that turns a vector of K real values into a vector of K real values that sum to 1. The input values can be positive, negative, zero, or greater than one, but the softmax transforms them into values between 0 and 1, so that they can be interpreted as probabilities. If one of the inputs is small or negative, the softmax turns it into a small probability, and if an input is large, then it turns it into a large probability, but it will always remain between 0 and 1.
  *Closer to 1 means Good Move
  *Closer to 0 means Bad Move

