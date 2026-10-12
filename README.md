# Credit-Risk-Statistical-Learning
# Credit Risk Prediction: Parametric vs Non-Parametric Statistical Models

## Project Overview

This project is part of my MSc Artificial Intelligence coursework in Statistical Learning at Kabarak University.

The study investigates the suitability of parametric and non-parametric statistical models for predicting loan defaults among informal-sector borrowers.

Unlike traditional borrowers, informal-sector workers may experience irregular incomes, incomplete financial records, and complex relationships between financial characteristics and credit risk. These characteristics raise important questions about the assumptions underlying conventional statistical models.

The objective is to evaluate whether the assumptions of a parametric model are sufficiently violated to justify adopting a more flexible non-parametric approach.

## Research Objectives

1. Explore the distribution and characteristics of the credit risk dataset.
2. Develop and evaluate a parametric Logistic Regression model.
3. Test the validity of relevant parametric modeling assumptions.
4. Critically assess and justify the rejection of an unsuitable model.
5. Develop and evaluate a non-parametric Random Forest classifier.
6. Compare the models in terms of predictive performance, interpretability, robustness, generalization, and deployment suitability.

## Dataset

The project uses a synthetic credit risk dataset containing historical loan applicant characteristics.

**Predictor variables:**

- `Age` — Applicant's age in years
- `Monthly_Income` — Average reported monthly income
- `Income_Variance` — Income variability over six months
- `Loan_Amount` — Requested loan amount
- `Loan_Term` — Loan duration in months
- `Credit_History_Length` — Length of borrowing history in months
- `Previous_Defaults` — Number of previous defaults

**Target variable:**

`Default` — Binary classification outcome:
- `0` = Loan repaid
- `1` = Loan defaulted

The dataset is synthetic and is used for educational and statistical modeling purposes.

## Methodology

The analysis follows six stages:

### 1. Exploratory Data Analysis

Examine descriptive statistics, data distributions, skewness, outliers, relationships with loan defaults, and class imbalance.

### 2. Parametric Modeling

Fit a Logistic Regression model and interpret its coefficients, odds ratios, and predictive performance.

### 3. Assumption Diagnostics

Investigate linearity in the log-odds, multicollinearity, influential observations, and class separation to assess the validity of the parametric approach.

### 4. Model Rejection

Critically assess a candidate model and justify its rejection using statistical evidence, including the bias–variance tradeoff, interpretability, and model stability.

### 5. Non-Parametric Modeling

Train a Random Forest classifier to investigate whether a flexible model better captures complex and potentially non-linear relationships in the data.

### 6. Model Comparison and Recommendation

Compare model assumptions, predictive performance, interpretability, robustness, and practical deployment considerations before recommending a suitable approach.

## Tools and Technologies

- Python
- Google Colab
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Statsmodels (for statistical diagnostics, where applicable)

## Model Evaluation

The models will be evaluated using appropriate classification metrics, including:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion matrix

Given the potential imbalance between defaulted and repaid loans, evaluation will consider more than accuracy alone.

## Running the Project

1. Open the Jupyter notebook (`.ipynb`) in Google Colab.
2. Ensure that the dataset (`synthetic_credit_risk.csv`) is available in the repository.
3. Install any required Python dependencies.
4. Run the notebook cells sequentially to reproduce the analysis.

## Project Status

**In progress:** Exploratory analysis, model development, assumption diagnostics, and comparative evaluation.

Results and conclusions will be documented after completing the statistical analysis.

## Author

**Marice Ziana Otoyi**

MSc Artificial Intelligence  
Kabarak University

**Course:** Statistical Learning

## Academic Purpose

This repository documents coursework undertaken as part of the MSc Artificial Intelligence programme. The emphasis is on statistical reasoning, model assumption validation, empirical comparison, and evidence-based model selection rather than predictive accuracy alone.
