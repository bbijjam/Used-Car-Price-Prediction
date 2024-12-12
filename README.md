# Used Car Price Prediction

This project focuses on predicting the prices of used cars based on various features such as age, mileage, fuel type, and more. Leveraging data-driven insights, this project employs machine learning models to make accurate price predictions.

## Overview

Buying or selling a used car can be challenging without proper valuation. This project aims to simplify the process by building a machine learning model that predicts car prices based on historical data.

## Dataset

The dataset used in this project is sourced from CarDekho and includes information about various car features and their corresponding selling prices.

### Key Columns:
- **Car_Name**: Name of the car
- **Year**: Year of manufacture
- **Present_Price**: Current ex-showroom price
- **Selling_Price**: Price at which the car was sold
- **Fuel_Type**: Type of fuel used (Petrol/Diesel/Other)
- **Seller_Type**: Individual or Dealer
- **Transmission**: Manual or Automatic
- **Owner**: Number of previous owners

## Workflow

1. **Data Loading**: Importing the dataset for analysis.
2. **Data Exploration**: Initial checks and summary statistics.
3. **Data Cleaning**: Handling missing values and outliers.
4. **Feature Engineering**: Creating new features to enhance the dataset.
5. **Feature Scaling**: Standardizing features to ensure comparability.
6. **Encoding Categorical Features**: Converting categorical data into numeric format.
7. **Model Building**: Training machine learning models such as Linear Regression, Decision Trees, or Random Forest.
8. **Model Evaluation**: Measuring performance using metrics like R-squared, RMSE, etc.

## Models Used

- **Random Forest**

## Results

The project achieved significant accuracy in predicting car prices, demonstrating the effectiveness of the applied machine learning models. For detailed evaluation metrics, refer to the notebook.

## Requirements

To run this project, you need the following libraries:

- Python 3.7+
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Acknowledgments

This project is inspired by the CarDekho dataset and the challenges of accurately pricing used cars. Special thanks to Kaggle for providing a platform to work on meaningful datasets.

