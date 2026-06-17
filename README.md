# Insurance Cost Prediction using Decision Tree Regression

## Project Overview

This project predicts medical insurance charges based on customer demographic and health-related information. A Decision Tree Regressor was used to model the relationship between various features and insurance costs.

## Problem Statement

Insurance companies need to estimate medical insurance charges based on customer characteristics. The goal of this project is to build a machine learning model that can accurately predict insurance costs using customer information.

## Dataset Features

The dataset contains the following features:

* Age
* Sex
* BMI
* Number of Children
* Smoker Status
* Region
* Insurance Charges (Target Variable)

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Decision Tree Regressor
* Pipeline
* ColumnTransformer
* StandardScaler
* OneHotEncoder

## Project Workflow

1. Data Loading
2. Data Exploration
3. Train-Test Split
4. Data Preprocessing
5. Feature Encoding and Scaling
6. Model Building using Decision Tree Regressor
7. Model Evaluation

## Data Preprocessing

* Numerical features were scaled using StandardScaler.
* Categorical features were encoded using OneHotEncoder.
* ColumnTransformer was used to combine preprocessing steps.
* Pipeline was used to streamline preprocessing and model training.

## Model Performance

| Metric                    | Score       |
| ------------------------- | ----------- |
| Train R² Score            | 0.8811      |
| Test R² Score             | 0.8334      |
| Mean Absolute Error (MAE) | 2911.16     |
| Mean Squared Error (MSE)  | 25857792.06 |

## Results

The model achieved a Test R² Score of 0.8334, indicating that it can explain approximately 83% of the variance in insurance charges. The relatively small gap between training and testing scores suggests that the model generalizes well to unseen data.

## Conclusion

The Decision Tree Regressor successfully captured nonlinear relationships between customer characteristics and insurance charges. This project demonstrates the complete machine learning workflow, including preprocessing, model training, and evaluation.

## Future Improvements

* Random Forest Regression
* Gradient Boosting Regression
* XGBoost Regression
* Hyperparameter Tuning
* Model Deployment using Flask or FastAPI