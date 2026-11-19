# Telecommunications Customer Churn Analysis

## Project Overview

This project analyzes customer churn for a telecommunications business using 4,250 customer records. The analysis focuses on customer usage, service plans, customer service interactions, charges, and churn behavior.

The project was designed to identify customer characteristics associated with churn and estimate the potential revenue impact of customer loss.

---

## Objectives

1. Measure the overall customer churn rate.
2. Identify customer groups with higher churn.
3. Analyze the relationship between service plans and churn.
4. Examine customer service interactions as a potential churn indicator.
5. Analyze usage patterns and their relationship with churn.
6. Compare revenue and charges between churned and non-churned customers.
7. Explore monthly churn patterns.
8. Estimate potential revenue loss associated with churn.

## Tools & Techniques Used

1. Microsoft Excel
2. Data cleaning and preparation
3. Excel formulas
4. PivotTables
5. Sorting and filtering
6. Conditional aggregation
7. Correlation analysis
8. Customer segmentation
9. Churn-rate calculations
10. Date and month analysis
11. Clustering / usage-group analysis
12. Synthetic date generation for time-based analysis
13. Revenue impact calculations
14. Charts and data visualization

---

## Process

### 1. Data Preparation

The raw telecommunications data contained customer information such as:

- State and area code
- Account length
- International and voicemail plans
- Day, evening, night, and international usage
- Customer service calls
- Churn status

Additional analytical fields were created, including:

- Churn Numeric
- Usage Score
- Usage Group
- Synthetic Date
- Month
- Interaction
- Monthly Revenue

### 2. Churn Analysis

The project calculated churn rates and compared churned and non-churned customers across service plans, usage levels, customer service interactions, and other characteristics.

### 3. Customer Segmentation

Customers were grouped based on overall usage. The analysis compared churn rates across Low, Medium, and High Usage groups.

### 4. Time-Based Analysis

Because the original dataset did not contain a real date field, synthetic dates were created to distribute customers across months. Monthly churn trends were therefore treated as illustrative rather than historical.

### 5. Revenue Impact

The analysis calculated the monthly revenue associated with churned customers and estimated the potential annual revenue impact if those customers were lost.

---

## Key Insights

| Metric
