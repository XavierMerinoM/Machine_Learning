# Student Pass Classification

This project analyzes historical student performance data to predict if a student will approve a class. The objective is to classify students based on specific data and get insights based on this data. This project uses scikit-learn to perform the prediction.

## Algorithms

**Dataset Analysis**
- For ouliers: Tukey's Fences and Z-Score.
- For column analysis: Low Variance and High correlation
  
**Prediction**
- Logistic Regression
  
**Evaluation**
- Confusion matrix
- Performance metrics: accuracy, precision, recall, specificity, and false positive rate.

## Project Structure

- **StudentPerformanceFactors.csv**: Contains the dataset used for training and testing the model. This databse is open-data from Kaggle.
- **Student_Performance_Prediction.ipynb**: Jupyter Notebook for data exploration, model training, and evaluation.

## Versioning

- **Version 1**: Initial prediction model, including data preprocessing, model training, and basic evaluation.
