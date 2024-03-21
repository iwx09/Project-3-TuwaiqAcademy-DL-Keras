## Introduction
This project demonstrates how to use Keras with TensorFlow backend to work with the Fashion MNIST dataset. The dataset consists of 60,000 training images and 10,000 test images, each being a 28x28 grayscale image associated with a label from 10 classes.

## Dataset
We use the Fashion MNIST dataset, which is a modern alternative to the traditional MNIST dataset. It contains images of various clothing items that are more complex patterns than the handwritten digits.

## Preprocessing
The images are reshaped from a 2D array of 28x28 pixels to a flat 1D array of 784 pixels. Data normalization is performed by converting the pixel values from integers to floats and scaling them to the range [0, 1].

## Model Architecture
The neural network model built in this project is a simple sequential model with the following layers:
- A dense layer with 784 inputs (flattened image pixels) and 100 neurons, using ReLU activation function.
- A softmax output layer with 10 neurons, corresponding to the 10 classes of the dataset.

## Code Structure
The code is structured as follows:
1. Import necessary libraries.
2. Load and preprocess the Fashion MNIST dataset.
3. Define the neural network model architecture.
4. Compile the model (the code for this is not included in the provided snippet).
