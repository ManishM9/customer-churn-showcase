# customer-churn-showcase

# Customer Churn Prediction System

> Due to academic integrity policies, the full codebase is private.  
> For access or collaboration, feel free to reach out to me directly.

## Overview

This project was developed as part of the **CSE 587: Data Intensive Computing** course at the University at Buffalo.  
The objective is to identify customers likely to churn from a credit card portfolio and proactively suggest retention strategies using predictive modeling.

## Problem Statement

A business manager is facing customer attrition in a credit card portfolio. Our goal was to analyze the data, identify the key factors behind churn, and develop a robust model that can predict customer attrition accurately and support strategic business decisions.

---

## Tech Stack

| Component     | Technology                |
|---------------|----------------------------|
| Data Cleaning & Modeling | Python (Pandas, NumPy, scikit-learn, Seaborn, Matplotlib) |
| Frontend      | Angular (Single-page form UI) |
| Backend       | Node.js (API + Python execution) |
| Hosting       | Local demo only (academic use) |

---

## Phase-wise Breakdown

### Phase 1: Data Cleaning & Preprocessing
- Removed duplicates, handled outliers
- Imputed missing values using k-NN and statistical methods
- Feature transformation: One-hot encoding, normalization
- Conducted correlation analysis and exploratory data analysis (EDA)

### Phase 2: Model Development & Evaluation
We evaluated several machine learning models:
- k-Nearest Neighbors (Accuracy: 92%)
- Naïve Bayes (Accuracy: 88%)
- Logistic Regression (Accuracy: ~90%)
- Support Vector Machine (Accuracy: 90%)
- Decision Tree (Accuracy: 93%)
- Random Forest (Accuracy: 95.5%)

Metrics used: Accuracy, Precision, Recall, F1 Score, Confusion Matrix, ROC Curve, PR Curve.

### Phase 3: Web Integration
- Built a minimal frontend using **Angular** with a form-based UI to take user input
- The backend in **Node.js** receives the input and executes the trained **Python model**
- Model predicts churn likelihood and returns the result to the user via the UI

---

## Key Features
- Clean data pipeline with strong preprocessing steps
- Multiple ML models evaluated and tuned
- Real-time user interface to interact with the trained model
- Modular architecture: Data → Model → Prediction → Frontend Display

---

## 📸 Screenshots / Demo

> Screenshots of the predictions, and model visualizations can be provided upon request.
![IMG-20231209-WA0002](https://github.com/user-attachments/assets/e647b832-e0cf-4de1-9ed5-b20f0f6f2747)


---

## Access Policy

The repository is private for academic integrity reasons.  
For demonstration or verification purposes, feel free to contact me at:

📧 **manishma@buffalo.edu**

---

## 📚 References

- Dataset: [BankChurners.csv](https://github.com/susanli2016/Machine-Learning-with-Python/blob/master/data/BankChurners.csv)
- Scikit-learn, Pandas, NumPy, Seaborn documentation
- CSE 587 Lecture Notes
