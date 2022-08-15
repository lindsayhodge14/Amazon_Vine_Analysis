# Amazon_Vine_Analysis
Big Data (postgresql, spark, aws)

## Overview
In this project, we were tasked with assessing and manipulating big data, more particularly reviews related to Amazon products. I chose to conduct my project on pet products. I analyzed the reviews through PySpark, AWS and postgres to determine if there is a presence of bias within reviews due to Amazon vine, Amazon's paid review program. 

## Results
The following table illustrates how many vine and non-vine reviews were collected, and what percentage of each groups' reviews were 5 star reviews.

* How many Vine reviews and non-Vine reviews were there?

![bullet_1.png](/Resources/bullet_1.png) 

* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

![bullet_2.png](/Resources/bullet_2.png)

* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

![bullet_3.png](/Resources/bullet_3.png)

## Summary
Considering the calculations from above, it appears that bias is likely present amongst Amazon Vine participants. The majority (54%) of Amazon Vine participants rated their pet products with 5 stars, while pet products only earned 38% of unsolicited/unpaid earned a rating of 5 stars. Given that the number of individuals who were not paid through Amazon vine constitute a substantial portion of the reviews, it is unlikely that review biases presented by Vine participants is going to have a dramatic effect on a particular pet products rating. 

However, studying the particular products reviewed by Vine participants would be a helpful, supplemental study to our project. Knowing which products are likely to present skewed reviews or to be reflected inaccurately is key information for pet owners.
