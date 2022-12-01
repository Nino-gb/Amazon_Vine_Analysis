# Amazon_Vine_Analysis

## Overview

We are analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. We choose amazon_reviews_us_Wireless_v1_00.tsv.gz database and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. We also use SpySpark to determine if there is any bias toward favorable reviews from Vine members in your dataset.


## Results: 

- How many Vine reviews and non-Vine reviews were there? 
Vine = 613
non-Vine = 64771

- How many Vine reviews were 5 stars? 
Vine = 222

- How many non-Vine reviews were 5 stars?
Non-Vine = 30523

- What percentage of Vine reviews were 5 stars? 
Vine = 36

- What percentage of non-Vine reviews were 5 stars?
Non-vine = 47

![Screenshot 2022-12-01 at 12 08 39 AM](https://user-images.githubusercontent.com/110786136/204978735-61c67cfd-04cd-4f75-9bf6-8c158ff95e69.png)



## Summary: 

With the results above we can conclude that there is not bias for reviews in the Vine program. Unpaid vine had a higher total reviews , 5 Star Total and 5 Star percentages. Verified_purchase column should be anayzed and filtered before calculating the vine total review to confirm the veracity of the review and avoid any mistake or discrepancy in the report.
