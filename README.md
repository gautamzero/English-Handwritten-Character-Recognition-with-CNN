# English-Handwritten-Character-Recognition-with-CNN

We constructed a Convolutional Neural Network(CNN) model. Model architecture described below:
Convolutional Layer #1: Applies 32 3x3 filters, with ReLU activation function
Pooling Layer #1: Performs max pooling with a 2x2 filter and stride of 2
Convolutional Layer #2: Applies 64 5x5 filters, with ReLU activation function
Pooling Layer #2: Again, performs max pooling with a 2x2 filter and stride of 2
Dense Layer #1: 100 neurons, with dropout regularization rate of 0.4, with ReLU activation function
Dense Layer #2: 26 neurons, one for each digit target class (1-26), with softmax activation function
