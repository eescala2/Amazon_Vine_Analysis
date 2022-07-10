# Amazon_Vine_Analysis
Analysis utilizing PySpark to perform ETL extracting one of the numerous datasets from Amazon reviews written by Amazon Vibe members. Transforming data, connecting to AWS RDS, and loading data into pgAdmin to identify bias from Vine members. The dataset taken from Amazon will consist of Furniture items.

# The Results
![Screen Shot 2022-07-10 at 6 06 52 PM](https://user-images.githubusercontent.com/102098068/178165528-33ed2ae1-5e2b-4db1-a56c-06659dee9a95.png)

* There is a huge discrepancy in the amount of non-Vine reviews as compared to Vine reviews. As the photo above indicates, there are a total of 136 for Vine reviews. The rest, around 99% of reviews are non-Vine members. 

![Screen Shot 2022-07-10 at 6 12 22 PM](https://user-images.githubusercontent.com/102098068/178165717-2185f355-0724-4c37-a73e-5f0da54baf92.png)

* For Vine and non-Vine 5 star reviews, there is a percentage of 5 star reviews from Vine of 54.4%, and 47% for non-Vine reviews for furniture.

# Conclusion
From this analysis, one can conclude that there is a positivity bias coming from Vine members in the furniture category. There are other datasets however that would have to be analyzed to make sure that the bias is not solely from furniture and it is actually from Vine members. Additional analyses could also be employed, such as summary statistics (mean, median, mode for star ratings) and checking out more different categories. 
