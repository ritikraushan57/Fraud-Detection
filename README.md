💳 Credit Card Fraud Detection

  This project aims to detect fraudulent credit card transactions using exploratory data analysis (EDA) and Logistic Regression. The dataset is highly imbalanced, with        frauds being a tiny minority, so i use proper preprocessing and metric evaluation (Recall, F1-score) to ensure accuracy in the real world.

🧠 Skills Applied

   Exploratory Data Analysis (EDA)

   Feature Engineering

   Logistic Regression 

   Model Evaluation (Recall, Precision, F1)

📁 Dataset Info(https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
  
  Rows: 284,807 transactions

  Columns: 30 features (V1–V28, Amount, Time, Class)

  Target Variable: Class → 1 = Fraud, 0 = Not Fraud

🚀 Steps Performed

  1. Data Preprocessing
  
  Normalized Amount using StandardScaler

  Extracted Hour from Time

  Dropped unused columns (Time, Amount)

  2. Exploratory Data Analysis
  
  Count of fraud vs non-fraud cases

  Time-based trends in fraudulent activity

  Amount distribution by class

  3. Model Building
     
  Split dataset (70/30)

  Trained Logistic Regression

  Made predictions + probability scores

  4. Evaluation
     
  Confusion Matrix

  ROC-AUC Score

  Classification Report
  (Precision, Recall, F1-score)

  📊 Visualizations Included
  Fraud vs Non-Fraud Count Plot

  Amount Distribution by Class

  Hourly Transaction Density

  ROC Curve

  📈 Why Focus on Recall & F1-Score?
  
  In fraud detection:

  Recall = How many real frauds we actually caught

  F1-Score = Balance between false alarms and missed frauds

  These metrics are more important than accuracy, especially with imbalanced data.


