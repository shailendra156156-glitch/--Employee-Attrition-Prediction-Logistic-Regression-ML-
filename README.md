Employee Attrition Prediction using Logistic Regression
📖 Introduction

Employee attrition, also known as employee turnover, is a key concern for HR departments. Predicting which employees are likely to leave an organization helps in reducing recruitment costs and improving retention strategies.

This project applies Logistic Regression to predict attrition using an HR dataset. It involves data preprocessing, exploratory data analysis (EDA), and model evaluation to uncover insights about employee turnover trends.

🎯 Objectives

Import and preprocess employee data.

Perform EDA to understand attrition patterns.

Build a Logistic Regression model to classify employees as "leaving" or "staying".

Evaluate model performance with multiple metrics.

Provide insights into the most significant features influencing attrition.

📂 Project Structure

predicting employee attrition using logistic reg.ipynb → Jupyter Notebook with preprocessing, modeling, and evaluation.

README.md → Documentation file (this file).

data/employee_attrition.csv (example) → HR dataset containing employee records.

📊 Dataset Description
Source: HR dataset (commonly IBM HR Analytics dataset or similar).

Format: CSV/Excel.

Attributes: Age, Gender, Job Role, Department, Salary, Education, Satisfaction, Overtime, Years at Company, etc.

Target Variable: Attrition (Yes/No).
Methodology

Data Loading

Import dataset into pandas DataFrame.

Data Preprocessing

Handle missing values.

Encode categorical variables (e.g., One-Hot Encoding, Label Encoding).

Scale numerical features if needed.

Exploratory Data Analysis (EDA)

Analyze attrition rates by age, salary, overtime, and job role.

Use visualizations (Matplotlib/Seaborn) to highlight trends.

Modeling

Train Logistic Regression model using scikit-learn.

Split data into training and test sets.

 Results & Insights  
- Cleaned dataset prepared for analysis.  
- Metadata rows removed for accurate processing.  
- Structured dataset enables:  
  - Player performance tracking.  
  - Match-level analysis.  
  - Statistical and ML-based modeling in the future.  

---

## 🛠️ Requirements  
- Python 3.x  
- Jupyter Notebook  
- pandas  

Evaluation

Use Accuracy, Precision, Recall, F1-score.
Confusion Matrix to visualize predictions.
ROC-AUC curve to evaluate classification performance.
