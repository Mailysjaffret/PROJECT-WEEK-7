# PROJECT-WEEK-7 : Birth Weight Prediction

👥 The Team:
- Konstantin Leube
- Loredane Nery
- Mailys Jaffet
- Garima Sharma

# 🔍 Project Overview

This project aims to predict newborn birth weights using machine learning techniques by analyzing maternal health and medical data. The goal is to build an accurate model that can forecast birth weights, enabling early intervention and improved healthcare outcomes. This work highlights the versatility and importance of machine learning in the healthcare sector, showcasing its potential to reduce complications and enhance maternal and neonatal health.

# 🎯 Objective

Build a predictive model to estimate newborn birth weights using maternal health data, aiming to support early medical intervention and reduce complications.

# 🏗️ Project stucture

### Dataset used
- Dataset containing info surrounding the baby and the pregnancy
- Source: https://www.kaggle.com/c/birth-weight-prediction/data

### Data cleaning
- Replacing categorical columns with numerical values
- Dropping NaN-values

# 🛠️ Tools and Technologies used

- Data Handling and Analysis:
    - pandas : Data manipulation and analysis.
    - numpy : Numerical computations.

- Machine Learning:
  - scikit-learn:
    - Model selection: train_test_split for splitting data into training and testing sets.
    - Regression models: KNeighborsRegressor, LinearRegression, DecisionTreeRegressor, BaggingRegressor, RandomForestRegressor, AdaBoostRegressor, GradientBoostingRegressor.
  - Evaluation metrics: r2_score, mean_absolute_error, mean_squared_error.
  - Hyperparameter tuning: GridSearchCV for model optimization.

# 📊 Findings and Conclusions

- Key Features:
The Pregnancy Week variable had the highest correlation with the target variable, making it the most significant predictor of birth weight.

- Multicollinearity:
Features such as Age, Race, and Education of both Mother and Father showed high multicollinearity, as identified by elevated VIF scores. This suggests these variables are highly interrelated and could impact model performance.

- Model Performance:
Linear Regression struggled to capture non-linear relationships in the data, limiting its predictive accuracy.
Ensemble methods like Bagging and Random Forest provided better performance by reducing overfitting and increasing model robustness, proving to be more suitable for this complex dataset.


# 📦 Deliverables

- 📝 Jupyter Notebook:
Contains the complete code, data analysis, and model development process.
- 📑 Slide Deck:
A comprehensive presentation of the project findings and insights.
- 📄 README:
Detailed project documentation, including objectives, methodology, and results.







