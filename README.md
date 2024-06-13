# Boston Housing Analysis

This repository contains the final project for the [Course Name], which involves analyzing the Boston Housing dataset. The project tasks include generating descriptive statistics, visualizations, and performing various statistical tests to answer specific questions about the data.

## Project Overview

The project is divided into the following tasks:

1. **Familiarize yourself with the dataset:**
   - Description of dataset variables.

2. **Generate Descriptive Statistics and Visualizations:**
   - Boxplot of median value of owner-occupied homes (MEDV).
   - Bar plot for the Charles River variable (CHAS).
   - Boxplot for MEDV vs AGE variable (discretized).
   - Scatter plot of nitric oxide concentrations (NOX) vs non-retail business acres (INDUS).
   - Histogram for pupil-teacher ratio (PTRATIO).

3. **Statistical Analysis:**
   - T-test for independent samples to check the difference in MEDV by Charles River variable.
   - ANOVA to check the difference in MEDV for different AGE groups.
   - Pearson correlation to check the relationship between NOX and INDUS.
   - Regression analysis to determine the impact of distance to employment centres (DIS) on MEDV.

4. **Share your Jupyter Notebook:**
   - Instructions for sharing the notebook.

## Dataset

The dataset used in this project is the Boston Housing dataset. It includes various variables related to housing in Boston, such as crime rate, average number of rooms, age of houses, and more.

## Installation

To run the notebook, you need to install the required libraries. Use the following commands:

```bash
pip install pandas numpy seaborn matplotlib scipy statsmodels
