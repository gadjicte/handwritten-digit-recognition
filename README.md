# 🧠 Handwritten Digit Recognition with Neural Networks

This project uses a simple deep learning model to recognize handwritten digits (0–9) using the MNIST dataset. Built in Python using TensorFlow and Keras, this notebook trains a neural network and evaluates its performance visually.

## 📚 Overview

- Dataset: **MNIST** (images of handwritten digits)
- Model: **Sequential Neural Network** (Fully Connected)
- Framework: **TensorFlow/Keras**
- Interface: **Jupyter Notebook (`main.ipynb`)**

## 📁 Files

```text
handwritten-digit-recognition/
│
├── main.ipynb         # Jupyter Notebook with full code and explanation
├── README.md          # Project overview and usage instructions
└── requirements.txt   # List of required Python packages
```


## 🚀 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/gadjicte/handwritten-digit-recognition.git
cd handwritten-digit-recognition
```
### 2. Create a Virtual Environment (optional but recommended)
```
python -m venv venv
venv\Scripts\activate  # On Windows
```
### 3. Install Requirements
```
pip install -r requirements.txt
```
### 4. Launch Jupyter Notebook
```
jupyter notebook main.ipynb
```
### 🧠 Model Summary
Input: 28x28 grayscale images

Flatten layer

2 Dense layers with ReLU activation

Output layer with Softmax activation

The model learns to classify digits with high accuracy after training.

### 📊 Training Results
Add screenshots here (optional):

Accuracy & loss plot

Sample predictions

### 📦 Requirements
See requirements.txt file or use:
```
pip install tensorflow numpy matplotlib
```
### 🎓 Learning Goals
Understand basic deep learning workflows

Preprocess image data for neural networks

Visualize training performance

Predict and evaluate model accuracy
