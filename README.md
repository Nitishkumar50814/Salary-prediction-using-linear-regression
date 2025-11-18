# Salary-prediction-using-linear-regression
A machine learning project to predict employee salary using HR data.

# Employee Monthly Income Prediction
### Linear Regression • Machine Learning • HR Analytics

A clean and beginner-friendly machine learning project where we build a **Linear Regression model** to predict an employee’s **Monthly Income** based on experience, job level, and other HR features.

---

## 1. Project Summary
This project demonstrates how machine learning can be used for HR analytics.  
We use a structured dataset of employees and apply **Linear Regression** to predict salary.

The notebook includes:
- Data exploration  
- Encoding categorical variables  
- Feature selection  
- Model training  
- Performance evaluation  

---

## 2. Dataset Information
The dataset contains various employee attributes such as:

- **Age**
- **JobLevel**
- **TotalWorkingYears**
- **YearsAtCompany**
- **YearsInCurrentRole**
- **YearsWithCurrManager**
- **PercentSalaryHike**
- **TrainingTimesLastYear**
- **MonthlyIncome** (Target)

---
## 3. Model Performance

Replace with your values:
Metric	Value
Mean Squared Error:1358868.17,
R² Score:92.3%

## 4. Machine Learning Workflow

### 4.1 Importing Libraries
```python
import pandas as pd
import numpy as np
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_squared_error, r2_score


