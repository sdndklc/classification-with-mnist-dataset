# Classification with MNIST Dataset

This repository includes classification of MNIST dataset using neural network from scratch and  PyTorch with models multilayer perceptron (MLP), LSTM, and convolutional neural network (CNN). 

MNIST is a dataset consisting of 70000 images of handwritten digits (0-9) which is available in http://yann.lecun.com/exdb/mnist/. 

Pre-processing of data contains normalizing and one-hot-encoding.

- Neural network from scratch consists of 3 layers and Sigmoid activation function is used between these layers. It gives % 97.34 accuracy.
- Multilayer perceptron (MLP) consists of 3 layers ReLu and LogSoftmax activation functions are used between these layers. Cross entropy loss is used as loss function. It gives % 97.70 accuracy. 
- LSTM consist of one LSTM layer and one linear layer. Cross entropy loss is used as loss function. It gives % 98.23 accuracy. 
- Convolutional neural network (CNN) consists of two (fully- connected) linear layers, two 2-D convolutional layers, and 2 dropout layers as a means of regularization. Also, there exists two 2-D max-pooling layers performed after convolutional layers. Activation function used between layers is ReLU and in output layer is LogSoftmax. Loss function is NLL (Negative Log-Likelihood).

Confusion matrix and precision, recall, f1 scores are used as model evalution metric.
