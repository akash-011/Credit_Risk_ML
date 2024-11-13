# Credit Risk Prediction Project

This repository contains a machine learning project focused on predicting loan default probabilities using a dataset from Kaggle. The goal of this project is to develop a credit risk model that helps identify high-risk borrowers, using techniques in data preprocessing, feature engineering, and predictive modeling.

## Project Overview

Credit risk modeling is a crucial tool for lenders to evaluate the likelihood of borrowers defaulting on loans. In this project, I applied XGBoost, a high-performance gradient boosting algorithm, to build a predictive model that estimates the probability of loan default. 

### Key Steps
1. **Data Preprocessing:** Cleaned and prepared the data, handling missing values and outliers to ensure quality input for the model.
2. **Feature Engineering:** Selected and engineered relevant features to improve model performance and interpretability.
3. **Model Training:** Utilized XGBoost due to its efficiency and effectiveness in handling large datasets with complex patterns.
4. **Evaluation:** Assessed model performance using appropriate metrics to gauge predictive accuracy and stability.

## Dataset

The dataset was sourced from [Kaggle's Credit Risk Dataset](https://www.kaggle.com/), which includes borrower characteristics, credit history, and loan information. The target variable indicates whether a borrower defaulted on a loan, enabling us to frame the problem as a binary classification task.

## Requirements

- Python 3.9.x
- Jupyter
- XGBoost
- Pandas
- Scikit-learn
- Matplotlib / Seaborn (for data visualization)

Install the dependencies via:

```bash
pip install -r requirements.txt
```

### Usage 

Open and run the notebook:

```bash
jupyter notebook main.ipynb
```

The notebook main.ipynb contains all steps of data exploration, model training, and evaluation, with detailed explanations and visualizations.

### Results 

The XGBoost model showed strong predictive capabilities, providing valuable insights into borrower risk levels. This model can serve as a basis for lenders to improve credit risk assessment and mitigate default risks.


