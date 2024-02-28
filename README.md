# Neural Network Image Classification README

This repository contains a Python program for image classification using a neural network. The neural network predicts whether an image belongs to class 0 or 1. The architecture of the neural network is as follows:

- **Inputs**: 784 (28x28 pixels)
- **First hidden layer**: 128 neurons
- **Second hidden layer**: 64 neurons
- **Output layer**: 1 neuron (binary classification)

## Getting Started

To run the program, you need Python installed on your system along with the following libraries:

- NumPy
- pandas
- Keras
- Matplotlib

## Dataset

The program uses the MNIST dataset provided by Keras. It consists of handwritten digit images. For this classification task, we filter the dataset to include only images labeled as 0 or 1.

## Code Structure

- `neural_network.py`: Contains the implementation of the neural network including functions for forward propagation, backward propagation, parameter initialization, training, and prediction.
- `README.md`: This file provides information about the program and instructions for running it.

## How to Use

1. Ensure you have Python and the required libraries installed.
2. Clone this repository to your local machine.
3. Run the `neural_network.py` file.
4. The program will load the dataset, preprocess it, train the neural network, and then evaluate its performance on the test set.
5. Finally, it will display the test accuracy and make a prediction on a randomly selected image from the test set.

## Example Usage

```python
python neural_network.py
```

## Acknowledgments

This program is based on a tutorial on neural networks and image classification. Special thanks to the creators of the MNIST dataset and the Keras library for providing the dataset and tools for deep learning research.

Feel free to modify and extend this code for your own projects! If you have any questions or suggestions, please don't hesitate to reach out.

**Author**: Arshad Mehmood 
**Contact**: e.c.a.h.t.t@gmail.com
