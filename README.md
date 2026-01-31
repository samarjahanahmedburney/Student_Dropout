🎓 Student Dropout Prediction System
📌 Project Overview

This project predicts the risk of student dropout using Machine Learning.
The system helps teachers and advisors identify high-risk students early so they can take preventive actions.

The model classifies students into Low, Medium, or High risk categories and predicts whether a student is likely to drop out.

🧹 Data Cleaning & Preprocessing

The following steps were used to clean the data:

Missing numerical values were filled using the mean of the column

Missing categorical values were filled with "Unknown"

Irrelevant columns were removed

Features were scaled using StandardScaler

All preprocessing and model steps were combined into a single pipeline

📊 Features Used

The model uses the following student features:

Attendance percentage

Academic grades

Participation score

Previous academic performance

Other relevant student-related factors

(Exact features depend on the dataset)

🤖 Model Used

Algorithm: Random Forest Classifier

Reason:

Works well with tabular data

Handles non-linear relationships

Provides feature importance for explainability

📈 Model Evaluation

The model was evaluated using:

Accuracy

Precision

Recall

F1-Score

These metrics help measure how well the model predicts student dropout.

⚠️ Risk Score & Thresholds

The model outputs a risk score between 0 and 1.

Risk levels are defined as:

Low Risk: 0.00 – 0.33

Medium Risk: 0.34 – 0.66

High Risk: 0.67 – 1.00

Students with higher scores have a higher probability of dropping out.

🔍 Key Reasons for Dropout Prediction

Based on feature importance, the main factors behind dropout predictions are:

Low attendance

Poor academic performance

Low participation level

These factors strongly influence student success.

✅ Conclusion

This project demonstrates how Machine Learning can be used in education to predict student dropout risk and support early intervention strategies.
