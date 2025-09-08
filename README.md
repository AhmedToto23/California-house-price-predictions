Overview

This project, implemented in a Jupyter Notebook (Untitled4.ipynb), demonstrates a full data science workflow:

Data preprocessing and cleaning

Exploratory Data Analysis (EDA)

Building and evaluating a Linear Regression model

The goal is to understand relationships between variables and make predictions using regression techniques.

Dataset

The project works with a structured dataset (CSV format).

The dataset includes both numerical and categorical features.

Target variable: (replace with the column you predicted, e.g., adr, price, or sales)

Dataset path must be updated in the notebook before running.

Project Workflow

Import libraries
(pandas, numpy, matplotlib, seaborn, scikit-learn)

Load dataset
Read the CSV file into a pandas DataFrame.

Data Cleaning

Handle missing values

Remove duplicates

Fix data types

Exploratory Data Analysis (EDA)

Summary statistics

Distribution plots and correlations

Outlier detection with IQR and boxplots

Feature Engineering

Encode categorical variables

Scale numerical features

Model Building

Train/test split

Build a Linear Regression model

Train the model on the dataset

Model Evaluation

Evaluate using metrics such as R² score, MSE, RMSE, MAE

Plot predicted vs actual values

Requirements

Install the following Python packages:

pip install pandas numpy matplotlib seaborn scikit-learn

How to Run

Clone or download this repository.

Open the notebook:

jupyter notebook Untitled4.ipynb


Run all cells in order to reproduce preprocessing, analysis, and model training.

Results

A cleaned dataset ready for machine learning

Visual analysis of feature relationships

A trained Linear Regression model with evaluation metrics

Future Work

Try more advanced regression models (Ridge, Lasso, Random Forest Regressor)

Perform hyperparameter tuning

Deploy the model with a simple API or web app
