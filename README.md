# 📈 Profit Prediction Model

This project builds a predictive model to estimate **profit** based on various business attributes using multiple regression techniques. It is a classic example of a **supervised machine learning regression problem**.

---

## 🚀 Overview

I began with a raw dataset containing financial transaction data. After cleaning and transforming the data, we explored various regression models to find the one best suited for profit prediction.

---

## 🛠️ Workflow

1. **Data Cleaning**  
   - Removed missing and inconsistent entries  
   - Renamed columns (e.g., `Discount Band` → `discount_band`)  
   - Encoded categorical variables using one-hot encoding

2. **Initial Modeling**  
   - Tried **Linear Regression** as a baseline  
   - Applied **Random Forest Regressor** which yielded better results with higher accuracy and lower error

3. **Model Evaluation**  
   - Metrics used: Mean Squared Error (MSE), R² Score  
   - Plotted Residuals, Error Distributions, and Feature Importance

4. **Advanced Comparison with PyCaret**  
   - Leveraged PyCaret to:
     - Compare all available regression models
     - Automatically identify the top 3 performing models
     - Visualize model behavior and performance
   - Found that models like **LightGBM** and **ExtraTreesRegressor** performed exceptionally well

---

## 🧠 Machine Learning Type

This is a **supervised learning** project focused on **regression**, as the target variable `profit` is a continuous value.

---

## 📊 Tools & Technologies

- Python (pandas, scikit-learn, matplotlib, seaborn)
- Jupyter Notebook
- PyCaret
- Git & GitHub

---

## 🔮 Outcome

- Identified the most accurate regression model for predicting profit
- Built a reusable pipeline that can take business input and return profit estimates
- Visualized model insights (feature importance, error residuals)


