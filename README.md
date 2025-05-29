🧠 Brain Stroke Detection System
A Machine Learning approach to save lives by predicting stroke risk early.


📘 Introduction
Stroke is a serious medical condition and a leading cause of long-term disability and death worldwide. Early prediction and timely intervention can significantly reduce its impact. This project uses machine learning to predict the probability of a stroke using patient health data, helping healthcare professionals take preventive actions.

🧪 Technologies Used
Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)

Jupyter Notebook

Machine Learning Algorithms (Random Forest, Logistic Regression, XGBoost, etc.)

Visualization Tools

Exploratory Data Analysis (EDA)

📂 Dataset Description
We use the publicly available Stroke Prediction Dataset from Kaggle.

Feature	Description
age	Patient’s age
hypertension	0: No, 1: Yes
heart_disease	0: No, 1: Yes
avg_glucose_level	Average glucose level in blood
bmi	Body Mass Index
smoking_status	never smoked / formerly / smokes
stroke	Target variable: 0 (No) / 1 (Yes)

📊 Exploratory Data Analysis (EDA)
Visuals make insights clearer. Here are some examples:

🔹 Stroke Distribution by Age Group
Patients above 60 are more prone to strokes.


🔹 Correlation Heatmap
Understanding feature relationships.


🧠 Model Building
We used multiple classification models to predict stroke:

✔️ Logistic Regression

✔️ Random Forest Classifier

✔️ XGBoost

✔️ Decision Tree

After tuning and evaluation, XGBoost gave the best performance.

📈 Model Performance

| Model               | Accuracy | Precision | Recall | F1 Score |
| ------------------- | -------- | --------- | ------ | -------- |
| Logistic Regression | 91%      | 0.89      | 0.85   | 0.87     |
| Random Forest       | 94%      | 0.91      | 0.90   | 0.90     |
| XGBoost             | 96%      | 0.94      | 0.93   | 0.94     |
