# Data Cleaning and Preprocessing

## Project Overview

This project demonstrates professional data cleaning and preprocessing techniques using the Titanic dataset.

The objective is to identify and handle common data quality issues such as missing values, duplicate records, inconsistent formatting, incorrect data types, and potential outliers.

## Business Objective

The objective of this project is to transform a messy dataset into a cleaner and more consistent dataset that is suitable for further analysis.

## Dataset

Dataset: Titanic Dataset

The dataset contains passenger information such as:

- Passenger ID
- Passenger Class
- Name
- Sex
- Age
- Number of Siblings/Spouses
- Number of Parents/Children
- Ticket
- Fare
- Cabin
- Embarked Port

## Data Cleaning Process

The project follows these steps:

1. Dataset inspection
2. Data quality assessment
3. Missing value analysis
4. Missing value handling
5. Duplicate detection and removal
6. Data standardization
7. Data type correction
8. Outlier detection using IQR
9. Before vs. after data quality comparison
10. Exporting the cleaned dataset
11. Final data quality verification

## Missing Value Handling

Missing values were handled using appropriate strategies:

- Age → Median imputation
- Cabin → Filled with "Unknown"
- Embarked → Mode imputation

## Data Standardization

The project standardizes categorical values and corrects data types.

Examples include:

- Standardizing Sex values
- Standardizing Embarked values
- Converting PassengerId to string format

## Outlier Detection

The Interquartile Range (IQR) method was used to identify potential outliers in numerical columns such as:

- Age
- Fare
- SibSp
- Parch

Detected outliers were retained when they represented legitimate observations rather than being automatically removed.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

```text
DataAnalytics-L1-DataCleaning/
│
├── README.md
├── Project_3_Data_Cleaning.ipynb
└── Titanic_Cleaned.csv
