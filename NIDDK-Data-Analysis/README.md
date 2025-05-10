### Interactive Diabetes Data Exploration Dashboard built with: 
- **Python** for backend logic and data manipulation  
- **Pandas** & **NumPy** for efficient data processing and statistical analysis  
- **Matplotlib** & **Seaborn** for visualizations and trend analysis  
- **Scikit-Learn** for predictive modeling (Linear Regression, Ridge)  
- **PolynomialFeatures** & **StandardScaler** for feature transformations  
- **GridSearchCV** for hyperparameter tuning  

---

# NIDDK Diabetes Data Analysis

This project explores the **National Institute of Diabetes and Digestive and Kidney Diseases (NIDDK)** dataset, investigating factors that contribute to diabetes onset and applying machine learning models to predict diabetes outcomes.  

## Key Insights: 
- Glucose Levels Have the Strongest Correlation → Higher glucose readings significantly increase diabetes probability.  
- Age Plays a Role in Diabetes Prediction → Older individuals tend to have a higher likelihood of diabetes.  
- BMI & Diabetes Pedigree Function Influence Risk → Higher BMI and diabetes family history affect diabetes occurrence.  
- Polynomial Regression Struggles with Overfitting → Linear models outperform high-degree polynomial models for diabetes classification.  
- Ridge Regression Improves Stability → Regularization helps control feature importance and enhances prediction consistency.  

---

## Visualization Gallery 

- Boxplot: Glucose Levels & Diabetes Outcome
- Correlation Heatmap of Features
- Age Distribution for Individuals with Diabetes
- Performance of Different Regression Models

---

## Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn tqdm
```

---

## License 

This project is licensed under the MIT License.

