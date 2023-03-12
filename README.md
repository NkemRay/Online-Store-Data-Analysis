# Online Store Analysis

## Introduction:

![](https://github.com/NkemRay/Online-Store-Data-Analysis/blob/main/images/hoping%20image.jfif)

This is a transnational data set which contains all the transactions occurring between 2010 and 2011 for a UK-based and registered non-store online retail. 
The company mainly sells unique all occasions gifts.  Many customers of the store are wholesalers. 

## Data sourcing:

![](https://github.com/NkemRay/Online-Store-Data-Analysis/blob/main/images/Data%20sourcing.jfif)

The dataset was gotten from Kaggle with 541910 records and 8 fields. 
The data was imported into excel for cleaning and ensuring its ready for further analysis.

## Data Pre-processing:

### Check for duplicates first:

![](https://github.com/NkemRay/Online-Store-Data-Analysis/blob/main/images/Screenshot%20(75).png)

I noticed that there are lots of duplicates base on the invoice number but we can’t delete them because,

•	A customer can buy different gifts from the store at the same time and have same invoice number and will help me ascertain the number of purchases by the customer 

•	Also, deleting lots of duplicate base on the invoice number or customer_ID will make us loose important data for the analysis.

•	Finally, I would have to leave the duplicates.

Prompts to check for duplicates: 

•	Highlighted the table

•	Select the ‘conditional formatting tab

•	Click on highlight cells

•	Click on duplicated cells

•	Voila! You have the records repeated colored.

### Checking for empty cells;

![](https://github.com/NkemRay/Online-Store-Data-Analysis/blob/main/images/Screenshot%20(76).png)

![](https://github.com/NkemRay/Online-Store-Data-Analysis/blob/main/images/Screenshot%20(78).png)

There are blank cells especially the customer_ID, Description column and even the price column with ‘0’ value in most records and its not possible for a unit price of a product to be '0'. The total records with empty cells on the column listed above are "8724".

Prompts to check for blank cells:

•	Click on the on ‘find and select tab 

•	Select ‘Go to special’ and finally click on blanks 

•	You get to see the rows with blank or null cells

### Spelling checks on the country column;

![](https://github.com/NkemRay/Online-Store-Data-Analysis/blob/main/images/Screenshot%20(82).png)

Ireland was spelt as  ‘EIRE’, Republic of South Africa was spelt like thus ‘RSA’ and United states of America was spelt like thus; USA. The thing is some people understands some of this acronym but not everyone, so it is important to change the names to a more appropriate ones known by many. 

Prompts to correct spellings:

•	Highlight the column which in this case is the country column

•	Click on the find and select tab 

•	Click on the ‘replace’ or ‘find’ option

•	Type in the name you wish to replace and the name to be replaced with.

Also, on the quantity column, I noticed that some values were stored with negative sign and this can mean two things

•	It can be a way of saving returned products by the company  

•	It can also be an error.

Because of the problem statement that asks to get Customer behavior, it is important to keep the quantities as it is with both the negative and the positive values

## Problem statement:

Analyze customer behavior and segment them into different groups based on demographics, spending habits. 

## Skills/ Concepts:

Data cleaning, Excel, Tableau, Exploratory Analysis / Visualization.

## Modelling:

No modelling was done because it’s just a table.

## Visualization:

After the cleaning process, the data was imported into Tableau to answer important Business problem.

•	Open the Tableau desktop software

•	Select the data to import which in this case is the online retail data

•	Started by creating KPIs and continued with the rest of the visuals

Below is the Dashboard and for more interactivity, click on  the link 

![](https://github.com/NkemRay/Online-Store-Data-Analysis/blob/main/images/Screenshot%20(98).png)

https://public.tableau.com/app/profile/racheal.ogbozor1965/viz/OnlineStoreDataAnalysisfortheyear2010and2011/Dashboard1

## Conclusion:

•	Convenience; Most customers buy more during the day, possibly because they are free during this period to shop. The time with the highest number of customers is 12:00 pm, indicating that both working-class customers may have free time to get launch or generally breaks from work.

•	The country with the highest number of customers is the United Kingdom and it shows that customer within this demographic spend more than other countries

•	The month with the highest customers is November and this could be because, people get to shop for the festive season coming up (Christmas) and also it could be that  a lot of customers already have more money base on their savings from the beginning of the year.

## Recommendations: 

•	Online stores could create a more marketing campaigns or strategies example; knowing what kind of product that thrives in the countries where customers are few, creating promo sales for these countries where the customers are less or with low purchasing power Example; brazil.

•	I recommend that online store look into their product in terms of packaging and quality to ensure that it meets the audience preferences to avoid refund of products as done by some of these customers


