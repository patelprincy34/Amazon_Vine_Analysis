# Amazon_Vine_Analysis
Big Data

### Overview
For this project I choose Video Games data from Amazon reviews.  I utilized Pyspark to complete the ETL process by extracting, processing, and connecting to a database through the AWS webserver. I used Pyspark again to determine if there is any bias towards reviews that were written as part of the Vine program.

### Results
#### How many Vine reviews and non-Vine reviews were there?
* Total of Vine reviews: 94

![image](https://user-images.githubusercontent.com/93439516/156948402-1a7b6d49-e879-4287-ad77-f578849fc21e.png)

* Total of Non-Vine reviews: 40471

![image](https://user-images.githubusercontent.com/93439516/156948429-af6ae04e-ed50-446d-b680-3dedfc2a1bc7.png)

#### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
* Total of Vine Five-Star reviews: 48

![image](https://user-images.githubusercontent.com/93439516/156948603-79d5bc55-0487-4990-9a78-89d52d21ee25.png)

* Total of Non-Vine Five-Star reviews: 15663

![image](https://user-images.githubusercontent.com/93439516/156948568-58835b71-53d7-4b50-8d48-ebb836d5cdc7.png)


#### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
 
 * Total percentage of Vine Five-Star reviews: 51%

![image](https://user-images.githubusercontent.com/93439516/156948768-ac9754ee-3ae6-4329-8f6e-2c72e659d7e4.png)

* Total percentage of Non-Vine Five-Star reviews: 39%

![image](https://user-images.githubusercontent.com/93439516/156948804-3b5c386b-24ee-4570-83ba-d1ff7b20f13e.png)

### Summary
In the Vine program there is a positivity bias for reviews because 51% of the Vine reviews were 5 stars, compared to only 39% in non-Vine reviews. We might also look at the statistical distribution of the star rating for Vine and non-Vine reviews (mean, median, and mode).
### Resources
* Data Source: https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz
* Sofware: PostgreSQL, pgAdmin, Google Colab Notebook, AWS
