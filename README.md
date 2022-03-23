# Amazon_Vine_Analysis

![](https://github.com/lightbright832/Amazon_Vine_Analysis/blob/main/amazon%20vine.jpg)

## Overview of the analysis
### Purpose
The purpose of this analysis was to extract, transform, and load data so that conclusions can be drawn on the results. With the help of RDS, Google Colab, and PGAdmin data was extracted, transformed, and loaded into tables. With this data it was possible to create visuals that depicted the number of reviews that were received from Amazon Vine members versus none members. The results help to determine if members are motivated to provide reviews that are not bias. 

## Results

![](https://github.com/lightbright832/Amazon_Vine_Analysis/blob/main/tables%20in%20pgadmin.png)

The tables were successfully created in pgAdmin

![](https://github.com/lightbright832/Amazon_Vine_Analysis/blob/main/customers%20table.png)

Customers_table data

![](https://github.com/lightbright832/Amazon_Vine_Analysis/blob/main/products%20table.png)

Products_table data

![](https://github.com/lightbright832/Amazon_Vine_Analysis/blob/main/review%20table.png)

Review_tables data

![](https://github.com/lightbright832/Amazon_Vine_Analysis/blob/main/vine%20table.png)

Vine_table data

![](https://github.com/lightbright832/Amazon_Vine_Analysis/blob/main/vine%20reviews.png)

* How many Vine reviews and non-Vine reviews were there?
There was a total of 61 Vine reviews and 28,174 non-Vine reviews

* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
There was a total of 20 "5" star reviews received, and 15,672 non-Vine "5" star reviews received

* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
33% of Vine reviews were 5 stars and 56% of non-Vine reviews were "5" star


## Summary:
Based on the results of the analysis it does not appear that there is any positivity bias for reviews in the Vine program. Members of the program only provided "5" star ratings 33% of the time when 56% of the time non-Vine members provided "5" star reviews. Those who are not members are more just as likely to provide "5" star ratings as those who are members. An additional analysis that could be done on the dataset would be the length of time customers were within the program to see if new members are more likely to provide reviews as those who have been members for a longer period. 

