# Amazon_Vine_Analysis
## Overview of the analysis

Analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products.
In this project, I have accessed https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Toys_v1_00.tsv.gz for my analysis.
This contains reviews of a specific toys and used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin.Then we can use either PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset.

## Results :

- How many Vine reviews were there? 62028
- How many Non-Vine reviews were there? 1266
- How many Vine reviews were 5 stars? 14324
- How many non-Vine reviews were 5 stars? 16090
- What percentage of Vine reviews were 5 stars? 48%
- What percentage of non-Vine reviews were 5 stars? 47%

## Summary 
According to the above summary the percentage of 5 star reviews for each paid and unpaid very close in numbers. 48% and 47% 
This analysis does not show any bias towards the vine program. 
