# 🚀 Linear Regression from Scratch (Gradient Descent)

This project demonstrates how Linear Regression works internally by implementing Gradient Descent from scratch in Python and comparing the results with sklearn's LinearRegression.

---

## 📌 Objective

The goal of this project is to:

- Understand the mathematics behind Linear Regression
- Manually derive gradient update rules
- Implement Gradient Descent optimization
- Compare results with sklearn’s built-in implementation

---

## 🧠 Problem Statement

We try to fit a line:

ŷ = mx + b

Where:
- m = slope
- b = intercept

We minimize the Sum of Squared Errors (SSE):

SSE = Σ (y - ŷ)²

Using Gradient Descent, parameters are updated as:

b = b - learning_rate * (-2 Σ (y - ŷ))
m = m - learning_rate * (-2 Σ (y - ŷ)x)

---

## 🛠️ Implementation Steps

1. Generate synthetic dataset using `make_regression`
2. Split into train and test sets
3. Train model using:
   - sklearn LinearRegression (baseline)
   - Custom Gradient Descent implementation
4. Compare performance using R² score

---

## 📊 Results

The custom Gradient Descent model achieves an R² score very close to sklearn’s implementation, validating correctness.

Minor differences may occur due to:
- Iterative optimization
- Learning rate choice
- Number of epochs

---

## 🔍 Key Learnings

- Effect of learning rate on convergence
- Oscillation and divergence behavior
- Difference between closed-form solution and iterative optimization
- Importance of scaling in Gradient Descent

---

## 🚀 Future Improvements

- Add Loss vs Epoch visualization
- Extend to Multiple Linear Regression
- Implement Mini-batch Gradient Descent
- Add feature scaling

---

## 👨‍💻 Author

Built as a hands-on project to deeply understand how machine learning algorithms work internally.

If you found this helpful, consider giving it a ⭐
