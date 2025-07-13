---

🧠 Employee Attrition Prediction (ML Learning Project)

📌 Project Description

This project explores and models employee attrition using the IBM HR Analytics Employee Attrition dataset. The goal is to practice the full machine learning pipeline from data loading to model training and evaluation using Python libraries such as pandas, seaborn, and scikit-learn.

I’m currently in the process of learning machine learning, and this project is designed as a practical learning experience. It is structured step-by-step so I can easily expand it as I improve my skills.


---

✅ What Has Been Done So Far

1. Data Loading

Loaded CSV file into a Pandas DataFrame.

Explored basic structure using .head(), .info(), and .describe().


2. Exploratory Data Analysis (EDA)

Checked data types, value counts, and basic statistics.

Visualized target variable (Attrition) with countplots.

Plotted histograms of numeric features such as Age, MonthlyIncome, YearsAtCompany, etc.

Created boxplots to compare features across attrition classes.

Generated a heatmap to examine correlations between numeric features.

Found constant columns like EmployeeCount and StandardHours with no variance (and thus no correlation), which will be removed in the cleaning step.




---

🔧 Next Steps (Planned)

Step 3: Data Cleaning

Handle missing values.

Drop constant or irrelevant columns.

Encode categorical features using one-hot encoding.


Step 4: Model Training

Use logistic regression or decision trees with default hyperparameters.


Step 5: Model Evaluation

Evaluate performance with metrics like accuracy, precision, recall, F1-score.


Step 6: Improvements

Try other models and tune hyperparameters.

Add feature scaling and feature engineering.




---

📁 Dataset

IBM HR Analytics Employee Attrition & Performance (Kaggle)



---

🚀 Purpose

This project is not intended for production but as a learning tool to practice:

Exploratory data analysis

Data preprocessing

Model training and evaluation

Visualization and interpretation


It will continue to grow and improve as I learn more about machine learning and best practices in data science.
