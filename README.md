# Osteoporosis-Prediction
Osteoporosis Prediction using Machine Learning

This project was developed as part of my Healthcare Data Science & AI Internship at Zion Tech Hub. The goal is to build a predictive model for osteoporosis risk, leveraging patient demographic, lifestyle, and clinical features.

📌 Project Overview

Osteoporosis is a condition characterized by weak and fragile bones, increasing the risk of fractures. Early prediction is vital for timely intervention. This project applies machine learning techniques to classify whether a patient is at risk of osteoporosis based on health and lifestyle data.

⚙️ Workflow

Data Preprocessing

Loaded dataset (osteoporosis.csv)
Handled missing values by filling with "Unknown" for categorical fields (e.g., Alcohol Consumption, Medications, Medical Conditions).
Encoded categorical features using:
Binary encoding (e.g., Family History, Smoking, Prior Fractures)
One-Hot Encoding for multi-class variables (e.g., Gender, Medications, Medical Conditions, Alcohol Consumption).

Exploratory Data Analysis (EDA)

Visualized data distributions (Age, Gender, Smoking habits, Alcohol consumption).
Count plots and histograms to explore patterns in risk factors.

Feature Engineering

Converted categorical variables into numerical representations.
Selected important predictors such as:
Age, Gender
Hormonal Changes, Family History
Body Weight, Physical Activity
Calcium & Vitamin D Intake
Smoking, Alcohol Consumption
Medications and Medical Conditions

Model Training

Split dataset into train/test sets (80/20).
Applied Logistic Regression as a baseline model.
Trained Random Forest Classifier, tuned with RandomizedSearchCV for hyperparameter optimization.

Evaluation

Metrics: Accuracy, Confusion Matrix, Classification Report (Precision, Recall, F1-score).
Tuned Random Forest achieved ~91% accuracy.

🛠️ Technologies Used

Python
Pandas, NumPy for data processing
Matplotlib, Seaborn for visualization
scikit-learn for model building and evaluation

🚀 Key Results

Logistic Regression provided a baseline classification.
Random Forest (with hyperparameter tuning) improved performance significantly.
Achieved 91%+ accuracy on test data.
