# 🚀 Neural Network Binary Classification with SGD & Adam

A complete, step-by-step implementation of a **basic neural network for binary classification**, demonstrating the full learning workflow including **forward propagation, loss computation, backpropagation, and weight updates using both SGD and Adam optimizers**.

This project is designed for **educational, research, and demonstration purposes**, with a strong focus on clarity, mathematical correctness, and optimization comparison.

---

## 📌 Project Overview

This project demonstrates:

- Binary classification using a **feedforward neural network**
- **Manual implementation** of:
  - Forward propagation
  - Binary cross-entropy loss
  - Backpropagation using the chain rule
- Parameter optimization using:
  - ✅ Stochastic Gradient Descent (SGD)
  - ✅ Adam Optimizer
- Performance comparison:
  - Training loss
  - Accuracy
  - Decision boundary visualization

The network is intentionally kept small to make the workflow easy to understand.

---

## 🧠 Neural Network Architecture

- **Input Layer:** 2 neurons  
- **Hidden Layer:** 2 neurons (kept small for demonstration)  
- **Activation:** ReLU  
- **Output Layer:** 1 neuron  
- **Output Activation:** Sigmoid  
- **Loss Function:** Binary Cross-Entropy  
- **Optimizers:** SGD & Adam  


---

## ⚙️ Features

- Clean forward propagation implementation  
- Detailed backpropagation with gradient calculations  
- Manual weight & bias updates  
- Learning rate parameterization  
- Epoch-based training visualization  
- Adam vs SGD comparison  
- Decision boundary plotting  

---

## 📊 Results Summary

- Adam shows **faster convergence**
- SGD is **slower and more sensitive** to the learning rate
- Adam achieves **higher accuracy and smoother training**
- The decision boundary learned by Adam is **more precise**

---

## 🔬 Scientific Basis

This project is aligned with core machine learning research:

- **Adam Optimizer** – Kingma & Ba (2015)  
- **ReLU Activation** – Nair & Hinton (2010)  
- **Binary Classification Theory** – Zhang (2004)