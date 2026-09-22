Student Performance Analytics & AI-Based Final Grade Prediction
AICTE | IBM SkillsBuild Data Analytics with AI Internship 2026
Project Information

Student: ABHINAV KUMAR
Institute: Bansal Institute of Science and Technology, Bhopal
Organization: BharatCares
Internship: AICTE | IBM SkillsBuild Data Analytics with AI Internship 2026
Project Type: Data Analytics & Machine Learning
Programming Language: Python

1. Project Overview

This project analyzes student academic-performance data using Data Analytics, Data Visualization, Machine Learning, and AI-assisted interpretation techniques.

The project uses the Student Performance Dataset from the UCI Machine Learning Repository.

The main objective is to explore factors associated with students' final grades and develop machine-learning regression models that estimate the final grade (G3).

The project follows a complete analytics workflow:

Data collection

Data inspection

Data-quality checking

Exploratory Data Analysis (EDA)

Data visualization

Correlation analysis

Data preprocessing

Machine-learning model training

Model evaluation

Feature-importance analysis

AI-assisted interpretation

2. Dataset
Dataset Name

Student Performance Dataset

Dataset Source

UCI Machine Learning Repository:

https://archive.ics.uci.edu/dataset/320/student+performance

Dataset DOI

https://doi.org/10.24432/C5TG7T

The dataset contains demographic, social, school-related, and academic information about students.

The target variable used in this project is:

G3


G3 represents the final grade.

3. Project Objectives

The main objectives are:

Analyze student-performance data.

Identify patterns and relationships in the data.

Visualize important academic and student-related variables.

Study correlations with final grade.

Prepare data for machine learning.

Train multiple regression models.

Evaluate model performance using standard metrics.

Analyze Random Forest feature importance.

Generate AI-assisted analytical insights.

Produce a reproducible Data Analytics project.

4. Technologies Used

The project is developed using Python.

Libraries

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Ucimlrepo

Development Environment

Jupyter Notebook

Google Colab

5. Machine-Learning Models

The following regression algorithms are implemented:

Linear Regression

Used as a baseline regression model.

Decision Tree Regression

A tree-based regression algorithm that learns decision rules from the data.

Random Forest Regression

An ensemble method that combines multiple decision trees.

Gradient Boosting Regression

An ensemble method that builds models sequentially to improve prediction performance.

6. Model Evaluation

The models are evaluated using:

MAE — Mean Absolute Error

Measures the average absolute difference between actual and predicted values.

Lower values indicate smaller average errors.

RMSE — Root Mean Squared Error

Measures prediction error while giving greater influence to larger errors.

Lower values indicate smaller errors.

R² Score

Measures the proportion of variation in the target explained by the model relative to a baseline.

Higher values indicate stronger performance on the evaluated test set.

The actual evaluation values are generated automatically when the notebook is executed.

7. Machine-Learning Design

The final grade G3 is used as the target variable.

For the primary prediction experiment, G1 and G2 are excluded because they are previous-period grades and are strongly related to the final grade.

This design allows the project to investigate prediction using other student-related information rather than directly relying on previous grades.

The dataset is divided into:

80% training data

20% testing data

A fixed random state of 42 is used for reproducibility.

8. Data Preprocessing

Numerical variables are processed using:

Median imputation

Standard scaling

Categorical variables are processed using:

Most-frequent-value imputation

One-hot encoding

The preprocessing operations are included inside the machine-learning pipeline.

9. Exploratory Data Analysis

The project performs analysis of:

Final-grade distribution

Study time

Previous grades

Absences

Gender

Internet access

Numerical correlations

The project generates visualizations including:

Histograms

Box plots

Scatter plots

Correlation heatmaps

Model-comparison charts

Actual-vs-predicted plots

Feature-importance charts

10. AI-Assisted Analytics

The notebook contains an AI-assisted interpretation section that summarizes important analytical results.

It identifies:

Strong numerical associations

Model evaluation results

Important Random Forest features

Prediction performance

Analytical limitations

The AI-assisted interpretation is used to make technical findings easier to understand.

It does not replace statistical analysis.

11. Project Structure

The final project contains:

student-performance-analytics-ai/
│
├── ABHINAVKUMAR_StudentPerformanceAnalytics.ipynb
├── requirements.txt
├── ABHINAVKUMAR_ProjectReport.docx
└── README.md

12. Installation

Clone or download the repository.

Then install the required Python packages:

pip install -r requirements.txt

13. Running the Project
Option 1 — Google Colab

Open the .ipynb file in Google Colab and run:

Runtime → Run all

The notebook downloads the dataset through the ucimlrepo package.

Option 2 — Jupyter Notebook

Install the dependencies:

pip install -r requirements.txt


Then open the notebook:

jupyter notebook


Open:

ABHINAVKUMAR_StudentPerformanceAnalytics.ipynb


and run all cells.

14. Expected Output

After successful execution, the notebook produces:

Dataset information

Missing-value analysis

Duplicate-record analysis

Descriptive statistics

Exploratory visualizations

Correlation analysis

Machine-learning model results

MAE values

RMSE values

R² scores

Actual-vs-predicted visualization

Random Forest feature importance

AI-assisted interpretation

Final project summary

The exact numerical results are generated by the notebook from the dataset.

15. Important Notes

The project findings describe patterns in the selected dataset.

Correlation does not establish causation.

Machine-learning predictions are estimates and should not be treated as definitive judgments about an individual student's academic ability.

The dataset should not automatically be assumed to represent every student population or educational institution.

Any real-world deployment involving student information should follow appropriate privacy and data-protection requirements.

16. Project Limitations

Some limitations of the project are:

The analysis is based on the available UCI dataset.

The dataset may not represent all educational populations.

Statistical association does not prove causation.

Machine-learning performance depends on the available features and data.

The model requires additional validation before being used in a different educational environment.

G1 and G2 are excluded from the primary prediction experiment.

17. Future Scope

Future improvements may include:

Hyperparameter optimization

Cross-validation

Additional machine-learning algorithms

Explainable AI

Interactive dashboards

Larger and more diverse datasets

Longitudinal student records

Student-performance classification

Model deployment

Automated monitoring

18. Internship Details

Program: AICTE | IBM SkillsBuild Data Analytics with AI Internship Program 2026

Organization: BharatCares

Duration: 17 August 2026 – 30 September 2026

Mode: Online

Focus: Data Analytics with AI: Foundation to Implementation

Trainer: Mr. Kartik Hooda

19. Student Details

Name: ABHINAV KUMAR

Institute: Bansal Institute of Science and Technology, Bhopal

20. Project Files

The submission contains the following required files:

ABHINAVKUMAR_StudentPerformanceAnalytics.ipynb
requirements.txt
ABHINAVKUMAR_ProjectReport.docx
README.md

21. References

UCI Machine Learning Repository — Student Performance Dataset:

https://archive.ics.uci.edu/dataset/320/student+performance

Dataset DOI:

https://doi.org/10.24432/C5TG7T
