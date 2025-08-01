# Credit_Score_classification

![Credit_Score_classification-Examples-1024x430](https://images.app.goo.gl/zd4Yzrj9hHYcpQoH7)
Tools used🛠: Python, Machine Learning, Scikit-learn, Plotly

# 🎯Objective
The goal is to build a machine learning model to classify a person’s credit score into categories like Poor, Standard, or Good, based on multiple financial, behavioral, and demographic features.

# 💡 Why We Use It
Credit score classification is crucial in the finance and banking sector to evaluate the risk profile of a customer. It is used in:

-Loan approval processes

-Credit limit decisions

-Financial advisory systems

-Personalized investment recommendations

This model helps financial institutions assess creditworthiness using behavioral patterns like income, debt, payment delays, number of loans, and more.

# ✅ Step-by-step Approach
### 📥 Imported required libraries such as NumPy, Pandas, Plotly, and Scikit-learn.

### 🧹 Cleaned the dataset by checking for missing values and exploring class distributions of credit scores.

### 🔍 Exploratory Data Analysis (EDA):

Explored impact of features like Occupation, Annual Income, Monthly Inhand Salary, Bank Accounts, Credit Cards, etc., on credit scores using plotly.express.box visualizations.

-Identified key patterns like:

-Higher income → better credit score

-Too many loans or credit cards → negative impact

-Longer credit history → better score

-Timely payments → positive credit profile

### 🧠 Feature Engineering:

Converted the categorical feature Credit_Mix into numeric values for model compatibility.

### 📊 Model Training:

Used Random Forest Classifier from Scikit-learn to build a credit score prediction model.

Split the dataset into training and testing using train_test_split.

### 🧪 Model Testing:

Took real-time input for features like income, loans, delays, and used the trained model to predict the credit score category.

# Output
