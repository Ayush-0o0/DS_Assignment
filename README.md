Mobile Price Analysis and Data Cleaning

Project Overview

This project involves data cleaning, exploratory data analysis (EDA), and visualization of a mobile phone dataset. The goal is to clean the data, analyze trends, and visualize patterns using univariate, bivariate, and multivariate analysis.

Dataset Description

The dataset contains mobile specifications and prices across different regions. Key attributes include:

Numerical Variables: RAM, Battery Capacity, Screen Size, Mobile Weight, Launched Price (Pakistan, India, China, USA, Dubai).

Categorical Variables: Company Name, Operating System, Model Name.


Data Cleaning Steps

1. Handling Missing Values: Filled numerical column NaNs with median values.
2. Removing Duplicates: Removed duplicate entries.
3. Cleaning Numeric Data: Stripped units (e.g., "mAh", "GB") and converted values to numeric format.
4. Outlier Detection & Treatment: Used IQR method to cap extreme values.


Exploratory Data Analysis (EDA)

Univariate Analysis
Summary Statistics: Mean, Median, Mode, Variance, Skewness.
Visualizations: Frequency distributions, histograms, and box plots.

Bivariate Analysis

Correlation Matrix: Identifies relationships between numerical variables.
Scatter Plots: Shows relationships between continuous variables.
Comparisons Between Categorical & Numerical Variables:
Bar plots for price distribution across brands.
Violin and box plots for RAM, Battery Capacity, and Screen Size vs. Price.

Programming Language: Python

Libraries: Pandas, NumPy, Seaborn, Matplotlib, SciPy
