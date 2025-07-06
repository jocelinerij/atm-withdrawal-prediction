# Predictive Modeling of ATM Withdrawals Using Regularized Regression

This project investigates how urban environmental features influence ATM cash withdrawal behavior. Using a dataset of over 22,000 observations, we performed extensive analysis and built predictive models to estimate withdrawal amounts based on area characteristics such as number of shops, ATMs, proximity to downtown, and day of the week.

We explored multiple modeling techniques, including:
- **Ordinary Least Squares (OLS)**
- **Lasso Regression (L1 regularization)**
- **Ridge Regression (L2 regularization)**
- **Elastic Net Regression (combination of L1 and L2)**

After rigorous cross-validation and performance comparison, **Ridge Regression** was selected as the final model due to its strong generalization capability and ability to manage multicollinearity.

---

## Repository Contents

- `Group_14_implementation.ipynb` — Complete Jupyter Notebook containing:
  - Data preprocessing
  - Exploratory Data Analysis (EDA)
  - Model building and evaluation
- `Group_14_document.pdf` — Formal project report detailing the methodology, analysis, and discussion of findings

---

## Tools & Libraries Used

- Python 3.8+
- `pandas`, `numpy` — data manipulation
- `matplotlib`, `seaborn` — visualization
- `scikit-learn` — machine learning models and cross-validation
