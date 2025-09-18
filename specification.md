# Project specification for ncdr

This project aims to create a small python library utility for using autoencoder models. 

## Features
The library will provide a single class, `NCDR`, which will implement the scikit learn interface for fit/transform/predict methods. This class will wrap around a PyTorch-lightning autoencoder model and Trainer, allowing users to easily train and use autoencoders for dimensionality reduction and reconstruction tasks.

The autoencoder model will be configurable, allowing users to specify the architecture (number of layers, layer sizes, activation functions, etc.) and training parameters (learning rate, batch size, number of epochs, etc.) through the `NCDR` class constructor. 

