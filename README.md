# Module12_challenge_FinTech

## Credit Risk Analysis 
 Technologies used 
 The following technologies are used in the credit risk project: 
 
* Python: A programming language used for data analysis and model implementation. 
*  Pandas: A data processing and analysis library used for reading and preprocessing citation data. 
*   NumPy: A library of mathematical operations on arrays used for various data calculations. 
*   Scikit-learn ( sklearn ): a machine learning library that provides tools for model training, evaluation and preprocessing. 
*   Imbalanced-learn: a library for handling unbalanced datasets used in resampling techniques.  
*   Jupyter Notebook: an interactive coding environment used to run project code and document analysis. 

## Procedures
In this challenge we will achieve:
1. Split the Data into Training and Testing Sets
2. Create a Logistic Regression Model with the Original Data
3. Predict a Logistic Regression Model with Resampled Training Data
With all the information provided we will be able to write a Credit Risk Analysis Report.

The Credit Report 
The purpose of this analysis is to evaluate the performance of logistic regression models in predicting credit risk. The dataset used contains information about loan applicants, including various features such as income, debt-to-income ratio, and credit history. The target variable is the loan_status, which indicates whether a loan is classified as high risk (1) or healthy (0).

Two versions of the logistic regression model are evaluated: one using the original data and another using resampled data. The resampling technique employed is RandomOverSampler from the imbalanced-learn library, which addresses the class imbalance issue in the dataset
 
## Summary
The credit risk analysis project utilizes Python as the programming language and various libraries such as Pandas, NumPy, scikit-learn, and imbalanced-learn. The analysis is conducted in a Jupyter Notebook environment, allowing for interactive coding and documentation. The project's purpose is to evaluate the performance of logistic regression models in predicting credit risk using the lending data provided. Detailed instructions are provided to replicate the analysis and generate a README.md file summarizing the project.
