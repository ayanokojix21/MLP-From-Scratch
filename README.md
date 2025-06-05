# Building an MLP from Scratch

This repository contains a step-by-step implementation of a **Multi-Layer Perceptron (MLP)** built from the ground up using basic PyTorch operations, without relying on high-level abstractions like `nn.Linear` or `nn.Sequential`.

It is intended as a deep learning educational project to gain a low-level understanding of how neural networks are built, trained, and evaluated—focusing on concepts like weight initialization, forward propagation, loss calculation, and backpropagation.

---

## 📓 Notebook: `Building_MLP_From_Scratch.ipynb`

### 🧩 Features Implemented:
- Manual creation of weights and biases
- Custom forward pass using `torch.tanh` and matrix operations
- Logits computation and softmax-based prediction
- Manual loss calculation using Cross Entropy
- Manual gradient computation and parameter updates
- Training and validation loops
- Seed control for reproducibility

### 📊 Dataset
This notebook uses a small character-level dataset to predict next characters (inspired by name-generation tasks). You can swap in your own datasets for experimentation.

---

### Acknowledgements

This project was heavily inspired by ***Andrej Karpathy*** and his low-level deep learning explorations. Special thanks for his educational content and clean explanations on building neural networks from scratch.
