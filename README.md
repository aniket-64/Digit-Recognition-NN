# Digit-Recognition-NN
This repository contains the code for digit recognition using an artificial neural network. 
  
The neural net implemented has a single hidden layer. It has been trained and subsequently tested using the MNIST database of handwritten digits. The major features of the neural net include:  
- The input of the neural network are the brightness values of the individual pixels of an image, for which the digit is to be recognised. The net accepts 28X28 pixel images as input.
- The net has a single hidden layer with 20 neurons in it.
- The net outputs the prediction to the output layer containing 10 output neurons.
- The net uses the logistic sigmoid function as the activation function for the hidden and output layer neurons.  
- The quadratic cost function is used as the cost function.
  
  
The net has been trained using the training set of the MNIST database containing 60000 labelled samples. The test set of the MNIST database has 10000 labelled samples.  
  
In order to train the model, backpropagation and stochastic gradient descent have been used.

The model achieves an accuracy of 87.98%.

