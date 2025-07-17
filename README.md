# Task 1 🏠 House Price Prediction — Linear Regression

This project implements a simple **Linear Regression** model to predict house prices based on:
- Square footage (`GrLivArea`)
- Number of bedrooms (`BedroomAbvGr`)
- Number of bathrooms (`FullBath`)

---

## 🎯 Objective
To predict Sale Price of houses using:

🏠 GrLivArea (Above Ground Living Area)
🛏 BedroomAbvGr (Number of Bedrooms)
🛁 FullBath (Number of Full Bathrooms)
---

## 🚀 Tools Used
- Python (Pandas, NumPy, Matplotlib)
- Scikit-learn
- Google Colab

---

🗂 Dataset
Dataset Source: Kaggle: House Prices - Advanced Regression Techniques
File Used: train.csv extracted from house-prices-advanced-regression-techniques.zip

---
## 📈 Project Workflow
1. Data Cleaning
  Dropped rows with missing values in selected features.
2. Feature Selection
   Selected GrLivArea, BedroomAbvGr, FullBath as input features.
3. Model Training (Linear Regression)
   Applied Linear Regression using scikit-learn.
4. Model Evaluation (MSE, R²)
   Evaluated using Mean Squared Error (MSE) and R² Score.
5. Visualization of predicted vs actual prices
   Plotted:

Actual vs Predicted Sale Price

Feature vs Predicted Sale Price graphs

---

🖼️ Output Visualizations
Actual vs Predicted Sale Prices

GrLivArea vs Predicted SalePrice

BedroomAbvGr vs Predicted SalePrice

FullBath vs Predicted SalePrice

---
###📌 How to Run

pip install pandas numpy matplotlib scikit-learn
Run the notebook in Google Colab or Jupyter Notebook.


