# 🏘️ ML Project: Property Price Prediction

This repository contains a machine learning project aimed at predicting **property prices** based on various real estate features. The goal is to understand the impact of different variables on price and build a regression model to accurately forecast property prices.

---

## 🎯 Objective

To develop and evaluate a **predictive model** that estimates the price of a property using relevant numerical and categorical attributes.

---

## 📁 Files Included

- `Property_Price_Prediction.ipynb`: Jupyter Notebook containing the full implementation from data loading to model evaluation.
- `property_data.csv`: Dataset used for training and testing the model .
- `README.md`: Project description and overview.

---

## 🧪 Steps Performed

### 1. **Data Understanding**
- Loaded property dataset with features like:
  - Area
  - Bedrooms
  - Location
  - Bathrooms
  - Furnishing Status
  - Parking
  - Price (Target)

### 2. **Exploratory Data Analysis (EDA)**
- Checked for missing values and data types.
- Visualized relationships using:
  - Pair plots
  - Correlation heatmaps
  - Boxplots

### 3. **Data Preprocessing**
- Handled missing data if present.
- Applied **Label Encoding** to categorical columns (e.g., Location, Furnishing).
- Converted data into numerical format for modeling.

### 4. **Model Building**
- Used **Linear Regression** as the base model.
- Performed Train-Test Split (`80-20` split).
- Trained the model using `scikit-learn`.

### 5. **Model Evaluation**
- Calculated metrics:
  - R² Score
  - Adjusted R²
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - Mean Absolute Percentage Error (MAPE)
- Checked model predictions against actual values.

---

## 🛠️ Technologies Used

```python
pandas, numpy, seaborn, matplotlib, sklearn
