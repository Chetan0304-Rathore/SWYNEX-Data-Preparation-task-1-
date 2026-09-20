# SWYNEX-Data-Preparation: Insurance Cost Prediction

## 📌 Project Overview
This project focuses on data-science preparation, cleaning, exploratory data analysis (EDA), and feature engineering on a medical insurance dataset (`insurance.csv`). The goal is to prepare the data and train a baseline Linear Regression model to predict individual medical costs.

## 🛠️ Steps Performed
1. **Data Cleaning:** Checked for missing values, inspected data types, and removed duplicate rows.
2. **Handling Categorical Variables:** 
   - Mapped binary columns (`sex`, `smoker`) into numeric values (`0` and `1`).
   - One-hot encoded the `region` column.
3. **Feature Engineering:**
   - **`smoker_high_bmi`**: Created an interaction feature for high-risk smokers with a BMI > 30.
   - **`has_children`**: Added a binary flag indicating if a policyholder has dependents.
   - **`is_senior`**: Created an age category flag for seniors above 50.
4. **Data Scaling:** Standardized numerical variables (`age`, `bmi`, `children`) using `StandardScaler`.
5. **Model Training & Evaluation:** Split the dataset (80-20 train-test split) and trained a Linear Regression model, evaluating performance using R-squared and RMSE.

## 🚀 Files Included
- `insurance.csv` (Dataset used)
- `anaconda with Jupyter Notebook ` (Main script/notebook)
