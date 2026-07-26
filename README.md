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
Customers who churned paid approximately $36.29 more per month on average than customers who remained.
The test produced a t-statistic of approximately 39.28.
The p-value was effectively less than 0.001, which is below the significance level of 0.05.
Therefore, the null hypothesis was rejected.
Conclusion

The analysis found that customers who churned had significantly higher average monthly charges than customers who remained with the company. This result suggests that monthly charges are associated with customer churn and may help identify customers who are at greater risk of leaving.

However, the t-test demonstrates an association rather than causation. Higher monthly charges may contribute to customer dissatisfaction, but other variables—including contract type, service reliability, equipment issues, customer location, and competing offers—may also influence churn.

The dataset was sufficiently large for the sampling distribution of the mean to be approximately normal. The group variances were also similar, with a variance ratio of approximately 0.90. Nevertheless, because the data was not collected through a truly random sample, the results may not generalize to every customer population.

## Recommendations

The company should examine retention strategies for customers with high monthly charges. Potential actions include:

Offering targeted loyalty discounts or promotional rates
Reviewing whether high-paying customers receive adequate service value
Encouraging eligible customers to adopt longer-term contracts
Investigating service outages, equipment problems, and customer-support experiences
Building a broader churn model that incorporates monthly charges, contract type, tenure, service usage, and customer complaints

These actions could help the company better understand why high-paying customers leave and develop more targeted retention strategies.

## Project Files

- [View the Jupyter Notebook](customer_churn_t_test_analysis.ipynb)
- [View the Full Written Report](Customer_Churn_Two_Sample_T_Test_Report.pdf)
- [View the data in csv format](churn_clean.csv)

