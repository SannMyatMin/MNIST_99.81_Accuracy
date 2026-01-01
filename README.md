# MNIST Digit Classification - 99.81% Accuracy

This repository contains a high-performance Deep Learning model designed to classify handwritten digits from the MNIST dataset. By utilizing a custom Convolutional Neural Network (CNN) architecture, this model achieves a top-tier test accuracy of **99.81%**.

## 📊 Performance Summary
- **Test Accuracy:** 99.81%
- **Dataset:** MNIST (Handwritten Digits)
- **Framework:** TensorFlow/Keras
- **Epochs:** (Insert number of epochs, e.g., 50)

## 🏗️ Model Architecture
The architecture is optimized to prevent overfitting while maintaining high feature extraction capabilities:
* **Conv2D Layers:** Filters with 3x3 kernels for spatial feature extraction.
* **Batch Normalization:** Applied after conv layers to stabilize and accelerate training.
* **Max Pooling:** To reduce dimensionality and computation.
* **Dropout:** Strategic dropout layers (0.25 - 0.5) to ensure generalization.
* **Dense Layers:** Fully connected layers with ReLU activation and a final Softmax output.



## 🚀 Installation & Usage

### 1. Clone the Repository
```bash
git clone [https://github.com/SannMyatMin/MNIST_99.81_Accuracy.git](https://github.com/SannMyatMin/MNIST_99.81_Accuracy.git)
cd MNIST_99.81_Accuracy
