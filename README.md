# Amazon_Vine_Analysis

## Overview of Project
This project analyzes Amazon reviews for softwares sold on its platform. The purpose of this project is to determine whether there is a bias in the reviews written by members of the paid Amazon Vine program - a service that allows manufacturers and publishers to receive reviews for their products. We have used PySpark to perform the ETL process, connect to an AWS RDS instance and load the transformed data in pgAdmin. Pyspark is again used to determine any bias toward favorable reviews from Vine members. 


## Results

- **Total Vine Reviews** - 
![Total Vine Reviews](https://github.com/vedikanigam/Amazon_Vine_Analysis/blob/main/Images/Total_vine_reviews.png)

There are 248 total vine reviews.
	
- **Total Non-Vine Reviews** -
![Total Non-Vine Reviews](https://github.com/vedikanigam/Amazon_Vine_Analysis/blob/main/Images/Total_nonvine_reviews.png)

There are 17,514 total non-vine reviews.


- **Total 5 star Vine Reviews** -
![Total 5 star Vine Reviews](https://github.com/vedikanigam/Amazon_Vine_Analysis/blob/main/Images/Fivestars_Vine_stars.png) 

Out of the 248 reviews, 102 are 5 star reviews.


- **Total 5 star Non-Vine Reviews** - 
![Total 5 star Non-Vine Reviews](https://github.com/vedikanigam/Amazon_Vine_Analysis/blob/main/Images/Fivestar_nonvine_reviews.png)

Out of the 17,514 reviews, 5,154 are five star reviews.

- **Percentage - 5 star Vine Reviews ** - 
![Percentage 5 star Vine Reviews](https://github.com/vedikanigam/Amazon_Vine_Analysis/blob/main/Images/Percentagefivestars_Vine_reviews.png)

41% of the total vine reviews are five star reviews.	

- **Percentage - 5 star Non-Vine Reviews ** - 
![Percentage 5 star Non-Vine Reviews](https://github.com/vedikanigam/Amazon_Vine_Analysis/blob/main/Images/Percentagefivestars_Nonvine_reviews.png)

29% of the total non-vine reviews are five star reviews.

## Summary

From the calculations, we can clearly see that there is a positivity bias for reviews in the Vine program. 41% of the Vine reviews are 5 stars in comparison to 29% of the non-vine reviews. 

It would be helpful to further find out what is the average helpful rating for paid reviews versus unpaid reviews. 