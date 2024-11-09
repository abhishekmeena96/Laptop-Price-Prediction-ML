# Laptop Price Prediction 💻📈

This project uses machine learning regression algorithms to predict laptop prices based on various features. After testing multiple models, the **Random Forest Regressor** showed the best performance.

## Project Overview
The goal of this project is to predict laptop prices by utilizing different regression models. The best model, **Random Forest**, achieved an **R² score of 0.822** and an **MAE of 9204.19**.

## Data Preprocessing
- **Data Cleaning**: Removed inconsistencies and handled missing values.
- **Encoding Categorical Data**: Converted categorical columns (e.g., `Company`, `TypeName`, `Cpu brand`) to numerical values using **OneHotEncoder**.

## Feature Engineering
The following features were selected for modeling based on their relevance to laptop pricing:
- `Company`
- `TypeName`
- `Ram`
- `Weight`
- `Touchscreen`
- `IPS`
- `ppi`
- `Cpu brand`
- `HDD`
- `SSD`
- `Gpu brand`
- `OS`

## Model Selection and Evaluation
The following models were trained and evaluated for this project:

- **Linear Regression**: R² = 0.7178 | MAE = 12540.05
- **Ridge Regression**: R² = 0.7402 | MAE = 12095.87
- **Lasso Regression**: R² = 0.7178 | MAE = 12540.04
- **Decision Tree**: R² = 0.7604 | MAE = 10817.40
- **Support Vector Machine (SVM)**: R² = 0.5441 | MAE = 15316.62
- **Random Forest** 🔥: R² = 0.8222 | MAE = 9204.19
- **AdaBoost**: R² = 0.6282 | MAE = 15897.45
- **Gradient Boosting**: R² = 0.7864 | MAE = 9246.09
- **XGBoost**: R² = 0.7923 | MAE = 9333.93

## Results and Key Insights
The **Random Forest Regressor** emerged as the top-performing model with:
- **R² Score**: 0.822
- **MAE**: 9204.19

### Key Insights
- **Feature Selection**: Key features like `Company`, `Ram`, and `Cpu brand` significantly contributed to the model’s predictive accuracy.
- **Ensemble Methods**: The success of Random Forest and Gradient Boosting demonstrates the value of ensemble techniques in improving prediction accuracy for regression tasks.

Through this project, I enhanced my skills in feature engineering, model evaluation, and optimization for real-world predictive modeling.

