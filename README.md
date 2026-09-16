# B104_Artificial-Intelligence-Machine-Learning
## Project Overview

This repository contains an individual machine learning project focused on analysing telecom customer data and predicting customer churn.

The project explores customer characteristics, service usage, account information, and billing details to identify patterns associated with customer churn. Machine learning models are developed and evaluated to support customer retention decisions.

## Project Objectives

- Explore and understand the telecom customer churn dataset.
- Clean and preprocess the data for machine learning.
- Apply feature engineering and categorical encoding.
- Train and tune machine learning classification models.
- Evaluate model performance using suitable classification metrics.
- Discuss the practical implications, limitations, and possible future improvements.

## Dataset

The project uses a telecom customer churn dataset containing customer demographic, account, billing, and service-related information.

The dataset includes a churn outcome that indicates whether a customer has left the telecommunications service.

> Add the original dataset URL here if required by the assessment brief.

## Models Used

The project includes machine learning classification models such as:

- Logistic Regression
- Random Forest Classifier

Hyperparameter tuning is used where appropriate to improve model performance.

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Cross-validation performance

## Repository Structure

```text
Bl04 Artificial Intelligence & Machine
Learning/
│
├── 
│   └── telecom_customer_churn.csv
│
├── 
│   └── customer_churn_prediction.ipynb
│
├── 
│   └── customer_churn_prediction.html
│
├── README.md
└── .gitignore
```

## How to Run the Project

1. Download or clone this repository.
2. Install the required Python libraries.
3. Open the Jupyter Notebook.
4. Update the dataset path if necessary.
5. Run the notebook cells in sequence.
6. Review the visualisations, model results, and evaluation metrics.

## Required Python Libraries

The project may require the following libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

## Results

The notebook presents the exploratory data analysis, preprocessing steps, model training process, hyperparameter tuning, and final evaluation results.

The final model should be selected based on the evaluation results and the business purpose of identifying customers who may be at risk of leaving.

## Limitations

- The dataset represents a particular telecom customer population and may not generalise to all companies.
- Customer behaviour may change over time.
- Class imbalance may affect some evaluation metrics.
- The model identifies patterns and does not prove the causes of customer churn.

## Academic Note

This repository has been prepared for the DV835 individual machine learning project. All analysis, interpretations, and final conclusions should be reviewed and understood by the student before submission.
