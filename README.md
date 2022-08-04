# Amazon_Vine_Analysis
## Project Overview
 The purpose of this project is to analyze Amazon Vine program data and conclude whether there is any meaningful impact caused by positive or negative reviews. I used PySpark to perform the ETL process to extract, transform and load the dataset using AWS, postgresql, Google Colab. I chose to analyze US reviews of toys on Amazon from the 50 different datasets. 

## Resources
- Data Sources: [Amazon Review datasets](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt), [Toys Review datasets](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Toys_v1_00.tsv.gz)
- Software:  Google Colab Notebook, PostgreSQL 11.9, pgAdmin 4, AWS

## Results

### Filtered total_votes above or equal to 20

![Filtered_Dataframe.png]()

### Filtered helpful_votes ratio above or equal to 50%

![Total_reviews]()

### Vine reviews and non-Vine reviews

![Vine_reviews]()

![non-Vine_reviews]()

### 5 stars Vine and non-Vine reviews / Percentage of 5 stars Vine and non-Vine reviews

![fivestar_percentage]()

## Summary
In conclusion, I found out that 34% of 5 star reviews originated from Vine users, compared to 48% of 5 star reviews originated from non-Vine users. Results do not show bias towards Amazon Vine reviewers in the dataset. I believe we should also analyze 1 Star to 4 Stars review data in order to determine if there is any meaningful impact of View reviewers.