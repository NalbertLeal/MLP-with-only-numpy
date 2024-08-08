# Simple Neural Network with Numpy

This project demonstrates the implementation of a simple Multi-Layer Perceptron (MLP) neural network using only Numpy. The goal is to build a foundational understanding of neural networks by constructing one from scratch without relying on high-level libraries like TensorFlow or PyTorch.

## Overview

In this project, we implement a basic neural network to classify handwritten digits from the MNIST dataset. The network consists of an input layer, one hidden layer with ReLU activation, and an output layer with softmax activation. The implementation includes forward propagation, backward propagation, and weight updates to train the network.

## Features

- **Numpy-based implementation**: No high-level deep learning frameworks are used.
- **MNIST dataset**: The network is trained on the MNIST dataset, a collection of 70,000 images (60,000 training images and 10,000 testing images) of handwritten digits.
- **Forward and backward propagation**: Custom implementation of forward and backward propagation.
- **Activation functions**: leaky ReLU (and other activations available) for the hidden layer and softmax for the output layer.
- **Loss calculation**: Mean Absolute Error (MAE) is used to calculate the loss.
- **Accuracy and loss Tracking**: Tracks and prints the accuracy and loss of the validation set during training.

## Network Architecture

- **Input Layer**: 784 neurons (28x28 pixels per image)
- **Hidden Layer**: 30 neurons with **leaky ReLU** activation
- **Output Layer**: 10 neurons with softmax activation (one for each digit class 0-9)

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/mpl-with-only-numpy.git
cd mpl-with-only-numpy
```

Install the required dependencies:

```bash
pip install numpy
pip install sklearn
```

Sklearn is used only to mek the download of the mnist dataset

## Usage

1. Ensure you have internet to make the download of the MNIST dataset available with the sklearn library;
3. Run the training process;
4. Colect the trained parameters W1, B1, W2 and B2 to test.

## Contributing

Feel free to submit issues, fork the repository, and make pull requests. Any contributions are welcome!

## License

This project is licensed under the GNU LESSER GENERAL PUBLIC LICENSE - see the [LICENSE](https://choosealicense.com/licenses/lgpl-2.1/) file for details.

## Acknowledgements

- The MNIST dataset is a collection of handwritten digits provided by Yann LeCun, Corinna Cortes, and Christopher J.C. Burges.
- Inspiration and concepts were derived from various online resources and tutorials on neural networks.