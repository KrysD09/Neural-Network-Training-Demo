# Neural Network Training Demo

This repository contains three interactive Jupyter notebooks designed for a **PhD-level workshop on training neural networks**.  
It demonstrates a **from-scratch NumPy implementation**, a **PyTorch implementation**, and a **Keras implementation**, with experiments to explore key training concepts.

---

## 📂 Contents
- **`nn_training_demo.ipynb`**  
  Build and train a neural network **from scratch** using only NumPy. Covers:
  - Forward propagation
  - Backpropagation
  - Gradient checking
  - Loss curves & decision boundaries
  - Experiments: learning rate, regularization, overfitting

- **`nn_training_pytorch_demo.ipynb`**  
  Train the **same network using PyTorch**. Covers:
  - Training loop with `torch.nn` and `torch.optim`
  - Learning rate, weight decay, and dropout experiments
  - Seed sensitivity and robustness to noisy labels
  - Gradient sanity checks (autograd vs finite differences)

- **`nn_training_keras_demo.ipynb`**  
  Train the **same network using Keras (TensorFlow)**. Covers:
  - High-level training with `model.fit`
  - Learning rate, L2 regularization, dropout experiments
  - Seed sensitivity and robustness to noisy labels
  - Gradient sanity check with `tf.GradientTape`

- **`requirements.txt`**  
  Minimal dependencies (NumPy, Matplotlib, Jupyter). Add PyTorch/TensorFlow for framework demos.

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/KrysD09/Neural-Network-Training-Demo.git
cd Neural-Network-Training-Demo
```

### 2. Set up a virtual environment
```bash
python -m venv nn_env
source nn_env/bin/activate   # Mac/Linux
nn_env\Scripts\activate    # Windows
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

---

## ☁️ Run on Google Colab

You can run the demos directly in Colab without installing anything locally:

- [![Open In Colab - NumPy](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KrysD09/Neural-Network-Training-Demo/blob/main/nn_training_demo.ipynb)  
- [![Open In Colab - PyTorch](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KrysD09/Neural-Network-Training-Demo/blob/main/nn_training_pytorch_demo.ipynb)  
- [![Open In Colab - Keras](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KrysD09/Neural-Network-Training-Demo/blob/main/nn_training_keras_demo.ipynb)

---

## 🎓 Workshop Experiments
- **Learning rate sweep** → stability vs divergence  
- **L2 regularization** → prevents overfitting  
- **Dropout** → adds robustness  
- **Seed sensitivity** → initialization effects  
- **Label noise** → robustness to imperfect data  
- **Gradient check** → compare framework autograd with finite differences  

---

## 📜 License
MIT License (free to use, modify, and share).
