
# Data Cleaning – Titanic Dataset

## Internship
Oasis Infobyte – Data Analytics Internship

## Task
Level 1 – Task 3: Cleaning Data

## Project Overview
This project focuses on identifying and resolving
data quality issues in the Titanic passenger dataset.

The objective is to prepare a clean and reliable dataset
for further data analysis and machine learning.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Cleaning Operations Performed
1. Dataset inspection
2. Missing value identification and treatment
3. Duplicate record removal
4. Text standardisation
5. Outlier detection using IQR
6. Data type verification
7. Before-and-after comparison
8. Cleaned CSV export

## Missing Value Treatment
- Age: Median imputation
- Embarked: Mode imputation
- Cabin: Removed due to extensive missing values

## Outlier Treatment
Potential outliers were detected using the
Interquartile Range (IQR) method.

Legitimate outliers were retained to preserve
genuine passenger information.

## Dataset Source
https://www.kaggle.com/competitions/titanic/data

## Project Files
- data_cleaning.ipynb – Complete data cleaning notebook
- cleaned_titanic_dataset.csv – Cleaned dataset
- charts/ – Data quality visualisations

## Conclusion
The project demonstrates the importance of data
cleaning in preparing accurate and reliable datasets
using Python and its data analysis libraries.
