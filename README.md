# House-Price-Prediction
# 🏠 Task 6: House Price Prediction (Regression)

## 📌 Objective
Build a machine learning regression model that predicts the **price of a house** based on its features such as area, number of bedrooms, bathrooms, floors, year built, location, condition, and garage availability.

---

## 📂 Dataset Details
- **File:** House Price Prediction Dataset.csv
- **Columns Used:**
  - `Area`
  - `Bedrooms`
  - `Bathrooms`
  - `Floors`
  - `YearBuilt`
  - `Location` (Categorical)
  - `Condition` (Categorical)
  - `Garage` (Yes/No)
  - `Price` (Target)

---

## ⚙️ Tools & Libraries
- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn (`LinearRegression`, `GradientBoostingRegressor`, `StandardScaler`)

---

## 🧹 Preprocessing Steps
- Removed missing values
- Converted `Garage` column from 'Yes'/'No' to `1`/`0`
- Applied one-hot encoding to `Location` and `Condition` categorical columns
- Standardized features using `StandardScaler`

---

## 🤖 Models Used
1. **Linear Regression**
2. **Gradient Boosting Regressor**

---

## 📈 Evaluation Metrics
- **MAE** (Mean Absolute Error)
- **RMSE** (Root Mean Squared Error)
- **Actual vs Predicted** price scatter plot

---

## 📊 Example Results
