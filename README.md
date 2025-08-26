# Handwritten-Digit-Recognition-MNIST-



This project demonstrates **Handwritten Digit Recognition** using the famous **MNIST dataset**.  
We apply three different Machine Learning models and compare their performance:

- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)

---

## 🚀 Dataset
The **MNIST dataset** contains 70,000 images of handwritten digits (0–9):  
- 60,000 training images  
- 10,000 testing images  

Each image is **28x28 pixels (grayscale)**.

We load it using:
```python
from sklearn.datasets import fetch_openml
mnist = fetch_openml('mnist_784', version=1)
