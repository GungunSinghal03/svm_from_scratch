# 🚀 Support Vector Machine (SVM) from Scratch

## 📌 Overview

This project implements a **Support Vector Machine (SVM)** classifier from scratch using **Python and NumPy**, without relying on machine learning libraries like `scikit-learn`.

The model is trained using **gradient descent optimization** and uses **hinge loss with L2 regularization**.

---

## 🎯 Objectives

* Understand the working of SVM at a low level
* Implement the math behind SVM manually
* Learn optimization using gradient descent

---

## 🧠 Concepts Covered

* Hyperplane & Decision Boundary
* Margin Maximization
* Support Vectors
* Hinge Loss Function
* Gradient Descent
* Regularization (Lambda parameter)

---

## ⚙️ Tech Stack

* Python 🐍
* NumPy

---

## 📂 Project Structure

```
svm.py        # SVM implementation from scratch
train.py      # Script to train and test the model
```

---

## 🔍 How It Works

1. Initialize weights and bias
2. Convert labels into -1 and 1
3. Apply hinge loss function
4. Update weights using gradient descent
5. Predict using sign function

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
python train.py
```

---

## 📊 Sample Output

```
Predictions: [0 0 0 1 1 1]
```

---

## 🔧 Hyperparameters

| Parameter        | Description                            |
| ---------------- | -------------------------------------- |
| learning_rate    | Controls step size in gradient descent |
| no_of_iterations | Number of training iterations          |
| lambda_parameter | Regularization strength                |

---

## 🚀 Future Improvements

* Add Kernel Trick (RBF, Polynomial)
* Add visualization of decision boundary
* Use stochastic gradient descent (SGD)
* Support multi-class classification

---

## 💡 Key Learnings

* How SVM maximizes margin
* Role of support vectors in defining the boundary
* Importance of regularization in avoiding overfitting

---

## 👨‍💻 Author

**Gungun Singla**

---

## ⭐ If you found this useful

Give this repo a ⭐ and share it!
