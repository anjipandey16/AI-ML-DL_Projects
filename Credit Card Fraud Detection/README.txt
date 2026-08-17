# Credit Card Fraud Detection

A Machine Learning project designed to identify fraudulent credit card transactions using classification models and anomaly detection techniques on imbalanced financial datasets.

## 📌 Project Overview
Credit card fraud detection is a critical challenge due to extreme class imbalance, where legitimate transactions vastly outnumber fraudulent ones. This project processes transactional features, addresses data imbalance, and trains machine learning models to effectively flag fraudulent activity while minimizing false positives.

## 🛠️ Tech Stack & Dependencies
* **Language:** Python 3.x
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Machine Learning & Modeling:** Scikit-Learn (Logistic Regression, Decision Trees, Random Forest)
* **Imbalanced Data Handling:** Imbalanced-learn (SMOTE / Undersampling)
* **Visualization:** Matplotlib, Seaborn

## ⚡ Pipeline & Implementation
1. **Data Preprocessing & Scaling:** Scaled transaction amounts and time features using standard scaling techniques.
2. **Handling Class Imbalance:** Applied resampling techniques (such as SMOTE or random undersampling) to balance legitimate vs. fraudulent class distributions for training.
3. **Model Selection & Training:** Built and trained binary classification algorithms including Logistic Regression, Decision Trees, and Ensemble methods.
4. **Performance Evaluation:** Evaluated model robustness using metrics critical for imbalanced data, such as Precision, Recall, F1-Score, and ROC-AUC curves.

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone [https://github.com/anjipandey16/AI-ML-DL_Projects.git](https://github.com/anjipandey16/AI-ML-DL_Projects.git)
   cd "AI-ML-DL_Projects/Credit Card Fraud Detection"
