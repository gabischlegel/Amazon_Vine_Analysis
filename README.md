# Amazon_Vine_Analysis
Module 16
## Overview 
In this project I analyzed Amazon reviews for watches written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.
I used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset.

## Results
There were 43 Vine reviews and 7750 non-Vine reviews. 
<img width="332" alt="image" src="https://user-images.githubusercontent.com/110864175/204690106-60e78ed3-ffea-4e33-8a8b-4e4c09319d19.png">

There were 14 five-star Vine reviews and 4027 five-star non-Vine reviews.
<img width="452" alt="image" src="https://user-images.githubusercontent.com/110864175/204690290-0bb75006-bb31-4e29-84f8-b7855a4ebed9.png">

32.56% of the Vine reviews were five stars while 51.96% of non-Vine reviews were five stars. 
<img width="458" alt="image" src="https://user-images.githubusercontent.com/110864175/204690342-9d72430c-c5f1-4ccc-8b44-1dd49839298e.png">

## Summary 
Per this analysis, there was no positivity bias for the Vine program. The program only came out with an 32.55% of the total reviews being five-star reviews. There were only 14 five-star reviews that were through the Vine program and only 43 Vine program reviews in total. The non-Vine reviews were more positive as 51.96% of the total reviews were five-star reviews. There was a of 7750 five-star reviews that were not through the Vine program and 4027 non-Vine reviews in total. I would perform an additional analysis to see the quantity and percentage of 1-star reviews in the Vine program and in the non-Vine program. This was we could see if the Vine program does not feel comfortable giving 1-star reviews. 
