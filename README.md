Salaries by College Major – Data Analysis
Project Overview

This project explores how college majors influence salary outcomes. Using a dataset containing salary information for different undergraduate majors, the analysis investigates trends in starting salaries, mid-career salaries, and salary growth potential.

The goal of this project is to demonstrate data cleaning, exploration, and analysis using Python and Pandas in a Jupyter Notebook.

Objectives

The analysis aims to answer the following questions:

Which majors have the highest starting salaries?

Which majors have the highest mid-career salaries?

Which majors have the lowest salaries?

Which degrees offer the highest long-term earning potential?

Which majors have the lowest salary risk (small salary spread)?

Dataset

The dataset contains salary statistics for different undergraduate majors, including:

Undergraduate Major

Starting Median Salary

Mid-Career Median Salary

Mid-Career 10th Percentile Salary

Mid-Career 90th Percentile Salary

These values help analyze earning potential and salary variability across careers.

Tools and Technologies

The project was completed using:

Python

Pandas

Jupyter Notebook

Key techniques used:

Data loading and inspection

Data cleaning

Handling missing values

Statistical exploration

Sorting and filtering datasets

Calculating salary spread

Key Analysis Steps
1. Data Loading

The dataset is loaded using Pandas and inspected to understand its structure.

2. Data Cleaning

Missing values are removed to ensure accurate analysis.

3. Salary Exploration

The project identifies:

Majors with the highest and lowest starting salaries

Majors with the highest and lowest mid-career salaries

4. Salary Spread Calculation

A new column called Spread is created:

Spread = Mid-Career 90th Percentile Salary − Mid-Career 10th Percentile Salary

This measures salary risk or variability within each major.

5. Risk Analysis

Majors are sorted by salary spread to identify low-risk careers where earnings are more predictable.

Example Insights

Some insights explored in the analysis include:

Majors in engineering and technical fields tend to have higher starting salaries.

Some majors have large salary spreads, meaning earnings vary widely.

Other majors show lower spreads, indicating more consistent salary outcomes.

Project Structure
Salaries-by-College-Major
│
├── Salaries_by_college_major.ipynb
├── salaries_by_college_major.csv
└── README.md
How to Run the Project

Clone the repository

Open the notebook in Jupyter Notebook or Jupyter Lab

Run the cells step by step to reproduce the analysis

Skills Demonstrated

This project demonstrates:

Data cleaning

Exploratory data analysis

Data manipulation with Pandas

Analytical thinking

Python data analysis workflow
