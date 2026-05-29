# Titanic EDA Project

## Overview
This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to understand passenger survival patterns and gain insights from the data using Python.

The analysis includes:
- Data cleaning
- Missing value handling
- Univariate analysis
- Bivariate analysis
- Multivariate analysis
- Data visualization
- Statistical insights

---

## Dataset
The dataset contains information about Titanic passengers such as:
- Passenger class
- Gender
- Age
- Fare
- Embarkation port
- Survival status

Dataset used:
- Titanic_Dataset.csv from the Titanic dataset

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Colab Notebook

---

## Project Workflow

### 1. Data Understanding
- Checked dataset shape
- Explored columns and datatypes
- Identified missing values

### 2. Data Cleaning
- Dropped Cabin column due to excessive missing values
- Filled missing Age values using median
- Filled missing Embarked values using mode

### 3. Univariate Analysis
Analyzed individual features:
- Survived
- Sex
- Pclass
- Age
- Fare

### 4. Bivariate Analysis
Analyzed relationships between features:
- Sex vs Survived
- Pclass vs Survived
- Age vs Survived
- Fare vs Survived

### 5. Multivariate Analysis
Studied combined feature relationships:
- Sex + Pclass + Survived
- Age + Survival + Gender

---

## Key Insights

- Female passengers had a significantly higher survival rate.
- First-class passengers survived more compared to lower classes.
- Most passengers were between 20 and 40 years old.
- Fare distribution was highly right-skewed with extreme outliers.
- Third-class passengers formed the majority of the dataset.

---

## Conclusion
This project demonstrates the complete EDA workflow including data preprocessing, visualization, statistical analysis, and insight extraction using Python.

---

## Author
Muhammad Ahmed
