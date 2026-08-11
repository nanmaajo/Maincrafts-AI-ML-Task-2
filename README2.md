# Maincrafts AI/ML Task 2 – House Price Prediction

## Project Overview

This project was completed as part of the Maincrafts Technology Artificial Intelligence & Machine Learning internship.

The task focuses on **Feature Engineering, Model Optimization & Performance Comparison** using the California Housing Dataset.

## Objective

The objective is to build an enhanced house price prediction system by:

- Preparing and scaling input features
- Training multiple regression models
- Evaluating model performance
- Comparing models using RMSE and R² score
- Selecting the best-performing model

## Dataset

The project uses the **California Housing Dataset** available through scikit-learn.

The dataset contains **20,640 observations** and **8 input features**, with `HousePrice` used as the target variable.

## Methodology

The workflow includes:

1. Loading the California Housing Dataset
2. Exploring the dataset using pandas
3. Separating features (`X`) and target (`y`)
4. Feature scaling using `StandardScaler`
5. Splitting the data into training and testing sets
6. Training three regression models
7. Evaluating the models using RMSE and R²
8. Comparing model performance
9. Selecting the best-performing model
10. Visualizing actual vs predicted house prices

## Models Used

### 1. Linear Regression
Used as the baseline regression model.

### 2. Ridge Regression
A regularized linear regression model used to help reduce overfitting.

### 3. Decision Tree Regressor
Used to capture non-linear relationships between the input features and house prices.

## Model Performance

| Model | RMSE | R² Score |
|---|---:|---:|
| Linear Regression | 0.745581 | 0.575788 |
| Ridge Regression | 0.745554 | 0.575819 |
| **Decision Tree** | **0.724234** | **0.599732** |

## Best Model

The **Decision Tree Regressor** achieved the best performance among the three models.

- **RMSE:** 0.724234
- **R² Score:** 0.599732

It was selected as the final model because it achieved both the **lowest RMSE** and **highest R² score**.

## Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Project Files

- `AI_ML_Task2_Model_Comparison.ipynb` – Complete Jupyter Notebook with code, outputs, model evaluation, and visualization
- `AI_ML_Task2_1-2_Page_Report.pdf` – Project report containing methodology, results, and conclusion

## Conclusion

The project demonstrates a complete machine learning workflow for house price prediction, including data preparation, feature scaling, model training, evaluation, comparison, and final model selection.
