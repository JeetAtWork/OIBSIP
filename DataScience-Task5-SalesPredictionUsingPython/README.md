# Sales Prediction Using Python

## Oasis Infobyte Data Science Internship — Task 5

### By Somyajeet Satapathy

### Project Overview

This project focuses on predicting product sales using advertising expenditure data. The dataset contains spending information for three advertising channels — TV, Radio, and Newspaper — along with the corresponding Sales.

The project uses exploratory data analysis and machine learning regression models to understand the relationship between advertising expenditure and sales and to predict sales values.

## Dataset

The dataset contains **200 records** with the following columns:

* **TV** — Advertising expenditure through TV
* **Radio** — Advertising expenditure through Radio
* **Newspaper** — Advertising expenditure through Newspaper
* **Sales** — Product sales

## Work Performed

The project includes:

* Dataset loading and inspection
* Data type and null-value checking
* Descriptive statistical analysis
* Exploratory data visualizations
* Pairplot analysis
* Scatter plots for advertising channels and Sales
* Correlation heatmap
* Train-test splitting
* Linear Regression modelling
* Random Forest Regression modelling
* Model evaluation using MAE, RMSE and R²
* Residual analysis of the best model
* Advertising channel impact analysis
* Comparison of regression models

## Models Used

### Linear Regression

Linear Regression was used as the baseline regression model.

**Results:**

* MAE: **1.4608**
* RMSE: **1.7816**
* R² Score: **0.8994**

### Random Forest Regression

Random Forest Regression was used as the second regression model and performed better than Linear Regression on the test data.

**Results:**

* MAE: **0.6201**
* RMSE: **0.7686**
* R² Score: **0.9813**

## Best Model

**Random Forest Regression** was selected as the best-performing model because it achieved the lowest MAE and RMSE and the highest R² score among the two models.

## Advertising Channel Analysis

The Linear Regression coefficients were used to compare the impact of the advertising channels.

The analysis identified **Radio** as the advertising channel with the highest coefficient magnitude.

**Radio coefficient magnitude:** 0.1892

## Conclusion

The analysis shows a strong relationship between advertising expenditure and product sales. Both models were able to predict Sales, but Random Forest Regression provided better performance on the test data.

The final Random Forest model achieved an R² score of **0.9813**, indicating a strong fit on the test dataset. The advertising channel analysis also showed that Radio had the highest impact among the three channels based on the regression coefficients.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Project Structure

```text
DataScience-Task5-SalesPrediction/
│
├── Sales_Prediction_Using_Python.ipynb
├── README.md
```

