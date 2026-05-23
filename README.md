# Water Potability - DWDM Assignment 3 & 4

**Course:** Data Warehousing and Data Mining  
**Submitted To:** Mam Nadia Mushtaq  
**Submitted By:** Muhammad Mohsin  
**University:** The University of Lahore  

---

## About This Project

This project applies data preprocessing and machine learning on the 
Water Potability dataset to predict whether water is safe for drinking.

---

## Files in This Repository

| File | Description |
|------|-------------|
| water_potability.csv | Original dataset with missing values and outliers |
| cleaned_water_potability_dataset.csv | Preprocessed and cleaned dataset |
| Assignments_DWDM.ipynb | Complete Jupyter Notebook with all code |
| assignments_dwdm.py | Python script version |

---

## Assignment 3 - Data Preprocessing & Classification

**Preprocessing Steps:**
- Missing values handled using Median Imputation
- Outliers removed using IQR Method
- Categorical column created (ph_category)
- Label Encoding applied
- Min-Max Normalization and Standardization applied
- Train-Test Split (80/20)

**Classification Models:**
- Decision Tree — Accuracy: 55.26%
- Random Forest — Accuracy: 66.54%

---

## Assignment 4 - Regression Analysis

**Target Variable:** Sulfate (continuous)

**Regression Models:**
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

**Evaluation:** RMSE, MAE, R2 Score

---

## Dataset Source

Kaggle: https://www.kaggle.com/datasets/adityakadiwal/water-potability

---

## Tools Used

- Python 3
- Google Colaboratory
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
