# Data_Mining_Semi_Supervised-
🧠 Data Mining Project — Credit Card Fraud Detection


📌 Overview

This project applies Data Mining and Machine Learning techniques to detect fraudulent credit card transactions.
It analyzes real transaction data (creditcard.csv) and uses various algorithms to identify anomalies or suspicious behavior.

The Jupyter Notebook DataMining.ipynb contains the entire workflow — from data preprocessing to model evaluation.

⚙️ Installation & Setup

Clone the repository:

git clone https://github.com/<your-username>/<repository-name>.git
cd <repository-name>

Install dependencies:

pip install -r requirements.txt

(If not available, install manually: pandas, numpy, matplotlib, seaborn, scikit-learn, imbalanced-learn, jupyter)

Open the notebook:

jupyter notebook DataMining.ipynb

🧩 Features

Data cleaning and preprocessing

Exploratory data analysis (EDA)

Handling class imbalance using SMOTE

Model training and testing using:

Logistic Regression

Random Forest

Decision Tree

XGBoost (optional)

Model evaluation using accuracy, precision, recall, F1-score, and confusion matrix

📊 Dataset Information

File: creditcard.csv

Contains credit card transactions made by European cardholders in September 2013.

Includes 284,807 transactions, with 492 fraud cases (highly imbalanced).

Features are anonymized (V1, V2, ..., V28) plus Amount and Class (target variable).


🚀 How It Works

Load and explore the dataset.

Perform data cleaning and normalization.

Handle class imbalance using oversampling.

Train multiple models and compare their performance.

Visualize results with confusion matrix and ROC curve.



📈 Results

The models achieved high accuracy, but recall and precision are the most important metrics due to class imbalance.

The Random Forest Classifier performed best in balancing recall and precision.

