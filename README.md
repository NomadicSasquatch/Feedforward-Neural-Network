# Exploring Custom Feedforward Neural Network Framework from Scratch
A fully custom feedforward neural network framework built from scratch using Python and NumPy. This project demonstrates how to implement feedforward neural networks entirely from scratch without relying on deep learning frameworks. It is intended for experimental purposes, providing a clear, step-by-step breakdown of forward passes (both elementwise and vectorized), backpropagation logic (manual chain rule for each parameter), different optimizers and how they update weights, various datasets of increasing difficulty to illustrate how networks adapt, while the ElementWiseFFN and MatrixFFN classes serve primarily as teaching tools, the MultiLayerFFN class is more flexible and closer to real-world architectures.

## Table of Contents
### 1. Features
### 2. Installation
### 3. Usage
---

## 1. Features

### 1. Fundamental Building Blocks:
- Activation functions (Sigmoid, ReLU)
- Loss functions (Binary Cross-Entropy, Mean Squared Error)
- Optimizers (SGD, Momentum, Adam)

### 2. Three Implementation Variants:
- ElementWiseFFN: A simple, hardcoded 2-2-1 network with elementwise operations
- MatrixFFN: A two-layer, fully-connected network using matrix operations
- MultiLayerFFN: An extensible, arbitrary-depth network suitable for experimentation

### 3. Training on Multiple Datasets:
- Linearly Separable
- Two Moons
- Interleaved Spirals

### 4. Systematic Comparisons:
- Investigations into how different activation functions, loss functions, and optimizers perform on various datasets, with MultiLayerFFN serving as the primary testbed
---
## 2. Installation
1. Clone the Repository:
   ```bash
    git clone https://github.com/NomadicSasquatch/Feedforward-Neural-Network.git
    cd Feedforward-Neural-Network
   ```
2. Set up a Python Virtual Environment:
  ```bash
    python -m venv venv
    source venv/bin/activate #on Mac
    venv\Scripts\activate #on Windows
  ```
3. Install Dependencies:
   ```bash
     pip install -r requirements.txt
   ```
--- 
## 3. Usage
- Run all cells
