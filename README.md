# Placement Salary Prediction

## Overview

This project aims to predict the placement salaries of students based on various features such as academic performance, personal details, and other relevant attributes. The goal is to build multiple machine learning models and evaluate their performance in terms of accuracy and generalization ability.

## Data Understanding

The dataset contains features that represent student profiles, including:
- **Academic Scores**: Marks and grades from various examinations.
- **Personal Information**: Gender, degree type, specialization, etc.
- **Placement Details**: Whether the student was placed and the salary offered.

### Data Preprocessing

The preprocessing steps involve:
- **Handling Missing Values**: Ensuring that no null values interfere with the model training.
- **Encoding Categorical Variables**: Converting categorical data into numerical form using one-hot encoding.
- **Feature Scaling**: Standardizing or normalizing features to bring all data to a comparable scale.

## Models Used

The project experiments with several machine learning models to predict placement salaries:

1. **Linear Regression**
2. **Support Vector Regression (SVR)**
3. **Decision Tree Regressor**
4. **Random Forest Regressor**
5. **Gradient Boosting Regressor**
6. **Ridge Regression**
7. **Lasso Regression**

### Evaluation Metrics

The models were assessed using the following metrics:
- **Mean Squared Error (MSE)**: To measure the average squared differences between the predicted and actual salaries.
- **Mean Absolute Error (MAE)**: To capture the average magnitude of errors.
- **R2 Score**: To understand the proportion of variance in the dependent variable explained by the model.

### Visualizations

The project includes visualizations comparing predicted and actual salaries for each model, providing insights into the model's accuracy and reliability.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/IZU-ON/PLacement_predictions/tree/main
