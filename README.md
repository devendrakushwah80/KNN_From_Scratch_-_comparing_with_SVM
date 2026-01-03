# 🔍 KNN & SVM From Scratch (NumPy Implementation)

This project demonstrates **how core machine learning algorithms work internally** by implementing **K-Nearest Neighbors (KNN)** and **Support Vector Machine (SVM)** **from scratch using NumPy**, without relying on high-level ML libraries like `sklearn` for modeling.

The goal is to build **strong algorithmic intuition** by coding everything manually — distance calculations, margin optimization, predictions, and evaluation.

---

## 📌 Algorithms Implemented

### 1️⃣ Support Vector Machine (SVM) – From Scratch
- Binary classification
- Hard-margin / Soft-margin logic
- Gradient descent–based optimization
- Manual weight & bias updates
- Hinge loss intuition

### 2️⃣ K-Nearest Neighbors (KNN) – From Scratch
- Distance-based classification
- Supports multiple distance metrics
- Majority voting using nearest neighbors
- No training phase (lazy learning)

---

## 🧠 Key Concepts Covered

- Margin maximization in SVM
- Support vectors intuition
- Regularization using λ (lambda)
- Distance metrics (Euclidean, Manhattan)
- Bias–variance trade-off
- From-scratch ML without shortcuts

---

## ⚙️ Tech Stack

- **Python**
- **NumPy**
- **Collections (Counter)**
- **scikit-learn** (only for metrics comparison)

---

## 📂 Project Structure
KNN_&_SVM_From_Scratch.ipynb
README.md
requirements.txt

---

## 🧩 SVM Implementation Highlights

- Labels converted to `{-1, +1}` format
- Weight vector initialized manually
- Uses hinge-loss–based update rule
- Iterative optimization using gradient descent
- Bias updated separately

**Why this matters:**  
Understanding SVM internally helps in debugging, tuning `C`, kernel intuition, and interview-level clarity.

---

## 🧩 KNN Implementation Highlights

- Custom distance function
- Supports:
  - Euclidean distance
  - Manhattan distance
- Uses `Counter` for majority voting
- Simple and interpretable logic

**Why this matters:**  
KNN shows how distance geometry drives classification decisions.

---

## 🧪 Dataset Used

- **Synthetic 2D dataset**
- Binary class labels: `+1` and `-1`
- Designed to clearly visualize decision boundaries

---

## 📊 Evaluation Metrics

- Custom accuracy function
- `accuracy_score`
- `confusion_matrix`
- `classification_report`

Metrics are used **only for evaluation**, not model training.

---

## 🎯 Learning Outcomes

✔ Understand SVM weight updates mathematically  
✔ Learn how margins and penalties work  
✔ Build KNN without `sklearn`  
✔ Strengthen ML fundamentals  
✔ Interview-ready algorithm clarity  

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
Open the notebook:
jupyter notebook KNN_&_SVM_From_Scratch.ipynb
