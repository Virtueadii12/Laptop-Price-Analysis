# Laptop-Price-Analysis
# 💻 Laptop Price Analysis

This project analyzes a dataset of various laptop specifications and their prices to uncover patterns, identify key features influencing pricing, and build a predictive model. It involves cleaning messy data, visualizing trends, and applying machine learning techniques for price prediction.

---

## 🎯 Objective

- Understand the relationship between laptop specifications and pricing.
- Visualize how features like RAM, processor, brand, etc. affect cost.
- Build a regression model to predict laptop prices.

---

## 📂 Dataset Overview

The dataset contains features like:

- Brand  
- Processor Type  
- RAM Size  
- Storage (HDD/SSD)  
- Operating System  
- GPU  
- Display Size  
- Weight  
- Price (Target variable)

> Data Source: [Kaggle or CSV provided]

---

## 🛠️ Tools & Libraries

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook

---

## 🔁 Workflow

1. **Data Cleaning**
   - Removed duplicates
   - Handled missing values
   - Converted units (e.g., weight to float, storage sizes to GB)

2. **EDA (Exploratory Data Analysis)**
   - Correlation heatmaps
   - Brand vs price comparison
   - RAM/Storage vs price distribution

3. **Feature Engineering**
   - Label Encoding for categorical variables
   - Combining SSD + HDD into total storage

4. **Model Building**
   - Applied Linear Regression, Random Forest Regressor
   - Compared model performances (R² score, RMSE)

---

## 📊 Key Insights

- Brands like Apple and Dell have higher average prices.
- More RAM and SSD storage directly increase price.
- GPU and Processor type are strong predictors of cost.

---



