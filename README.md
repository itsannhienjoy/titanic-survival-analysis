# Titanic Survival Analysis 

## Overview
This project applies data analysis and machine learning techniques to explore the factors that influenced passenger survival on the Titanic. The analysis covers exploratory data analysis (EDA), feature engineering, and predictive modeling to extract actionable insights from historical data using Python.

## Objectives
- Understand key demographic and socio-economic factors affecting survival rates.
- Clean and transform raw data into a structured, machine-learning–ready format.
- Engineer relevant features that enhance predictive performance.
- Build and evaluate classification models to predict survival outcomes.
- Communicate findings through data visualizations and performance metrics.

## Dataset
- Source: Kaggle Titanic Dataset
- Files:
  - train.csv: Used for EDA, training, and evaluation.
  - test.csv: Used for final prediction/testing.

## Key Techniques
- Data Cleaning: Handling missing values, inconsistent data, and categorical encoding.
- EDA: Visualizing survival rates by gender, age, class, fare, and family size.
- Feature Engineering: Extracting titles from names, creating family groupings, and binning continuous variables.
- Modeling: Logistic Regression, Random Forest, and Gradient Boosting Classifier.
- Evaluation: Accuracy, precision-recall, confusion matrix, and cross-validation scores.

## Tools and Tech Stacks
- Languages: Python
- Libraries: pandas, NumPy, seaborn, matplotlib, scikit-learn
- Environment: Jupyter Notebook

## Project Structure
```
titanic-survival-analysis/
├── data/                  # Input dataset files (train/test)
├── notebooks/             # Jupyter notebooks for EDA and modeling
├── scripts/               # Custom Python scripts for preprocessing or modeling
├── output/                # Generated outputs (e.g., charts, metrics)
├── requirements.txt       # Project dependencies
└── README.md              # Project documentation
```
