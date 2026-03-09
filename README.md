# Predictive Analytics for Workforce Stability
**Identifying Attrition Factors with Supervised Machine Learning**

*MSDS692 - Michelle Zheng*

---

## Project Overview

This project builds and compares machine learning models to predict employee attrition using the synthetic [IBM Watson HR Employee Attrition and Performance dataset]. 

Two classification algorithms were evaluated, Logistic Regression and Random Forest across accuracy, AUC, precision, recall and F1-score. Logistic Regression was selected as the preferred model, achieving an AUC of **0.8374** and a recall of **76.60%** for the attrition class on the test set.

Key attrition drivers identified: monthly income, age, overtime status, total working years, years at the company and years with current manager.

---

## Dataset

- **Source:** [IBM HR Analytics Employee Attrition & Performance](https://github.com/studnt001/Predictive-Analytics-for-Workforce-Stability/blob/main/Code/IBM_Wat_EMPL_Data.csv)
- **Records:** 1,470 employees, 35 features
- **Target variable:** `Attrition`
- **Class distribution:** 83.88% current employees, 16.12% past employees


```

---

## Setup Instructions


### Install Required Packages


| Package | Purpose |
|---|---|
| `pandas` | Data loading and manipulation |
| `numpy` | Numerical operations |
| `matplotlib` / `seaborn` | Static data visualization |
| `plotly` | Interactive visualization |
| `scipy` | Statistical testing (t-test) |
| `scikit-learn` | Preprocessing, modeling, and evaluation |




### Load the Data

```python
df = pd.read_csv("IBM_Wat_EMPL_Data.csv")
```

---

## Project Model Files

```
├── IBM_Wat_EMPL_Data.csv 
├── EMPL_ATTR_PRDTN.ipynb               
```
