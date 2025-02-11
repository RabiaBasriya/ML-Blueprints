# ML-BLUEPRINT
## Overview
This project is a collection of machine learning algorithms implemented from scratch. It includes various regression and classification models with evaluation metrics. The goal is to understand how these algorithms work internally without relying on built-in libraries like Scikit-Learn.
## Implemented Algorithms
### 1. Linear Regression
- A supervised learning algorithm that fits a straight line to the data.
- Used Gradient Descent to find the best parameters.
- Evaluated using the R2 score: 0.8417.
- Plotted cost vs. iterations graph.
### 2. Polynomial Regression
- Similar to Linear Regression but fits a polynomial curve instead of a straight line.
- Used a polynomial of degree 5 for better fitting.
- Applied Feature Scaling to improve training.
- Achieved an R2 score of 0.9999.
### 3. Logistic Regression
- A classification algorithm that uses the Sigmoid Function to classify data.
- Implemented binary classification and extended it to multi-class classification using One-Hot Encoding.
- Achieved an accuracy of 77.18%.
### 4. K-Nearest Neighbors (KNN)
- A supervised classification model that assigns a class based on the majority class of its nearest neighbors.
- Used Euclidean Distance to find the closest neighbors.
- Achieved an accuracy of 79.46%.
### 5. Neural Network
- A model inspired by the human brain, consisting of multiple layers of neurons.
- Overcomes the limitation of Logistic Regression by handling complex decision boundaries.
- Used ReLU or Tanh activation functions for hidden layers and Softmax for the output layer.
- Implemented Backpropagation for training.
- Achieved an accuracy of 75.62% on image classification.
