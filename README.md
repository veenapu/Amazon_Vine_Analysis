# Amazon_Vine_Analysis
# Module_16_Big_Data

## Overview of the analysis: Explain the purpose of this analysis.
Analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

## Deliverable 1: Perform ETL on Amazon Product Reviews
The Amazon_Reviews_ETL.ipynb file does the following:
- An Amazon Review dataset is extracted as a DataFrame
- The extracted dataset is transformed into four DataFrames with the correct columns
- All four DataFrames are loaded into their respective tables in pgAdmin 

## Deliverable 2: Determine Bias of Vine Reviews
The analysis does the following:
- There is a DataFrame or table for the vine_table data using PySpark, Pandas, or SQL
- The data is filtered to create a DataFrame or table where there are 20 or more total votes
- The data is filtered to create a DataFrame or table where the percentage of helpful_votes is equal to or greater than 50%
- The data is filtered to create a DataFrame or table where there is a Vine review
- The data is filtered to create a DataFrame or table where there isn’t a Vine review
- The total number of reviews, the number of 5-star reviews, and the percentage 5-star reviews are calculated for all Vine and non-Vine reviews

## Results: Using bulleted lists and images of DataFrames as support, address the following questions:

### Total number of Vine reviews and non-Vine reviews
fig 1
fig 2

### Total number of 5-star Vine reviews and 5-star non-Vine reviews
fig 3
fig 4

### Total percentage of 5-star Vine reviews and 5-star non-Vine reviews
fig 5
fig 6

## Summary: 
Looking at the analysis, positivity bias can be seen for the reviews in the Vine program.  51 % of Vine reviews were 5 stars while the percentage of non-Vine reviews is ony 39%. 

Additionally, a statistical analysis can be done for trhe star rating for the vine and non-vine reviews.