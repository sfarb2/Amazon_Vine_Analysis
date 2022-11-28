# Amazon_Vine_Analysis

## Purpose
The purpose of this analysis was to determine whether Vine reviews of a specific subset of Amazon data (sports) exhibited positivity bias that was not present for non-Vine reviews.

## Results
- The data set was heavily weighted toward non-Vine reviews; there were nearly 200 times more of them (61,614) than Vine reviews (334).

![vine_total_reviews](/vine_total_reviews.png)

![Other_total_reviews](/other_total_reviews.png)

- There were 139 5-star Vine reviews compared to 32,665 5-star reviews that were not from Vine.

![vine_5_reviews](/vine_5_reviews.png)

![Other_5_reviews](/other_5_reviews.png)

- Not only is the chasm between the two groups of 5-star reviews enormous, but also the percentage of 5-star reviews differs greatly as well. Less than 42% of Vine reviews earned 5 stars whereas greater than 53% of non-Vine reviews did so.

![vine_5_pct](/vine_5_pct.png)

![Other_5_pct](/other_5_pct.png)

## Summary
In conclusion, it certainly seems as if the Vine reviews do not exhibit any positivity bias. Though there are fewer data points (compared to the volume of non-Vine reviews) and thus the sample could be less significant, more than 10 percentage points _fewer_ Vine reviews received 5-star ratings. Further investigation could potentially drill down on verified purchases to ensure that the reviewers actually did buy and receive the item that they were reviewing. 


#### Note
I was unable to load the vine_table.csv to Github because of size restrictions, so it's stored at this Google Drive link:
https://drive.google.com/file/d/1KL9AGyAwUkuYFztPn9vN0PcJ45CHRuG0/view?usp=share_link
