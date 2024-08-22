# Healthcare Performance Analysis

## Overview

This project involves analyzing hospital performance scores using a comprehensive dataset. The analysis aims to explore, clean, and interpret the data to gain insights into healthcare quality across hospitals, states, and counties. The project includes descriptive statistics, performance evaluations, trend analysis, and various visualizations to understand and compare performance metrics.

## Objectives

- **Data Exploration and Cleaning:** Manage missing values, convert data types, and create new variables for analysis.
- **Descriptive Analysis:** Compute summary statistics, assess score distributions, and analyze performance by different categories.
- **Performance Analysis:** Rank hospitals based on average scores, and analyze variability by address, ZIP code, and phone number.
- **Trend Analysis:** Examine changes in performance scores over time and compare them to national benchmarks.
- **Visualization:** Develop visualizations such as bar plots, box plots, and line plots to effectively communicate findings.
- **Insights and Recommendations:** Provide actionable insights and recommendations for improving hospital performance.

## Dataset

The dataset contains the following columns:
- Provider ID
- Hospital Name
- Address
- City
- State
- ZIP Code
- County Name
- Phone Number
- Measure Name
- Measure ID
- Compared to National
- Score
- Footnote
- Measure Start Date
- Measure End Date
- Location

## Analysis Summary

1. **Descriptive Statistics:** Summary statistics to understand data distribution and central tendencies.
2. **Performance Evaluation:** Identified top and bottom-performing hospitals, and analyzed score distributions.
3. **Trend Analysis:** Studied performance trends over time and compared against national benchmarks.
4. **Visualization:** Created plots to visualize key insights, including score distributions and performance trends.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Files Included

- `notebook/Healthcare_Performance_Analysis.ipynb`: Jupyter Notebook with the complete analysis, code, and visualizations.
- `data/Healthcare Associated Infections.csv`: Dataset used for analysis.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/healthcare-performance-analysis.git

2. Navigate to the project directory:
   ```bash
   cd healthcare-performance-analysis

3. Open and run the Jupyter Notebook:
   ```bash
   jupyter notebook notebook/Healthcare_Performance_Analysis.ipynb
