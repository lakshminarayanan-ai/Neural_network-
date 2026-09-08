# Neural Networks

## 📌 Overview

This repository contains learning material about Neural Networks, an important concept in Artificial Intelligence (AI) and Machine Learning (ML).

A Neural Network consists of interconnected artificial neurons that receive input data, process information, identify patterns, and produce an output.

## 📚 Topics Covered

- Introduction to Neural Networks
- Basic Structure of Neural Networks
- Input Layer
- Hidden Layer
- Output Layer
- Activation Functions
- Binary Step Function
- Linear Activation Function
- Sigmoid Function
- Tanh Function
- ReLU
- Leaky ReLU
- Softmax
- Neural Network Terminology
- Forward Propagation
- Loss Function
- Backpropagation
- Epoch
- Learning Rate
- Gradient Descent

## 🧠 Basic Structure

Input Layer → Hidden Layer(s) → Output Layer

## ⚡ Activation Functions

### Binary Step Function

Produces 0 or 1 based on a threshold.

### Linear Activation Function

f(x) = x

### Sigmoid Function

f(x) = 1 / (1 + e⁻ˣ)

### Tanh Function

f(x) = (eˣ − e⁻ˣ) / (eˣ + e⁻ˣ)

### ReLU

f(x) = max(0, x)

### Leaky ReLU

f(x) = x, if x > 0  
f(x) = αx, if x ≤ 0

### Softmax

Softmax is mainly used for multiclass classification. It converts output values into probabilities whose total is 1.

Example:

- Cat = 0.70
- Dog = 0.20
- Bird = 0.10

## 🔄 Neural Network Training

### Forward Propagation

Input → Hidden Layer → Output

### Loss Function

Measures the difference between the actual output and the predicted output.

### Backpropagation

Updates the weights and biases based on the error produced by the network.

### Epoch

One complete pass of the entire training dataset through the Neural Network.

### Learning Rate

Determines how much the weights are changed during training.

### Gradient Descent

An optimization algorithm used to minimize the loss function.

## 🎯 Applications

- Image Recognition
- Speech Recognition
- Natural Language Processing (NLP)
- Medical Diagnosis
- Recommendation Systems
- Classification
- Prediction

## 📄 Reference

Detailed notes are available in:

`NeuralNetworks.pdf`

## 🏁 Conclusion

Neural Networks learn patterns and relationships from data using interconnected neurons, weights, biases, layers, and activation functions.
