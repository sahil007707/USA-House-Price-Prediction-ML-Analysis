# USA House Price Index & Macroeconomic Prediction 🏠📉

A data science project aimed at analyzing and predicting the **USA House Price Index** using macroeconomic indicators. This project involves data cleaning, exploratory analysis, PCA, clustering, and predictive modeling using machine learning.

---

## 📊 Project Overview

This notebook performs an end-to-end analysis and prediction of the **Median Listing Price per Square Feet** in the US housing market. It combines multiple data sources, performs extensive feature engineering, applies clustering techniques, and leverages ML models to forecast house price trends.

---

## 📁 Sections Breakdown

### 1. 📚 Importing Libraries
Essential packages like `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`, and more are loaded.

### 2. 🧾 Data Info
Description and structure of datasets:
- House pricing data
- Macroeconomic indicators
- Combined dataframe for analysis

### 3. 🧹 Data Cleaning & Preprocessing
- Missing value treatment
- Feature engineering
- Normalization and transformation

### 4. 📈 Correlation Analysis
Heatmaps to identify strong relationships between features and target variables.

### 5. 📉 Dimensionality Reduction
**PCA** used to reduce feature space while maintaining variance.

### 6. 🎯 Clustering
**KMeans Clustering** applied on PCA components to find similar economic regions.

### 7. 🕒 Time Series Trends
Visual analysis of feature and target trends over time.

### 8. 🤖 Machine Learning
Regression models to predict housing prices:
- Model training and evaluation
- Feature importance analysis
- Metrics: MAE, RMSE, R²

---

## 📌 Features Used

Macroeconomic indicators like:
- Unemployment Rate
- Consumer Sentiment Index
- GDP Growth Rate
- 10-Year Treasury Rate
- Others aggregated from FRED

---

## 📦 Tech Stack

- **Python** (Jupyter Notebook)
- **Pandas**, **NumPy**
- **Scikit-learn**
- **Matplotlib**, **Seaborn**
- **Plotly**
- **KMeans**, **PCA**

---

## 📈 Results

- Achieved accurate predictions for housing prices using economic indicators.
- Identified key drivers using feature importance.
- Showed clusters of regions with similar economic behaviors.

---

