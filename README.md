# Student Performance Prediction Project

## Overview
This project applies machine learning techniques to predict student performance (pass/fail) based on a dataset of 395 students and 33 features. The aim is to identify key factors that contribute to academic success and provide insights that could be useful in educational settings.

## Dataset
The dataset, sourced from Kaggle, includes a variety of features related to student demographics, academic history, family background, and personal habits. Key attributes include:
- Student grades
- Study time
- Family support
- Extracurricular activities
- Health status
- Absenteeism

## Models
We use three different machine learning models to predict student performance:
- **K-Nearest Neighbors (KNN):** A non-parametric method used for classification and regression.
- **Random Forest Classifier:** An ensemble learning method for classification, regression, and other tasks.
- **Logistic Regression:** A statistical model that in its basic form uses a logistic function to model a binary dependent variable.

## Features
The project involves several key stages in the data analysis process:
- **Exploratory Data Analysis (EDA):** We conduct a comprehensive examination of the dataset to understand its characteristics and uncover any underlying patterns or anomalies.
- **Feature Selection:** Utilizing the Random Forest importance ranking, we identify the most impactful features that influence student performance.
- **Hyperparameter Tuning:** We fine-tune the models to achieve the best possible performance.

## Model Evaluation
Each model is rigorously evaluated based on several metrics:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

A comparison is drawn to highlight the strengths and limitations of each model.

## Conclusions
The project concludes with insights into the effectiveness of machine learning in predicting student outcomes. The Random Forest model, in particular, shows a high degree of accuracy and reliability.

## Repository Structure
- `README.md`: Project overview and information.
- `student-mat.csv`: Dataset containing student performance data.
- `Code.ipynb`: Jupyter Notebook with all the code for model development, analysis, and evaluation.
- `Report.pdf`: Comprehensive report including detailed analysis, outputs, model evaluation metrics, and visualizations.
