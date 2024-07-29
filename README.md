# HR-Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [References](#references)

### Project Overview

The HR Analysis project aims to provide comprehensive insights into HR data. This project includes data preprocessing, exploratory data analysis (EDA), and visualization techniques to help HR professionals in an organization to improve employee performance, employee retention (reduce attrition) and make data-driven decisions.

[HR Analytics New Project.pdf](https://github.com/user-attachments/files/16417351/HR.Analytics.New.Project.pdf)

### Data Sources

Hr Data: The primary dataset used for analysis in this project contains various HR metrics.

Dataset Source: [HR_Analytics.csv](https://github.com/user-attachments/files/16417990/HR_Analytics.csv)

File Format: CSV
 
### Tools

- Microsoft Power BI :- Data Cleaning, Data Analysis & Data Visualization.

### Data Cleaning

In the initial data preparation phase, the following tasks were performed.

1. Data loading & inspection.
2. Handling missing values/null values.
3. Data cleaning & formatting.

### Exploratory Data Analysis

EDA involved exploring the HR data to answer KPI's, such as;

- What is the total number of employees in the organization?
- Find the overall attrition and attrition rate.
- Evaluate the average age of personnel in the organization.
- Calculate the average salary of personnel in the organization.
- Figure out the average employment period.

### Data Analysis

include some interesting code/features worked with

```power bi

#Conditional Column

Column Name:AttritionCount, Operator:Equals, Value:Yes, Output:1, Else:0

#New Measure

AttritionRate = SUM(HR_Analytics[AttritionCount])/SUM(HR_Analytics[EmployeeCount])

```

### Results

1. The total Head count is (1,470).
2. Total Attrition count (237) & Attrition rate (16.1%).
3. Average age (37yrs).
4. Average salary (6.5k).
5. Average years spent (7.0yrs).

### References

- Google
- Youtube
- Credits:Rishabh Mishra
