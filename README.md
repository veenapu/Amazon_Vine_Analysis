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
![total_vine_reviews](https://github.com/veenapu/Amazon_Vine_Analysis/blob/main/Images/fig1_total_vine_reviews.PNG)

<<<<<<< HEAD

=======
>>>>>>> ac5d69b48a412ef21ecab849aed52dc9128302ad
![total_non_vine_reviews](https://github.com/veenapu/Amazon_Vine_Analysis/blob/main/Images/fig2_total_non_vine_reviews.PNG)

### Total number of 5-star Vine reviews and 5-star non-Vine reviews
![no_of_5_star_reviews](https://github.com/veenapu/Amazon_Vine_Analysis/blob/main/Images/fig3_total_vine_5_star_reviews.PNG)

![no_of_5_star_non_vine_reviews](https://github.com/veenapu/Amazon_Vine_Analysis/blob/main/Images/fig4_total_non_vine_5_star_reviews.PNG)

### Total percentage of 5-star Vine reviews and 5-star non-Vine reviews
![total_percentage_vine_reviews](https://github.com/veenapu/Amazon_Vine_Analysis/blob/main/Images/fig5_total_percentage_vine_reviews.PNG)

![total_percentage_non_vine_reviews](https://github.com/veenapu/Amazon_Vine_Analysis/blob/main/Images/fig6_toal_percentage_non_vine_reviews.PNG)

## Summary: 
Looking at the analysis, positivity bias can be seen for the reviews in the Vine program.  51 % of Vine reviews were 5 stars while the percentage of non-Vine reviews is ony 39%. 

<<<<<<< HEAD
Additionally, a statistical analysis can be done for the star rating for the vine and non-vine reviews.
=======
Additionally, a statistical analysis can be done for trhe star rating for the vine and non-vine reviews.
>>>>>>> ac5d69b48a412ef21ecab849aed52dc9128302ad
