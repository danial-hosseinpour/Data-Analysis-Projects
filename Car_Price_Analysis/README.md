### Car Price Prediction Dashboard built with:
- Python for backend logic and machine learning workflows
- Plotly Express & Graph Objects for intuitive and interactive data visualizations
- Dash for developing a clean, responsive web interface
- Pandas & NumPy for data manipulation and exploratory analysis
- Scikit-learn for model training, evaluation, and prediction

---
# Car Price Prediction Dashboard
An interactive web application that enables users to visualize car market trends and predict used car prices based on user-defined inputs. Built using Python, Dash, and Scikit-learn, the app supports transparent model exploration and user-friendly interaction.

---
## Objective
The goal of this project is to explore the relationship between various car features and their resale value, and to build a machine learning model that accurately predicts car prices. Users can interact with visualizations and make real-time predictions through a dashboard.

---
## Visualizations

- Histogram of Car Prices
- Scatter plots: Engine Size vs Price, Mileage vs Price, etc.
- Boxplots: Car brands vs Prices
- Residual plot: visualizing errors
- Predicted vs Actual Prices

---
## Model & Workflow

1. **Data Preprocessing**
   - Cleaned missing values
   - Standardized categorical fields
   - Converted car names and models to consistent formats
   - Created new features like car age

2. **Exploratory Data Analysis**
   - Visualized relationships between price and fuel type, company, model year
   - Identified skewness and outliers

3. **Feature Engineering**
   - One-hot encoding for categorical variables
   - Extracted numerical features (e.g., engine capacity, mileage)

4. **Model Building**
   - Used **Linear Regression** for training
   - Splitting data into train/test (80/20)
   - Achieved decent R² score and minimal overfitting
     
---
## Prediction Example

Users can select:
- Fuel Type
- Company
- Year of Purchase
- Car Name

---

## License
This project is open-source and free to use under the MIT License.
   
