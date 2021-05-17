# Amazon_Vine_Analysis
  This module contains a statistical analysis of Amazon reviews written by members of the paid Amazon vine program. Amazons Vine members provide incentive to create reviews 
  for the use of manufacturers and publishers. This analysis uses movie data The data can be found [here](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Music_v1_00.tsv.gz).
  This repository uses the power of Pyspark and Google colab to extract the data, create associated dataframes, connect to AWS and upload these dataframes to pgadmin. 



## Results
As we can see by analyzing the last few cells of [amazon_vine_analysis.ipynb](https://github.com/K-Sharma95/Amazon_Vine_Analysis/blob/main/Vine_Review_Analysis.ipynb), about 70% of our total reviws were conducted by verified members, or members of the vine program. This suggests that the large majority of reviews are conducted with an incentive from the verified vine group; to be presented to the publisher. This data suggests that the reviewers who had this incentive were more likely to give a five star review for that publisher. 

## Summary 

The measure to determine if the Vine members are biased when reviewing movies is ones of the last considered. The two variables verified_five_star and non_verified_five_star measure the number of people whho gave five star reviews from each subtype. A significant difference indicates bias in the verified group. The variance caluclated was about 6%-7%. This means that members of the vine program were more likely to give a five star review than a non-member. In my opinion this suggests a slight bias among the verified vine program members, to give a good review to a publisher who you have been hired to review. This is an expectedbias in this case, and the low percentage difference suggests that most reviewers who were biased just exaggerated their scores, rather than scoring a low-ranking film with a five star review. 
