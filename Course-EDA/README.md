# 🏠 Ames Housing Data Analysis & EDA Project

This project is part of the **IBM Machine Learning Professional Certificate** on Coursera. It focuses on performing a full **Exploratory Data Analysis (EDA)** and hypothesis testing on the **Ames Housing dataset** to prepare it for machine learning tasks.

---

## 📌 Project Overview

In this project, I applied data science and analytical skills to explore the Ames Housing dataset, clean it, generate new features, perform hypothesis testing, and summarize key insights. The goal was to understand the data deeply and prepare it for predictive modeling.

---

## 📂 Steps Completed

### 1️⃣ Dataset Summary
- Loaded the Ames Housing dataset containing **80+ features** and over **1400 rows**
- Identified `SalePrice` as the target variable
- Categorized features into **numerical**, **categorical**, and **binary**

### 2️⃣ Data Exploration Plan
Outlined a structured EDA approach:
- Analyze the target variable
- Examine feature distributions
- Investigate correlations with `SalePrice`
- Detect outliers and missing values
- Engineer new features

### 3️⃣ Exploratory Data Analysis (EDA)
- Visualized distributions of `SalePrice` (raw and log-transformed)
- Plotted relationships between `SalePrice` and key predictors
- Explored categorical variables using boxplots
- Created a heatmap of correlations
- Identified strong predictors: `OverallQual`, `GrLivArea`, `GarageCars`, `TotalSF`

### 4️⃣ Data Cleaning & Feature Engineering
- Handled missing values using median/mode imputation
- Converted boolean columns to binary integers (0/1)
- Converted the categorical values to numerical values
- Binary flags: `HasGarage`, `HasBasement`

### 5️⃣ Key Insights
- High quality (`OverallQual`) and larger homes (`GrLivArea`, `TotalSF`) command higher prices
- Outliers (very large homes with low prices) were identified and removed
- Neighborhood and garage presence affect price

### 6️⃣ Hypothesis Formulation
Formulated 3 testable hypotheses, including:
- "Higher overall quality leads to higher sale price"
- "Presence of a garage increases price"
- "Neighborhood affects average price"

### 7️⃣ Hypothesis Testing
- Used **Kruskal-Wallis Test** to confirm `OverallQual` significantly affects `SalePrice` (p < 0.001)
- Log-transformed target variable to meet normality assumptions

### 8️⃣ Conclusion & Next Steps
- The dataset is ready for regression modeling
- Next steps: train models (Linear Regression, Random Forest, XGBoost), evaluate with cross-validation, interpret with SHAP

---

## 📊 Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib & Seaborn
- SciPy (for hypothesis testing)
- Jupyter Notebook

---

## 🛠️ How to Run

1. Clone the repository or download the `.ipynb` file
2. Open the notebook using Jupyter Lab / Jupyter Notebook
3. Run cells sequentially

---

## 💡 Key Takeaway

> A clean, well-explored dataset is the foundation of good machine learning.  
> EDA not only improves accuracy but also ensures model decisions are understandable and fair.

---

