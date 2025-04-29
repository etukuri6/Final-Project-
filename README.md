MSc Data Science Final Project
Module: 7PAM2002
Department: Physics, Astronomy and Mathematics
University: University of Hertfordshire

Project Title
Multi-Class Classification of Hepatitis C Stages Using Machine Learning Models: XGBoost, Random Forest, and Logistic Regression

Student Details
Name: Naveen Etukuri
Student Registration Number: 23017408
Supervisor: Dr. Souradeep Bhattacharya
Date Submitted: 29 April 2025
Word Count: 5000
GitHub Repository: https://github.com/etukuri6/Final-Project-

Project Overview
This project aims to classify Hepatitis C disease progression stages using supervised machine learning models—specifically XGBoost, Random Forest, and Logistic Regression. Using a clinical dataset with 615 samples and 13 biochemical and demographic features, patients were classified into five categories: Blood Donor, Suspect Donor, Hepatitis, Fibrosis, and Cirrhosis. The primary objective was to assess each model's classification performance and identify the most influential features for diagnosis.

Research Objectives
To preprocess and clean clinical data for machine learning model input.

To train and evaluate Logistic Regression, Random Forest, and XGBoost classifiers.

To address class imbalance using SMOTE.
To optimize models using Grid Search.

To assess model performance using precision, recall, accuracy, and F1-score.

To apply SHAP for model interpretability.

To verify ethical compliance, anonymization, and open data licensing.

Dataset Information
Source: UCI Machine Learning Repository / Kaggle
Dataset Name: Hepatitis C Virus (HCV) for Egyptian Blood Donors
Features: Age, Sex, ALB, ALP, ALT, AST, BIL, CHE, CHOL, CREA, GGT, PROT
Target Variable: Disease stage (encoded into 5 classes)
Classes: Blood Donor, Suspect Donor, Hepatitis, Fibrosis, Cirrhosis
Number of Records: 615
License: Open access under public research terms

System Requirements
Python 3.8 or higher

Jupyter Notebook or Google Colab environment

Required Python Libraries:

pandas

numpy

matplotlib

seaborn
scikit-learn

imblearn

xgboost

shap

Running the Project
Execution Steps:

Clone or download the repository from GitHub.

Open the notebook file HepatitisC_Classification_Project.ipynb.

Ensure the dataset HepatitisCdata.csv is present in the working directory.

Run each cell sequentially to process data, train models, and generate evaluation metrics and plots.

Results, including confusion matrices, feature importance plots, and SHAP summaries, will be displayed in the notebook output.

Project Files
HepatitisC_Classification_Project.ipynb: Complete implementation

HepatitisCdata.csv: Dataset used in the project

final_project_report.pdf: Final academic report submitted for assessment
Ethical Considerations
The dataset is publicly available and anonymised.

No personally identifiable data is included.

Usage complies with GDPR and University of Hertfordshire research ethics.

No human subjects were contacted, and no social media or external data scraping was involved.

Source verification confirms data usage rights under open public license.

Academic Integrity
This project complies with the academic integrity policy of the University of Hertfordshire. All references are appropriately cited, and the work presented is original and completed independently.
