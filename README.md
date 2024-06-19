# Python_KPMG_Data_Analysis
## I. Introduction
The project was about conduting cohort analysis to obtain the insights about customer engagement from their first transaction for KPMG retailer. 
## II. Data Understanding
Dataset KPMG.xlsx includes one table containing transaction information of customers purchasing products in 2017.

<img width="388" alt="image" src="https://github.com/mistletoegoegoe/Python_KPMG_Data_Analysis/assets/121160527/1d5da97a-6ef9-41c4-a72d-6d8ce7bb610f">

- Missing values: There were many missing values that could be seen in the columns that had the number of values less than 20000. However, this issue did not impact on the cohort analysis, thus, it would be temporarily ignored. 

- The transaction_id column is unique, which met the requirement of the key in this data. Checked by is_unique function in Python. 

- order_status = ‘Approved’ needed to be filtered before cohort analysis.

## III. Cohort analysis introduction
### Definition
- Cohort analysis is a type of behavioral analytics in which you take a group of users, and analyze their usage patterns based on their shared traits to better track and understand their actions.
- A cohort is simply a group of people with shared characteristics
### Types of cohort analysis
- Time cohorts: customers who signed up for a product or service during a particular time frame.
- Behavior cohorts: customers who purchased a product or subscribed to service in the past.
- Size cohorts: refer to the various sizes of customers who purchase the company’s products or services.
### Cohort analysis in this project
- This project concentrated on **Time cohorts**.
- Customers would be divided into acquisition cohorts depending on the month of their first purchase (cohort month)
- The cohort index would then be assigned to each of the customer’s purchases, which would represent the number of months since the first transaction
## IV. Visualisation 
<img width="626" alt="image" src="https://github.com/mistletoegoegoe/Python_KPMG_Data_Analysis/assets/121160527/1a39d54b-0f72-4b4f-a40e-b48aabe5a424">

<img width="629" alt="image" src="https://github.com/mistletoegoegoe/Python_KPMG_Data_Analysis/assets/121160527/41818b12-8dfa-48b9-b6e0-b87f2ac5b7cc">

## V. Insights
- Retention rate remains stable, ranging from 31% to 45% over time. However, the number of customers who made the first purchase falls significantly, from 1347 (January, 2017) to 4 (December, 2017).
- In the time frame from April to July, 2017, the number of customers who made the first purchass has tendency to retain longer than the other groups. Specifically, 48.1% after five months since July 2017, 45.1% after four months since April 2017.
- The retention rate of customers who placed their first order in January, February and March were consistently fluctuated in the range of 33% to 43%. While, this figure in August, September and October appeared to vary significantly, especially in Auguest: 43.1% in the 3rd month but 25.5% in the 5th month.
## VI. Recommendations
- The retention rate was remained stabably over customer's lifetime at KPMG. In contrast, the number of customers who place the first order declines. This raised the need to collect more data about the context of the past in terms of promotions, seasonal event, product quality changes, etc to analyse deeper regarding the cause of this issue, plus the effectiveness of marketing campaigns.
- Dig deeper in the characteristics of the mid-year months (April-July) groups which had the highest retention rate, so the company would offer them deals or new marketing activities for other groups. 

