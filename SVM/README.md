# Support Vector Machine (SVM) From Scratch

This project implements a **Support Vector Machine (SVM) classifier from scratch** using **Python and NumPy**, without using machine learning libraries such as `scikit-learn`.

The purpose of this implementation is to understand how SVM works internally, including **margin maximization, weight updates, hinge loss, and predictions**.

---

## 📌 Project Objectives
- Understand the core idea behind Support Vector Machines
- Learn how margins and hyperplanes are formed
- Implement SVM optimization logic manually
- Strengthen machine learning fundamentals

---

## 🚀 Features
- Manual implementation of Linear SVM
- Uses **hinge loss** for optimization
- Gradient-based weight and bias updates
- Separate training and prediction logic
- Implemented using NumPy only

---

## ⚙️ How It Works
1. Initialize weights and bias
2. Compute the decision function  
   \[
   y = w \cdot x + b
   \]
3. Apply hinge loss  
   \[
   \max(0, 1 - y(w \cdot x + b))
   \]
4. Update weights and bias using gradient descent
5. Repeat the process for multiple epochs
6. Predict class labels based on the sign of the output

---

## 🧮 Mathematical Background
- **Learning Type:** Supervised Learning
- **Algorithm Type:** Classification
- **Loss Function:** Hinge Loss
- **Regularization:** L2 (weight penalty)
- **Decision Boundary:** Maximum margin hyperplane

---

## 📚 Libraries Used
- **NumPy**
- **Matplotlib** (if used for visualization)

> No machine learning libraries are used.

---

## ▶️ Usage
This project is intended **for educational and learning purposes**.

You can:
- Modify learning rate and epochs
- Test with different datasets
- Visualize the decision boundary (for 2D data)

Run the notebook:
```bash
jupyter notebook SVM.ipynb
