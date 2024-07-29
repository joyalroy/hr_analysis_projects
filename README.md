# HR-Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)

### Project Overview

The HR Analysis project aims to provide comprehensive insights into HR data. This project includes data preprocessing, exploratory data analysis (EDA), and visualization techniques to help HR professionals in an organization to improve employee performance, employee retention (reduce attrition) and make data-driven decisions.

[HR Analytics New Project.pdf](https://github.com/user-attachments/files/16417351/HR.Analytics.New.Project.pdf)

### Data Sources

Hr Data: The primary dataset used for analysis in this project contains various HR metrics.[Uploading HR_Analytics.csv…]()

(Dataset Source:[HR_Analytics.csv](https://github.com/user-attachments/files/16417990/HR_Analytics.csv)
File Format: CSV
 
### Tools

- Microsoft Excel Workbok :- Data Cleaning, Data Analysis & Data Visualization.

### Data Cleaning

In the initial data preparation phase, the following tasks were performed.

1. Data loading & inspection.
2. Handling missing values.
3. Data cleaning & formatting.

### Exploratory Data Analysis

EDA involved exploring the sales data to answer key questions, such as;

- In which month was the highest sales produced?
- Who made the most purchases- men or women?
- What are different order status?
- List top 5 states contributing to the sales?
- Which channel is contributing to maximum sales?
- Which is the highest selling category?
- Compare the sales and orders.
- Relation between age and gender based on number of orders.

### Data Analysis

include some interesting code/features worked with

```excel

#NewColumn

=IF(E2>=50,"Senior",IF(E2>=30,"Adult","Teenager"))

#New Column

=TEXT(G2,"mmm")
```

### Results

1. Month of March had the most peak sales(1.9M).
2. Women are more likely to buy compared to men(~65%).
3. Maharashtra, Karnataka & Uttar Pradesh are the top 3 states(~35%).
4. Adult age group (30-49yrs) is max contributing (~50%).
5. Amazon, Flipkart & Myntra channels are max contributing(~80%).

### Recommendations

- Target women customers of age group (30-49yrs) living in Maharashtra, Karnataka & Uttar Pradesh by showing ads/offers/coupons available on Amazon, Flipkart & Myntra.

### Limitations

- I had to create new columns to classify age-groups and distinguish sales on monthly basis to generate meaningful insights & data precision.

### References

- Google
- Youtube
