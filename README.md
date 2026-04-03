# 🧠 Perceptron from Scratch using NumPy

## 📌 Overview

This project implements a simple **Perceptron model from scratch** using only NumPy, without relying on any machine learning libraries like Scikit-learn or TensorFlow.

The Perceptron is one of the earliest and simplest types of artificial neural networks used for binary classification.

---

## 🎯 Objective

The goal of this project is to understand how a basic machine learning model works internally by building it manually.

---

## 🛠️ Technologies Used

* Python
* NumPy

---

## 📊 Dataset

A simple logical dataset is used:

| Input (X) | Output (y) |
| --------- | ---------- |
| [0, 0]    | 0          |
| [0, 1]    | 1          |
| [1, 0]    | 1          |
| [1, 1]    | 1          |

This represents a logical **OR gate**.

---

## ⚙️ How It Works

1. Initialize weights and bias to zeros
2. Loop over the dataset multiple times (epochs)
3. Calculate the linear combination:

   ```
   z = w.x + b
   ```
4. Apply activation function:

   * If z ≥ 0 → output = 1
   * Else → output = 0
5. Update weights and bias if prediction is wrong

---

## 🚀 Features

* Built completely from scratch
* No external ML libraries
* Easy to understand implementation
* Demonstrates core ML concepts:

  * Linear model
  * Activation function
  * Weight updates

---

## 📁 Project Structure

```
Simple_Perceptron_Model/
│
├── main.py   # Main implementation
└── README.md       # Project documentation
```

---

## 💡 Key Learning Points

* Understanding how ML models learn
* Importance of learning rate
* Role of activation functions
* Basics of linear classification

---


## ⭐ Notes

This project is for educational purposes and demonstrates the fundamentals of machine learning.
