# MNIST Digit Classifier

A simple neural network implementation for classifying handwritten digits using the MNIST dataset and scikit-learn's MLPClassifier.

## Overview
This project demonstrates a basic machine learning workflow for digit recognition, including data loading, visualization, model training, and prediction visualization. The model achieves 96.7% accuracy on the test set.
## Features
- Loads the classic MNIST dataset (70,000 handwritten digit images)
- Visualizes sample digits from the dataset
- Trains a Multi-Layer Perceptron (MLP) neural network
- Evaluates model performance on test data
- Displays predictions with color-coded accuracy (green for correct, red for incorrect)

## Model Architecture
-   **Algorithm**: Multi-Layer Perceptron (MLP)
-   **Hidden Layers**: 2 layers with 100 neurons each
-   **Solver**: Adam optimizer
-   **Regularization**: L2 penalty (alpha = 0.01)
-   **Train/Test Split**: 67% training, 33% testing
