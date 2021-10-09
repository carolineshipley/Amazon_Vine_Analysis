# Amazon_Vine_Analysis
## Overview

The purpose of this project is to analyze video game Amazon Vine reviews. 

For this project was performed an ETL performed on the data by using AWS, Google Colaboratory, PostgreSQL, and PySpark. Then the result tables were analyzed to determine if there was any bias for reviews in the Vine Program.

## Results

The objective of this analyzis is to answer the following questions:
1. How many Vine reviews and non-Vine reviews were there?
2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

And these are the result of the analyzis:

1. There are 94 vine reviews and 40,471 non-vine reviews.
2. There were 48 5-star vine reviews and 15663 5-star non-vine reviews.
3. 51.06% of paid reviews are 5-stars and 38.7% of unpaid reveiws are 5-stars.

![Results](https://github.com/carolineshipley/Amazon_Vine_Analysis/blob/main/Resources/Results.PNG)

## Summary

Taking into consideration that the sample of non-vine reviews are much greater than vine review,and that the the paid reviews correspond to 51% of 5-starts and un-paid correspond to 38% of the 5-stars. With that we can conclude that there is a positivity bias for reviews in the Vine program. 
An additional analysis to have a better understanding of reviews patterns is to analyze REVIEW_ID and CUSTOMER_ID to see if a specific customer have a tedency of providing positive or negative reviews.
