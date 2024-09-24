# Handwritten Digit Recognition using Neural Networks

## Project Overview
This project demonstrates a deep learning model that recognizes handwritten digits (0-9) from the MNIST dataset. Using a simple feedforward neural network, the model is trained to classify images of digits into their respective categories. The project provides an introduction to neural networks and basic image classification using popular deep learning libraries like TensorFlow and Keras.

## Key Features
- Data preprocessing, including normalization of pixel values.
- Simple neural network architecture with fully connected layers.
- Utilization of ReLU and softmax activation functions.
- Model evaluation using accuracy and confusion matrix visualization.
- Easy-to-run code for training, testing, and evaluating the model.

## Dataset
The model is trained on the **MNIST dataset**, which consists of:
- **Training set**: 60,000 images of handwritten digits.
- **Test set**: 10,000 images of handwritten digits.

Each image is a grayscale 28x28 pixel image representing digits from 0 to 9.

## Model Architecture
- **Input Layer**: 784 neurons (28x28 pixels, flattened into a vector).
- **Hidden Layers**: 
  - 1st hidden layer: 128 neurons, ReLU activation.
  - 2nd hidden layer: 32 neurons, ReLU activation.
- **Output Layer**: 10 neurons (one for each digit class), softmax activation for probability distribution.

The model is trained using the **Adam optimizer** and categorical cross-entropy as the loss function.

## Technologies Used
- **Python 3**
- **TensorFlow/Keras** for building and training the neural network.
- **NumPy** for numerical operations.
- **Matplotlib** and **Seaborn** for plotting and visualizations.
- **Pandas** for data manipulation.

