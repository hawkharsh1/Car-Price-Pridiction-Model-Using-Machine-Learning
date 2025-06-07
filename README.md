# 🚗 Car Price Prediction using Machine Learning

This project utilizes machine learning techniques to predict the prices of used cars based on various features. By employing a Random Forest Regressor from scikit-learn, the model aims to provide accurate price estimations, assisting buyers, sellers, and dealerships in making informed decisions.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Use Cases](#use-cases)
- [Dataset](#dataset)
- [Features](#features)
- [Modeling Approach](#modeling-approach)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

---

## 📖 Overview

The goal of this project is to develop a predictive model that estimates the selling price of used cars based on their attributes. Leveraging the ensemble learning capabilities of Random Forest, the model captures complex relationships between features to deliver robust predictions.

---

## 💼 Use Cases

- **Dealerships**: Determine competitive pricing for inventory.
- **Buyers**: Assess fair market value before purchasing.
- **Sellers**: Set appropriate selling prices based on car features.
- **Market Analysts**: Analyze pricing trends in the used car market.

---

## 📊 Dataset

- **Source**: [Kaggle - Vehicle Dataset from CarDekho](https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho)
- **Attributes**:
  - Year
  - Present_Price
  - Kms_Driven
  - Fuel_Type
  - Seller_Type
  - Transmission
  - Owner
  - Selling_Price (Target Variable)

---

## ⚙️ Features

- **Data Preprocessing**: Handling missing values, encoding categorical variables, and feature scaling.
- **Model Training**: Implementing Random Forest Regressor with hyperparameter tuning.
- **Evaluation Metrics**: Utilizing R² Score, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).
- **Visualization**: Plotting feature importances and prediction results.

---

## 🧠 Modeling Approach

1. **Data Cleaning**: Address missing or inconsistent data entries.
2. **Feature Engineering**: Create new features or transform existing ones to enhance model performance.
3. **Model Selection**: Choose Random Forest Regressor due to its ability to handle non-linear relationships and reduce overfitting.
4. **Hyperparameter Tuning**: Optimize parameters like the number of estimators, maximum depth, and minimum samples split using GridSearchCV.
5. **Model Evaluation**: Assess the model's performance on the test set using appropriate metrics.

---
