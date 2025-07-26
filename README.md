# Car-Price-Prediction
Linear Regression project predicting car prices based on features


# Car Price Prediction using Linear Regression

This project demonstrates a simple and interpretable machine learning model using **Linear Regression** to predict the prices of used cars. It explores the relationship between key features like mileage, manufacturing year, fuel type, and others to estimate a car's selling price.

---

## Objective

To build and evaluate a Linear Regression model that predicts the resale price of a car using historical data and various vehicle attributes.

---

## Project Workflow

1. **Data Cleaning**
   - Removed duplicates and irrelevant columns
   - Handled categorical features with label encoding
   - Converted year to car age

2. **Exploratory Data Analysis (EDA)**
   - Visualized feature relationships using heatmaps and scatter plots
   - Analyzed price trends based on car brand, fuel type, and age

3. **Feature Engineering**
   - One-Hot Encoding for categorical variables
   - Created new features (like `Car Age`)

4. **Model Building**
   - Applied `LinearRegression()` from Scikit-learn
   - Trained on 80% data, tested on 20%

5. **Model Evaluation**
   - R² Score
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - RMSE (Root Mean Squared Error)

---

## Technologies Used

- **Python**
- **Pandas & NumPy** – Data cleaning and manipulation
- **Matplotlib & Seaborn** – Visualizations
- **Scikit-learn** – Machine Learning

---

## Results

The model gives reasonably accurate predictions with:
- Good **R² Score** on training and testing datasets
- Clear understanding of how each feature affects car price
- Visual analysis of predicted vs actual prices

---

