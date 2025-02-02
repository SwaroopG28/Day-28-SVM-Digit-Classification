# 🖥️ SVM Digit Classification using MNIST Dataset

## 📜 Project Overview
This project implements **Support Vector Machine (SVM)** for **handwritten digit classification** using the **inbuilt MNIST Digits dataset** from `sklearn.datasets`.  
The dataset consists of **8x8 grayscale images of digits (0-9)**, and the goal is to build an SVM classifier to predict the correct digit.

## 🎯 Objective
- Train an **SVM model** to classify digits from 0 to 9.
- Use **feature scaling** to improve model performance.
- Evaluate **accuracy, confusion matrix, and classification report**.

---

## 📂 Dataset Information
- **Source**: Built-in `digits` dataset from `sklearn.datasets`
- **Images**: 8x8 grayscale pixels per digit
- **Total Samples**: 1,797
- **Classes**: 10 (Digits 0-9)
- 
---

## 🚀 Model Training Steps
1. **Load Data**: Fetch MNIST Digits dataset using `datasets.load_digits()`.
2. **Preprocessing**:
   - Split dataset into **Training (80%)** & **Testing (20%)**.
   - Normalize features using **StandardScaler**.
3. **Train SVM Model**:
   - Kernel: **RBF (Radial Basis Function)**
   - Hyperparameters: **C=10, Gamma=0.01**
4. **Model Evaluation**:
   - Compute **Accuracy**: `98.06%`
   - Generate **Confusion Matrix**.
   - Display **Classification Report**.
5. **Prediction on Test Images**:
   - Visualize a sample test image and check model prediction.

---

## 🏆 Results
✅ **Test Accuracy**: `98.06%`  
✅ **SVM performed well in recognizing handwritten digits**.
