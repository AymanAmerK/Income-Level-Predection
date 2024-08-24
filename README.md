# Income Level Prediction

This project aims to predict income levels (above or below $50,000 annually) using various machine learning models. It follows the CRISP-DM (Cross-Industry Standard Process for Data Mining) methodology to analyze and process a dataset from the 1994 US Census database.

## Project Overview

The goal is to predict whether an individual's annual income exceeds $50,000 based on census data such as age, work class, education, and occupation. This analysis can provide insights into factors influencing income levels.

## Dataset

The dataset contains 32,561 rows and 15 columns, including:
- Numerical variables: age, capital gain, capital loss, hours per week
- Categorical variables: work class, education, marital status, occupation, relationship, race, sex, native country
- Target variable: income level (>50K or <=50K)

## Methodology

The project follows the CRISP-DM methodology:

1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Model Building
5. Testing and Evaluation
6. Deployment

## Models

Four different models were developed and compared:

1. Decision Tree (DT)
2. Random Forest (RF)
3. Neural Network (MLP type)
4. Logistic Regression (LR)

## Tools Used

- KNIME Analytics Platform

## Key Findings

- The Random Forest model performed best with 0.916 accuracy.
- The Decision Tree model had the lowest prediction results with 0.836 accuracy.
- Capital gain, relationship status, and marital status were the most important variables for prediction.


## Data Preprocessing

- Removed 'final weight' and 'education' columns
- Imputed missing string values with "Missing"
- Grouped native countries into "US" and "Non-US" categories
- Applied equal size sampling to balance the training data

