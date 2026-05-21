# Ecommerce Customers Spending Prediction using Multiple Linear Regression

## Project Overview
This project uses Multiple Linear Regression (MLR) to predict how much a customer spends yearly on an e-commerce platform based on customer behavior data.

The main goal is to identify which customer activities contribute most to yearly spending and help the company make better business decisions.

---

# Business Problem

An e-commerce company wants to understand:

- Which factors affect customer spending the most?
- Should the company focus more on the mobile app or website?
- Does customer membership duration impact revenue?
- How can the company increase yearly revenue?

The company collected customer behavior data and wants to use Machine Learning to predict:

```python
Yearly Amount Spent
```

---

# Business Objective

The objective of this project is to:

- Predict yearly customer spending
- Analyze customer behavior
- Identify important business-driving factors
- Improve customer retention strategy
- Help company optimize app and website investment

---

# Dataset Information

Dataset contains customer behavior features such as:

| Feature | Description |
|---|---|
| Avg. Session Length | Average customer session duration |
| Time on App | Time spent on mobile app |
| Time on Website | Time spent on website |
| Length of Membership | Customer membership duration |
| Yearly Amount Spent | Total yearly spending by customer |

---

# Machine Learning Type

- Supervised Machine Learning
- Regression Problem
- Multiple Linear Regression

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

# Project Workflow

## 1. Data Loading
- Loaded dataset using Pandas

## 2. Data Understanding
- Checked dataset shape
- Checked datatypes
- Checked statistical summary

## 3. Data Cleaning
- Checked null values
- Verified clean dataset

## 4. Exploratory Data Analysis (EDA)
- Pairplot visualization
- Correlation heatmap
- Feature relationship analysis

## 5. Feature Selection
Selected independent variables:

```python
['Avg. Session Length',
 'Time on App',
 'Time on Website',
 'Length of Membership']
```

Target variable:

```python
'Yearly Amount Spent'
```
