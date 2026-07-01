# ApexPlanet-DataAnalytics-Task4
Apex planet Task-4: Data Storytelling &amp; Statistical Validation using Python, EDA, and T-test to derive business insights from sales data.

## 🔹 Overview
This project is part of the ApexPlanet Data Analytics Internship.

The objective of this task is to transform data analysis into a meaningful business story and validate insights using statistical methods.

---

## 🔹 Dataset
- Contains 1000 records of customer transactions
- Includes customer details, product categories, and sales information
- Key columns: Category, Total_Sales, Age, City, High_Value_Order

---

## 🔹 Key Insights
- Sales distribution varies across different product categories
- Some categories generate higher overall revenue
- Customer purchasing patterns differ across segments

---

## 🔹 Hypothesis Testing

### Problem Statement
To determine whether there is a significant difference in average sales between product categories.

### Hypotheses
- **H0 (Null Hypothesis):** No significant difference in average sales between categories  
- **H1 (Alternative Hypothesis):** Significant difference exists  

### Statistical Method
- Independent T-test was used to compare two categories

### Result
- **T-Statistic:** 0.2616  
- **P-Value:** 0.7937  

### Interpretation
Since the p-value is greater than 0.05, we fail to reject the null hypothesis.

This indicates that there is no statistically significant difference in sales between the selected categories.

---

## 🔹 Business Conclusion
The analysis suggests that category alone may not strongly influence sales performance.

Businesses should consider other factors such as pricing, marketing strategies, and customer segmentation to improve sales.

---

## 🔹 Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- SciPy

---

## 🔹 Files Included
- Jupyter Notebook (.ipynb)
- README.md

---

## 🔹 Learning Outcome
This task demonstrates how data storytelling combined with statistical validation can support data-driven decision-making.

---
