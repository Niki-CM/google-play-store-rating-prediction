# google-play-store-rating-prediction# 📱 Google Play Store Rating Prediction

A Machine Learning project to predict **Google Play Store app ratings** using app-level features such as reviews, installs, size, price, category, and content rating.

## 🎯 Objective

Build a regression model to predict the **Rating** of Google Play Store applications and compare different regression algorithms.

## 🔄 Project Workflow

1. Data Loading & Understanding
2. Data Cleaning
3. Missing Value Handling
4. Data Type Conversion
5. Outlier Treatment
6. Exploratory Data Analysis (EDA)
7. Log Transformation
8. Feature Engineering
   - Review Rate
   - Log Price
9. Categorical Variable Encoding
10. Train-Test Split
11. Model Building
12. Model Evaluation
13. Residual Analysis
14. Model Comparison

## 🤖 Models Used

- OLS Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor

## 📊 Model Results

| Model | Test R² | Test RMSE |
|---|---:|---:|
| Baseline | ~0.000 | 0.543 |
| **OLS Regression** | **0.148** | **0.501** |
| Random Forest | 0.134 | 0.505 |
| Gradient Boosting | 0.138 | 0.504 |

### 🏆 Best Model

**OLS Linear Regression**

- Test R²: **0.148**
- Test RMSE: **0.501**

## 🛠️ Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels
- Jupyter Notebook

## 📁 Project Structure

```text
Google-Play-Store-Rating-Prediction/
│
├── Regression_google_play_store.ipynb
├── README.md
└── data/
    └── googleplaystore.csv
