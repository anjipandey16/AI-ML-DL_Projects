# Customer Segmentation using K-Means Clustering

A Machine Learning project using Unsupervised Learning techniques to segment customers based on purchasing behavior and demographic attributes.

## 📌 Project Overview
Customer segmentation is critical for targeted marketing and personalized user experiences. This project applies the K-Means clustering algorithm to group customers into distinct clusters based on features such as annual income and spending score.

## 🛠️ Tech Stack & Dependencies
* **Language:** Python 3.x
* **Data Processing & Analysis:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (`KMeans`)
* **Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

## ⚡ Pipeline & Implementation
1. **Data Preprocessing & EDA:** Loaded and inspected customer demographics, checking for missing values and distribution patterns.
2. **Feature Selection:** Extracted key attributes (e.g., Annual Income and Spending Score) for clustering analysis.
3. **Optimal Cluster Selection:** Implemented the **Elbow Method** (WCSS - Within-Cluster Sum of Squares) to identify the optimal number of clusters ($K$).
4. **Model Training:** Trained the K-Means algorithm using the selected $K$ value to partition dataset records.
5. **Cluster Visualization:** Generated 2D scatter plots using Matplotlib and Seaborn to visualize cluster boundaries and centroids.

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone [https://github.com/anjipandey16/AI-ML-DL_Projects.git](https://github.com/anjipandey16/AI-ML-DL_Projects.git)
   cd "AI-ML-DL_Projects/Customer Segmentation"
