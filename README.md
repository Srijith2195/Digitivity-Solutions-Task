# Heart Disease Prediction Project

# About the Project
This project is about predicting whether a person has heart disease or not using machine learning.  
It is based on patient health data such as age, cholesterol, blood pressure, and other medical factors.

The idea is to understand how machine learning can be used in healthcare for early detection and better decision-making.

# Dataset
I used the Heart Disease dataset from Kaggle (UCI dataset) https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data

It contains different medical attributes of patients along with a column that indicates the presence of heart disease.

# Data Preprocessing
Before training the model, I performed some basic data cleaning steps:
- Replaced missing values (`?`) with proper values
- Converted all columns into numeric format
- Filled missing values using mean
- Created a new target column for prediction (0 = No disease, 1 = Disease)
- Removed unnecessary columns to avoid data leakage

# Exploratory Data Analysis
I created a few visualizations to understand the dataset better:
- A count plot to see how many people have heart disease
- A histogram to analyze how age affects heart disease
- A heatmap to check relationships between features

These helped me understand which features are important.

# Models Used
I used two machine learning models:

**1. Logistic Regression**
- Simple and easy to understand
- Used as a baseline model

**2. Random Forest**
- More powerful model
- Works better for complex data

# Model Training
- Split the data into training and testing sets (80/20)
- Applied feature scaling for better performance
- Trained both models using Scikit-learn

# Results
- Logistic Regression gave decent accuracy
- Random Forest performed better compared to Logistic Regression

# Future Improvements
- Try more advanced models like XGBoost
- Tune model parameters
- Use a larger dataset
- Build a web app for prediction

# Conclusion

This project demonstrates how machine learning can be used to predict heart disease based on patient data. Logistic Regression and Random Forest models were trained, with Random Forest giving better performance. The project highlights the importance of data cleaning, feature selection, and proper model evaluation. This approach can be useful in healthcare systems for early detection and decision support.