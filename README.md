# 💳 Credit Card Fraud Detection using Hybrid ML + SHAP

## 📌 Overview
This project detects fraudulent credit card transactions using a hybrid machine learning approach combining SMOTE, Random Forest, and SHAP.

---

## 🚀 Key Features
- Handles class imbalance using SMOTE
- Uses Random Forest for classification
- Applies SHAP for explainable AI
- Achieves ~95% accuracy and ROC-AUC

---

## 🧠 Hybrid Model
This project uses a hybrid approach:
- **Data Level** → SMOTE (balances dataset)
- **Model Level** → Random Forest (prediction)
- **Explainability** → SHAP (interpretation)

---

## 📊 Dataset
- 284,807 transactions
- Highly imbalanced dataset
- Fraud cases: 492

Dataset Source: Kaggle Credit Card Fraud Dataset

---

## 📈 Results
- Accuracy: ~95%
- ROC-AUC: ~0.95
- High recall for fraud detection

---

## 🔍 SHAP Insights
- Fraud depends on specific dominant features
- Legitimate transactions are more evenly distributed
- Improves model interpretability

---

## 🛠 Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- imbalanced-learn (SMOTE)
- SHAP

---

## ▶️ How to Run
1. Open notebook in Google Colab
2. Install required libraries
3. Run all cells

---

## 📂 Project Structure
