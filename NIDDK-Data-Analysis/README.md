# NIDDK Data Analysis

## Overview
The `NIDDK-Data-Analysis` project is part of the `Data-analysis-projects` repository. It focuses on analyzing the **National Institute of Diabetes and Digestive and Kidney Diseases (NIDDK) dataset**, which contains medical data used to predict diabetes outcomes.

The project applies **exploratory data analysis (EDA), statistical tests, and machine learning models** to extract insights and improve predictive accuracy.

## Dataset
- **Source:** The dataset is fetched from IBM's cloud storage.
- **Features:** Various medical measurements such as Blood Pressure, BMI, Age, and Pregnancies.
- **Target Variable:** `Outcome` (1 = Diabetes, 0 = No Diabetes).

## Requirements
The analysis uses the following Python libraries:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn tqdm scipy
```

## Workflow
### 1. Data Loading & Exploration
- Reads the dataset into a Pandas DataFrame.
- Prints data shape and metadata.
- Checks for missing values.
- Generates summary statistics.

### 2. Data Visualization
- **Box plots & violin plots** for variable distribution across outcomes.
- **Correlation heatmap** to identify relationships between features.
- **Age distribution analysis** for diabetic patients.

### 3. Statistical Analysis
- **Pearson correlation coefficient** to measure relationships between variables.
- **P-value analysis** for statistical significance.

### 4. Machine Learning Models
#### Linear Regression
- Used to understand feature impact on the `Outcome` variable.

#### Polynomial Regression
- Explores higher-order relationships using different polynomial degrees.

#### Ridge Regression
- Applies L2 regularization to reduce overfitting.
- **Hyperparameter tuning** with cross-validation.

## Results & Insights
- Identifies key risk factors for diabetes prediction.
- Evaluates model performance using **R² score and Mean Squared Error (MSE)**.
- Determines optimal Ridge Regression hyperparameters for improved generalization.


## Future Improvements
- Feature engineering to improve model performance.
- Testing other machine learning algorithms (e.g., Random Forest, SVM).
- Implementing fairness-aware models to reduce bias in predictions.

---
### Author
This project is maintained as part of the `Data-analysis-projects` repository. Contributions and improvements are welcome!
