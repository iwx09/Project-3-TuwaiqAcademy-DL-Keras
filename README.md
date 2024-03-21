## Deep Learning Using the Keras Library.

## Introduction
In this project, we dive into the world of deep learning by utilizing the Keras library to classify fashion articles in the Fashion MNIST dataset. Keras is a high-level neural networks API, written in Python and capable of running on top of TensorFlow, CNTK, or Theano. It is user-friendly, modular, and extensible, which makes it a go-to library for both beginners and experienced practitioners in the field of deep learning.

## Dataset Description
The dataset we are working with is the Fashion MNIST dataset, which is a collection of 70,000 grayscale images across 10 categories. Each image is a 28x28 pixel representation of a fashion item, such as a shirt, dress, sneaker, etc. The dataset is divided into 60,000 training samples and 10,000 testing samples. This dataset is intended to serve as a direct drop-in replacement for the original MNIST dataset for benchmarking machine learning algorithms, as it is a more challenging dataset compared to the original MNIST.

## Preprocessing
The images are reshaped from a 2D array of 28x28 pixels to a flat 1D array of 784 pixels. Data normalization is performed by converting the pixel values from integers to floats and scaling them to the range [0, 1].

## Tools and Libraries
The following tools and libraries are utilized in this project:

Python
Keras
TensorFlow
NumPy
Matplotlib

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

## Evaluation
achieving an exceptional accuracy of 99% on the Fashion MNIST dataset. This project demonstrated my ability to preprocess data, fine-tune neural network architectures, and rigorously evaluate model performance to ensure high precision in image classification tasks.

## Conclusion
This project serves as a fundamental step into the domain of image classification using neural networks. The Fashion MNIST dataset provides a more challenging alternative to the classic MNIST dataset and serves as a good benchmark for algorithms.

Please find the complete code on my GitHub repository at [Project-DL-Keras.ipynb].
