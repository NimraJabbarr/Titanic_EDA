# Titanic Exploratory Data Analysis

## Introduction
The Titanic dataset is one of the most popular datasets used for data science and machine learning. It contains information about the passengers on the Titanic, including if they survived or not. This repository focuses on performing exploratory data analysis (EDA) on this dataset to extract meaningful insights.

## Dataset
The dataset consists of the following columns:
- **PassengerId**: Unique identifier for each passenger
- **Survived**: Survival (0 = No; 1 = Yes)
- **Pclass**: Ticket class (1 = 1st; 2 = 2nd; 3 = 3rd)
- **Name**: Name of the passenger
- **Sex**: Sex of the passenger
- **Age**: Age of the passenger
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Ticket**: Ticket number
- **Fare**: Ticket fare
- **Cabin**: Cabin number
- **Embarked**: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

## EDA Steps
1. **Data Cleaning**: This includes handling missing values and correcting data types.
2. **Descriptive Statistics**: Generating summary statistics to understand the distribution of features.
3. **Data Visualization**: Utilizing plots to visualize distributions, relationships, and trends.
4. **Correlation Analysis**: Analyzing the correlation between different features and survival outcomes.

## Visualizations
- **Distribution of Age**: Plots showing how age is distributed among survivors and non-survivors.
- **Survival Rate by Gender**: Analyzing survival rates based on gender.
- **Survival Rate by Class**: Evaluating how ticket class affects survival.

## Conclusion
Conducting EDA on the Titanic dataset provides valuable insights into the factors that affected passenger survival. The analysis helps in understanding not just the distribution of data but also relationships between features.

## Getting Started
To run the EDA scripts, follow these steps:
1. Clone the repository: `git clone https://github.com/NimraJabbarr/Titanic_EDA.git`
2. Install the required libraries: `pip install -r requirements.txt`
3. Execute the main script: `python main.py`
## Future goals
Build predictive models (Logistic Regression, Random Forest, XGBoost) to estimate survival probabilities.
Enhance feature engineering by creating new variables (e.g., family size, titles from names) to improve model accuracy.


This notebook is intended for educational and portfolio purposes. Please do not reuse without proper attribution.
