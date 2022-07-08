# Generating automatically Convolutional Neural Network Architectures using Genetic Algorithms for image classification

## Project Overview

This project aims to apply genetic algorithms to automatically generate a convolutional neural network that performs satisfactorily for image classification tasks. The network will be the result of applying the different genetic operators to an initial random population of multiple neural networks, in order to improve the loss and accuracy metrics after each generation by adjusting the number and type of layers, as well as the number of filters in the networks.

For now, it is intended to be only a case study to deepen the topics of neural networks and evolutionary algorithms. However, the use of genetic algorithms can be a great tool for hyperparameter tuning, a very important topic in Artificial Intelligence.

The project still has a lot of things to test concerning genetic algorithms, since only a small set of parameters has been selected for the genetic operators. This is partly due to the fact that testing different configurations takes a long time, caused by the large amount of computational resources required to compute the adaptation of the individuals (training the network for some epochs).

## References
- Some programming ideas where taken from this [github repository](https://github.com/Marius-Juston/AutoCNN).
- This paper: [Automatically designing CNN architectures using genetic algorithm for image classification](arXiv:1808.03818)
