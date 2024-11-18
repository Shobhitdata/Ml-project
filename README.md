# Price Prediction of Australian Real Estate Market

This project focuses on building a predictive model to estimate the prices of real estate in the Australian market. The analysis leverages **Ridge Regression** and **Lasso Regression** to improve prediction accuracy and tackle overfitting.

## Project Overview

The primary goal of this project is to use machine learning models to predict property prices based on various features such as location, size, and property type. The project involves data preprocessing, feature engineering, and model evaluation.

### Key Steps in the Project

#### 1. Data Preparation
- **Data Cleaning:** Handled missing values and outliers.
- **Feature Engineering:** Generated new variables to improve model performance.
- **Data Splitting:** Used `train_test_split` from `sklearn.model_selection` to divide the dataset into training and testing subsets.

#### 2. Model Building
- **Ridge Regression:**
  - Applied to mitigate multicollinearity by penalizing large coefficients.
  - Controlled the complexity of the model using regularization.
- **Lasso Regression:**
  - Used to perform both regularization and feature selection by shrinking coefficients to zero.

#### 3. Model Evaluation
- Metrics used to evaluate model performance:
  - Mean Squared Error (MSE)
  - R-squared value
- Compared performance between Ridge and Lasso Regression.

### Technology Used

- **Python:** For data preprocessing, model building, and evaluation.
- **Libraries:**
  - `pandas` and `numpy`: For data manipulation.
  - `sklearn.model_selection`: For splitting the dataset.
  - `sklearn.linear_model`: For Ridge and Lasso regression models.
  - `matplotlib` and `seaborn`: For data visualization.

### Insights and Findings

- **Feature Importance:** Lasso regression identified key features influencing real estate prices by reducing coefficients of less significant variables to zero.
- **Model Comparison:** Ridge regression performed better with higher predictive accuracy due to its ability to handle multicollinearity.
- **Market Trends:** The analysis revealed location and property size as primary factors driving real estate prices in Australia.

### Results

- Achieved high predictive accuracy with both Ridge and Lasso Regression.
- Demonstrated the importance of regularization techniques in improving model robustness and generalization.

### Future Scope

- Integrate advanced machine learning techniques like Gradient Boosting or Random Forest for better accuracy.
- Explore more diverse datasets to generalize findings to other real estate markets.

---

_Feel free to explore the codebase and experiment with the models!_
