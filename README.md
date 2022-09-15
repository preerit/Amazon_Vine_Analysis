# Amazon_Vine_Analysis

## Overview of Project

 We are analyzing one of the 50 databases. The major information this database provides is for the reviews. One of the key information we would like to analyze is the paid program -Vine. We will use PySpark to download the data and import to pgAdmin and create several different tables for different analyzing purposes.

### Results
* How many Vine reviews and non-Vine reviews were there?
Vine reviews: 585
non-Vine reviews: 61139
* How many Vine reviews were 5 stars? 
28839
* How many non-Vine reviews were 5 stars?
213
* What percentage of Vine reviews were 5 stars? 36.41 %
* What percentage of non-Vine reviews were 5 stars? 47.17%


### Summary
   
We sorted out the data with higher helpful votes and then compare pain and non-paid members for the vine program. The result should be closer to the actual situation than just use star-rating column However, we only use 5-start in the star-rating column. My suggestion would be taking 4-star rating into consideration and we can see some data from customers who actually enjoy the program as well even it is not their favorite.
