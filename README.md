# Amazon_Vine_Analysis

## Overview

Analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. We choose amazon_reviews_us_Wireless_v1_00.tsv.gz database and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. We also use Pandas to determine if there is any bias toward favorable reviews from Vine members in your dataset.


