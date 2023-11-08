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
- **Conclusion 1:** Through univariate and bivariate analysis, key variables strongly associated with loan defaults were identified. These variables include credit score, debt-to-income ratio, loan amount, and grade assigned to the applicant. Applicants with lower credit scores and higher debt-to-income ratios are more likely to default, indicating these variables as crucial indicators of default risk.

- **Conclusion 2:** Time-based analysis revealed fluctuations in default rates over different years, highlighting the need for periodic risk assessment. Additionally, loan term length also influences default rates, with longer-term loans exhibiting higher default tendencies.

- **Conclusion 3:** Visualizations, such as heatmaps and bar charts, were utilized to showcase relationships between various attributes and default rates. These visualizations offer valuable insights into the factors influencing loan defaults and assist in making data-driven lending decisions.

## Technologies Used
- **pandas -** Used for data manipulation and analysis, enabling efficient handling of the loan dataset.

- **numpy -** A package for scientific computing in Python, it is a math library for super charging matrix operations.
  
- **matplotlib -** Employed for data visualization, aiding in the creation of insightful charts and graphs to represent patterns and trends in the data.

- **seaborn -** Utilized for statistical data visualization based on matplotlib, providing an aesthetically appealing and informative representation of the dataset's characteristics.

## Acknowledgements
- This project was inspired by real-world challenges faced by financial institutions and lending companies in minimizing loan defaults.
- This project was done as a part of project for IIIT Bangalore's Executive Post Graduate Programme in Machine Learning & Artificial Intelligence.

## Contact
Created by [@himanshuxd] 
