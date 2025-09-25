Project : Heart Disease Prediction Using Machine Learning

1. Introduction

Heart disease is one of the leading causes of death worldwide. Early prediction of heart disease can help in taking preventive measures and timely treatment. With the advancement of data science and machine learning, it is now possible to analyze medical data and predict the chances of heart disease with good accuracy.

This project focuses on developing a machine learning-based system that predicts whether a person has heart disease based on medical attributes like age, sex, blood pressure, cholesterol level, etc.


---

2. Objectives

To analyze the Heart Disease dataset using exploratory data analysis (EDA).

To build a machine learning model that predicts the presence of heart disease.

To evaluate the model using accuracy and other metrics.

To deploy the model using Streamlit as an interactive web application.



---

3. Dataset

The dataset used is the UCI Heart Disease dataset. It contains 14 attributes which are:

age: Age of the patient (years)

sex: Gender (1 = male, 0 = female)

cp: Chest pain type (0–3)

trestbps: Resting blood pressure (mm Hg)

chol: Serum cholesterol (mg/dl)

fbs: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)

restecg: Resting ECG results (0–2)

thalach: Maximum heart rate achieved

exang: Exercise-induced angina (1 = yes, 0 = no)

oldpeak: ST depression induced by exercise

slope: Slope of the peak exercise ST segment (0–2)

ca: Number of major vessels (0–3)

thal: Thalassemia (1 = normal, 2 = fixed defect, 3 = reversible defect)

target: (1 = heart disease, 0 = no heart disease)



---

4. Methodology

Step 1: Data Preprocessing

Load dataset using Pandas.

Check for missing values.

Normalize/scale features if required.

Split data into training (80%) and testing (20%) sets.


Step 2: Model Training

Applied Logistic Regression as a baseline model.

Trained the model on the training dataset.

Saved the trained model using Joblib.


Step 3: Model Evaluation

Evaluated model on the test dataset.

Achieved an accuracy score of around 85%.

Other evaluation metrics like confusion matrix and precision-recall were analyzed.


Step 4: Deployment

Built an interactive Streamlit app.

Users can enter their medical details.

The app predicts whether the person has heart disease or not.



---

5. Technologies Used

Python – Programming language

Pandas, NumPy – Data manipulation

Scikit-learn – Machine learning library

Matplotlib, Seaborn – Data visualization

Joblib – Saving the trained model

Streamlit – Web app deployment

GitHub – Project hosting and version control



---

6. Results

Logistic Regression model achieved an accuracy of ~85% on test data.

Streamlit app successfully predicts heart disease in real-time based on user input.



---

7. Conclusion

This project demonstrates how machine learning can be effectively used in healthcare for predicting heart disease. The system can assist doctors and patients by providing quick predictions. Future improvements could include:

Using more advanced models (Random Forest, XGBoost, Neural Networks).

Adding more medical features for better accuracy.

Deploying the model on cloud platforms for wider accessibility.



---

8. References

UCI Machine Learning Repository: Heart Disease Dataset

Scikit-learn Documentation

Streamlit Documentation
