# DAI-101-ASSIGNMENT-

## Overview
This repository contains the solution for Assignment 12-1PM DAI, which focuses on data cleaning, exploratory data analysis (EDA), and multivariate analysis. The dataset used in this assignment contains multiple numerical and categorical variables, and the tasks involve handling missing values, removing duplicates, treating outliers, and performing various types of data analysis.

## Dataset
The dataset chosen for this assignment contains a mix of numerical and categorical variables. It includes missing values, duplicate entries, and potential outliers, which were addressed during the data cleaning process.

## Tasks Performed

### 1. Data Cleaning
- **Loading and Inspecting the Dataset**: The dataset was loaded and its structure was inspected to understand the types of variables and identify any immediate issues.
- **Handling Missing Values**: Missing values were addressed using imputation techniques or by removing records with excessive missing data.
- **Removing Duplicate Records**: Duplicate entries were identified and removed to ensure data integrity.
- **Treating Outliers**: Outliers were detected using statistical methods (e.g., IQR, Z-score) and treated appropriately.
- **Standardizing Categorical Values**: Categorical variables were standardized by fixing typos and formatting inconsistencies.

### 2. Exploratory Data Analysis (EDA)
- **Univariate Analysis**: 
  - Summary statistics (mean, median, mode, variance, skewness, etc.) were calculated for numerical variables.
  - Frequency distributions were generated for categorical variables.
  - Histograms and box plots were used to visualize the distributions of numerical variables.
  
- **Bivariate Analysis**:
  - A correlation matrix was created to identify relationships between numerical variables.
  - Scatter plots were used to explore relationships between continuous variables.
  - Bar plots, violin plots, and box plots were used to compare categorical and numerical variables.
  
- **Multivariate Analysis**:
  - Pair plots were used to analyze multiple relationships simultaneously.
  - Heatmaps were generated to visualize correlations among multiple variables.
  - Grouped comparisons were performed to identify the combined effects of multiple features.

## Expected Outcomes
By completing this assignment, the following outcomes were achieved:
- Applied data cleaning techniques to prepare the dataset for analysis.
- Understood and visualized the distributions of individual variables.
- Identified relationships between variables and interpreted their significance.
- Used multivariate techniques to analyze complex interactions in the data.


**Note**: Ensure that all dependencies are installed before running the notebooks. You can install the required packages using `pip install -r requirements.txt` if a `requirements.txt` file is provided in the repository.
