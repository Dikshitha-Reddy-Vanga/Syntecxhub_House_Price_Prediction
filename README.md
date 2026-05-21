# House Price Prediction using Machine Learning

## Overview

This project focuses on predicting house prices using Machine Learning techniques. A Linear Regression model was developed using the Ames Housing Dataset to analyze various housing features and estimate sale prices accurately.

The project includes data preprocessing, exploratory data analysis, feature selection, model training, evaluation, and prediction.

---

## Dataset

Dataset Used: Ames Housing Dataset

The dataset contains various housing-related features such as:
- Overall Quality
- Living Area
- Garage Capacity
- Basement Area
- Number of Rooms
- Year Built
- Neighborhood
- Sale Price

Files Included:
- `AmesHousing.csv`
- `House_Price_Prediction.ipynb`
- `house_price_model.pkl`

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Joblib

---

## Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Cleaning
4. Exploratory Data Analysis
5. Feature Selection
6. Train-Test Split
7. Data Preprocessing
8. Linear Regression Model Training
9. Model Prediction
10. Model Evaluation using RMSE and R² Score
11. Coefficient Interpretation
12. Model Saving using Joblib

---

## Machine Learning Model

Algorithm Used:
- Linear Regression

Evaluation Metrics:
- RMSE (Root Mean Squared Error)
- R² Score

---

## Features Used

- Overall Qual
- Gr Liv Area
- Garage Cars
- Garage Area
- Total Bsmt SF
- 1st Flr SF
- Year Built
- Full Bath
- TotRms AbvGrd
- Neighborhood

---

## Output

The model predicts house prices based on housing features provided as input.

Example prediction is included in the notebook.

---

## Model File

The file `house_price_model.pkl` contains the trained machine learning model serialized using Joblib.

---

## Future Improvements

- Random Forest Regressor
- XGBoost Regressor
- Hyperparameter Tuning
- Streamlit Web Application Deployment
- Advanced Feature Engineering

---

## How to Run

1. Open the Jupyter Notebook:
   `House_Price_Prediction.ipynb`

2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn joblib

3. Run all the notebook cells sequentially

---

## Project Structure

```text
Syntecxhub_House_Price_Prediction/
│
├── AmesHousing.csv
├── house_price_model.pkl
├── House_Price_Prediction.ipynb
└── README.md

---

