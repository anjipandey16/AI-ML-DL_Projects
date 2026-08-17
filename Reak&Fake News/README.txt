# Real & Fake News Detection Classifier

This repository contains a Machine Learning pipeline to detect and classify news articles as either **Real** or **Fake** using Natural Language Processing (NLP) techniques and ensemble models.

## 📌 Project Overview
With the widespread dissemination of news online, identifying reliable content is critical. This project extracts textual features from news titles using TF-IDF vectorization and compares multiple classification models to accurately flag fake news articles.

## 🛠️ Tech Stack & Dependencies
* **Language:** Python 3.x
* **Data Processing & Analysis:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (`TfidfVectorizer`, `DecisionTreeClassifier`, `RandomForestClassifier`)
* **Visualization:** Matplotlib, Seaborn

## 📊 Dataset Structure
The dataset consists of thousands of news records combined from two source files:
* `True.csv`: Contains verified authentic news articles (`label: 0`).
* `Fake.csv`: Contains flagged fake news articles (`label: 1`).

**Features extracted for training:**
* `title`: Article title/headline used as the primary text feature.
* `label`: Binary target classification (`0` = Real, `1` = Fake).

## ⚡ Pipeline & Implementation
1. **Data Preprocessing & Merging:** Concatenated real and fake datasets and analyzed label distribution.
2. **Train-Test Split:** Partitioned data using a **70/30 ratio** (`train_test_split`).
3. **Feature Extraction:** Transformed text headlines into numeric feature vectors using **TF-IDF Vectorization** (`stop_words='english'`, `max_features=500`).
4. **Model Training & Evaluation:** Trained baseline Decision Tree and Random Forest classifiers.

## 📈 Model Performance & Results

The models were evaluated using Accuracy, Precision, Recall, and F1-Score on the test dataset:

| Model | Accuracy | Precision | Recall | F1-Score |
| :--- | :---: | :---: | :---: | :---: |
| **Decision Tree** (`max_depth=5`) | 73.19% | 98.93% | 49.00% | 65.54% |
| **Random Forest** (`n_estimators=100`) | **90.15%** | **91.24%** | **89.67%** | **90.45%** |

* **Key Takeaway:** The **Random Forest Classifier** significantly outperformed the Decision Tree, providing a balanced F1-score of **90.45%** across all classes.

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone [https://github.com/anjipandey16/AI-ML-DL_Projects.git](https://github.com/anjipandey16/AI-ML-DL_Projects.git)
   cd "AI-ML-DL_Projects/Reak&Fake News"
