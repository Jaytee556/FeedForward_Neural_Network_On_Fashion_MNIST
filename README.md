# FeedForward_Neural_Network_On_Fashion_MNIST
In this repository, I implemented and trained a feed-forward neural network (also known as an "MLP" for "multi-layer perceptron") on a dataset called "Fashion MNIST", consisting of small greyscale images of items of fashion.

The goal is to build a model that will perform well on future data that we have not seen yet. We say that we want our models to be able to generalize well from whatever training data we can collect and have available, to whatever data we will be applying them to in the future. To do this, we split whatever data we have available into a training set, a validation set, and a test set. The idea is that we train our model and use the performance on the validation set to make any adjustments to the model and its hyperparameters, but then we report the final accuracy on the test set.

1. Use Keras Layers to build a neural network architecture.
2. Train and evaluate the model
