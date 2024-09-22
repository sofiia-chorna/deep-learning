# Deep Learning Course
## Lab 1: Multi-Layer Perceptron (MLP)

This lab consists of two parts where we explore the implementation of a Multi-Layer Perceptron (MLP) for classification problems. We first build an MLP from scratch using `numpy` and then move on to different approaches using `pytorch`.

### Part One: MLP Implementation with Numpy
**Notebook**: [DL_MLP_fromscratch.ipynb](./DL_MLP_fromscratch.ipynb)

In this part, we manually implement a two-layer MLP with one hidden layer using only `numpy`. 

Key Concepts Covered: Forward Propagation, Backward Propagation, Loss Calculation, Manual Weight Updates.

---

### Part Two: MLP Implementation with PyTorch
**Notebook**: [DL_MLP_pytorch.ipynb](./DL_MLP_pytorch.ipynb)

In this part, we develop a MLP with two hidden layers using `pytorch` and experiment with three different approaches for binary classification.

### Three Models Implemented:
- **Model A**: Manual parameter definition (W1, b1, W2, b2, W3, b3), forward propagation equations, backpropagation, and update the weights using the gradients.
- **Model B**: Implementation using `torch.nn.Sequential`.
- **Model C**: A custom class inheriting from `torch.nn.Module`, where the forward method is explicitly defined.

Key Concepts Covered: PyTorch tensors, PyTorch’s automatic differentiation, custom neural network architectures
