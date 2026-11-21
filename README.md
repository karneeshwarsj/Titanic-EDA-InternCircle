# Titanic Dataset – Exploratory Data Analysis (EDA)

## Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on the Titanic passenger dataset using Python.

The objective is to understand passenger survival patterns by analyzing factors such as gender, age, and passenger class.

## Project Objectives

- Explore and understand the Titanic dataset.
- Identify and handle missing values.
- Detect duplicate records.
- Perform statistical analysis using Pandas.
- Analyze survival rates based on gender, passenger class, and age group.
- Create visualizations using Matplotlib and Seaborn.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Key Findings

### 1. Survival by Gender

- Female survival rate: 74.20%
- Male survival rate: 18.89%

### 2. Survival by Passenger Class

- First class: 62.96%
- Second class: 47.28%
- Third class: 24.24%

### 3. Survival by Age Group

- Children: 57.97%
- Teenagers: 42.86%
- Adults: 36.05%
- Middle-aged passengers: 39.06%
- Senior passengers: 22.73%

## Data Preprocessing

- Handled missing age values using median imputation based on passenger class and sex.
- Filled missing embarkation values using the mode.
- Removed the deck column due to extensive missing values.
- Identified duplicate records without automatically deleting them.
- Examined column data types.

## Project Structure

```text
Titanic-EDA-InternCircle/
│
├── InternCircle_Project_01_Titanic_EDA.ipynb
├── README.md
└── Titanic_EDA_Report.html
```

## Conclusion

The analysis revealed differences in survival rates based on gender, passenger class, and age group.

This project provided practical experience in data cleaning, data exploration, statistical analysis, and data visualization using Python.

## Project Information

- Program: InternCircle – Data Science & AI
- Project: Project 01 – Exploratory Data Analysis on Titanic
- Environment: Google Colab
- Dataset: Titanic Passenger Dataset</
