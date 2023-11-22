# Data-Analytics-Project

# Salary Survey Data Analysis

## Overview

This repository contains Python code for analyzing and cleaning a dataset from a salary survey. The main tasks include exploratory data analysis (EDA), outlier removal, and correlation analysis. The dataset is sourced from a skills network provided by IBM.

## Files

- `salary_survey_analysis.ipynb`: Jupyter Notebook containing the Python code for the analysis.
- `m2_survey_data.csv`: Dataset used in the analysis.

## Analysis Steps

1. **Exploratory Data Analysis (EDA):**
   - Analyzing the distribution of salary data.
   - Visualizing the data using box plots and histograms.

2. **Outlier Removal:**
   - Identifying and removing outliers from the 'ConvertedComp' column using the interquartile range (IQR) method.

3. **Correlation Analysis:**
   - Calculating the correlation between the 'Age' column and other numerical columns in the dataset.

## Usage

To run the analysis, you can use Jupyter Notebook and open the `salary_survey_analysis.ipynb` file.

## Dependencies

The code utilizes the following Python libraries:
- pandas
- matplotlib
- seaborn

Install the required dependencies using:

```bash
pip install pandas matplotlib seaborn
