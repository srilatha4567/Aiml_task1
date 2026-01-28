# AI & ML Internship - Task 1: Data Understanding

## Overview
This task focuses on performing **Exploratory Data Analysis (EDA)** to understand the structure, types, and quality of a dataset before applying Machine Learning models.

## Steps Performed
* **Data Loading:** Imported the Titanic dataset using Pandas.
* **Inspection:** Used `.head()`, `.tail()`, and `.info()` to observe the dataset structure.
* **Feature Engineering:** Manually categorized features into Numerical, Categorical, Ordinal, and Binary types.
* **Statistical Analysis:** Used `.describe()` to calculate mean, spread, and quartiles.
* **Data Quality Check:** Identified missing values (Nulls) and analyzed class imbalance in the target variable (`Survived`).

## Key Observations
* **Target Variable:** `Survived` (Binary Classification).
* **Missing Data:** Significant missing values found in 'Age' and 'Cabin' columns.
* **Suitability:** The dataset is suitable for ML classification once missing values are handled and categorical data is encoded.

## Tools Used
* **Language:** Python
* **Libraries:** Pandas, NumPy
* **Environment:** Jupyter Notebook / Google Colab
