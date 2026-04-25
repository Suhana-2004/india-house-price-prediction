# india-house-price-prediction
Predicting house prices in India using EDA and ML model comparison (Linear Regression, Decision Tree, Random Forest)


## Overview
Analyzing factors affecting house prices in India and comparing 
multiple ML models to find the best predictor.  
Dataset: Indian Real Estate Listings (187,531 rows)

## Key Findings
- Dataset had extreme outliers — max price 6.7M vs median 6,300
- Outlier removal using IQR significantly improved model performance
- Random Forest outperformed all other models with 88% accuracy

## Workflow
1. Data Loading & Understanding
2. Data Cleaning (missing values, encoding, feature extraction)
3. Exploratory Data Analysis (EDA)
4. Outlier Removal using IQR
5. Feature Scaling using MinMaxScaler
6. Model Building & Comparison
7. Prediction

## Results
| Model | R2 Score |
|-------|----------|
| Linear Regression | 0.19 |
| Decision Tree | 0.80 |
| Random Forest | 0.88 |

**Best Model: Random Forest with 88% R2 Score**

## Tools & Libraries
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## Kaggle Notebook
[View on Kaggle](https://www.kaggle.com/code/suhanaabdulla/house-price)
