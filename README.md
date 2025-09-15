# Machine-Learning-Project-Regression-Analysis-and-Model-Selection

This project involves building and evaluating regression models using a real-world dataset, focusing on improving model accuracy, preventing overfitting, and selecting optimal models. Both linear and nonlinear regression techniques, along with feature selection and regularization methods, are implemented to achieve these objectives.

## Project Overview

The objective of this project is to:
- Build a series of regression models using a dataset.
- Evaluate and compare model performance.
- Apply techniques such as feature selection, regularization, and hyperparameter tuning.
- Select the best-performing model.

This project can be completed in groups of up to two students.

## Dataset

### Dataset Source
[Cars Dataset on Kaggle](https://www.kaggle.com/datasets/ahmedwaelnasef/cars-dataset/data)

### Description
The dataset, scraped from the YallaMotors website, includes approximately 6,750 rows and 9 columns. It contains features such as:
- Car make, model, and year
- Mileage
- Engine size
- Price  

The goal is to predict car prices, making it suitable for regression analysis.

### Key Considerations
- **Exploratory Data Analysis (EDA):** Identify patterns, outliers, and relationships in the data to refine models.
- **Currency Standardization:** Convert car prices to a common currency (e.g., USD) for consistency in the target variable.

## Data Preprocessing Steps
- Handle missing values, encode categorical features, and normalize/standardize numerical features if required.
- Split the dataset into training, validation, and test sets (e.g., 60% training, 20% validation, 20% testing).

## Steps and Requirements

### 1. Building Regression Models

#### Linear Models:
- Linear Regression
- LASSO (L1 Regularization)
- Ridge Regression (L2 Regularization)
- Closed-form solution for Linear Regression (implemented without external libraries) and comparison with gradient descent.

#### Nonlinear Models:
- Polynomial Regression (polynomial degree: 2 to 10)
- Radial Basis Function (RBF) Kernel Regression

### 2. Model Selection Using Validation Set
Evaluate models using the validation set with metrics such as:
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R-squared  

Select the best model based on the lowest MSE or highest R-squared.

### 3. Feature Selection with Forward Selection
- Start with an empty model and iteratively add features that improve validation performance.
- Stop when additional features no longer improve performance or a maximum number of features is reached.

### 4. Applying Regularization Techniques
- **LASSO and Ridge Regression:**
  - Implement with varying regularization parameters (λ).
  - Use Grid Search to find the optimal λ value.

### 5. Hyperparameter Tuning with Grid Search
- Apply Grid Search to optimize hyperparameters for each model, ensuring improved performance.

### 6. Model Evaluation on Test Set
- Evaluate the selected model on the test set and report its generalization performance.

### 7. Optional Analysis
- Identify another target variable in the dataset and build a regression model to predict its values.

## Deliverables

### Comprehensive Report
The report includes:
- Dataset description, preprocessing steps, and features used.
- Details and performance of regression models on the validation set.
- Feature selection results using forward selection.
- Regularization results with optimal λ values.
- Final model evaluation on the test set.
- Visualizations: feature importance, error distribution, and predictions vs. actual values.

### Python Code
Code provided in `.py` format or a Jupyter Notebook with visualizations.



