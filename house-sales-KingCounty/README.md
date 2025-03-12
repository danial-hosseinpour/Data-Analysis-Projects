# House Sales in King County - Data Analysis Project

This repository is part of the **Data-Analysis-Projects** collection and contains exploratory data analysis (EDA) and predictive modeling for the **House Sales in King County** dataset. The analysis is conducted using Python and popular data science libraries.

## Project Overview

The goal of this project is to analyze housing data from King County, USA, to:
- Clean and preprocess the dataset.
- Perform exploratory data analysis (EDA).
- Build predictive models using linear regression and polynomial regression.
- Evaluate model performance using metrics like R-squared and mean squared error (MSE).

## Dataset

The dataset used in this project is **kc_house_data_NaN.csv**, which includes housing information in King County, including the following features:
- Bedrooms
- Bathrooms
- Square footage (living space)
- Grade (construction and design quality)
- Price (target variable)

## Notebook Overview

The **House-Sales-KingCounty.ipynb** notebook is structured as follows:

1. **Data Loading & Cleaning**
   - Read CSV and handle missing values.
   - Data type conversion and basic inspection.

2. **Exploratory Data Analysis (EDA)**
   - Correlation analysis using Pearson's coefficient.
   - Visualizations: Box plots, bar charts, and regression plots.

3. **Model Building & Evaluation**
   - Linear Regression: Fit a baseline model and evaluate performance.
   - Polynomial Regression: Explore non-linear relationships using polynomial features.
   - Model comparison using R-squared and mean squared error (MSE).

## Key Findings

- **Square footage (living space)** and **grade** exhibit strong positive correlations with house prices.
- Polynomial regression (degree 3) provides better performance compared to simple linear regression.


## Results

Model evaluation metrics for linear regression and polynomial regression are computed:

- **Linear Regression**: Outputs R-squared and MSE.
- **Polynomial Regression**: Compares performance across polynomial degrees (2, 3, 4).

## Future Work

- Implement additional advanced models (e.g., Ridge/Lasso regression).
- Hyperparameter tuning using GridSearchCV.
- Further feature engineering and outlier detection.

## Contributing

Feel free to fork this repository and submit pull requests. Any suggestions for improving the analysis or code are welcome.

