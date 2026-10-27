# Student Exam Score Prediction using Machine Learning

## Problem Statement
Predict a student's final exam score using study habits, attendance, family background and other factors.

## Dataset
Student Performance Factors (Kaggle) - 6,607 rows, 20 columns.
Target column: Exam_Score

## Steps Followed
1. Data Cleaning - filled missing values with the mode, removed duplicates, capped scores at 100
2. EDA - histograms, correlation heatmap, scatter plot and box plots
3. Feature Engineering - created Effort_Score (Hours_Studied x Attendance) and one-hot encoded text columns
4. Train-Test Split - 80% training, 20% testing
5. Modeling - Linear Regression and Random Forest
6. Evaluation - R2, MAE and RMSE

## Results
| Model | R2 | MAE | RMSE |
|---|---|---|---|
| Linear Regression | add value | add value | add value |
| Random Forest | add value | add value | add value |

## Key Findings
- Attendance and hours studied have the strongest effect on exam score.
- Add your own findings from the charts here.

## Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Google Colab