### Exploratory-Insuarance-Data-Analysis
The project demonstrates data cleaning, data quality assessment and root cause analysis on simulated insuarance dataset using Python.

## Executive Summary
Data governance is paramount to every institution.This project involves cleaning simulated insuarance data and performing both data quality assessment and root cause analysis.The simulated insuarance data consist of customerID, fullname, preminum amounts,claim status. It has been simulated to include issues such as missing values, duplicates and inconsistent categorical data. The dataset has been cleaned, assessed and analysed.


## Business Problem

Insuarance companies needs high quality data to make informed decisions and enhance their customer's experience. When the quality is not checked and data is poorly cleaned these companies are faced by problems such as:
- Misreported claims.
- Poor customer experiences
- Regulatory non complaince.
  
This all leads to reduction in the number of customers and loss of revenue.

## Skills

Python: Pandas(data cleaning)

Data governance: Root cause analysis, audit flags

## Results and Business Recommendation

The results is a cleaned dataset and documentaion of the root cause analysis.
I recommend:
- Enforcement of unique policy numbers(CustomerID)
- Maintainance of mandatory fields for CustomerID, preminum amount and claim status
- Implementationn of audit flags for missing values or corrected data to preserve the audit trail
- Standardization of categorical values such as those in claim status to ensure uniformity of the vocabulary used
