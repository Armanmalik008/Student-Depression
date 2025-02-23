# Student-Depression
# Students Depression Prediction using Machine Learning Approach

![WebApp](https://github.com/sahasourav17/Student-Anxiety-and-Depression-Prediction/blob/main/images/outputsnapshot.png)
# Project Overview
Student depression is a growing concern that affects academic performance, social interactions, and overall well-being. This project aims to analyze various factors contributing to student depression using data analysis and machine learning techniques.

The project involves data cleaning, visualization, preprocessing, and predictive modeling to understand the patterns behind student mental health issues. By leveraging machine learning algorithms, we aim to predict depression risks and provide insights that can help students, educators, and mental health professionals.

# Dataset Description
The dataset consists of various features that reflect student behaviors, mental health indicators, and external influences. These features include:

Sleep Duration – The number of hours a student sleeps daily.
Gender – Encoded as Male (0) and Female (1) for analysis.
Suicidal Thoughts – Encoded as No (0) and Yes (1).
Family Mental Health History – Indicates if there is a family history of mental illness.
Academic Pressure – Measures the stress level related to academic performance.
Social Life & Support System – Captures whether a student has social support.
Lifestyle Habits – Includes exercise, diet, and other health-related factors.
Anxiety & Stress Levels – Self-reported stress and anxiety indicators.

# Project Workflow
1. Loading the Dataset
Import necessary libraries such as pandas, numpy, matplotlib, and seaborn.
Load the dataset into a Pandas DataFrame for further processing.
2. Data Cleaning & Preprocessing
To ensure high-quality analysis, we perform the following steps:

Data Cleaning
Checking for missing values and handling them appropriately.
Removing duplicate entries to prevent redundancy.
Renaming column names for better readability.
Data Encoding & Transformation
Gender Encoding: Male → 0, Female → 1
Suicidal Thoughts Encoding: No → 0, Yes → 1
Family Mental Health History Encoding: No → 0, Yes → 1
Scaling numerical data where necessary for better performance in machine learning models.

3. Data Visualization
Visualization helps in identifying patterns and relationships among different factors.

4. Machine Learning Models
We apply various machine learning techniques to predict whether a student is at risk of depression:

Model Selection
Logistic Regression – For binary classification of depression risk.
Random Forest Classifier – To capture complex relationships in the data.
Support Vector Machine (SVM) – For high-dimensional data classification.
Neural Networks (TensorFlow/Keras) – For deep learning-based predictions.

 ![WhatsApp Image 2025-02-24 at 00 23 35_61688417](https://github.com/user-attachments/assets/35115dab-df01-4ed5-837a-0fb6ca6bea68)
