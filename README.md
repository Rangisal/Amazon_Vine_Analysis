# Amazon_Vine_Analysis
Analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products.
In this project, I have accessed https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Toys_v1_00.tsv.gz for my analysis.
This contains reviews of a specific toys and used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin.Then we can use either PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset.

