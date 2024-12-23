# Student Grades Prediction - V2

This project analyzes historical student performance data data to predict grade class using Linear Regression. The objective is to predict the grade of students based on specific data and get insights based on this data. This second version uses scikit-learn to perform the prediction.

## Algorithms

**Dataset Analysis**
- For ouliers: Tukey's Fences and Z-Score.
- For column analysis: Low Variance and High correlation
**Prediction**
- Linear Regression: Lasso, Ridge, and Elastic Net
- Polynomial degree two and three for the three methods
- Neural Network Model for Regression
- Gradient Boosting Model for Regression
**Evaluation**
- Performance: Mean Squared Error
- Loss curve for Neural Network convergence

## Project Structure

- **StudentPerformanceFactors.csv**: Contains the dataset used for training and testing the model. This databse is open-data from Kaggle.
- **Student_Performance_Prediction.ipynb**: Jupyter Notebook for data exploration, model training, and evaluation.

## Versioning

- **Version 1**: Initial prediction model, including data preprocessing, model training, and basic evaluation.
