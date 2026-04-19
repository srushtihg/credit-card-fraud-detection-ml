# Hybrid Credit Card Fraud Detection using Autoencoder + XGBoost

# Overview
This project implements a hybrid machine learning approach for detecting fraudulent credit card transactions by combining unsupervised anomaly detection and supervised classification.

The system integrates:
- Autoencoder (anomaly detection)
- Reconstruction error (feature engineering)
- ADASYN (class imbalance handling)
- XGBoost (classification)
- Threshold optimization (performance tuning)

---

##  Hybrid Model Architecture

The model combines multiple techniques:

### 🔹 1. Autoencoder (Unsupervised Learning)
- Trained only on normal transactions
- Learns patterns of legitimate behavior
- Outputs reconstruction error as anomaly score

### 🔹 2. Feature Engineering
- Reconstruction error is added as a new feature
- Helps capture abnormal transaction behavior

### 🔹 3. ADASYN (Class Balancing)
- Generates synthetic fraud samples
- Improves learning on minority class

### 🔹 4. XGBoost Classifier
- Trained on enhanced dataset
- Handles complex relationships efficiently

### 🔹 5. Threshold Optimization
- Adjusts decision threshold
- Maximizes F1-score
- Improves fraud detection accuracy

---

## 📊 Dataset

- Total transactions: **284,807**
- Fraud cases: **492**
- Highly imbalanced dataset

Dataset Source:
👉 Kaggle Credit Card Fraud Detection Dataset

To reduce computation, a sample (~30,000 rows) was used.

---

## ⚙️ Methodology

1. Data preprocessing and sampling  
2. Feature scaling (StandardScaler)  
3. Train Autoencoder on normal transactions  
4. Compute reconstruction error  
5. Add anomaly score as feature  
6. Apply ADASYN for balancing  
7. Train XGBoost model  
8. Optimize classification threshold  
9. Evaluate model performance  

---

## 📈 Results

- Strong fraud detection performance  
- Improved F1-score through threshold tuning  
- Reduced false negatives (critical for finance)  
- Enhanced detection using anomaly feature  

---

## 🔍 Key Insights

- Fraud transactions show higher reconstruction error  
- Combining anomaly detection + supervised learning improves performance  
- Hybrid models outperform single-model approaches  

---

## 🛠 Tech Stack

- Python  
- Pandas, NumPy  
- Scikit-learn  
- TensorFlow / Keras (Autoencoder)  
- XGBoost  
- imbalanced-learn (ADASYN)  

---

## ▶️ How to Run

1. Open notebook in Google Colab  
2. Install required libraries  
3. Run all cells  

---

## 📂 Project Structure
