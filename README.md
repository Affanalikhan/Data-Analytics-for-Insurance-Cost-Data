<div align="center">

# 📊 Data Analytics for Insurance Cost Data

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org)

> Exploratory data analysis and predictive modeling to uncover the key drivers of insurance costs.

</div>

---

## 🎯 Overview

This project performs a full data analytics pipeline on insurance cost data — from raw exploration to predictive modeling. The goal is to understand what factors (age, BMI, smoking status, region, etc.) most significantly influence insurance charges, and build models to predict costs accurately.

---

## 📁 Dataset Features

| Feature | Type | Description |
|---|---|---|
| `age` | Numeric | Age of the primary beneficiary |
| `sex` | Categorical | Gender (male/female) |
| `bmi` | Numeric | Body mass index |
| `children` | Numeric | Number of dependents covered |
| `smoker` | Categorical | Smoking status (yes/no) |
| `region` | Categorical | Residential region in the US |
| `charges` | Numeric | Individual medical costs billed (target) |

---

## 🔍 Analysis Breakdown

### 1. Exploratory Data Analysis (EDA)
- Distribution analysis of all features
- Correlation heatmaps
- Outlier detection and handling
- Pairplot visualizations

### 2. Feature Engineering
- Encoding categorical variables
- Normalization and scaling
- Feature importance ranking

### 3. Predictive Modeling
- Linear Regression baseline
- Decision Tree Regressor
- Random Forest Regressor
- Model evaluation with RMSE, MAE, R²

### 4. Key Insights
- Smoking status is the single strongest predictor of insurance charges
- BMI combined with smoking creates a compounding cost effect
- Age has a strong positive correlation with charges
- Region has minimal impact on cost variation

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/Affanalikhan/Data-Analytics-for-Insurance-Cost-Data.git
cd Data-Analytics-for-Insurance-Cost-Data

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

# Launch Jupyter
jupyter notebook
```

---

## 🛠️ Tech Stack

- **Python 3.x** — Core language
- **Pandas & NumPy** — Data manipulation
- **Matplotlib & Seaborn** — Visualization
- **Scikit-learn** — Machine learning models
- **Jupyter Notebook** — Interactive analysis environment

---

## 📄 License

MIT License — feel free to use and build on this.

---

<div align="center">
  Made with ❤️ by <a href="https://github.com/Affanalikhan">Affan Ali Khan</a>
</div>
