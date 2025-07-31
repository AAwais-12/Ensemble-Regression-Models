# Ensemble-Regression-Models
This project implements and compares multiple regression models—including individual and ensemble techniques—to solve a supervised learning problem using a real-world dataset. 
ensemble-regression-models

It focuses on model building, training, evaluation, and performance comparison of various regression approaches, including Random Forest, Gradient Boosted Trees, and Stacking.
📌 Project Overview
The goal of this project is to explore the performance of both individual and ensemble regression models on a structured dataset. Implemented in a Jupyter Notebook, the lab demonstrates practical applications of ensemble learning by comparing prediction accuracy across different methods.
🎯 Objectives and Goals
Construct and evaluate two individual regression models.
Build and compare three ensemble models: Random Forest, Gradient Boosted Trees, and Stacking Regressor.
Visualize model performance using scatter plots and residual error metrics.
Interpret the effectiveness of ensemble learning for regression tasks.
🧠 Machine Learning Problem
This is a supervised regression problem, where the task is to predict a continuous target variable based on several input features. The dataset is split into training and testing sets to evaluate generalization performance.
🧪 Models Implemented
Individual Models
Linear Regression
Decision Tree Regressor
Ensemble Models
Random Forest Regressor
Gradient Boosted Decision Trees (GBDT)
Stacking Regressor
🛠️ Methodology
Data Preparation
Load dataset into a Pandas DataFrame.
Preprocess features (e.g., handle missing values, normalize if necessary).
Create labeled examples.
Split into training and testing sets.
Model Training & Evaluation
Train each model on the training set.
Predict and evaluate using Mean Squared Error (MSE), R², and visual inspection.
Compare model performance.
Visualization
Use matplotlib and seaborn to plot:
Actual vs. Predicted values.
Residual plots.
Comparison bar charts across models.
📈 Results and Key Findings
Model	R² Score	MSE
Linear Regression	~0.62	~220.35
Decision Tree Regressor	~0.67	~201.78
Random Forest Regressor	~0.79	~148.64
Gradient Boosted Trees	~0.82	~132.59
Stacking Regressor	~0.83	~128.12
Ensemble models consistently outperformed individual models.
Gradient Boosted Trees and Stacking Regressor provided the best accuracy.
Visualizations helped diagnose overfitting and residual trends.
📊 Visualizations
Actual vs. Predicted scatter plots for each model.
Residual error plots.
Bar chart comparing model R² scores and MSEs.
All plots are included in the Jupyter Notebook.
