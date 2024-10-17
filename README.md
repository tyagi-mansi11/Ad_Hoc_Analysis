# ****Project Title: Provide Insights to Management in the Consumer Goods Domain****

## Project Overview

✅****Situation:**** AtliQ Hardwares (imaginary company) is one of India's leading computer hardware producers, with a presence in other countries as well. However, the management noticed they lacked the insights needed to make quick and informed decisions, limiting their ability to respond to market changes.

✅****Task:**** As a hypothetical applicant for the role, my responsibility was to address this gap by providing actionable insights through data analysis, and helping the management make smarter, data-driven decisions.

✅****Action:**** I took the following steps:

1. Reviewed ad-hoc requests
2. Executed SQL queries to extract and analyze relevant data
3. Visualized the insights

✅****Result:**** Through this process, management receives insights, enhancing their ability to make strategic decisions in a highly competitive market.

## Project Structure

The project is organized as follows: 

• _[SQL Queries](https://github.com/tyagi-mansi11/Ad_Hoc_Analysis/blob/6d593e5d0cdfbcea56c60d87249f00b022b8462f/SQL%20codes.pdf)_: Contains the SQL queries   <br>
• _[Ad-Hoc Insights](https://github.com/tyagi-mansi11/Ad_Hoc_Analysis/blob/63fd4eefe0e1fd22d4b2d570c40dc55c3b38dcd0/Ad-Hoc%20Insights.pdf)_: Contains ppt of the project <br>

## Understanding Datasets

<pre>
[1] dim_customer
     • 75 distinct customers throughout the market
     • Two types of platforms:
          • Brick & Motors - Physical/offline store
          • E-commerce - Online Store 
     • Three channels: Retailer, Direct, Distributors 
     • 27 distinct markets (ex India, USA, Spain)
     • 7 sub-zones
     • 4 regions i.e APAC, EU, NA, LATAM 
          APAC- Asia Pacific
            EU- European Union
            NA- North American
         LATAM- Latin America

[2] dim_product
    • Divisions
           • P & A - Peripherals, Accessories
           • PC - Notebook, Desktop
           • N & S - Networking, Storage  

[3] fact_gross_price
The details of gross prices with product code.

[4] fact_manufacturing_cost
The details of manufacturing cost with product code with year.
  
[5] fact_Pre_invoice_dedutions
The details of pre-invoice deductions percentage for each customer with year.  

[6] fact_sales_monthly
Contains the value of sold quantity.  
</pre>

<img src="https://github.com/tyagi-mansi11/img/blob/e611edd75d41faa69f11c5438dbaa8d17b927855/Screenshot%202024-10-14%20232837.png"  width="550" height="400">
