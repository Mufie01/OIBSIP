# Task 5: Sales Prediction Using Python

## Oasis Infobyte Data Analytics Internship

### Project Overview
This project focuses on predicting product sales based on advertising expenditure across three marketing channels: TV, Radio, and Newspaper. Using Python and machine learning algorithms, the project analyses the relationship between advertising budgets and sales performance.

### Dataset
- **Dataset:** Advertising Dataset
- **Source:** [Kaggle – Advertising Dataset](https://www.kaggle.com/datasets/ashydv/advertising-dataset)
- **Features:**
  - TV – Advertising expenditure on TV
  - Radio – Advertising expenditure on Radio
  - Newspaper – Advertising expenditure on Newspaper
- **Target Variable:** Sales

### Tools and Technologies
- Python
- Google Colab / Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn

### Project Workflow

1. **Data Loading:** Imported the advertising dataset using Pandas.
2. **Data Exploration:** Examined dataset structure, data types, statistical summaries, missing values, and duplicate records.
3. **Exploratory Data Analysis:** Used pair plots, correlation heatmaps, and scatter plots to understand relationships between advertising expenditure and sales.
4. **Data Preparation:** Separated independent variables (TV, Radio, Newspaper) and the target variable (Sales), then split the data into training and testing sets.
5. **Model Building:** Implemented two machine learning algorithms:
   - Linear Regression
   - Random Forest Regression
6. **Model Evaluation:** Compared model performance using:
   - Mean Absolute Error (MAE)
   - Root Mean Squared Error (RMSE)
   - R² Score
7. **Visualization:** Created actual-versus-predicted plots, residual analysis plots, and feature importance charts.

### Results and Analysis
The performance of Linear Regression and Random Forest Regression was compared using MAE, RMSE, and R² Score.

Feature importance analysis was also performed to identify which advertising channel contributed most to the Random Forest model's predictions.

The model comparison helps determine which algorithm performs better on the test dataset.

### Project Files

| File | Description |
|---|---|
| `sales_prediction.ipynb` | Complete Python notebook containing analysis, model training, evaluation, and visualizations |
| `advertising.csv` | Dataset used for the project (if included) |

### Conclusion
This project demonstrates how machine learning can be used to predict sales based on advertising expenditure. By applying Linear Regression and Random Forest Regression, the project compares different prediction approaches and evaluates their performance.

The analysis also provides insights into the relationship between advertising channels and sales, helping businesses make more informed advertising budget decisions.

---

**Internship:** Oasis Infobyte  
**Domain:** Data Analytics  
**Task:** Level 1 – Task 5: Sales Prediction Using Python
