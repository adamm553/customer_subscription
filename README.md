# Customer Subscription

Author: Adam Piatek
Date: 2023-04-16

This project involves data cleaning, quality checking, and analysis of a dataset containing information about customers, including their age, gender, income, number of kids, homeownership status, subscription status, and segment.

## Overview

The project includes the following steps:

1. Cleaning the dataset to remove unnecessary characters and fix data format issues.
2. Checking the quality of the data for missing values and outliers.
3. Analyzing the data to understand relationships between variables and perform statistical tests.

## Data Cleaning

The dataset was cleaned by:

- Removing unnecessary characters from column names.
- Removing double quotes from string variables.
- Converting the 'age' variable to numeric and rounding it to the nearest integer.
- Removing prefixes from 'ownHome' and 'subscribe' variables.
- Replacing negative values in the 'income' variable with the median income.

## Data Quality Check

- No missing values were found in the dataset.
- Outlier detection was performed using boxplots for the 'age', 'kids', and 'income' variables.
- Negative values in the 'income' variable were replaced with the median income.

## Data Analysis

### Analysis of Income by Number of Kids

- Null Hypothesis (H0): The means of income are similar.
- Alternative Hypothesis (H1): The means of income differ significantly.
- Kruskal-Wallis test was conducted to compare the means of income across different groups of kids.
- Pairwise Wilcoxon test was performed to identify significant differences in income between groups of kids.

### Relationship between Income and Segment

- Null Hypothesis (H0): There is a relationship between income and segment.
- Alternative Hypothesis (H1): There is no relationship between income and segment.
- Chi-squared test was conducted to examine the relationship between income and segment.

## Results

- The statistical tests revealed that there is a significant difference in income between groups of kids, but the pairwise comparisons showed only minor differences.
- There is no significant relationship between income and segment.

## Author

This project was conducted by Adam Piatek.

If you have any questions or feedback, feel free to reach out!
