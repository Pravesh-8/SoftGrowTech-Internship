# Boston Housing Price Prediction

## Project Overview
This project focuses on predicting house prices using the Boston Housing dataset. The goal is to analyze different factors affecting housing prices and build a Linear Regression model to estimate the median value of homes based on relevant features.

The project includes data exploration, data preprocessing, feature analysis, and building a regression model for prediction.

---

## Dataset
This project uses the Boston Housing Dataset.

Features in the dataset include:

- CRIM – Per capita crime rate by town
- ZN – Proportion of residential land zoned for large lots
- INDUS – Proportion of non-retail business acres per town
- CHAS – Charles River dummy variable
- NOX – Nitric oxide concentration
- RM – Average number of rooms per dwelling
- AGE – Proportion of owner-occupied units built before 1940
- DIS – Distance to employment centres
- RAD – Index of accessibility to highways
- TAX – Property tax rate
- PTRATIO – Pupil-teacher ratio
- B – Proportion of Black population
- LSTAT – Percentage of lower status population
- MEDV – Median value of owner-occupied homes (Target Variable)

---

## Project Workflow

### 1. Data Understanding
The dataset was explored to understand the structure, features, and relationships between variables.

### 2. Data Cleaning
- Checked for missing values
- Handled missing values
- Verified data types

### 3. Exploratory Data Analysis (EDA)
Several visualizations were created to understand the data:

- Distribution plots
- Correlation heatmap
- Scatter plots between features and target variable
- Outlier detection using boxplots

Key observations:
- RM has a strong positive correlation with house prices
- LSTAT has a strong negative correlation with house prices

---

### 4. Feature Selection
Relevant features were selected based on correlation analysis and their impact on house prices.

---

### 5. Model Building
A Linear Regression model was built to predict house prices.

Steps:
- Split dataset into training and testing sets
- Trained the Linear Regression model
- Generated predictions on test data

---

### 6. Model Evaluation
The model performance was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

These metrics help measure the accuracy of the regression model.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Results
The Linear Regression model successfully captures the relationship between housing features and house prices. Features such as the number of rooms and the percentage of lower status population significantly influence housing prices.

---

## Future Improvements
Possible improvements to this project include:

- Using advanced regression models
- Feature engineering
- Hyperparameter tuning
- Trying models such as Random Forest or Gradient Boosting

---

## Conclusion
This project demonstrates how machine learning techniques can be used to analyze housing data and predict property prices. The insights obtained from exploratory data analysis and the regression model help understand key factors affecting housing values.

---

## Author
Pravesh Yadav
