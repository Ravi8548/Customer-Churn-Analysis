📘 Overview

Customer churn is a crucial metric in industries such as telecom, banking, and subscription-based services. It represents the number of customers who stop using a service over a specific period. Predicting churn helps companies implement strategies to retain customers and reduce revenue loss.

This project performs churn prediction using simulated big data to mimic real-world large datasets and applies Decision Tree and K-Nearest Neighbors (KNN) machine learning algorithms to classify churn behavior.

The project includes dataset simulation, preprocessing, EDA, model building, and performance comparison.

🎯 Objectives

A) To simulate a large telecom-style customer dataset for churn analysis.

B) To perform EDA to identify the factors contributing to churn.

C) To apply classification models Decision Tree and KNN.

D) To evaluate model accuracy and compare performance.

E) To demonstrate big data concepts through large-scale synthetic dataset generation.

🛠 Technologies Used
Technology / Library	Purpose
Python	Implementation
Pandas, NumPy	Data processing & simulation
Scikit-Learn	Machine Learning
Matplotlib, Seaborn	Visualizations
Jupyter Notebook	Research execution
GitHub	Version control
📂 Project Structure
customer-churn-analysis/
│
├── data/                        # Simulated dataset
├── notebooks/                   # EDA & ML model notebooks
├── src/                         # Processing & modeling scripts
├── results/                     # Graphs, confusion matrix, metrics
├── models/                      # Saved ML model files
├── README.md                    # Documentation
└── requirements.txt             # Required dependencies

📊 Dataset Description
Feature	Description
CustomerID	Unique Identifier
Gender	Male / Female
Age	Customer age
Tenure	Subscription duration
MonthlyCharges	Monthly fee
TotalCharges	Total amount billed
ContractType	Monthly / Yearly
PaymentMethod	UPI / Credit / Debit / Online
Churn	Yes / No (target variable)

Dataset generated using randomized large-scale simulation to resemble real telecom customer behavior.

📈 Exploratory Data Analysis (EDA)

Analysis performed:

Churn distribution visualization

Numerical attributes histogram

Correlation heatmap

Tenure vs Churn dependency

Monthly charges vs churn comparison

Outliers & missing value handling

Visual outputs included:

Bar charts

Heatmaps

Scatter plots

Pie charts

🧠 Machine Learning Models
A) Decision Tree

Rule-based learning model

Easy to interpret and visualize

Handles categorical features effectively

B) K-Nearest Neighbors (KNN)

Distance-based classification algorithm

Predicts similarity among customers

Works well in non-linear datasets

📐 Model Performance Evaluation
Model	Accuracy	F1-Score
Decision Tree	~ Higher Accuracy (Example: 82-88%)	
KNN	Depends on best K value	

Decision Tree performed better than KNN in classification performance.

▶️ How to Run the Project
# Clone the repository
git clone https://github.com/username/customer-churn-analysis.git

# Navigate to folder
cd customer-churn-analysis

# Install Dependencies
pip install -r requirements.txt

# Run Notebook
jupyter notebook

📍 Key Findings

Short-term contract users churn more frequently.

Higher churn among customers with expensive monthly plans.

Payment method and tenure strongly influence churn.

Decision Tree model gives better predictive performance than KNN.

🚀 Future Enhancements

Include Random Forest & XGBoost for model comparison

Build churn prediction dashboard using Streamlit

Deploy model API using Flask

Add feature selection optimization
