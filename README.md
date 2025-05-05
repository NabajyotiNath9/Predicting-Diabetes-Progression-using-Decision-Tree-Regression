# Predicting Diabetes Progression using Decision Tree Regression

This project demonstrates how to use a Decision Tree Regressor to predict diabetes disease progression using the diabetes dataset provided by `sklearn.datasets`. The model is fine-tuned using GridSearchCV for optimal performance.

## 📊 Dataset

The dataset used is the **Diabetes dataset** from `sklearn.datasets`, which contains:
- 10 baseline variables (age, sex, BMI, average blood pressure, and six blood serum measurements)
- A quantitative measure of disease progression one year after baseline

## 🔍 Objective

To predict disease progression scores using a regression model and evaluate its performance using various metrics:
- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

## 🛠️ Methods Used

- **DecisionTreeRegressor** from `sklearn.tree
- **GridSearchCV** for hyperparameter tuning
- Evaluation metrics from `sklearn.metrics
