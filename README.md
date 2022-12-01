# Amazon_Vine_Analysis

## Overview

Analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. We choose amazon_reviews_us_Wireless_v1_00.tsv.gz database and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. We also use Pandas to determine if there is any bias toward favorable reviews from Vine members in your dataset.


## Results: 
How many Vine reviews and non-Vine reviews were there?

How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
