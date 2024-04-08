Heart Disease Prediction Project

This project is aimed at predicting the likelihood of heart disease in patients based on various medical attributes. We will use machine learning techniques to develop models capable of making these predictions.

Problem Definition

Given clinical parameters about a patient, can we predict whether or not they have heart disease?

Data

The original dataset is from the Cleveland dataset from the UCI Machine Learning Repository and is also available on Kaggle. It contains various attributes such as age, sex, chest pain type, resting blood pressure, cholesterol level, and more.

Evaluation

Our goal is to achieve at least 95% accuracy in predicting heart disease during the proof of concept.

Features

Here are some of the features present in the dataset:

- age: Age of the patient (in years)
- sex: Gender of the patient (1=male, 0=female)
- cp: Chest pain type
- trestbps: Resting blood pressure (in mm Hg on admission to the hospital)
- chol: Serum cholesterol in mg/dl
- fbs: Fasting blood sugar > 120 mg/dl (1=true, 0=false)
- restecg: Resting electrocardiographic results
- thalach: Maximum heart rate achieved
- exang: Exercise induced angina (1=yes, 0=no)
- oldpeak: ST depression induced by exercise relative to rest
- slope: Slope of the peak exercise ST segment
- ca: Number of major vessels (0-3) colored by fluoroscopy
- thal: Thalassemia

Tools Used

We used various Python libraries for data analysis and modeling:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

Models Explored

We explored the following machine learning models:

1. Logistic Regression
2. K-Nearest Neighbors Classifier
3. Random Forest Classifier

Model Development Process

1. Data Exploration (EDA): We performed exploratory data analysis to understand the dataset's characteristics, identify correlations, and visualize relationships between variables.
2. Data Preprocessing: We checked for missing values, handled categorical variables, and prepared the data for modeling.
3. Model Building: We built initial models using Logistic Regression, KNN, and Random Forest classifiers.
4. Model Evaluation: We evaluated model performance using accuracy scores.
5. Model Comparison: We compared model performance to identify the most promising approach.

Next Steps

1. Hyperparameter Tuning: We performed hyperparameter tuning using RandomizedSearchCV to optimize model performance.
2. Model Interpretation: We analyzed feature importance to understand which attributes contribute most to heart disease prediction.
3. Final Model Selection: Based on evaluation metrics, we selected the best-performing model for deployment.
4. Further Improvements: We can explore additional feature engineering, ensemble methods, or deep learning techniques to enhance model accuracy.

Conclusion

This project demonstrates the application of machine learning in predicting heart disease based on patient attributes. The goal of achieving 95% accuracy serves as a benchmark for future improvements in model performance and healthcare applications.
