# Amazon_Vine_Analysis

## Overview of the analysis of the Vine program

The purpose of this analysis was to determine if there was favorable bias of reviews from Vine members in Amazon ratings of a set of products. I looked at a dataset about video games, and used PySpark, Google Colaboratory, AWS and PostgreSQL to extract, transform and load the data, and analyze it.

## Results

1. Vine reviews and non-Vine reviews: There were 40,471 non-Vine and 4,291 Vine reviews in our dataset about video games.

3. Vine reviews that were 5 stars; Non-Vine reviews that were 5 stars: According to this dataset, there were 15,711 five-star reviews total. There were 15,663 five-star reviews that were non-Vine.
<img src="https://github.com/itochax23/Amazon_Vine_Analysis/blob/51af19b43a94cfd64a8295d08bca6948df57f694/Resources/totals.png" height="300">

5. Percentage of Vine reviews that were 5 stars: percentage of non-Vine reviews that were 5 stars: 38.2% of the five-star reviews were Vine, while 38.9% of the five-star reviews were from a source other than Vine.
<img src="https://github.com/itochax23/Amazon_Vine_Analysis/blob/51af19b43a94cfd64a8295d08bca6948df57f694/Resources/percentages.png" height="300">

## Summary

There does not appear to be any significant bias based on whether a review was from members of the Vine community, because the percentages of five-star ratings from non-Vine and Vine members was about the same, at around 38%. This would indicate there's no favorable bias but there's also no negative bias, and not all of the five-star ratings are generated from Vine members.
