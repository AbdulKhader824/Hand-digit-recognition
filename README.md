# Hand-digit-recognition
This project recognizes handwritten digits using the MNIST dataset with a feedforward neural network. It preprocesses images by normalizing and flattening them. The Keras model has one hidden layer with 100 neurons (ReLU) and an output layer with 10 neurons (sigmoid). After training for 5 epochs, it achieves over 90% accuracy on the test set.
# Hand Digit Recognition Using MNIST Dataset

## Overview
This project aims to recognize handwritten digits using the MNIST dataset and a feedforward neural network built with Keras. The model preprocesses the images, trains on the dataset, and achieves over 90% accuracy in recognizing digits.

## Dataset
- **MNIST Dataset**: A collection of 70,000 grayscale images of handwritten digits (0-9).
  - **Training Set**: 60,000 images
  - **Test Set**: 10,000 images

## Methodology
1. **Data Preprocessing**
   - Normalize and flatten the 28x28 pixel images into 784-dimensional vectors.

2. **Model Architecture**
   - A feedforward neural network with:
     - One hidden layer with 100 neurons and ReLU activation.
     - One output layer with 10 neurons (one for each digit) and sigmoid activation.

3. **Model Compilation**
   - Optimizer: Adam
   - Loss Function: Sparse Categorical Crossentropy

4. **Model Training**
   - Trained for 5 epochs on the training dataset.

5. **Model Evaluation**
   - Achieved over 90% accuracy on the test set.

## Requirements
- Python 3.x
- TensorFlow/Keras
- NumPy
- Matplotlib (for visualization, if needed)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/hand-digit-recognition.git
   cd hand-digit-recognition

