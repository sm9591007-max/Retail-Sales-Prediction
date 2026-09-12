# 🛒 Retail Sales Prediction & Inventory Analytics

An end-to-end **Machine Learning & Data Analytics** project that forecasts daily retail sales for **1,115 Rossmann stores** across Germany. The system uses historical sales, promotions, holidays, competition, and seasonal patterns to predict sales **up to 6 weeks in advance**, helping businesses optimize inventory and budget planning.

---

## Business Problem

Rossmann operates more than **3,000 drug stores** in 7 European countries. Accurate sales forecasting is essential for inventory management, staffing, promotions, and budgeting. Manual forecasting often leads to inconsistent results, making machine learning a more reliable solution.

**Objective:** Predict daily sales for each store with high accuracy using historical retail data.

---

## Dataset

**Source:** Kaggle — Rossmann Store Sales

### Files

| File             | Description                    |
| ---------------- | ------------------------------ |
| `train.csv`      | Historical daily sales data    |
| `store.csv`      | Store information and metadata |
| `test.csv`       | Future dates for prediction    |
| `submission.csv` | Final predicted sales          |

**Dataset Summary**

* **1,115 Stores**
* Daily sales records
* Promotions & holidays
* Competition information
* Seasonal and calendar features

---

## Tech Stack

| Category         | Technology                              |
| ---------------- | --------------------------------------- |
| Language         | Python                                  |
| Data Analysis    | Pandas, NumPy                           |
| Visualization    | Matplotlib, Seaborn                     |
| Machine Learning | Scikit-learn                            |
| Models           | Linear Regression, Lasso, Random Forest |
| Notebook         | Jupyter                                 |

---

## Project Workflow

```text
Raw Data
    │
    ▼
Data Cleaning
    │
    ▼
Feature Engineering
    │
    ▼
Exploratory Data Analysis
    │
    ▼
Feature Selection
    │
    ▼
Model Training
    │
    ▼
Hyperparameter Tuning
    │
    ▼
Sales Forecast
```

---

## Exploratory Data Analysis

The project includes comprehensive business-oriented analysis to identify patterns affecting retail sales.

### Key Insights

* Impact of promotions on revenue
* Weekly & monthly sales trends
* Holiday sales behavior
* Competition distance analysis
* Seasonal demand patterns
* Store-wise performance comparison

---

## Feature Engineering

New features were created to improve prediction quality.

* Year, Month, Week & Day extraction
* Weekend indicator
* Holiday categories
* Promotion duration
* Competition open duration
* Seasonal variables

These engineered features significantly improved model performance.

---

## Machine Learning Models

Three regression algorithms were trained and compared.

| Model                       | Train Score | Test Score |
| --------------------------- | ----------: | ---------: |
| Linear Regression           |      0.7807 |     0.7824 |
| Lasso Regression            |      0.7807 |     0.7823 |
| **Random Forest Regressor** |  **0.9938** | **0.9564** |

**Best Model:** Random Forest Regressor

---

## Model Performance

| Metric          |         Value |
| --------------- | ------------: |
| MAPE            |     **5.65%** |
| MAE             |       **376** |
| Best Algorithm  | Random Forest |
| Forecast Window |   **6 Weeks** |

The model achieved **95.64% testing performance**, making it suitable for practical retail sales forecasting.

---

## Business Impact

This forecasting system enables retailers to:

* Reduce inventory shortages
* Optimize warehouse stock
* Improve promotion planning
* Estimate future revenue
* Support data-driven budgeting decisions

---

## Project Structure

```text
Retail-Sales-Prediction/
│
├── data/
│   ├── train.csv
│   ├── store.csv
│   ├── test.csv
│   └── submission.csv
│
├── notebooks/
│   └── retail_sales_prediction.ipynb
│
├── models/
│   └── random_forest.pkl
│
├── images/
├── README.md
└── requirements.txt
```

##

---

## Author

**Subhajit Manna**

* **LinkedIn:** https://www.linkedin.com/in/subhajit-manna-02104a336/
* **GitHub:** https://github.com/sm9591007-max
* **Email:** [sm9591007@gmail.com](mailto:sm9591007@gmail.com)
