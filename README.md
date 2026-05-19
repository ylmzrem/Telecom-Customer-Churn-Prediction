# Telecom Customer Churn Prediction

## Project Overview
This project aims to predict whether a telecom customer will churn (leave the service) based on their usage and contract information. Predicting customer churn helps telecom companies take proactive steps to retain valuable customers and optimize retention strategies.

## Dataset
* **Source:** [Telco Customer Churn (Kaggle)](#) https://www.kaggle.com/datasets/blastchar/telco-customer-churn
* **Type:** Binary Classification

## Repository Structure
To maintain a clean and reproducible environment, the repository is structured as follows:
* `notebooks/`: Contains the Jupyter notebook (`machine_project.ipynb`) for Exploratory Data Analysis (EDA), feature engineering, model training, and evaluation.
* `requirements.txt`: Lists all the necessary Python libraries required to run this project.
* `README.md`: Project documentation and reproduction instructions.

## Methodology & Models
The project follows a complete machine learning lifecycle. The following models were trained and evaluated:
* **Baseline Model:** Logistic Regression
* **Tree-Based Models:** Random Forest, Gradient Boosting (XGBoost/LightGBM)

Evaluation metrics include Accuracy, Precision, Recall, F1-Score, and ROC-AUC, with a specific focus on the confusion matrix to analyze false positives vs. false negatives.

## How to Reproduce Results
To run this project locally, please follow these steps:

1. Clone this repository:
   git clone [https://github.com/ylmzrem/Telecom-Customer-Churn-Prediction.git](https://github.com/ylmzrem/Telecom-Customer-Churn-Prediction.git)

2. Navigate to the project directory:
  cd Telecom-Customer-Churn-Prediction

3. Install the required dependencies:
  pip install -r requirements.txt

4. Run the Notebook:
  Open the machine_project.ipynb file located in the notebooks/ folder using Jupyter Notebook or Google Colab, and run the cells sequentially.
