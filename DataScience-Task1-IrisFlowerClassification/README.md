# Iris Flower Classification

## Oasis Infobyte Data Science Internship — Task 1

This project was completed as part of my Data Science Internship at Oasis Infobyte.

The objective of this project is to classify Iris flowers into three different species — **Setosa, Versicolor, and Virginica** — using their physical measurements and machine learning classification algorithms.

## Project Objective

The main goal is to explore the Iris dataset, understand the relationships between its features, and build machine learning models that can correctly predict the species of an Iris flower.

The project covers:

* Exploratory Data Analysis
* Data visualization
* Feature analysis
* Train-test splitting
* Machine learning model training
* Model evaluation
* Comparison of different classification models

## Dataset

The Iris dataset is loaded directly from `sklearn.datasets.load_iris()`.

It contains **150 flower samples** belonging to three species:

* Iris Setosa
* Iris Versicolor
* Iris Virginica

Each flower has four numerical measurements:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

There are 50 samples for each species.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook / Google Colab

## Exploratory Data Analysis

The dataset was first inspected to understand its structure and quality.

The analysis included:

* Checking the number of rows and columns
* Checking column names and data types
* Checking for missing values
* Checking for duplicate records
* Generating descriptive statistics
* Checking the distribution of the three species

The dataset contains no missing values, and the three species are equally represented.

## Data Visualization

Different visualizations were used to understand the dataset better.

### Pairplot

A pairplot was used to compare the four numerical features across the three Iris species.

It showed that the species are more clearly separated when petal measurements are considered.

### Box Plots

Box plots were created for all four features to compare their distributions across the three species.

These plots helped identify the differences in measurements between the species.

## Feature Analysis

The analysis showed that **petal length and petal width are the most discriminative features**.

These two features provide a clearer separation between Setosa, Versicolor, and Virginica compared with the sepal measurements.

## Machine Learning

The dataset was divided into training and testing sets using an **80/20 split**.

Two classification algorithms were trained:

1. Logistic Regression
2. Decision Tree Classifier

The models were then used to predict the species of the flowers in the test dataset.

## Model Evaluation

The models were evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report
* Precision
* Recall
* F1-score

### Results

| Model               |   Accuracy |
| ------------------- | ---------: |
| Logistic Regression | **96.67%** |
| Decision Tree       | **93.33%** |

### Logistic Regression

Logistic Regression achieved an accuracy of **96.67%**, correctly classifying 29 out of 30 test samples.

Its classification results were:

* Setosa: F1-score 1.00
* Versicolor: F1-score 0.95
* Virginica: F1-score 0.95

### Decision Tree

The Decision Tree achieved an accuracy of **93.33%**, correctly classifying 28 out of 30 test samples.

Its classification results were:

* Setosa: F1-score 1.00
* Versicolor: F1-score 0.90
* Virginica: F1-score 0.90

## Best Performing Model

Based on the test accuracy and classification results, **Logistic Regression** performed better than the Decision Tree for this dataset.

Logistic Regression achieved **96.67% accuracy**, compared with **93.33%** for the Decision Tree.

Therefore, Logistic Regression was selected as the best-performing model for this project.

## Project Files

This folder contains:

* `Iris_Flower_Classification.ipynb` — Jupyter/Colab notebook containing the complete analysis and machine learning implementation.
* `Iris_Project_Cover.png` — Project title/cover image.

## Conclusion

The Iris dataset was successfully explored and used to train two machine learning classification models.

The analysis showed that petal length and petal width were the most useful features for distinguishing the three Iris species. Both models performed well, but Logistic Regression achieved the highest accuracy of **96.67%**.

This project provided practical experience with exploratory data analysis, data visualization, feature analysis, classification algorithms, and model evaluation using Python and scikit-learn.

