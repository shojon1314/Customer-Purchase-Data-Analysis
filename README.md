# Customer Purchase Data Analysis using Pandas

## Overview
This project analyzes a customer purchase dataset using **Pandas** to extract key insights such as customer demographics, spending habits, and patterns.

## Dataset
The dataset (`Cust_Purch_FakeData.csv`) contains customer details, including names, ages, professions, spending history, and credit card information.

### Columns in the Dataset
- **Customer ID**: Unique identifier for each customer
- **Name**: Customer’s full name
- **Age**: Customer’s age
- **Gender**: Male/Female
- **Phone Number**: Customer’s contact number
- **Email**: Customer’s email address
- **Profession**: Job title of the customer
- **Province**: State/Province where the customer lives
- **Spending (CAD)**: Amount spent by the customer in CAD
- **Credit Card Number**: Payment card number (anonymized for security)
- **Credit Card Provider**: The provider of the credit card (Visa, MasterCard, etc.)
- **CC Expiry**: Expiry date of the credit card
- **Purchase Date**: Date of last purchase

## Analysis Performed


The following analyses were performed on the dataset using Python and Pandas:
1.	Dataset Overview
      o	Number of entries and columns.
      o	Max, min, and mean age of customers.
2.	Customer Names
      o	Top 3 most common customer names.
3.	Duplicate Phone Numbers
      o	Customers sharing the same phone number.
4.	Profession Analysis
      o	Number of customers with the profession "Structural Engineer."
      o	Number of male "Structural Engineers."
      o	Female "Structural Engineers" from Alberta (AB).
5.	Spending Analysis
      o	Max, min, and average spending.
      o	Customers who did not spend anything.
      o	Customers who spent 100 CAD or more.
6.	Credit Card Analysis
      o	Emails associated with a specific credit card number.
      o	Number of credit cards expiring in 2019.
      o	Number of customers using Visa.
    o	Customer who spent 100 CAD using Visa.
7.	Profession and Email Analysis
    o	Top 2 most common professions.
    o	Top 5 most popular email providers.
    o	Customers using an email with "am.edu."
8.	Customer Traffic Analysis
    o	Day of the week with the most customers.






## Installation and Usage
### Prerequisites
- Python 3.x
- Pandas Library
