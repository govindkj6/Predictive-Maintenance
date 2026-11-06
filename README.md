Predictive Maintenance Using Machine Learning

Project Overview

This project focuses on predicting machine failures using machine learning classification algorithms. The objective is to identify potential machine failures based on operational parameters and improve maintenance planning.

Dataset

The dataset contains machine operating parameters such as:

Air Temperature

Process Temperature

Rotational Speed

Torque

Tool Wear

Machine Type

Target Variable: Machine Failure (0 = No Failure, 1 = Failure)

Methodology

Data Collection and Preprocessing

Data exploration and analysis

Missing value identification

Outlier analysis

Correlation analysis

Categorical variable encoding

Feature selection

Feature scaling

Model Development

The following machine learning algorithms were implemented:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

XGBoost Classifier

Model Evaluation

Models were evaluated using:

Accuracy

Precision

Recall

The performance of the models was compared using a visualization.

Technologies Used

Python

Jupyter Notebook

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

XGBoost

Repository Structure

Predictive-Maintenance/
│
├── Predictive Maintenance.ipynb
├── Failure data.csv
└── README.md

How to Run

Clone this repository.

Install the required Python libraries.

Open the Jupyter Notebook.

Ensure Failure data.csv is available in the working directory.

Run the notebook cells to train and evaluate the models.

Objective

To explore how machine learning can support predictive maintenance by identifying potential equipment failures and enabling more informed maintenance decisions.