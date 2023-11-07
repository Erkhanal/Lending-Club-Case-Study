# Lending Club Case Study
Lending club case study using Exploratory Data Analysis (EDA)

## Table of Contents
* Introduction
* Background
* Problem Statement
* Objectives
* Data Overview
* Analysis Approach 
* Conclusion
* Recommendations
* Technologies Used
* Acknowledgements and References

## Introduction:  
<div align="justify">The consumer finance industry is highly competitive, and lending companies face various challenges. Identifying risky loan applicants and minimizing credit losses are major concerns for lending companies. Lending club case study aims to help a consumer finance company understand and mitigate the risk of loan defaults. We will use Exploratory Data Analysis (EDA) to gain insights into the factors that influence loan default. The main goal is to provide recommendations and suggestions to reduce credit losses and enhance the portfolio.</div>

## Background:  
<div align="justify">Lending Club is a consumer finance online marketplace that connects borrowers with investors. The company specializes in offering a wide range of loans to urban customers, business loans, including personal loans, and financing for medical procedures. The company operates as the largest online loan marketplace, offering lower interest rates through a convenient online interface. Their main business concern is minimizing credit losses caused by loans given to risky applicants who may default on payments.</div>

## Problem Statement:  
<div align="justify">For lending companies, the largest source of financial loss is credit loss, which occurs when borrowers unable to pay or default on their loans. To reduce credit losses, the company aims to identify risky loan applicants. By utilizing EDA technique, the company intends to understand the driving factors or driver variables behind loan default, which are strong indicators of potential credit losses.

The company receives various loan applications and must make decisions on whether to approve or reject these applications. Two primary risks are associated with this decision:

Risk of Not Approving the Loan:<br>
If an applicant is likely to repay the loan, but not approving the loan results in a loss of business for the company.

Risk of Default:<br>
If an applicant is not likely to repay the loan (i.e., likely to default), approving the loan can lead to a financial loss for the company.</div>

## Objectives:  
<div align="justify">The goal of this case study is to identify risky loan applicants by using exploratory data analysis (EDA). Our primary objective is to identify key leading indicators or driver variables in the dataset that contribute to loan defaults. The main target is to help in decision making of approval or rejection of loan applications to reduce credit loss by using EDA techniques to find driving factors which are strong indicators defaulting of loan. This knowledge can then be applied to portfolio management, risk assessment, and strategic decision-making.</div>

## Data Overview: 
<div align="justify">The provided dataset contains complete loan data for all loans issued between 2007 and 2011. It includes information about loan applicants and the outcome of their loans, specifically whether they defaulted or not. The key data attributes include:</div>

Loan Attributes:<br> 
Information related to the loan itself, such as loan amount, interest rate, term, grade, loan date and loan status etc.
Consumer Attributes:<br> 
Information about the loan applicants, including home ownership , employment length, state, and annual income etc.


## Analysis Approach:  
<div align="justify">To tackle this problem effectively, I have established a structured data analysis approach.

- Data Preprocessing:<br> 
It includes cleaning and preparing the data for analysis, handling missing values, encoding categorical variables, dropping unnecessary columns and standardizing data.

- Exploratory Data Analysis (EDA):<br>  Exploring the dataset to identify patterns, trends, and relationships in the dataset. This will involve univariate, bivariate, and multivariate analysis.

- Visualizations:<br>  It includes creating visual representations of the data to facilitate a better understanding of the insights, trends and relationship.

- Feature Importance:<br>  Identifying key variables that strongly influence loan default using statistical method Exploratory Data Analysis (EDA).

- Insights and Recommendations:<br>  Summarizing the findings and providing recommendations to the company based on the analysis.</div>

## Conclusion:  
<div align="justify">The key factors which can be used for predicting default and minimizing credit losses in lending include grades, Debt-to-Income ratio (DTI), verification status, annual income, and public record bankruptcies. Additionally, borrowers with over a decade of work experience, lower annual incomes, a history of public-recorded bankruptcies,high Debt-to-Income ratios, lower grades (E, F, G), and those located in non-urban regions are more likely to default on their loans.</div>

## Recommendations:  
To minimize credit losses and improve lending practices, it is recommended to:

- Focus on borrowers with lower DTI ratios, as they tend to have a lower risk of default<br>
- Prioritize borrowers with higher grades, as they are less likely to default<br>
- Exercise caution when lending to borrowers with over a decade of work experience<br>
- Pay special attention to borrowers with lower credit grades (E, F, G) due to their increased risk<br>
- Evaluate loans in non-urban regions more carefully<br>
- Be cautious when dealing with borrowers who have a history of public-record bankruptcies.

## Technologies Used:
- Python, version 3 for EDA
- NumPy for numerical computations
- Matplotlib and Seaborn for data visualization
- Pandas for data manipulation
- Jupyter Notebook for interactive analysis

## Acknowledgements:
- I acknowledge and appreciate the valuable course materials from upGrad and IIIT-B which enhanced my understanding of data analysis and EDA
## References:
- Python documentations
- Exploratory Data Analysis
- Stack Overflow

## Contact:
Created by https://github.com/Erkhanal - feel free to contact!
