# Public_data
This repo includes data from public sources on useful for different ML tasks.

## Regression
- OPERATIONS_Yerevan_Real_Estate_Prices.csv
  - Dataset Name: Yerevan_Real_Estate_Prices
  - Domain: Macroeconomy
  - Size of the Data: 33330 rows, 16 columns
  - Target Variable: Price
  - Task Type: Regression
  - Description: Official house price index does not cover the full dynamics and volatility of real estate market. The dataset was developed by scraping top real estate websites in Yerevan to estimate factors affecting house prices and developing a House Price Index for the capital of Armenia. Learn More

- [MARKETING_Customer_Lifetime_Value.csv](https://www.kaggle.com/ranja7/vehicle-insurance-customer-data)
  - Dataset Name: Customer_Lifetime_Value
  - Domain: Marketing
  - Size of the Data: 9134 rows, 24 columns
  - Target Variable: Customer Lifetime Value
  - Task Type: Regression
  - Description: Customer Lifetime Value is a key metric for measuring company growth. Based on information on customer’s education, employment, income, marital status and other factors this dataset provides the opportunity to estimate and understand the drivers of customer lifetime value. Learn More
  
- [MARKET_Car_Prices.csv](https://www.kaggle.com/toramky/automobile-dataset)
  - Dataset Name: Car_prices
  - Domain: Market research
  - Size of the Data: 206 rows, 24 columns
  - Target Variable: Price
  - Task Type: Regression
  - Description: Car prices in the used car market vary based on many factors including but not limited to car attributes and condition indicators. This dataset provides opportunity to learn factors driving car prices and interactions between them . Learn More

- [SOCIAL_Affairs.csv](https://www.kaggle.com/clarkchong/fairs-affairs-dataset)
  - Dataset Name: Fair's experimental affairs
  - Domain: Finance
  - Size of the Data: 601 rows, 9 columns
  - Target Variable: Affair
  - Task Type: Regression
  - Description: This experimental affairs dataset provides the opportunity to estimate time spend in affairs using indirect predictors and conditioned by censored data. It is used to explain the allocation of an individual’s time among work, time spent with a spouse, and time spent with a paramour.Learn More

- [SOCIAL_Compass_Scores.csv](https://www.kaggle.com/danofer/compass)
  - Dataset Name: COMPAS Recidivism Racial Bias
  - Domain: Law, Social Science, Crime, Demographics
  - Size of the Data: 60843 rows, 28 columns
  - Target Variable: **RawScore**, DecileScore, ScoreText
  - Task Type: Regression / Multiclass Classification
  - Description: COMPAS (Correctional Offender Management Profiling for Alternative Sanctions) is a popular commercial algorithm used by judges and parole officers for scoring criminal defendant’s likelihood of reoffending (recidivism). It has been shown that the algorithm is biased in favor of white defendants, and against black inmates, based on a 2 year follow up study (i.e who actually committed crimes or violent crimes after 2 years). The pattern of mistakes, as measured by precision/sensitivity is notable. Learn More.


## Binary Classification
- [OPERATIONS_Startup_Success.csv](https://www.kaggle.com/ajaygorkar/startup-analysis)
  - Dataset Name: Startup_Success
  - Domain: Business Analytics
  - Size of the Data: 478 rows, 116 columns
  - Target Variable: Dependent-Company Status
  - Task Type: Classification
  - Description: The dataset includes information of Startups and their Status of Success or Failure. Some of the features that help do distinguish whether the startup will be successful or not are year of founding of the startup, industry , internet activity score, investor information, employee count and etc. Learn More

- [MARKETING_FINANCE_Bank_targeting_default.csv](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
  - Dataset Name: Bank_targeting_default
  - Domain: Marketing, Finance
  - Size of the Data: 4120 rows, 21 columns
  - Target Variable: Response to targeting
  - Task Type: Binary Classification
  - Description: Default rate is one of the key measures that commercial banks aim to reduce. This dataset provides information on bank customers who were targeted by marketing campaign and, had positive or negative loan history. Based on the information, it is possible to develop targeted marketing strategy for offering financial products to customers likely not to default and likely to accept an offer. Learn More
  
- [FINANCE_Credit_Scoring.csv](https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data))
  - Dataset Name: German Credit Data
  - Domain: Finance
  - Size of the Data: 1000 rows, 20 columns
  - Target Variable: default
  - Task Type: Binary Classification
  - Description: Default rate is one of the key measures that commercial banks aim to reduce. This dataset provides information on bank customers who were given the loan and then experienced or did not experience default. The aim of the analysis is to reveal factors behind default, estimate PD (probability of default) and develop scoring system based on that. Learn More

- [HR_Employee_Attrition.csv](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset)
  - Dataset Name: Employee_Attrition
  - Domain: Human Resources
  - Size of the Data: 1471 rows, 35 columns
  - Target Variable: Attrition
  - Task Type: Binary Classification
  - Description: Employee attrition is the process when stuff is leaving the organization and replacement is not done. This dataset provides information on employee age, department, education, gender, hourly earning rate and other factors that help to predict and understand the reasons behind employee attrition.  Learn More

- [CUSTOMER_ANALYTICS_Telecom_churn.csv](https://www.kaggle.com/blastchar/telco-customer-churn/data)
  - Dataset Name: Telecom_churn
  - Domain: Customer Analytics
  - Size of the Data: 7043 rows, 21 columns
  - Target Variable: Churn
  - Task Type: Binary Classification
  - Description: Customer churn is the process of existing customers stopping using a company's product or service. This dataset provides information on employee product usage as well as demographic information such as gender and age group to help identifying beforehand the customers that are highly probably to leave. Learn More.
  
- [CUSTOMER_ANALYTICS_Telecom_customer_churn.csv](https://www.kaggle.com/abhinav89/telecom-customer)
  - Dataset Name: Telecom_customer_churn
  - Domain: Customer Analytics
  - Size of the Data: 100k rows, 100 columns
  - Target Variable: churn
  - Task Type: Binary Classification
  - Description: Customer churn is the process of existing customers stopping using a company's product or service. This dataset provides information on employee product usage as well as demographic information such as gender and age group to help identifying beforehand the customers that are highly probably to leave. Learn More.

- [SOCIAL_Adult_Census_Income.csv](https://www.kaggle.com/uciml/adult-census-income)
  - Dataset Name: Adult Census Income
  - Domain: Social Science, Demographics, Employement
  - Size of the Data: 32561 rows, 15 columns
  - Target Variable: income
  - Task Type: Binary Classification
  - This data was extracted from the 1994 Census bureau database by Ronny Kohavi and Barry Becker (Data Mining and Visualization, Silicon Graphics). A set of reasonably clean records was extracted using the following conditions: ((AAGE>16) && (AGI>100) && (AFNLWGT>1) && (HRSWK>0)). The prediction task is to determine whether a person makes over $50K a year. Learn More.