# micrograd-Tiny-Autograd-Engine-Neural-Net-from-Scratch
Inspired by Andrej Karpathy’s micrograd, this project implements a minimalistic autograd engine and a small feedforward neural network — all in under 100 lines of Python.

##  visualization

![2d neuron](gout.svg)


## 🔍 About Micrograd

[**micrograd**](https://github.com/karpathy/micrograd) is a minimalist, educational autograd engine and neural network library (MIT‑licensed), authored by **Andrej Karpathy**. It implements reverse‑mode automatic differentiation (backpropagation) over a dynamically constructed computation graph of **scalar `Value` objects**, and includes a tiny multilayer perceptron with a PyTorch‑like API—all in under ~200 lines of Python :contentReference[oaicite:1]{index=1}.

### Key Features
- **`Value` class** that tracks data and gradients, overloads operations (+, −, \*, **, tanh, exp, etc.)
- **Automatic topological sorting** for gradient propagation (`backward()`), implementing the chain rule :contentReference[oaicite:2]{index=2}
- **Small network library**: defines `Neuron`, `Layer`, and `MLP` classes to build and train feed‑forward networks :contentReference[oaicite:3]{index=3}
- Excellent for learning how deep learning frameworks compute gradients from first principles

---

## 🎥 Lecture: Building Micrograd

Karpathy walks through the implementation step‑by‑step in his “Neural Networks: Zero to Hero” YouTube lecture:

[The spelled‑out intro to neural networks and backpropagation: building micrograd](https://www.semanlink.net/doc/2022/11/the_spelled_out_intro_to_neural?utm_source=chatgpt.com)


In this ~2 h 25 m video he starts from scratch with a blank Jupyter notebook and builds up micrograd, explaining Value objects, manual backprop, and training a small MLP model on toy data :contentReference[oaicite:5]{index=5}.

---

## 🔗 Citations & Links

- **GitHub**: [karpathy/micrograd](https://github.com/karpathy/micrograd) :contentReference[oaicite:6]{index=6}  
- **Lecture**: [YouTube – Building micrograd from scratch]:contentReference[oaicite:7]{index=7}

---

## 📝 Attribution

This project is inspired by, or based on, Andrej Karpathy’s micrograd. Full credit to the original author under the MIT license.

