# Logistic Regression From Scratch

This project contains an implementation of Logistic Regression written from scratch using Python and NumPy.

The objective of this implementation is to understand how logistic regression works internally, including probability estimation and parameter updates using gradient descent, without using machine learning libraries such as scikit-learn.

## Features
- Binary classification
- Sigmoid activation function
- Gradient descent optimization
- Separate fit and predict methods
- No external ML libraries used

## How the Algorithm Works
1. Initialize weights and bias
2. Compute linear combination of inputs and weights
3. Apply sigmoid function to get probabilities
4. Calculate gradients using loss derivative
5. Update weights and bias using gradient descent
6. Repeat for multiple iterations

## Libraries Used
- NumPy

## Notes
- This implementation is for educational purposes
- The model outputs probabilities between 0 and 1
- Thresholding can be applied for final class prediction

## Author
Computer Science Undergraduate  
Learning Machine Learning from first principles
