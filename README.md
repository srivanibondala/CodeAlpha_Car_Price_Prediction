# Car Price Prediction using Machine Learning

## Project Description

This project predicts the selling price of used cars using Machine Learning techniques. The dataset was cleaned, preprocessed, and analyzed using Python. Two regression models, Linear Regression and Random Forest Regression, were trained and evaluated. The Random Forest model achieved better prediction accuracy and was saved for future predictions.

---

## Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Correlation heatmap visualization
- Feature engineering
- Train-test data splitting
- Linear Regression model
- Random Forest Regression model
- Model performance evaluation
- Scatter plot comparison of Actual vs Predicted values
- Model saved using Pickle
- Predict selling price for new car data

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Pickle
- Jupyter Notebook / VS Code

---

## Dataset

The dataset contains information about used cars, including:

- Present Price
- Driven Kilometers
- Fuel Type
- Selling Type
- Transmission
- Owner
- Car Age
- Selling Price (Target Variable)

---

## Machine Learning Models

### Linear Regression
- R² Score: 0.8467
- MAE: 1.2219
- MSE: 3.5316

### Random Forest Regression
- R² Score: 0.9599
- MAE: 0.6364
- MSE: 0.9248

Random Forest Regression performed better than Linear Regression and was selected as the final model.

---

## Project Workflow

1. Import required libraries
2. Load the dataset
3. Explore and preprocess the data
4. Encode categorical variables
5. Perform Exploratory Data Analysis (EDA)
6. Create correlation heatmap
7. Split dataset into training and testing sets
8. Train Linear Regression model
9. Train Random Forest Regression model
10. Evaluate both models
11. Visualize Actual vs Predicted values
12. Save the trained Random Forest model using Pickle
13. Predict selling price for new car data

---

## Files Included

- `Car_Price_Prediction.ipynb` – Complete project notebook
- `car data.csv` – Dataset
- `car_price_model.pkl` – Saved Random Forest model
- `README.md` – Project documentation

---

## Sample Prediction

Example Input:

- Present Price: 8.5 Lakhs
- Driven KMs: 35000
- Fuel Type: Petrol
- Selling Type: Dealer
- Transmission: Manual
- Owner: 0
- Car Age: 5 Years

Predicted Selling Price:

**6.65 Lakhs**

---

## Conclusion

This project demonstrates the complete Machine Learning workflow for predicting used car prices. After comparing multiple regression algorithms, Random Forest Regression achieved the highest prediction accuracy with an R² score of approximately 96%, making it the best-performing model for this dataset.

---

## Author

**Srivani Bondala**