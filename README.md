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
The following questions were explored using **Pandas**:

1. How many entries and columns are in the dataset?
2. What are the maximum, minimum, and average ages of customers?
3. What are the three most common customer names?
4. Are there duplicate phone numbers?
5. How many customers have "Structural Engineer" as a profession?
6. How many male customers are Structural Engineers?
7. How many female Structural Engineers are from Alberta (AB)?
8. What are the max, min, and average spending amounts?
9. Which customers did not spend anything?
10. Who spent 100 CAD or more (eligible for a loyalty reward)?
11. How many emails are associated with a specific credit card number?
12. How many credit cards are expiring in 2019?
13. How many people use Visa as their credit card provider?
14. Which customer spent 100 CAD using Visa?
15. What are the two most common professions?
16. What are the top five most common email providers (e.g., Gmail, Yahoo)?
17. Are there any customers using an email with "am.edu"?
18. Which day of the week has the highest number of customer purchases?


## Installation and Usage
### Prerequisites
- Python 3.x
- Pandas Library


Key Findings:
1.	Dataset Size
         - The dataset contains 500 entries and 19 columns.
2.	Customer Age
        - The youngest customer is 18 years old, and the oldest is 65 years old.
        - The average customer age is approximately 42.5 years.
3.	Top Names
         - The most common customer names are Harry, Cody, and Lily.
4.	Duplicate Phone Numbers
         - Two customers share the same phone number: Mrs. Lilly Tyler and Mrs. Peter Cain.
5.	Structural Engineers
         - There are 2 Structural Engineers in the dataset, with 1 male and 1 female from Alberta (AB).
6.	Spending Habits
         - The maximum spending is 100 CAD, and the minimum is 0.66 CAD.
         - One customer did not spend anything: Dr. Catherine Morales.
7.	Credit Card Usage
         - 50 customers use Visa as their credit card provider.
         - 5 credit cards are expiring in 2019.
8.	Email Providers
         - The top 5 email providers are yahoo.com, hotmail.com, gmail.com, kol.km, and jatsot.ug.
9.	Customer Traffic
         - The store receives the most customers on Friday.


## Pandas Code
The full Pandas code used for the analysis can be found in the Pandas Code section of this README.




