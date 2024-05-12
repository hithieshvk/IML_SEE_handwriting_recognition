# Handwritten Text Recognition with CRNN

This repository contains code for training a Convolutional Recurrent Neural Network (CRNN) model for handwritten text recognition. The model is trained using TensorFlow and Keras libraries.

## Dataset

The dataset used for training is the handwritten text dataset version 2.0. It contains images of handwritten text samples along with their corresponding labels.

## Installation

1. Clone the repository
2. Install the required dependencies:

## Usage

1. Download the dataset and place it in the appropriate directory.
2. Modify the file paths in the code to point to the dataset.
3. Run the training script:

## Running the Code

To run the project code, follow these steps:

1. Ensure you have Python installed on your system.
2. Clone the repository to your local machine.
3. Install the required dependencies using pip.
4. Download the handwritten text dataset and place it in the specified directory.
5. Modify the file paths in the code as necessary to point to the dataset.
6. Open a terminal or command prompt and navigate to the project directory.
7. Run the training script using the command `python train.py`.

## Model Architecture

The CRNN model consists of convolutional layers for feature extraction, followed by recurrent layers for sequence processing. The output layer predicts character probabilities.

## Results

After training for a certain number of iterations, the model achieves a certain accuracy on the validation set.

## References

- [Build a Handwritten Text Recognition System using TensorFlow](https://towardsdatascience.com/2326a3487cd5)
- [Scheidl - Handwritten Text Recognition in Historical Documents](https://repositum.tuwien.ac.at/obvutwhs/download/pdf/2874742)
- [Scheidl - Word Beam Search: A Connectionist Temporal Classification Decoding Algorithm](https://repositum.tuwien.ac.at/obvutwoa/download/pdf/2774578)
