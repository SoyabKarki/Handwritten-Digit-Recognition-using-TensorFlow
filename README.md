# Handwritten Digit Recognition using TensorFlow

### Overview
This project utilizes TensorFlow's Keras API to recognize handwritten digits from the MNIST dataset. The MNIST dataset consists of 28x28 grayscale images of handwritten digits (0 through 9). The goal of this project is to train a neural network model to accurately classify these digits.

### Dependencies
- NumPy
- TensorFlow 
- matplotlib

### Dataset
The code utilizes the MNIST dataset using TensorFlow's 'mnist' module.

### Model
The model consists of 3 Dense layers and is compiled with the Adam optimizer, sparse categorical cross-entropy loss function, and accuracy metric. 

### Results
After training for 5 epochs, the model achieved an accuracy of 97.5% with a loss value of 9.5%.
