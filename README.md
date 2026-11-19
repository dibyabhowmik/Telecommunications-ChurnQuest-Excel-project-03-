**Project Overview:**


This project analyzes customer churn for a telecommunications business using 4,250 customer records. The analysis focuses on customer usage, service plans, customer service interactions, charges, and churn
behavior.
The project was designed to identify customer characteristics associated with churn and estimate the potential revenue impact of customer loss.

•	**Objectives:**


1.	Measure the overall customer churn rate.

2.	Identify customer groups with higher churn.

3.	Analyze the relationship between service plans and churn.

4.	Examine customer service interactions as a potential churn indicator.

5.	Analyze usage patterns and their relationship with churn.

6.	Compare revenue and charges between churned and non-churned customers.

7.	Explore monthly churn patterns.

8.	Estimate potential revenue loss associated with churn.

•	**Tools & Techniques Used:**

1.	Microsoft Excel

•	Data cleaning and preparation

2.	Excel formulas

3.	PivotTables

4.	Sorting and filtering

5.	Conditional aggregation

6.	Correlation analysis

7.	Customer segmentation

8.	Churn-rate calculations

9.	Date and month analysis

10.	Clustering / usage-group analysis

11.	Synthetic date generation for time-based analysis

12.	Revenue impact calculations

13.	Charts and data visualization

•	**Process:**


**1. Data Preparation:**

The raw telecommunications data contained customer information such as:
State and area code
Account length
International and voicemail plans
Day, evening, night, and international usage
Customer service calls
Churn status
Additional analytical fields were created, including:
Churn Numeric
Usage Score
Usage Group
Synthetic Date
Month
Interaction
Monthly Revenue

**2. Churn Analysis:**

The project calculated churn rates and compared churned and non-churned customers across service plans, usage levels, customer service interactions, and other characteristics.

**3. Customer Segmentation:**

Customers were grouped based on overall usage. The analysis compared churn rates across Low, Medium, and High Usage groups.

**4. Time-Based Analysis:**

Because the original dataset did not contain a real date field, synthetic dates were created to distribute customers across months. Monthly churn trends were therefore treated as illustrative rather
than historical.

**5. Revenue Impact:**

The analysis calculated the monthly revenue associated with churned customers and estimated the potential annual revenue impact if those
customers were lost.

**Key Insights:**


The overall churn rate was approximately 14.1%.

598 customers were classified as churned out of 4,250 customers.

Customers with an international plan had a churn rate of approximately 42%.

Customers without an international plan had a much lower churn rate in the workbook's analysis.

Customers making more than 3 customer service calls had a churn rate of approximately 51%, compared with approximately 11%
for customers making 3 or fewer calls.

Customers with 4 customer service calls had a churn rate of approximately 44%, while customers with 5 or more calls had
a churn rate of approximately 62%.

The High Usage customer group had the highest churn rate at approximately 28%, compared with approximately 12% for Low
Usage and 8% for Medium Usage.

Customers using more than 250 daytime minutes had a churn rate of approximately 49%, considerably higher than the other
daytime-usage groups.

Churned customers averaged approximately 209 day minutes, compared with approximately 176 minutes for non-churned
customers.

Churned customers made approximately 2.28 customer service calls on average, compared with approximately 1.44 for non-churned
customers.

Customers with a voicemail plan had a much lower churn rate in the workbook's analysis than customers without one.

The correlation between account length and churn was approximately 0.019, indicating almost no linear relationship.

The correlation between total day minutes and churn was approximately 0.215, indicating a weak positive relationship.

Average monthly revenue associated with a churned customer was approximately 65.53.

Total monthly revenue associated with churned customers was approximately 39,188.

The workbook estimated an annual revenue impact of approximately 470,259 if the current churned-customer revenue were lost for
another year.

•	**Important Points:**

The telecommunications workbook uses synthetic dates because the original customer dataset did not contain an actual date/time variable. Therefore, the monthly churn analysis should be interpreted as an
illustrative analytical exercise rather than evidence of real seasonal churn patterns.

•	**Business Takeaway:**


The strongest churn signals in this analysis were frequent customer service interactions, high overall usage, high daytime usage, and international-plan status. These patterns suggest that customer support history and usage behavior can be useful for identifying customers who
may require proactive retention attention. The revenue analysis also demonstrates how customer churn can translate into a measurable financial impact.
