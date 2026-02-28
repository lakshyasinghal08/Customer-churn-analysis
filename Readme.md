#  Customer Churn Analysis – Telecom Industry

##  Project Overview

This project analyzes customer churn behavior in a telecom company to identify the key factors influencing customer attrition and provide actionable business recommendations to improve customer retention.

The dataset contains 7,043 customer records including demographic, service usage, and financial information.

## churn => if yes => means a customer stops using a company’s service 
##       => if no => means a customer still use the company service 

##  Project Objective

To identify the primary drivers of customer churn and recommend data-driven retention strategies to reduce the churn rate.

##  Dataset Features

###  Customer Demographics
- Gender
- SeniorCitizen
- Partner
- Dependents

###  Service Details
- PhoneService
- InternetService
- OnlineSecurity
- OnlineBackup
- DeviceProtection
- TechSupport
- StreamingTV
- StreamingMovies

###  Account Information
- Tenure (months with company) => how much a customer stayed with the comapany
- Contract Type
- Payment Method
- MonthlyCharges
- TotalCharges

##  Key Findings

- Overall churn rate is approximately 26%.
- Contract type is the strongest churn driver (~40% churn gap).
- Month-to-month customers have significantly higher churn.
- Customers with low tenure (0–12 months) are more likely to churn.
- Customers without TechSupport show higher churn rates.
- Higher monthly charges are associated with increased churn risk.

##  Business Recommendations

- Promote long-term contracts with discounts and incentives.
- Improve onboarding experience for new customers.
- Bundle TechSupport into standard service plans.
- Launch targeted retention campaigns for high-risk customers.

##  Tools & Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

##  Conclusion

The analysis identified contract type as the primary churn driver. Strategic focus on converting month-to-month customers into long-term contracts can significantly reduce churn and improve revenue stability.
