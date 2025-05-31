
# Linear, LASSO, Ridge & Elastic Net Regression Models

## Overview

This project demonstrates how to use various regression techniques — including **Linear Regression**, **LASSO**, **Ridge**, and **Elastic Net** — to model and predict **CO₂ emissions from vehicles** using a dataset of Canadian car specifications.

## Objective

To build predictive models for estimating car CO₂ emissions by exploring different regression approaches and evaluating their performance after applying data standardization techniques.

## Dataset

- **Source**: Canadian vehicle emissions dataset (specific source not listed).
- **Features**: Include various car specifications like engine size, fuel consumption, etc.
- **Target**: CO₂ emissions (g/km).

## Models Used

- **Linear Regression**: Baseline model.
- **LASSO Regression**: Adds L1 regularization to encourage sparsity.
- **Ridge Regression**: Adds L2 regularization to handle multicollinearity.
- **Elastic Net**: Combines L1 and L2 regularization.

## Workflow

1. **Data Preprocessing**:
   - Handling missing values
   - Feature scaling (standardization)
2. **Model Training**:
   - Split data into train and test sets
   - Train multiple regression models
3. **Model Evaluation**:
   - Metrics include RMSE, MAE, and R²
   - Comparison of performance across models


## License

This project is released under the MIT License.
