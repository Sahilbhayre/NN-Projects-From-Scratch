# Fashion-MNIST Neural Network From Scratch

A neural network built **from scratch using NumPy** to classify clothing images from the Fashion-MNIST dataset, without using deep-learning frameworks such as TensorFlow, PyTorch, or Keras.

## 📌 Project Overview

This project focuses on understanding the internal working of a neural network by implementing its major components manually.

The model classifies Fashion-MNIST images into **10 different clothing categories**.

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
Predicted Class
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

The project uses the **Fashion-MNIST dataset**.

Each image contains:

```text
28 × 28 pixels = 784 input features
```

The original pixel values range from:

```text
0–255
```

The values are normalized to:

```text
0–1
```

The dataset contains 10 clothing categories.

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

> Scikit-learn was used for dataset loading; the neural network itself was implemented manually using NumPy.

## 📈 Results

| Metric | Result |
|---|---:|
| Test Accuracy | **87%** |

The model achieved **87% accuracy** on the Fashion-MNIST classification task.

## 🔍 Model Workflow

```text
Fashion-MNIST Dataset
        ↓
Data Preprocessing
        ↓
Normalization
        ↓
Forward Propagation
        ↓
Softmax Prediction
        ↓
Cross-Entropy Loss
        ↓
Backpropagation
        ↓
Gradient Descent
        ↓
Updated Parameters
        ↓
Evaluation
```

## 📁 Project Structure

```text
Fashion-MNIST-Neural-Network-From-Scratch/
│
├── fashion_mnist_nn.ipynb
└── README.md
```

## 🚀 How to Run

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/Fashion-MNIST-Neural-Network-From-Scratch.git
```

Open the notebook:

```bash
jupyter notebook fashion_mnist_nn.ipynb
```

Run the cells from top to bottom.

## 🎯 What I Learned

This project helped me understand the complete learning process of a neural network, including:

```text
Forward Propagation
        ↓
Loss Calculation
        ↓
Backpropagation
        ↓
Gradient Descent
        ↓
Parameter Updates
```

Building the model without a deep-learning framework gave me a stronger understanding of what happens inside neural-network training.

## 👨‍💻 Author

**Sahil Bhayre**

B.Tech CSE — AI/ML  
UIET, MDU Rohtak

---

⭐ If you found this project useful, consider giving the repository a star.