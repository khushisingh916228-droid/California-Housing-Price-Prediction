# 🏠 California Housing Price Prediction

## 📋 Project Overview
This project builds and evaluates a **Linear Regression** model to predict median house values in California using the California Housing dataset. Completed as part of the **Artificial Intelligence & Machine Learning Internship** at **Maincrafts Technology**.

## 🎯 Objective
To introduce the complete ML workflow — data loading, exploration, preprocessing, model training, evaluation, and reporting — using a reproducible, portfolio-ready project.

## 🛠️ Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab

## 📊 Dataset
California Housing dataset (built into scikit-learn) — contains housing data across California districts including median income, house age, average rooms, population, and median house value (target).

## 🔍 Key Steps
1. **Data Loading** — Loaded dataset using `fetch_california_housing()`
2. **Exploratory Data Analysis** — Checked distributions, missing values, and correlations via heatmap
3. **Train/Test Split** — 80/20 split for reliable model evaluation
4. **Model Training** — Trained a `LinearRegression` model from scikit-learn
5. **Evaluation** — Assessed performance using MAE, RMSE, and R² Score
6. **Visualization** — Plotted Actual vs Predicted values and residuals

## 📈 Model Performance
| Metric | Value |
|---|---|
| MAE | [apna value daalo] |
| RMSE | [apna value daalo] |
| R² Score | [apna value daalo] |

## 💡 Key Insight
Median Income (`MedInc`) showed the strongest correlation with house prices, making it the most influential predictor in the model.

## 📁 Files
- `task1_ml_linear_regression.ipynb` — Full Jupyter Notebook with code, EDA, model training, and evaluation

## 🚀 How to Run
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/khushisingh916228-droid/California-Housing-Price-Prediction/blob/main/task1_ml_linear_regression.ipynb)

1. Click the badge above
2. Run all cells (`Runtime → Run all`)
3. Dataset loads automatically via scikit-learn — no manual download needed

## ✅ Skills Demonstrated
- Machine Learning Workflow (Data → Model → Evaluation)
- Exploratory Data Analysis (EDA)
- Train/Test Splitting
- Linear Regression Modeling
- Model Evaluation Metrics (MAE, RMSE, R²)
- Data Visualization
