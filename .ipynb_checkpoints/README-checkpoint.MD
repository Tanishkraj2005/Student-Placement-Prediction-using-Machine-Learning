🎓 Student Placement Prediction using Machine Learning

📌 Project Overview

This project focuses on predicting student placement status using supervised machine learning algorithms. The objective is to analyze academic performance and training-related attributes to determine the probability of a student getting placed.

The project compares multiple classification models and evaluates them using standard performance metrics to identify the most effective approach.

A research paper based on this work is also included in this repository.

Problem Statement
Educational institutions aim to improve placement outcomes by identifying key factors that influence student success. This project builds predictive models to:

Classify students as Placed or Not Placed
Analyze the impact of academic and training features
Compare multiple ML algorithms for performance

📊 Dataset Description

The dataset contains student-related attributes such as:

CGPA
Aptitude Test Score
Extracurricular Activities
Placement Training
Placement Status (Target Variable)
The target variable is binary:

1 → Placed
0 → Not Placed

Project Workflow

Data Loading and Cleaning
Missing Value Handling
Duplicate Removal
Categorical Encoding (Label Encoding)
Data Visualization and Correlation Analysis
Train-Test Split
Feature Scaling (StandardScaler)
Model Training and Evaluation
Model Comparison

🤖 Machine Learning Models Implemented

Logistic Regression
K-Nearest Neighbors (KNN)
Decision Tree
Random Forest
Naive Bayes

📈 Evaluation Metrics

Models were evaluated using:
Accuracy
Precision
Recall
F1 Score
Confusion Matrix
Classification Report

The best model was selected based on comparative performance.

📁 Repository Structure

placement_analysis.ipynb – Complete ML implementation
placementdata.csv – Dataset
research_paper.pdf – Research paper based on this project
requirements.txt – Required dependencies
README.md – Project documentation

How to Run

Clone the repository
Install dependencies:
pip install -r requirements.txt

Run the project:
python placement_prediction.py

Research Contribution

This project is supported by a research study that analyzes predictive modeling techniques for student placement classification and compares algorithmic performance in an academic context.

👤 Author

Tanishk Raj