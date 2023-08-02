# Predicting Credit Default Using Decision Trees and Random Forests

## Overview

This repository contains the code and data for a project that aims to predict whether a borrower will meet their obligation of repaying their loan. The prediction will be based on various variables obtained from publicly available data from [LendingClub.com](www.lendingclub.com). Lending Club is a platform that connects borrowers with investors, and as an investor, it is essential to identify borrowers who have a high probability of paying back their loans.

The project will involve building classification models using decision trees and random forests to predict whether a borrower paid back their loan in full. The dataset used for training and testing the models covers lending data from 2007-2010 and has been cleaned to remove any missing values.

## Table of Contents

1. [Introduction](#introduction)
2. [Project Overview](#project-overview)
3. [Dataset](#dataset)
4. [Installation](#installation)
5. [Usage](#usage)
6. [File Descriptions](#file-descriptions)
7. [Model Evaluation](#model-evaluation)
8. [Results](#results)
9. [Conclusion](#conclusion)
10. [Contact Information](#contact-information)

## Introduction

The aim of this project is to create a predictive model that helps determine whether a borrower will repay their loan. The project will use decision trees and random forests, two popular machine learning algorithms, for classification tasks. By analyzing various borrower attributes, such as credit policy, purpose of the loan, interest rate, income, credit score, and more, we seek to build accurate models for credit default prediction.

## Project Overview

The project will utilize Python and popular data science libraries such as pandas, scikit-learn, and matplotlib. The data analysis process will involve data preprocessing, feature engineering, model training, and model evaluation. We will assess the model's performance using appropriate metrics and explore ways to improve its accuracy.

## Data Source

The data for this project comes from LendingClub.com and includes lending data from 2007-2010. You can download the dataset from [here](https://www.kaggle.com/code/faressayah/lending-club-loan-defaulters-prediction/input). However, we recommend using the provided cleaned CSV file to ensure consistency and avoid issues with missing values.

## Data Description

The dataset contains the following columns:
- credit.policy: 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.
- purpose: The purpose of the loan (values: "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business", and "all_other").
- int.rate: The interest rate of the loan, as a proportion (e.g., a rate of 11% would be stored as 0.11). Borrowers judged to be riskier are assigned higher interest rates.
- installment: The monthly installments owed by the borrower if the loan is funded.
- log.annual.inc: The natural log of the self-reported annual income of the borrower.
- dti: The debt-to-income ratio of the borrower (amount of debt divided by annual income).
- fico: The FICO credit score of the borrower.
- days.with.cr.line: The number of days the borrower has had a credit line.
- revol.bal: The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).
- revol.util: The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available).
- inq.last.6mths: The borrower's number of inquiries by creditors in the last 6 months.
- delinq.2yrs: The number of times the borrower had been 30+ days past due on a payment in the past 2 years.
- pub.rec: The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments).

## Dependencies

The project requires the following dependencies:

- Python 3.x
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Seaborn


## Installation

To run the code and reproduce the results, follow these installation steps:

1. Clone this repository to your local machine.
2. Install the required dependencies listed above using `pip`.
3. Download the cleaned dataset from the link provided in the repository or use the provided CSV file.

## Usage

The repository contains Jupyter notebooks that walk you through the entire data analysis and modeling process. You can execute the cells in the notebooks step-by-step to understand the code and analyze the results.

## File Descriptions

* `data.csv`: The cleaned dataset used for this project.
* `decision_trees.ipynb`: Jupyter notebook containing the decision tree model implementation and analysis.
* `random_forests.ipynb`: Jupyter notebook containing the random forest model implementation and analysis.

## Model Evaluation

The performance of the decision tree and random forest models will be evaluated using relevant metrics such as accuracy, precision, recall, and F1-score. Additionally, we will employ techniques like cross-validation to ensure unbiased assessment.

## Results

The project results and findings will be summarized in the Jupyter notebooks. Visualizations and performance metrics will be used to showcase the model's effectiveness in predicting credit default.

## Conclusion

In conclusion, this project demonstrates how decision trees and random forests can be utilized to predict credit default using various borrower attributes. The models' performance will provide valuable insights into identifying borrowers with a higher likelihood of loan repayment.

## Contact Information

For any inquiries or suggestions related to this project, you can reach out to the project owner:

**Jacktone Etemesi**  
Email: Jacktoneetemesi1@gmail.com

Feel free to explore the code and the findings presented in this repository. Happy analyzing!
