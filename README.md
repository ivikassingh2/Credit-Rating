# 💳 Credit Card Debt Analysis – EDA & Linear Regression

This project explores credit card debt patterns using a dataset of customer financial and demographic information. It includes Exploratory Data Analysis (EDA), a linear regression model to predict average credit card debt (`Balance`), and detailed model diagnostics.

## 📦 Dataset Overview

- **Source:** [Google Drive CSV](https://drive.google.com/file/d/1Ga7Q25CTCR7EFYmdlR2JEr6m6ptcS_sk/view?usp=sharing)
- **Direct Load URL:** `https://drive.google.com/uc?id=1Ga7Q25CTCR7EFYmdlR2JEr6m6ptcS_sk`
- **Observations:** Hundreds of individual customers
- **Response Variable:** `Balance` – average credit card debt per individual

### 🔢 Features

| Feature     | Description                          |
|------------|--------------------------------------|
| `Income`   | Income in thousands of dollars       |
| `Limit`    | Credit limit                         |
| `Rating`   | Credit rating                        |
| `Cards`    | Number of credit cards               |
| `Age`      | Age of the customer                  |
| `Education`| Years of education                   |
| `Own`      | House ownership (Yes/No)             |
| `Student`  | Student status (Yes/No)              |
| `Married`  | Marital status (Yes/No)              |
| `Region`   | Region (East, West, South)           |
| `Balance`  | Average credit card debt             |

## 📊 Exploratory Data Analysis (EDA)

The EDA includes:
- Distribution plots for numeric variables
- Correlation heatmap
- Boxplots for categorical variables vs. `Balance`
- Pairplots to visualize relationships
- Outlier detection and missing value checks

## 📈 Linear Regression Modeling

We build a multiple linear regression model to predict `Balance` using quantitative predictors:
- `Income`, `Limit`, `Rating`, `Cards`, `Age`, `Education`

### 🧪 Model Diagnostics

-Pair plots
- Variance Inflation Factor (VIF) for multicollinearity
- R² and adjusted R²
- Lasso Regression for variable selection
- p-values and confidence intervals

## 🚀 Run in Google Colab

Click below to open the notebook directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/<your-username>/<your-repo>/blob/main/credit_analysis.ipynb)

> Replace `<your-username>` and `<your-repo>` with your actual GitHub details.

## 🛠️ Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `statsmodels`
- `scikit-learn`

## 📁 Project Structure

```
credit-analysis/
├── credit.ipynb
├── README.md

```

## 📌 Notes

- Dataset used for educational purposes.
- All modeling steps are reproducible and documented in the notebook.

---

Let me know if you'd like to add a license, contribution guidelines, or automate the data loading from Drive!
