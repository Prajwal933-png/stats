🌲 Decision Tree Classifier — Pima Indians Diabetes Dataset
🎯 Objective

The goal of this experiment is to predict whether a person has diabetes using a Decision Tree model trained on the Pima Indians Diabetes dataset.
By analyzing medical factors such as Glucose level, BMI, and Age, the study aims to understand how each attribute influences the likelihood of diabetes.
Both Entropy (Information Gain) and Gini Index metrics are employed to evaluate and compare the effectiveness of the classification model and identify the most informative feature.

📈 Dataset Overview

The diabetes.csv dataset includes health-related measurements of adult female Pima Indian patients (21 years or older).
Each record captures physiological attributes that may contribute to diabetes prediction.

Feature	Description
Pregnancies	Number of times the individual has been pregnant
Glucose	Plasma glucose level after a 2-hour oral glucose tolerance test
BloodPressure	Diastolic blood pressure (mm Hg)
SkinThickness	Thickness of the triceps skin fold (mm)
Insulin	2-hour serum insulin level (μU/ml)
BMI	Body Mass Index = weight(kg) / height²(m²)
DiabetesPedigreeFunction	Genetic likelihood of diabetes based on family history
Age	Patient’s age in years
Outcome	Target variable — 0 (Non-diabetic) or 1 (Diabetic)
🧠 Tools and Technologies Used
Library / Tool	Purpose
Python 3.x	Programming language used for data analysis
pandas	Handling, cleaning, and analyzing data
NumPy	Performing numerical and statistical computations
scikit-learn	Building and evaluating Decision Tree models
Matplotlib	Visualizing model structure and feature importance
Jupyter Notebook / Google Colab	Interactive environment for running and displaying results
⚙️ Methodology
1️⃣ Data Import and Preprocessing

The dataset is read into a pandas DataFrame and inspected for missing or inconsistent values.

Basic statistical summaries and correlations are explored to understand feature relationships.

2️⃣ Feature Selection

Independent variables: All columns except Outcome

Dependent variable: Outcome (represents diabetes status)

3️⃣ Data Splitting

The data is divided into training and test subsets to ensure fair evaluation.
The models are trained on the training data and validated using the test set.

5️⃣ Tree Visualization

The tree structures are plotted to show how features are used to split and classify data.

6️⃣ Manual Verification

Entropy, Information Gain, and Gini Index are manually calculated for the Glucose attribute to verify why it appears as the primary split in the decision tree.

📋 Results Summary
Criterion	Root Feature	Accuracy	Observation
Entropy	Glucose	~75%	Maximum information gain
Gini Index	Glucose	~75%	Lowest impurity (best split)

Key Findings:

Both entropy and Gini-based trees produced nearly identical accuracy and structure.

Glucose consistently emerged as the most informative feature, followed by BMI and Age.

The results confirm that glucose concentration is a strong indicator for predicting diabetes.

🧮 Core Mathematical Concepts
🔸 Entropy

A measure of randomness or impurity within a dataset:

🏁 Conclusion

In this experiment, a Decision Tree Classifier was successfully implemented to diagnose diabetes using health attributes.
Both Entropy and Gini criteria provided comparable outcomes, with Glucose emerging as the most influential predictor.

Through this exercise, we gained insights into:

The working of Decision Tree algorithms

The mathematical intuition behind Entropy, Information Gain, and Gini Index

How visualization aids in interpreting model decisions
4️⃣ Model Construction

Two Decision Tree models are built with different criteria:
