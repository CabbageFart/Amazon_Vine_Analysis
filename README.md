# Amazon_Vine_Analysis
![image](https://user-images.githubusercontent.com/111661058/230699844-48b44db1-0230-438d-921f-8c1f1ccfb48e.png)
## Purpose
We are trying to determine if there is any bias towards reviews that were written as part of the Vine program. We will divide the reviews into two different dataframes:Paid and Unpaid. Once we have those we will be able to count the amount of 5 star reviews for both camps and see if the Paid camp is inded biased.

## Results
We decided to take a look at the Personal Healthcare product category beacuse we certainly do not want any bias in that category. Our inital dataframe looked like this;
![image](https://user-images.githubusercontent.com/111661058/230700796-a4266c0d-b34a-4a54-b461-87b775c31579.png)
Alot more columns than we need to do this analysis. So we grabbed the view that we deemed important for our work.
![image](https://user-images.githubusercontent.com/111661058/230700940-4e1b8f77-2154-4e1e-8e4a-c7f5f37d3050.png)<BR>
Once that was done we then started out task of looking into bias.
* Reviews
  * 497 paid reviews
  * 120863 unpaid reviews
* 5 Star reviews
  * 220 paid 5 star ratings
  * 74470 unpaid 5 star ratings
* percentage of 5 Star reviews
  * 44.27% of paid reviews had a 5 star rating
  * 61.62% of unpaid reviews had a 5 star rating
## Summary
We did not see any bias based on the 5 star reviews from the paid participants. Only 44% of reviews came back as 5 star for the paid, while 61% for the unpaid came back at 5 star. Not having any bias from the paid participants means that they did actually take there part seriously. It would behoove someone, we think, to read the paid reviews.<BR>
### Other Analysis Suggestions
  * A further breakdown of the star system to have a dataframe for all 5 star ratings
  * Check to see how many reviews there were for each unique product and their star rating breakdown
  * Filter existing dataframes for marketplace and if the reviewer actaully purchased the product
