# ❤️ Heart Attack Risk Prediction (Logistic Regression)

A data science project aiming to estimate a patient's risk of heart attack using clinical, demographic, and lifestyle data. The project implements a **Logistic Regression** model optimized with **L2 regularization** and **SMOTE** for class balancing.

## 📖 Project Overview
This project analyzes health care data to identify high-risk patients early. We structured the workflow into clear phases: Exploratory Data Analysis (EDA), Preprocessing, Model Training, and Evaluation. The final model provides a data-driven risk score to assist clinicians in prioritizing resources.

---

## ✨ Key Results & Insights

### 📊 Performance Metrics
* **Accuracy:** 87%
* **AUC-ROC:** 0.89
* **F1-Score:** 0.82
* **Recall:** 80% (Crucial for reducing false negatives in medical diagnosis)

### 🔍 Top Risk Drivers
Based on the model's feature coefficients, the strongest predictors for heart attack risk are:
1.  **Age** (+0.52)
2.  **Cholesterol** (+0.47)
3.  **Previous Heart Problems** (+0.43)

---

## 🛠️ Technical Stack

* **Language:** Python
* **Libraries:** Scikit-learn, Pandas, NumPy, Matplotlib/Seaborn
* **Model:** Logistic Regression (GridSearch tuned)
* **Techniques:** One-Hot Encoding, StandardScaler, SMOTE (Synthetic Minority Over-sampling Technique)

---

## ⚠️ Collaboration Note

This project was developed for the **AI Applications** course (SS25) at the University of Europe for Applied Sciences.

**Team Roles:**
* **Eslam Aly:** Coding & Implementation (Original Repository Owner)
* **Josué Pavon (Me):** Lead Technical Documentation & Data Analysis Reporting
* **Roza Antonevici:** Presentation & Defense

* **Original Group Repository:** [https://github.com/Eslam-Aly/heart_attack_prediction.git]
