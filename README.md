# Human Resource Dashboard
## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning and Preparation ](#data-cleaning-and-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Data Cleaning and Preparation ](#data-cleaning-and-preparation)
- [Results and Findings](#results-and-findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)
  
### Project Overview
This project aim to analyzes the efficiency of a company's turnover off time by comparing factors such as gender, race and company branches in a bid to improve the productivity of the company in the future.

![Hr Dashboard](https://github.com/user-attachments/assets/07d6a43e-9b97-40d1-97ed-8019b5481a19)

![Hr Dashboard 1](https://github.com/user-attachments/assets/ca851217-db1f-41b9-bd91-7234bb17c392)


### Data Sources
Human Resuorce Data: The primary dataset used for this analysis is the "hr_data.csv" file, containing detailed information about the company.

### Tools
-  Excel - Data Cleaning
   -  Download here
-  SQL Server - Data Analysis
-  PowerBI - Creating reports
### Data Cleaning and Preparation
In the initial data preparation phase, we performed the following tasks:

-  Data loading and inspection.
-  Handling missing values.
-  Data cleaning and formatting.
### Exploratory Data Analysis
EDA involved exploring the sales data to answer key questions, such as:

-  What is the overall sales trend?
- Which products are top sellers?
-  What are the peak sales periods?
### Data Analysis
Include some interesting code/features worked with
```
SELECT * FROM table1
WHERE cond = 2;
```
### Results and Findings
The analysis results are summarized as follows:

-  The company's sales have been steadily increasing over the past year, with a noticeable peak during the holiday season.
-  Product Category A is the best-performing category in terms of sales and revenue.
-  Customer segments with high lifetime value (LTV) should be targeted for marketing efforts.
### Recommendations
Based on the analysis, we recommend the following actions:

-  Invest in marketing and promotions during peak sales seasons to maximize revenue.
-  Focus on expanding and promoting products in Category A.
-  Implement a customer segmentation strategy to target high-LTV customers effectively.
### Limitations
I had to remove all zero values from budget and revenue columns because they would have affected the accuracy of my conclusions from the analysis. There are still a few outliers even after the omissions but even then we can still see that there is a positive correlation between both budget and number of votes with revenue.

### References
-  SQL for Businesses by werty.
-  [Stack Overflow](https://stack.com)

