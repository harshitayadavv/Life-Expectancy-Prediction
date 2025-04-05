# 🌍 Life Expectancy Prediction using Machine Learning

This project aims to predict the **life expectancy** of a country based on various socio-economic and health-related factors. By analyzing real-world data, the goal is to understand which features impact life expectancy and how well we can model this relationship using regression techniques.

---

## 📌 Objective

To build a regression model that can accurately predict the **Life Expectancy** of a population using historical data that includes health indicators, economic metrics, and demographic statistics.

---

## 🧾 Dataset Overview

The dataset used in this project is sourced from the Global Health Observatory (GHO) data repository by the World Health Organization (WHO), originally obtained from Kaggle. It contains country-level data with the following key attributes:

- **Demographics**: `Year`, `Population`, `Schooling`, `GDP`
- **Health Indicators**: `Adult Mortality`, `infant deaths`, `BMI`, `HIV/AIDS`, `Hepatitis B`, `Polio`, `Measles`, etc.
- **Healthcare Metrics**: `Total expenditure`, `percentage expenditure`, `Diphtheria`, etc.
- **Nutrition & Lifestyle**: `Alcohol`, `thinness 1-19 years`, `thinness 5-9 years`, etc.

---

## ⚙️ Tools & Libraries Used

- **Python**
- **Pandas, NumPy** – Data processing and handling
- **Matplotlib, Seaborn** – Visualization
- **Scikit-learn** – ML modeling and evaluation

---

## 🤖 Machine Learning Models Applied

To find the best performing model for life expectancy prediction, the following regressors were trained and compared:

- Linear Regression  
- Polynomial Regression  
- Support Vector Regression (SVR)  
- Decision Tree Regression  
- **Random Forest Regression**

After comparing R² scores across all models, **Random Forest** was used for final prediction due to its **highest R² value**, indicating better generalization and accuracy.

---

## ✅ Model Evaluation

| Model                   | R² Score |
|------------------------|----------|
| Linear Regression       | ~0.84    |
| Polynomial Regression   | ~0.89    |
| SVR                     | ~0.87    |
| Decision Tree           | ~0.92    |
| **Random Forest**       | **~0.96** |

