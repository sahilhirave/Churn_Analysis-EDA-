# 📊 Customer Churn Analysis: Data-Driven Retention Insights

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-444444?style=for-the-badge&logo=python&logoColor=white)

## 📌 Project Overview
This project analyzes a dataset of **7,043 customers** to identify key factors leading to customer attrition (churn). By performing Exploratory Data Analysis (EDA), I identified specific behavioral and demographic patterns that predict whether a customer is likely to leave.

## 🛠️ Tech Stack & Skills
- **Languages:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Techniques:** Data Cleaning, Feature Engineering, Categorical Data Analysis, Data Visualization.

## 🔍 Key Insights from Analysis

### 1. The Churn Baseline
Out of the total customer base, **1,869 customers churned** (~26.5%). 
> *Add Screenshot: `images/churn_count.png`*

### 2. High-Risk Segments
- **Contract Type:** Customers on **Month-to-Month contracts** show drastically higher churn rates compared to long-term subscribers.
- **Tech Support:** There is a strong correlation between a lack of technical support and customer churn.
- **Payment Method:** Users paying via **Electronic Check** represent the highest churn group, indicating potential friction in the payment experience.

### 3. Demographics
- **Senior Citizens:** This segment is significantly more likely to churn than younger customers.
- **Gender:** Data shows that gender is **not** a primary driver of churn, with rates nearly equal between males and females.

## 📂 Workflow
1. **Data Cleaning:** Replaced empty spaces in `TotalCharges` with '0' and converted it to a float type.
2. **Feature Engineering:** Converted the `SeniorCitizen` numeric column (0/1) into readable "Yes/No" labels for better visualization.
3. **Exploratory Analysis:** Created count plots and bivariate charts to cross-reference 'Churn' against other service features.

## 🚀 How to Run
1. Clone this repository.
2. Ensure you have `pandas`, `seaborn`, and `matplotlib` installed.
3. Open `Churn_Analysis.ipynb` in Jupyter Notebook or Google Colab.
4. Place `Customer_Data.csv` in the same directory and run all cells.

---
**Author:** [Your Name]
**LinkedIn:** [Your Profile Link]
