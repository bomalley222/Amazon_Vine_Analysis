# Amazon_Vine_Analysis

## Overview of the Analysis

### The purpose of this analysis is to analyze Amazon reviews written by Amazon Vine members. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products.
###  The ETL process is used to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. PySpark, was used to determine if there is any bias toward favorable reviews from Vine members in your dataset.

## Results
### * There were 1,080 paid Vine reviews, and 49,673 unpaid reviews, totalling 50,753 reviews
### * There were 454 5-star paid Vine reviews, and 23,043 5-star unpaid reviews
### * 42% of the paid Vine reveiws were 5-star, and 46% of the unpaid reviews were 5-star

## Summary
### Our results do not show positivity bias, as the unpaid reviews had a greater 5-star review percentage. 

### The dataset we used to perform this analysis has been filtered. The original dataset has 3,093,869 reviews, and the filters used brought this number down to 50,753. It might be useful to perform this analysis without these filters, to gain greater insight.
