# Amazon_Vine_Analysis
  This module contains a statistical analysis of Amazon reviews written by members of the paid Amazon vine program. Amazons Vine members provide incentive to create reviews 
  for the use of manufacturers and publishers. This analysis uses movie data The data can be found [here](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Music_v1_00.tsv.gz).
  This repository uses the power of Pyspark and Google colab to extract the data, create associated dataframes, connect to AWS and upload these dataframes to pgadmin. 



## Results
The number of vine reviews, non vine reviews, five star, and non five star reviews will be considered when issues are resolved. The resulting analsis will be located here in the results section. My hypothesis is that the verified vine members are biased in their reviews and provide better ratings for movies that are published by certain publishers.

## Summary 

The measure to determine if the Vine members are biased when reviewing movies is ones of the last considered. The two variables verified_five_star and non_verified_five_star measure the number of people whho gave five star reviews from each subtype. A significant difference indicates bias in the verified group. 
