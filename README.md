# Health Insurance Costs Analysis

This repository contains code and analysis for exploring the factors influencing health insurance costs using a dataset of 1,338 observations. Each observation represents an individual insurance policyholder with various attributes.

## Overview

This study aims to determine the relationship between several predictors and the response variable (insurance charges) through exploratory data analysis and regression modeling.

## Dataset

The dataset includes the following variables:
- **age** (numeric)
- **sex** (categorical: male, female)
- **BMI** (numeric)
- **children** (numeric)
- **smoker** (categorical: yes, no)
- **region** (categorical: northeast, northwest, southeast, southwest)
- **charges** (numeric, representing insurance costs)

The data was sourced from an insurance company's database, reflecting policyholder characteristics and their associated charges.

## Methods

### Data Processing
- Checking for missing values and data inconsistencies.
- Encoding categorical variables as necessary for regression analysis.
- Normalizing/standardizing numerical variables if required, depending on the analysis.

### Exploratory Data Analysis (EDA)
- Creating scatter plots to investigate linear relationships between insurance charges and several predictors (age, BMI).
- Calculating summary statistics and distributions of variables.
- Checking for normal distribution of variables.

### Regression Modeling
Two models were fitted:
1. **Simple Linear Regression Model** focusing on one predictor.
2. **Multiple Linear Regression Model** incorporating all predictors.

### Model Evaluation
- Comparing coefficients, p-values, and R^2 values.
- Residual plots to evaluate model assumptions.
- Calculating a 95% prediction interval for insurance charges based on the average value of a selected predictor.

## Code and Dependencies

The analysis is performed in a Jupyter notebook. The main libraries used are:
- `pandas`
- `seaborn`
- `matplotlib`
- `scipy`
- `sklearn`
- `numpy`

## File Structure
- `Midterm_MAT326.ipynb`: Jupyter notebook containing the analysis and code.
- `Midterm_MAT326.pdf`: PDF report of the analysis.

## Running the Code

To run the notebook, follow these steps:
1. Ensure you have a Python environment set up with the necessary libraries installed. You can use the following command to install the required libraries:

```bash
pip install pandas seaborn matplotlib scipy scikit-learn numpy
```

2. Open the Jupyter notebook and run the cells to reproduce the analysis.

## Summary of Findings

- Age and BMI were found to have significant linear relationships with insurance charges.
- Smoking status was a major predictor of higher insurance charges.
- The multiple linear regression model explained about 78.3% of the variability in insurance charges, compared to 12.4% by the simple linear regression model.
- Residual plots indicated some non-linearity and heteroscedasticity, suggesting the need for further model refinement.

## Future Work

- Investigate non-linear models or transformations to improve model fit.
- Explore additional predictors or interaction terms.
- Conduct further analysis to address potential outliers and influential points.

## Contact

For any questions or feedback, please contact Brandon Mocco at Bmocc92@yahoo.com.

---

This README provides a comprehensive overview of the analysis and how to reproduce the results. Feel free to reach out if you have any questions or suggestions!
