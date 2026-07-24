# Housing Price Prediction using Linear Regression

## 📌 Project Overview
This project aims to build and evaluate a **Linear Regression** model to predict house prices (`price`) based on various numeric features such as property area, number of bedrooms, bathrooms, stories, and parking spaces.

## 🎯 Objectives
- Perform basic Exploratory Data Analysis (EDA) and data preprocessing.
- Select appropriate numeric feature variables.
- Train a Linear Regression model using `scikit-learn`.
- Evaluate model performance using standard regression metrics:
  - **MAE** (Mean Absolute Error)
  - **MSE** (Mean Squared Error)
  - **RMSE** (Root Mean Squared Error)
  - **R² Score** (Coefficient of Determination)

---

## 📊 Dataset Description
The dataset `Housing.csv` contains details about housing attributes:

| Column Name | Data Type | Description |
| :--- | :--- | :--- |
| **price** *(Target)* | Integer | House price |
| **area** | Integer | Total area in square feet |
| **bedrooms** | Integer | Number of bedrooms |
| **bathrooms** | Integer | Number of bathrooms |
| **stories** | Integer | Number of stories |
| **parking** | Integer | Number of parking spots |
| **mainroad**, **guestroom**, etc. | String | Categorical features |

---
