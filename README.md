🏡 House Price Prediction using Linear Regression
This project implements a simple Linear Regression Model to predict house prices based on basic housing features using the Kaggle House Prices Dataset.

🎯 Objective
To predict Sale Price of houses using:

🏠 GrLivArea (Above Ground Living Area)

🛏 BedroomAbvGr (Number of Bedrooms)

🛁 FullBath (Number of Full Bathrooms)

🗂 Dataset
Dataset Source: Kaggle: House Prices - Advanced Regression Techniques

File Used: train.csv extracted from house-prices-advanced-regression-techniques.zip

🛠 Tools & Libraries Used
Python

Pandas

NumPy

Matplotlib

scikit-learn

✅ Workflow
Data Cleaning

Dropped rows with missing values in selected features.

Feature Selection

Selected GrLivArea, BedroomAbvGr, FullBath as input features.

Model Building

Applied Linear Regression using scikit-learn.

Model Evaluation

Evaluated using Mean Squared Error (MSE) and R² Score.

Visualization

Plotted:

Actual vs Predicted Sale Price

Feature vs Predicted Sale Price graphs

📊 Results
Metric	Value
Mean Squared Error (MSE)	 2806426667.25
R² Score	0.6341

✅ Good model performance for basic linear regression on limited features.

🖼️ Output Visualizations
Actual vs Predicted Sale Prices

GrLivArea vs Predicted SalePrice

BedroomAbvGr vs Predicted SalePrice

FullBath vs Predicted SalePrice
---


