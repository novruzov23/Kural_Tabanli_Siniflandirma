# Kural_Tabanli_Siniflandirma

Calculating Lead Yield with Rule-Based Classification
 
Business Problem
A gaming company uses some of its customers' features
new level-based customer definitions (persona)
create and segment segments according to these new customer definitions
by creating new customers according to these segments.
He wants to estimate how much he can earn on average for the company.

For example:
A 25-year-old male from Turkey who is an IOS user
Determining how much the user can earn on average
is wanted.
Dataset Story:
Persona.csv data set includes the prices of products sold by an international game company and
It contains some demographic information of the users who purchase the products. Data
The set consists of records created in each sales transaction. What does this mean?
The table is not deduplicated. In other words, a person with certain demographic characteristics
The user may have made more than one purchase.

Variables:
PRICE – Customer's spending amount
Variables
SOURCE – The type of device the customer is connected to
SEX – Customer's gender
COUNTRY – Customer's country
AGE – Customer's age

Task 1: Answer the Questions Below
Question 1: Read the persona.csv file and show general information about the data set.
Question 2: How many unique SOURCE are there? What are their frequencies?
Question 3: How many unique PRICEs are there?
Question 4: How many sales were made from which PRICE?
Question 5: How many sales were made from which country?
Question 6: How much was earned from sales in total by country?
Question 7: What are the sales numbers according to SOURCE types?
Question 8: What are the PRICE averages by country?
Question 9: What are the PRICE averages according to SOURCEs?
Question 10: What are the PRICE averages in the COUNTRY-SOURCE breakdown?

Task 2: What are the average earnings in the COUNTRY, SOURCE, SEX, AGE breakdown?

Task 3: Sort the output by PRICE.
To better see the output in the previous question, apply the sort_values ​​method in decreasing order of PRICE.
• Save the output as agg_df.

Task 4: Convert the names in the index into variable names.
Task 5: Convert the age variable to a categorical variable and add it to agg_df.
• Create the intervals convincingly.

Task 6: Define new level-based customers (personas).










