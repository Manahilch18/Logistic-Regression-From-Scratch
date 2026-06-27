# 🎓 Student Placement Prediction — Logistic Regression from Scratch

A step-by-step implementation of **Logistic Regression built from scratch** using NumPy, compared against Scikit-Learn's built-in model. This project is part of my ML learning journey.

---

## 📌 What I Built

| Step | What I Did |
|------|------------|
| 1️⃣ Perceptron Trick | Implemented the basic perceptron algorithm from scratch |
| 2️⃣ Sigmoid Activation | Replaced the step function with sigmoid for smooth probabilities |
| 3️⃣ Gradient Descent | Added gradient descent with loss minimization (log-likelihood) |
| 4️⃣ L2 Regularization | Added weight decay to match Sklearn's behavior |
| 5️⃣ Sklearn Comparison | Compared decision boundaries side by side |

---

## 📊 Result

My scratch model achieved a decision boundary slope of **m = -1.11**, while Sklearn's Logistic Regression gave **m = -1.12** — a difference of just **0.01**.

> ✅ Near-perfect match with Sklearn using pure NumPy!

---

## 🗂️ Project Structure

```
📦 student-placement-prediction
 ┣ 📓 notebook.ipynb       # Main Kaggle notebook
 ┣ 📄 README.md            # This file
 ┗ 📁 input/
    ┗ placement.csv        # Dataset (from Kaggle)
```

---

## 🧠 Concepts Covered

- **Perceptron Algorithm** — weight update rule: `w = w + lr * (y - ŷ) * x`
- **Sigmoid Function** — `σ(z) = 1 / (1 + e^(-z))`
- **Binary Cross-Entropy Loss** — log-likelihood minimization
- **Gradient Descent** — `w = w - lr * ∇L`
- **L2 Regularization** — `gradient += (λ/m) * w` (bias excluded)
- **Decision Boundary** — derived from: `Feature2 = m * Feature1 + b`

---

## 📈 Visualizations

The notebook includes:
- Linearly separable synthetic data scatter plot
- Perceptron decision boundary
- Side-by-side comparison: Scratch vs Sklearn
- Three-way comparison: Perceptron vs Sigmoid vs Sklearn

---

## 🚀 How to Run

**Option 1 — Kaggle (Recommended):**
Open directly on Kaggle and click **Run All**.

**Option 2 — Local:**
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
jupyter notebook notebook.ipynb
```

**Dataset:** [Student Placement Prediction on Kaggle](https://www.kaggle.com/datasets/lizasareen/student-placement-prediction)

---

## 📚 Dataset

- **Source:** Kaggle — `lizasareen/student-placement-prediction`
- **Features Used:** Synthetic 2D data generated with `np.random.seed(10)` for clean linear separability

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![NumPy](https://img.shields.io/badge/NumPy-1.x-orange?logo=numpy)
![Sklearn](https://img.shields.io/badge/Scikit--Learn-1.x-green?logo=scikit-learn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-red)

---

## 🔑 Key Takeaway

> Building ML algorithms from scratch, then matching Sklearn's output, is the **best way to truly understand** what's happening under the hood.

---

## 👨‍💻 Author

**Manahilch18**
- 📌 Kaggle:  https://www.kaggle.com/code/eyaminal/logistic-regression-from-scratch-math-to-code-al 
- 🐙 GitHub:  https://github.com/Manahilch18/Logistic-Regression-From-Scratch.git

---

⭐ If you found this helpful, please **star the repo!**
