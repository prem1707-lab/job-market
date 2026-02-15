# job-market
it consists of sample projects about data analytics and data science 
💼 Job Salary Prediction using Machine Learning

This project applies machine learning techniques to predict job salaries based on structured job posting data. The goal is to demonstrate a practical end-to-end ML workflow including preprocessing, feature engineering, model training, and evaluation.

The dataset contains job-level attributes such as role, category, company, location, experience requirements, and salary ranges.

📊 Dataset Overview

Each record represents a job posting, containing:

Job_ID – Unique job identifier

Job_Title – Role / designation

Job_Category – Functional area of the job

Location – Job location

Year – Posting year

Company – Hiring company

Experience_Required_Years – Experience requirement

Salary_Min_LPA – Minimum salary (LPA)

Salary_Max_LPA – Maximum salary (LPA)

Employment_Type – Full-time / Contract / etc.

🎯 Project Objective

The primary objective is:

Predict job salary using job attributes → Regression Problem

To create a stable target variable, the model predicts:

Salary_Avg_LPA = (Salary_Min_LPA + Salary_Max_LPA) / 2

🧠 Machine Learning Approach

The project implements a complete ML pipeline:

✔ Data type corrections
✔ Feature selection
✔ Categorical variable encoding (One-Hot Encoding)
✔ Train/Test split
✔ Model training & prediction
✔ Performance evaluation

⚙️ Preprocessing Strategy

Since ML models require numeric inputs:

Categorical variables are encoded using OneHotEncoder

Numerical variables are passed directly

Data leakage is avoided by excluding salary columns from features

🤖 Models Used
✅ Baseline Model

Linear Regression

🚀 Improved Model

Random Forest Regressor (better for non-linear relationships)

📈 Evaluation Metrics

Model performance is measured using:

MAE (Mean Absolute Error) – Prediction error magnitude

R² Score – Variance explained by the model

🛠️ Tech Stack

Python

Pandas – Data manipulation

Scikit-learn – ML pipeline & models

NumPy – Numerical computations

🔥 Key Learnings

✔ Handling mixed-type datasets
✔ Feature engineering for salary prediction
✔ Avoiding data leakage
✔ Building reusable ML pipelines
✔ Regression model evaluation
