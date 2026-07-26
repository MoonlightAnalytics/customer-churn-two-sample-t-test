# Customer Churn Two-Sample t-Test Analysis

## Overview
This project investigates whether customers who churn have significantly different monthly charges than customers who remain with the company. An independent two-sample t-test was performed using Python to evaluate the difference in average monthly charges between the two groups.

## Business Question
Do churned customers pay significantly different monthly charges than retained customers?

## Dataset
- Customer Churn Dataset
- Features used:
  - Churn
  - MonthlyCharges

## Tools
- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook

## Statistical Method
- Independent Two-Sample t-Test
- α = 0.05

## Results
Conclusion:
I tested where customers who churn have higher monthly charges than those who stay using a right-tailed two sample t-test (similar variance, significance level = 0.05)
The null hypothesis is that churners do not pay more than non-churners
The alt hypothesis is that churners do pay more than non-churners. 
Mean difference between the two groups: $36.29 
The test produced a t-statistic of approximately 39.28, and a p-value close to 0.000, well below the significance level threshold of 0.05. The results provide strong evidence to reject the null hypothesis. Therefore, churned customers do pay significantly more on average than non-churned customers. This suggests that higher monthly charges are strongly associated with customer churn
 White the dataset for “MonthlyCharge” is large and satisfies Central Limit Theorem, it is not truly a random sample. This may limit how the results can be generalized. Additionally, the t-test assumes homogeneity of variance, which can only be approximated. Though calculating the variance it comes close to 1 to 1. The variance ratio was 0.9. 
T-test also only shows association and not truly the real cause of churn, it shows just one aspect of the concern. Other factors such as service issues like equipment failure and outages, location, contract type, better service from other competitors could be a factor of churn.

Recommendations:
Based on the findings, the company should consider strategies to reduce churn among high-paying customers. These may include offering discounts, promotions, or loyalty programs targeted at customers with higher monthly charges. Additionally, encouraging customers to adopt longer term contracts could reduce churn rates, as churn was far lower for two year contract customers as visualized in one of the categorical bivariate graphs. 


