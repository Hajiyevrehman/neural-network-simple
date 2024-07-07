# Neural Network for Multi-class Classification (Part 1)

## Overview

This project implements a neural network model for multi-class classification using a toy dataset. It focuses on building fundamental components of neural networks from scratch.

## Project Structure

project_root
├── README.md (this file)
├── neural_network.ipynb (main notebook)
├── layers/
│   ├── linear.py
│   ├── relu.py
│   ├── softmax.py
│   ├── loss_func.py
│   └── sequential.py
└── utils/
    ├── trainer.py
    └── optimizer.py

## Implementation Details

You are required to implement the following components:

1. Linear Layer (`layers/linear.py`)
   - Implement linear layers with arbitrary input and output dimensions

2. ReLU Activation (`layers/relu.py`)
   - Implement ReLU activation function, forward and backward pass

3. Softmax Function (`layers/softmax.py`)
   - Implement softmax function to calculate class probabilities

4. Cross-Entropy Loss (`layers/loss_func.py`)
   - Implement CrossEntropy loss, forward and backward pass

Additionally, familiarize yourself with the pre-implemented components:
- `layers/sequential.py`
- `utils/trainer.py`
- `utils/optimizer.py`

## Running the Project

1. Open Jupyter Notebook:

2. Navigate to and open 

3. Run through the cells in the notebook to implement the neural network, train it, and analyze the results.

## Usage Tips

- Run all code cells in the notebook sequentially.
- Answer all inline questions in the designated areas.
- Aim for vectorized implementations to avoid using for loops.
- Do not change the random seed where it is set to ensure reproducibility.

