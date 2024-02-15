# CUSTOMER SEGMENTATION DASHBOARD FOR CREDIT CARD
## Project Overview
This Project is based the bank domain , the requirements of the bank is to know the market of the customers who are willing to do the term deposit.The Marketing team has done their job but they need to know whether they need to improve or to know that the potential customers are targeted.
## Problem Statement 
A German Bank has collected the data of the customers who are using the credit card and marketing data.The objective is that the bank want to know that the how many customers will use term deposit(crediting amount).

## Steps followed 
### Data Cleaning
- The collected data was cleaned using the MySQL Workbench.First the data was overviewed and checked that any unneccessary data and null values are present. An unwanted row was removed from the data by using this MySQL Command 
![Screenshot 2024-02-15 191906](https://github.com/Sudarson-analyst/Tableau_Public-Project-/assets/159156381/6a8f3827-8171-4ecd-b492-7b266fe9aa8a)
- Then checked the datatype of the duration column and also replaced the job category value with their respective job name - as the datatype of that column is int the datatype is changed to varchar the replacing the job name was done using this following code
![Screenshot 2024-02-15 192414](https://github.com/Sudarson-analyst/Tableau_Public-Project-/assets/159156381/6356c017-687d-46b3-b306-cf476c4c2229)
- Formatted the text in a Proper format and used the upper function for the following column name "Housing" and "Purpose" and extracted the data from the MySQL Workbench.

### Creating Charts in the Worksheets
I have created different chart to make the visualization easier using the chart like Pie chart,Horizondal and Vertical Bar chart,Funnel Chart,Tree Map and Donut Chart.


https://public.tableau.com/app/profile/sudarson.s1147/viz/CustomerSegmentationProjectBank-Creditcard/CUSTOMERSEGMENTATIONFORCREDITCARD?publish=yes
