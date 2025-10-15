# Driver Churn Prediction for Ola

## Overview  
This project focuses on building a **machine learning classification model** to identify potential **driver churn** in Ola — a leading ridesharing platform. By analyzing driver behavioral patterns, activity metrics, and engagement trends, the project aims to provide **data-driven insights** and **actionable retention strategies** to reduce churn and improve operational efficiency.

---

## Objectives  
- **Predict** whether a driver is likely to churn using historical behavioral data.  
- **Analyze** key factors influencing driver churn.  
- **Recommend** data-backed strategies for improving driver retention.  

---

## Dataset  
The dataset (synthetic) includes key driver-related attributes such as:  
- Earnings and incentives  
- Ratings and feedback  
- Demographic and operational features (gender, location, tenure, etc.)  

---

## Approach  

1. **Data Preprocessing**  
   - Handled missing values and outliers.  
   - Normalized numerical features and encoded categorical variables.  
   - Created derived features (e.g., average earnings per trip, idle time ratio).  

2. **Exploratory Data Analysis (EDA)**  
   - Identified behavioral patterns distinguishing churned vs. retained drivers.  
   - Examined correlations between engagement metrics and churn.  
   - Visualized feature distributions and churn trends over time.  

3. **Model Development**  
   - Implemented multiple classification models:  
     - Bagging Classifier  
     - Random Forest  
     - Gradient Boosting Classifier
     - XGBoost
     - LightGBM
   - Performed hyperparameter tuning via cross-validation.  
   - Evaluated models on **precision**, **recall**, **F1-score**, and **ROC-AUC**.  

4. **Model Interpretation**  
   - Used **feature importance** analysis to understand key churn drivers.  
   - Derived actionable insights from interpretable model outputs.  

