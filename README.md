# Lending Club Case Study: A Risk Analytics Approach

## Table of Contents
- [Lending Club Case Study: A Risk Analytics Approach](#lending-club-case-study-a-risk-analytics-approach)
  - [Table of Contents](#table-of-contents)
  - [General Information](#general-information)
  - [Conclusions](#conclusions)
  - [Technologies Used](#technologies-used)
  - [Acknowledgements](#acknowledgements)
  - [Contact](#contact)

## General Information
This project delves into the domain of risk analytics in banking and financial services, specifically focusing on understanding loan default patterns in a consumer finance company, Lending Club. The objective is to identify customer and loan attributes that strongly indicate default tendencies. By leveraging Exploratory Data Analysis (EDA) techniques, this analysis aims to assist the company in minimizing financial losses associated with risky loan applicants.

**Business Understanding:**
Lending Club, a leading online loan marketplace, faces the challenge of distinguishing between loan applicants likely to repay and those prone to default. Approving loans for defaulters results in financial loss, while rejecting loans from potential repayable customers leads to a loss of business. The dataset `loan.csv` along with `Data_Dictionary.xlsx` provided contains information about past loan applicants, their attributes, and whether they defaulted or not. The company seeks patterns and indicators within this data to make informed lending decisions, such as denying loans, reducing loan amounts, or charging higher interest rates to risky applicants.

**Data Understanding:**
The dataset covers loan data from the period 2007 to 2011, encompassing approved loans and their outcomes. There are three possible loan outcomes:
1. Fully Paid: Applicant has repaid the principal and interest rate.
2. Current: Applicant is in the process of paying installments and not labeled as a defaulter.
3. Charged-Off: Applicant has defaulted, failing to pay installments for an extended period.

## Conclusions

- **Loan Purpose:** Most loans are primarily taken for debt repayment, followed by loans for credit card repayment. This suggests that borrowers are leveraging Lending Club to manage existing financial obligations.

- **Loan Repayment:** A significant majority, accounting for 85.4% of the loans, are fully repaid, while the proportion of loans charged off is relatively lower. This demonstrates that Lending Club borrowers exhibit a strong repayment history.

- **Loan Trends:** Over the years, there is a noticeable increase in the number of loans being fully repaid. This indicates a growing trust and popularity in the Lending Club platform among borrowers.

- **Housing Status:** The majority of borrowers reside in rented houses or have mortgages. Housing status does not seem to be a significant factor affecting loan approval, which is advantageous for a wide range of potential borrowers.

- **Loan Term:** Borrowers who opt for a 60-month repayment schedule are more likely to experience charge-offs compared to those selecting a 36-month term. This suggests that shorter loan terms may be a safer choice for both borrowers and lenders.

- **Income Influence:** Borrowers with lower incomes exhibit a higher likelihood of being charged off. Risk of default decreases as payee annual income increases. This underscores the importance of considering income when assessing creditworthiness.

These conclusions provide valuable insights into the operations of Lending Club and can inform business strategies and lending practices to enhance risk management and customer satisfaction.

## Technologies Used
- **pandas -** Used for data manipulation and analysis, enabling efficient handling of the loan dataset.

- **numpy -** A package for scientific computing in Python, it is a math library for supercharging matrix operations.
  
- **matplotlib -** Employed for data visualization, aiding in the creation of insightful charts and graphs to represent patterns and trends in the data.

- **seaborn -** Utilized for statistical data visualization based on matplotlib, providing an aesthetically appealing and informative representation of the dataset's characteristics.

## Acknowledgements
- This project was inspired by real-world challenges faced by financial institutions and lending companies in minimizing loan defaults.
- This project was done as a part of a project for LJMU and IIIT Bangalore's Masters in Machine Learning & Artificial Intelligence program.

## Contact
Created by [@himanshuxd]
