# Student Placement Prediction Using Logistic Regression

##  Project Overview

This project predicts whether a student is likely to be placed based on different academic, technical, and personal skill-related factors.

The project uses **Machine Learning** and specifically **Logistic Regression** to perform the placement prediction.

##  Dataset

The dataset contains student-related information such as:

- Age
- Gender
- Degree
- Branch
- CGPA
- Internships
- Projects
- Coding Skills
- Communication Skills
- Aptitude Test Score
- Soft Skills Rating
- Certifications
- Backlogs
- Placement Status

The dataset is used to train and evaluate the Logistic Regression model.

##  Machine Learning Model

The project uses:

**Logistic Regression**

The categorical data is converted into numerical form using **Label Encoding** before training the model.

The trained model is saved as:

`placement_model.pkl`

##  Project Workflow

```text
Dataset
   ↓
Data Preprocessing
   ↓
Label Encoding
   ↓
Exploratory Data Analysis
   ↓
Train-Test Split
   ↓
Logistic Regression
   ↓
Model Evaluation
   ↓
Placement Prediction
