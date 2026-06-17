# Activation Function Analysis in Deep Learning

## Overview

This project provides a comprehensive analysis of activation functions used in deep learning. The notebook explores the mathematical behavior, derivative characteristics, gradient propagation properties, computational efficiency, and practical limitations of various activation functions commonly employed in neural networks.

The study includes both classical and modern activation functions, along with a custom activation function designed for experimental evaluation.

---

## Objectives

* Implement activation functions from scratch using Python.
* Visualize activation curves and their derivatives.
* Analyze gradient propagation behavior.
* Investigate the vanishing gradient problem.
* Demonstrate the dead neuron problem.
* Compare computational efficiency across activation functions.
* Explore modern activation functions such as Swish, GELU, and Mish.
* Design and evaluate a custom activation function.

---

## Activation Functions Covered

* Sigmoid
* Tanh
* ReLU
* Leaky ReLU
* Swish
* GELU
* Mish
* Custom Activation Function

---

## Project Structure

```text
Activation-Function-Analysis/
│
├── Activation_Function_Analysis.ipynb
├── README.md
├── requirements.txt
└── LICENSE
```

---

## Experimental Phases

### 1. Implementation of Activation Functions

Implementation of activation functions and their derivatives using NumPy.

### 2. Visualization of Activation Functions

Graphical comparison of activation curves.

### 3. Derivative Analysis

Visualization and interpretation of derivative behavior.

### 4. Observational Analysis

Evaluation of activation characteristics and learning behavior.

### 5. Vanishing Gradient Experiment

Investigation of gradient decay in deep networks.

### 6. Dead Neuron Experiment

Analysis of inactive neurons caused by ReLU.

### 7. Output Distribution Analysis

Study of output activation distributions.

### 8. Computational Efficiency Benchmark

Performance comparison based on execution time.

### 9. Modern Activation Functions

Exploration of Swish, GELU, and Mish activations.

### 10. Custom Activation Function

Design and evaluation of a novel activation function.

---

## Technologies Used

* Python
* NumPy
* Matplotlib
* Jupyter Notebook

---

## Key Findings

* Sigmoid suffers from severe vanishing gradient issues.
* Tanh provides zero-centered outputs but still experiences gradient decay.
* ReLU offers efficient computation and strong gradient propagation.
* Leaky ReLU mitigates the dead neuron problem.
* Swish, GELU, and Mish provide smoother gradients and improved learning dynamics.
* Modern activation functions often outperform traditional activations in deep architectures.

---

## Future Improvements

* Integration with TensorFlow and PyTorch.
* Training neural networks using each activation function.
* Performance evaluation on real-world datasets.
* Hyperparameter optimization studies.

---

## Author

Sifat Bhatia

B.Tech Computer Science Engineering

Focused on Machine Learning, Artificial Intelligence, and Deep Learning Research.
