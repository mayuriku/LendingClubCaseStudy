# Lending Club  Case Study
> As an online lending marketplace, the company's goal is to:
> Identify borrowers who may be more likely to default on loans, in order to minimize financial losses and ensure responsible lending practices. Exploratory data analysis (EDA) can be used to analyze the driving factors behind loan defaults.
> Understand the key indicators of loan defaults. This understanding can be used to develop a more accurate risk assessment model. It is important to note that there is no single factor that can guarantee a loan repayment. However, by using data to identify patterns and trends, the company can make more informed lending decisions.


## Table of Contents
* [Problem Statement](#problem-statement)
* [Approach](#approach)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## Problem Statement
As an online lending marketplace, company aims to :
- Identify 'risky' loan applicants who are likely to default and cause credit loss. 
- Analyzing the driving factors behind loan defaults using exploratory data analysis (EDA).
- Understanding the key indicators of loan defaults, to minimize financial loss and for better risk assessment.


## Approach and Analysis
- Understanding and Data cleaning
  -  Understanding what each columns represents
  - Dropping columns which cannot be used, having null values, no variation etc.
  - imputing missing values, removing duplicates, and correcting inconsistencies.
- Analysing the data
  - Univariate Analysis
  - Bivariate Analysis
  - Multivariate and segmented Analysis
- Conclusion
  - Drawing observations and recommendations based on the data  


##  Recommendation and Conclusions
- The following segments seem to have strong influence on defaults :
  - purpose (small business is more likely to default)
  - grade (lower grades are more likely to default)
  - addr_state (some states are more likely to have high defaults)
  - delinq_2yrs (higher values seem to have more)
  - inq_last_6_months (probability of default increases with number of inq)
  - term (36 month loan has high probability of full payment)
  - pub_rec_bankrupcies/pub_rec (individuals reporting higher values can lead to defaulting)
  - loan_amnt (Higher rates can increases the probability of person defaulting)
  - int_rates(majority of the interest rate is in the range of 5% to 15%  and the Very High interest rates are in more likely to default which is greater than 15%)
- The following segments seem to have Low/No influence on loan defaults :
  - verfication_status
  - emp_length
  - home_ownership
  - installments
  - issue_d
  - total_acc
  - total_rec
  - dti
  - home_ownership


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- [Python - Version 3.12.3](https://www.python.org/download/releases/3.0/)
- [numpy - Version 1.26.4](https://github.com/numpy)
- [pandas - Version 2.2.2](https://github.com/pandas-dev/pandas)
- [matplotlib - Version 3.9.0](https://github.com/matplotlib)
- [seaborn](https://github.com/seaborn)
- [Jupyter Notebook - Version 7.2.0]()

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Team
- Mayuri Kumar

## Contact
Created by [@mayuriku] - feel free to contact me


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
