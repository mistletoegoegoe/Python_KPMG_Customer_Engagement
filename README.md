# Python_KPMG_Data_Analysis
## I. Introduction
The project was about conduting cohort analysis to obtain the insights about customer engagement from their first transaction for KPMG retailer. 
## II. Data Understanding
Dataset KPMG.xlsx includes one table containing transaction information of customers purchasing products in 2017.

<img width="388" alt="image" src="https://github.com/mistletoegoegoe/Python_KPMG_Data_Analysis/assets/121160527/1d5da97a-6ef9-41c4-a72d-6d8ce7bb610f">

- Missing values: There were many missing values that could be seen in the columns that had the number of values less than 20000. However, this issue did not impact on the cohort analysis, thus, it would be temporarily ignored. 

- The transaction_id column is unique, which met the requirement of the key in this data. Checked by is_unique function in Python. 

- order_status = ‘Approved’ needed to be filtered before cohort analysis.


## III. Data Cleaning
### 1. Data correction
### 2. Data completeness
### 3. Data Aggregation
## IV. Visualisation 
## V. Recommendations
