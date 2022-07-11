# Amazon_Vine_Analysis
## Overview
The purpose of this analysis was to use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed date into pgAdmin. We were able to choose a dataset and determine if there was any bias toward favorable reviews from Amazon Vine members using PySpark. I choose a dataset that analyzed shoe reviews.
## Results
### How many Vine reviews and non-Vine reviews were there?
Based on the shoe dataset, there were a total of 22 Vine reviews and 26,987 non-Vine reviews.
<img width="905" alt="Screen Shot 2022-07-11 at 11 50 08 AM" src="https://user-images.githubusercontent.com/101950175/178336781-81bf1336-7a08-410c-a72f-3c4bf497115d.png">

### How many Vine reviews were 5 stars?  How many non-Vine reviews were 5 stars?
Out of the 22 Vine reviews, 13 were 5 star, and out of the 26,987 non-Vine reviews, 14,475 were 5 star.
<img width="905" alt="Screen Shot 2022-07-11 at 11 52 40 AM" src="https://user-images.githubusercontent.com/101950175/178337256-5184b04f-958f-4759-86ff-ad402fbdab1a.png">

### What percentage of Vine reviews were 5 stars?  What percentage of non-Vine reviews were 5 stars?
The percentage of Vine reviews that were 5 stars was 59.1% and the percentage of non-Vine reviews that were 5 stars was 53.6%.
<img width="902" alt="Screen Shot 2022-07-11 at 11 54 30 AM" src="https://user-images.githubusercontent.com/101950175/178337580-06c0d23e-5f40-4e8c-b80f-0a63167983b8.png">
