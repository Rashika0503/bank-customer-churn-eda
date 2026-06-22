# 📊 Bank Customer Churn EDA

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Bank Customer Churn dataset using Python. The objective is to explore customer behavior, identify trends and relationships, and gain insights into factors associated with customer churn through statistical analysis and visualizations.

---

## 🎯 Objectives

- Objective: Extract insights using visual and statistical exploration.


## 🛠️ Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔍 Data Cleaning

The following preprocessing steps were performed:

- Checked dataset shape and column information.
- Verified data types.
- Checked for missing values.
- Checked duplicate records.
- Removed the `customer_id` column.
- Prepared the dataset for analysis.

---

## 📈 Exploratory Data Analysis

The following analyses were performed:

### ✔ Statistical Summary
- `.info()`
- `.describe()`
- `.value_counts()`

### ✔ Visualizations
- Histograms
- Boxplots
- Scatterplots
- Pairplot
- Correlation Heatmap
- Country-wise Customer Distribution
- Churn Distribution
- Churn by Gender
- Churn by Country

---

## 📊 Key Findings

- Dataset contains 10,000 records and 11 useful features.
- No missing values or duplicate records were found.
- Majority of customers belong to France.
- Most customers are aged between 30 and 45 years.
- Age is positively correlated with churn, suggesting that older customers tend to have higher churn rates.
- Active members are less likely to leave the bank.
- Germany exhibits relatively higher churn rates.
- Credit score has weak correlation with churn.
- Male and female customers are almost equally distributed, and churn behavior is observed across both genders.

---

## 📁 Repository Structure

```
bank-customer-churn-eda/
│
├── Bank Customer Churn Prediction.csv
├── Bank_Customer_Churn_EDA.ipynb
├── EDA_Presentation.pptx
├── README.md
```

---

## 🚀 Conclusion

The exploratory data analysis revealed that the dataset is clean and suitable for analysis. Age and customer activity show noticeable relationships with churn, while credit score has little association with customer attrition. Germany exhibits higher churn rates compared to France and Spain. These insights provide a foundation for further predictive modeling and customer retention strategies.

---

## 👩‍💻 Author

**Rashika Diwekar**

B.Tech Electronics and Communication Engineering | Aspiring Data Analyst
