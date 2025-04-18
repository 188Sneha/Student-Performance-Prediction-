# Student-Performance-Prediction-
# Student Performance Prediction

## Project Overview

This project aims to predict whether a student will pass or fail based on various factors such as study time, attendance, GPA, parental support, and extracurricular activities. Using machine learning, we built a classification model using the **Random Forest Classifier** to predict student outcomes (Pass/Fail).

The dataset used for this project comes from the **UCI Machine Learning Repository**, which contains student performance data. The project explores the relationship between student characteristics and their academic performance.

## Features

- **Study Time Weekly**: The average number of hours a student studies each week.
- **Absences**: The number of school days the student was absent.
- **GPA**: The student's Grade Point Average.
- **Parental Support**: A score indicating the level of support from parents.
- **Extracurricular Activities**: A binary indicator (1 or 0) showing whether the student participates in extracurricular activities.

The target variable is **GradeClass** which has been converted into a binary outcome (Pass/Fail). A value of 0 represents a "pass" and 1 represents a "fail."

## Prerequisites

Make sure you have the following dependencies installed:

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Tabulate

You can install the required libraries using **pip**:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn tabulate
