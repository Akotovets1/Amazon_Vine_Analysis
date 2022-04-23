# Amazon_Vine_Analysis
Big Data using PySpark, Amazon Web Service (AWS), Google Colaboratory, and pgAdmin

## Overview
Data analysts were tasked with analyzing Amazon reviews written by members of the paid Amazon Vine program. 
Data from Amazon's Shoes department was analyzed to determine if having a paid Vine review makes a difference in the percentage of 5-star reviews.  
The Extract, Transform, and Load (ETL) process was used on the Amazon Shoes dataset.  
pgAdmin was utilized to connect to AWS, and pySpark and postgreSQL were used against the data set to create four separate DataFrames to match the table schema in pgAdmin.  
The transformed data was then uploaded into AWS RDS.


## Results

![Pic 1](https://github.com/Akotovets1/Amazon_Vine_Analysis/blob/main/images/19.png)

### How many Vine reviews and non-Vine reviews were there?

Total number of reviews were 4366916

Total number of 5-star reviews were 2639935


### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

Total number of Vine 5-star reviews were 13

Total number of non-Vine 5-star reviews were 14475

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

Percentage of Vine 5-star reviews were 59%

Percentage of non-Vine 5-star reviews were 54%


## Summary

Based on analysis of the sample selected from the Amazon Shoes reviews, Vine reviews did not appear to have affected the 5-star reviews. There are slightly more 5-star reviews from unpaid reviews.

Additional analysis might be performed on all other Amazon review datasets with the same parameters that were used for the Shoes dataset.




