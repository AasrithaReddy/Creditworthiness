# Creditworthiness Causality Analysis

This project explores the **difference between correlation and causation** using a dataset on creditworthiness. It demonstrates how to read and analyze data, particularly for financial or behavioral modeling where causality can be a key consideration.

## 📘 Description

**Correlation** is a statistical measure that describes the extent to which two variables change together. However, **correlation does not imply causation**. This notebook uses a creditworthiness dataset to demonstrate how correlated variables might not necessarily be causal.

## 📂 Dataset

- The dataset used is `creditworthiness.csv`.
- It contains information about individuals' credit behavior and other factors that may or may not influence their credit default risk.

## 🛠️ Tools & Libraries Used

- Python 3
- Pandas
- (Optional) Causal inference libraries (if applicable)

## 📊 Features

- Data import and exploration
- Difference between correlation and causation
- Data preprocessing
- Exploratory analysis of relationships between variables

## 💡 Sample Code

```python
import pandas as pd

file_path = 'creditworthiness.csv'
ccdefault_causal_df = pd.read_csv(file_path)
print(ccdefault_causal_df.head())
