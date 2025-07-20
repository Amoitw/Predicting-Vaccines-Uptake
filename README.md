🧠 Project Title
![Vaccine short](./flu-vaccine.jpg).

# Who Gets Vaccinated? Machine Learning Predictions of H1N1 and Seasonal Flu Vaccine Uptake

📌 Overview
This project builds a machine learning model to predict the probability that individuals received the 2009 H1N1 and seasonal flu vaccines based on survey data. The solution is framed as a multi-label probabilistic classification task.

By understanding vaccine hesitancy patterns, public health institutions can better target at-risk populations and craft data-driven intervention strategies.

## Objectives
Predict likelihood of H1N1 and seasonal flu vaccination.

Profile vaccine-hesitant populations.

Enable targeted health messaging.

Support proactive policy-making in future pandemics.

 ## Stakeholders
Public Health Authorities (e.g., CDC, WHO)

Healthcare Providers & outreach programs

Researchers in epidemiology & behavioral science


## Tools & Technologies
Languages: Python

Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

Models: Logistic Regression, Random Forest, Grid Search, Feature Selection

Techniques: Preprocessing pipelines, One-Hot/Ordinal Encoding, ROC AUC, PR-F1 metrics


## Dataset
training_set_features.csv

training_set_labels.csv

test_set_features.csv

These datasets contain demographic, behavioral, and health-related survey data from 2009 related to vaccine uptake.
You can download the datsets from [datadriven.org](https://www.drivendata.org/competitions/66/flu-shot-learning/).


## Modeling Process
Data Cleaning & Preprocessing

Imputation of missing values

Encoding categorical features

Feature scaling

## Model Training & Evaluation

Logistic Regression & Random Forest

GridSearchCV for hyperparameter tuning

ROC AUC & PR-F1 as primary evaluation metrics

## Feature Selection

Used SelectFromModel to identify key predictors

## Prediction

Generated probabilistic outputs for each label

## Results
AUC and F1 scores used for model evaluation.

Key features identified influencing vaccine uptake.

Visualizations provided for feature importance and data distribution.

## Next Steps
Integrate model interpretability tools (e.g., SHAP, LIME).

Develop a web-based dashboard for real-time use.

Extend model to new datasets (e.g., COVID-19 hesitancy).

Incorporate ensemble or deep learning models for performance benchmarking.


## How to Run
# Clone the repo and install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook notebook.ipynb

## Acknowledgements
Thanks to the DrivenData H1N1 Vaccine Prediction competition for the dataset and problem framing.
