# Aktia-Challenge-2021

Please complete the following data processing challenge by DD.MM.YYYY.

## Description
Your task is to use the data provided in the file Aktia_challenge_data.xlsx, and through the use of visualizations and/or statistics try to find observations about branches, customers or products that you find relevant to the business.  

For example, you can examine how the service payments of different business areas have developed.

## Dataset
### Explanation
The dataset includes imaginary bank service payment income for 2017-2020. The dataset (excel file) used in the challenge consists of three different sheets. These sheets describe three different database tables from which you are supposed to build an overall picture of how service fees have evolved over the review period. 

In the beginning, you should combine these tables so that you can, for example, study how different business areas have developed. You can do this the way you want, for example, directly in Excel or using BI tools. As a bonus, you can add an SQL query to your final answer, which would have given you the entire usable dataset directly from the database.

### Tables (sheets)
#### Customers
Column | Explanation
------------ | -------------
CustomerID | Customer's unique ID
Age | Customer's age in years
Birth month | Customer's birth month
AUM | Assets under management in €
Segment | Customer segment
Business area | Customer's business area
Branch | Customer's branch. Payments made by the customer are included in the income of this branch.

#### Events
Column | Explanation
------------ | -------------
Date | The date of the service payment
EventID |The unique ID of the service payment
ProductID | Product's unique ID
CustomerID | Customer's unique ID
Payment | Is the payment successful. If false, the bank has not received that payment
Discount (%) | Discount received by the customer from the list price
Payment (€) | The price paid by the customer

#### Products
Column | Explanation
------------ | -------------
ProductID | Product's unique ID
Category | Product category
Product | Product name
Price 2017-2018 | List price 1.1.2017-31.12.2018
Price 2019-2020 | List price 1.1.2019-31.12.2020

## Submission requirements
### Submit your work:
* As a git repository (preferred way). Make sure your repo is public and submit a link to it via email.
* Or all files directly via email.

### Suggested tools / approaches

* Use summary statistics, visualization or other analytical means to present the main insights of the data clearly and comprehensibly. 
* You can for example use BI visualization tools (Tableau, Power BI, Excel) or ipython (jupyter) notebooks
* For example, your answer could be a dashboard, where the most important things / indicators to monitor are displayed. In addition to this, it is also good that you have written down your findings from the material.
* Remember to include your full answer (BI tool files, code, possible SQL query, etc.) in your submission. Please also add a brief description of how you set out to solve the problem and what you did. 

**Have fun!**
