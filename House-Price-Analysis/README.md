### King County House Sales Price Prediction built With:

- **Python** for data manipulation and model development
- **Seaborn** & **Matplotlib** for rich data visualization and pattern discovery
- **Scikit-learn** for regression models, evaluation, preprocessing, and pipeline creation
- **NumPy** & **Pandas** for fast numerical computations and data wrangling
- **SciPy** for statistical significance testing
- **TQDM** for progress monitoring during iterations

---
# King County House Sales Price Prediction

This project explores and models the **housing prices in King County, USA** using machine learning techniques. It walks through **data cleaning**, **exploratory analysis**, **correlation investigation**, and **multiple regression models**, including **linear** and **polynomial regression**, to build a predictive pipeline.

---

## Exploratory Data Analysis

* **Null Handling**: Replaced missing `bedrooms` and `bathrooms` with their respective means
* **Correlation Analysis**:

  * Strongest correlations with `price`:

    * `sqft_living` (0.70)
    * `grade` (0.66)
    * `sqft_above` (0.60)
    * `bathrooms` (0.51)
  * Weak or no correlation: `zipcode`, `long`, `condition`
* **Visuals**:

  * `Boxplot`: Bathrooms vs Price
  * `Barplot`: Bedrooms vs Price
  * `Regplot`: Sqft Living vs Price
  * `Lineplot`: Grade vs Price

---

## Modeling

### 1. **Linear Regression**

* Achieved R² score: **0.697**
* Basic model with all features

### 2. **Polynomial Regression**

* Explored 2nd to 4th degree
* Best R² score: **0.79** (degree 3)

### 3. **Pipeline Optimization**

* Combined PolynomialFeatures (degree=3) + LinearRegression
* Final R² score: **0.7957**
* MSE: **23.77 billion**

---

## Key Takeaways

* `sqft_living`, `grade`, and `bathrooms` are highly predictive of house prices.
* Adding polynomial terms improved performance, but too high a degree caused overfitting.
* Pipeline approach streamlined the transformation and prediction process.

---

## Future Improvements

* Integrate Ridge/Lasso regularization to handle potential multicollinearity
* Explore tree-based models (e.g., Random Forest, XGBoost) for non-linear relationships
* Deploy a web app (e.g., using Streamlit or Dash) for user-friendly predictions

---

## License

This project is for educational purposes only. No commercial use allowed without permission.


