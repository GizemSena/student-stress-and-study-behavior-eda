📘 Student Stress and Study Behavior Analysis
📌 Project Overview

This project analyzes the relationship between students' study habits, lifestyle behaviors, and stress levels. The goal is to understand how factors such as study time, sleep, and social media usage impact academic performance and stress.

📂 Dataset Description

The dataset contains 100 observations with the following features:

id: Unique identifier for each student
study_hours: Daily study time (hours)
sleep_hours: Daily sleep duration (hours)
social_media_hours: Daily social media usage (hours)
exam_score: Exam performance score
stress_level: Stress category (target variable)

🎯 Objectives
Perform exploratory data analysis (EDA)
Identify relationships between study habits and performance
Analyze the impact of lifestyle factors on stress levels
Build a machine learning model to predict stress level

🧹 Data Preprocessing
Verified that there are no missing values
Identified numerical and categorical features
Encoded the stress_level column for modeling
Removed unnecessary columns (e.g., ID)

📊 Exploratory Data Analysis

The analysis focused on:

Distribution of study hours, sleep hours, and social media usage
Stress level distribution
Relationships between behavioral variables and exam performance

🔥 Key Findings from EDA
Increased study hours are positively correlated with higher exam scores
Higher social media usage is associated with lower academic performance
Reduced sleep duration is linked to higher stress levels
Balanced study, sleep, and screen time leads to better outcomes

🤖 Machine Learning Model
Model Used
Random Forest Classifier
Target Variable
stress_level
Features Used
Study hours
Sleep hours
Social media usage
Exam score
Steps Performed
Train-test split
Model training and evaluation
Evaluation Metrics
Accuracy score
Classification report (precision, recall, F1-score)

📊 Feature Importance

The most influential features for predicting stress level:

Sleep hours
Study hours
Social media usage
Exam score

🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

🚀 Future Improvements
Apply advanced models (XGBoost, LightGBM)
Perform hyperparameter tuning
Expand dataset size for better generalization
Add more lifestyle variables (diet, exercise, etc.)
Build a student performance tracking system

👩‍💻 Author

Gizem Sena Çengel
Computer Engineer
