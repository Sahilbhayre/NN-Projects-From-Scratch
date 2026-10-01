# MNIST Neural Network From Scratch

A handwritten digit classification neural network built **from scratch using NumPy**, without using deep-learning frameworks such as TensorFlow, PyTorch, or Keras.

## 📌 Project Overview

This project implements a basic neural network to classify handwritten digits from the **MNIST dataset**.

The main goal was to understand how a neural network works internally by implementing the core components manually rather than using a pre-built deep-learning framework.

## 🧠 Neural Network Architecture

```text
Input Layer
784 neurons
     ↓
Hidden Layer
128 neurons
     ↓
ReLU Activation
     ↓
Output Layer
10 neurons
     ↓
Softmax
     ↓
Predicted Digit (0–9)
```

### Architecture

```text
784 → 128 → 10
```

- **Input:** 784 pixels (28 × 28 image)
- **Hidden layer:** 128 neurons
- **Activation:** ReLU
- **Output layer:** 10 neurons
- **Output activation:** Softmax

## ⚙️ Concepts Implemented From Scratch

- Neural network layers
- Weight and bias initialization
- Forward propagation
- ReLU activation
- Softmax activation
- Cross-entropy loss
- One-hot encoding
- Backpropagation
- Gradient calculation
- Gradient descent
- Mini-batch training
- Model evaluation

## 📊 Dataset

The project uses the **MNIST handwritten digit dataset**.

Each image:

```text
28 × 28 pixels = 784 input features
```

Pixel values are normalized from:

```text
0–255
```

to:

```text
0–1
```

## 🛠️ Technologies Used

- Python
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

> Scikit-learn was used for dataset loading; the neural network itself was implemented manually using NumPy.

## 📈 Results

| Metric | Result |
|---|---:|
| Test Accuracy | **97.5%** |

The model achieved **97.5% test accuracy** on the MNIST dataset.

## 🔍 Example Prediction

The notebook also includes visualization of predictions and comparison between predicted and actual labels.

## 📁 Project Structure

```text
MNIST-Neural-Network-From-Scratch/
│
├── MNIST_Neural_Network.ipynb
└── README.md
```

## 🚀 How to Run

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/MNIST-Neural-Network-From-Scratch.git
```

Open the notebook:

```bash
jupyter notebook MNIST_Neural_Network.ipynb
```

Run the cells from top to bottom.

## 🎯 What I Learned

Through this project, I developed a practical understanding of how a neural network learns:

```text
Input
  ↓
Forward Propagation
  ↓
Prediction
  ↓
Loss Calculation
  ↓
Backpropagation
  ↓
Gradient Descent
  ↓
Updated Weights
  ↓
Better Predictions
```

The project helped me understand the internal mechanics of neural networks before moving toward deep-learning frameworks.

## 👨‍💻 Author

**Sahil Bhayre**

B.Tech CSE — AI/ML  
UIET, MDU Rohtak

---

⭐ If you found this project useful, consider giving the repository a star.