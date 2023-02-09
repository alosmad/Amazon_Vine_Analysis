# Amazon_Vine_Analysis
Module 17 Challenge

## Overview of the analysis
The purpose of the analysis is to analyze Amazon review for musical instruments, we will segment our analysis by comparing Vine verified purchases vs Vine not-verified purchases so we can conclude if there is any bias for the reviews if the Vine program is used or not.

## Results

From our vine review table we have a total of 904,765 review but not of them are helpful votes so we will focus on the helpful votes where helpful votes divided by total votes is equal to or greater than 50%, with this table we have the following results.

![HelpfulVotes50percent](https://github.com/alosmad/Amazon_Vine_Analysis/blob/62b7c88aba79ba8f89b1843cd36060c81f332438/HelpfulVotes50percent.png)

- We have a total of 8,610 verified vine reviews and a total of 5,927 non-verified vine reviews

![HelpfulVotesVine](https://github.com/alosmad/Amazon_Vine_Analysis/blob/62b7c88aba79ba8f89b1843cd36060c81f332438/HelpfulVotesVine.png)

![HelpfulVotesnonVine](https://github.com/alosmad/Amazon_Vine_Analysis/blob/62b7c88aba79ba8f89b1843cd36060c81f332438/HelpfulVotesnonVine.png)

![totalverifiedandnonverified](https://github.com/alosmad/Amazon_Vine_Analysis/blob/62b7c88aba79ba8f89b1843cd36060c81f332438/totalverifiedandnonverified.png)

- The total review with a 5 star rating are:

  ° Verified vine review = 4,940

  ° Non-verified vine reviews = 3,306
  
  ![total5star](https://github.com/alosmad/Amazon_Vine_Analysis/blob/62b7c88aba79ba8f89b1843cd36060c81f332438/total5star.png)

- Percentage of 5 star rating reviews:
  
  ° Verified vine review = 57.4%
  
  ° Non-verified vine reviews = 55.8%
  
  ![percentage5star](https://github.com/alosmad/Amazon_Vine_Analysis/blob/62b7c88aba79ba8f89b1843cd36060c81f332438/percentage5star.png)
  
## Summary

With this numbers we can conclude that with the significant helpful votes there is a little positive bias for reviews if the product is a vine verified purchase.
Using NPL with pyspark it will be very interesting to analyze 5 star rating reviews so we can see which is the most valuable features that customers rate in a musical instrument this will be helpful to manufacturers if it is a technical feature or a design feature.

Alejandro Madrigal

Data Analysis



