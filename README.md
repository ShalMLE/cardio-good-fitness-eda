# 🏋️ Cardio Good Fitness - Exploratory Data Analysis

## 🔍 Overview

This project focuses on performing Exploratory Data Analysis (EDA) on the **Cardio Good Fitness** dataset. The dataset contains information about fitness club customers and their purchasing behavior. The goal is to derive insights that can help the company understand its customers better and optimize marketing and sales strategies.

---

## 🧾 Dataset

- **Source**: [Kaggle Dataset – Cardio Good Fitness](https://www.kaggle.com/datasets)
- **Rows**: 180
- **Columns**: 9
- **Features**:
  - `Product`: Type of fitness product purchased (TM195, TM498, TM798)
  - `Age`: Age of the customer
  - `Gender`: Male/Female
  - `Education`: Education level
  - `MaritalStatus`: Single/Married
  - `Usage`: Average number of times the customer uses the product each week
  - `Fitness`: Self-rated fitness level (1–5)
  - `Income`: Household income
  - `Miles`: Average miles the customer runs in a week

---

## 🧪 Goals of the Analysis

1. Understand customer demographics and usage behavior.
2. Analyze purchasing trends across different product types.
3. Identify patterns or correlations between variables like age, income, fitness, and product choice.
4. Segment the market based on product usage and fitness levels.

---

## 📈 Summary of Findings

| Insight | Summary |
|--------|---------|
| 👨‍👩‍👧‍👦 Demographics | TM195 is mostly purchased by younger customers, while TM798 is preferred by older and higher-income individuals. |
| 💰 Income Trends | TM798 buyers have the highest average income, suggesting it is a premium product. |
| 🧍 Gender | TM195 is slightly more popular among females, while TM798 skews toward males. |
| 🏃 Usage | High-usage customers tend to prefer TM498 and TM798. |
| 🧠 Fitness Level | Customers who rate themselves higher in fitness tend to choose TM798 more often. |

---

## 📊 Visualizations

- Distribution of income by product type
- Age and income comparisons across products
- Fitness level vs usage frequency
- Product preference by gender and marital status
- Correlation heatmap of all numerical variables

---

## 🧰 Tools Used

- Python 3.x
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `missingno` (for missing value check)
- `plotly` (for interactive plots – optional)

---

## 📓 View the Notebook
[👉 Click here to view the notebook](./Cardio_Good_Fitness.ipynb)
