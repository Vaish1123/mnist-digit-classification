# 🖊️ MNIST Digit Classification with Neural Networks

This project trains a simple Neural Network on the MNIST dataset (handwritten digits 0–9) using **Keras + TensorFlow**.  
It’s my first deep learning project and a foundation for more advanced experiments.

---

## 📌 Dataset
- **MNIST**: 70,000 images (28x28 grayscale digits).  
- 60,000 training, 10,000 testing.  

---

## ⚙️ Model
- Input layer: 784 neurons (28x28 images flattened)  
- Hidden layers: Dense + Dropout  
- Output: 10 classes (softmax activation)  

---

## 🚀 Results
- Test Accuracy: **~97%**  
- Confusion Matrix:  
  ![Confusion Matrix](results/confusion_matrix.png)  

---

## 📦 Setup
```bash
git clone https://github.com/yourusername/mnist-digit-classification.git
cd mnist-digit-classification
pip install -r requirements.txt
python mnist_classification.py
