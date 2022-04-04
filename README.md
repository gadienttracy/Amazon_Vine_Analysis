# Amazon_Vine_Analysis

## Purpose
  The purpose of this analysis was to create an ETL of dataframes from a large dataset and upload them to a SQL server.  Additionally, analysis was preformed on a specific dataframe to determine paid vs. unpaid Amazon reviewers and whether it had an impact on their review (bias).

## Results
  -"How many Vine reviews and non-Vine reviews were there?"
    When determining whether reviewers were paid or not for their reviews the "vine" column was filtered for "Y" or "N"
![vine_counts](https://user-images.githubusercontent.com/91269696/161457378-101ebf49-1122-444e-8341-107c6766f20c.PNG)

  -"How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?"
    The dataframes were then filtered based on their 5 star reviews.
![paidfivestar](https://user-images.githubusercontent.com/91269696/161457392-793b6ca2-3e71-44df-b9c6-7cf190186103.PNG)
![unpaidfivestar](https://user-images.githubusercontent.com/91269696/161457398-dcbd45fb-76cb-4df9-835b-c4abd5e5c933.PNG)

  -"What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?"
    From the above information the percent of 5 star reviews could then be determined
![paidpercent](https://user-images.githubusercontent.com/91269696/161457404-3be0252b-adc0-4ea8-8718-a81ffb5ad566.PNG)
![unpaidpercent](https://user-images.githubusercontent.com/91269696/161457414-a72b7e3d-db36-4ded-aceb-c3f256872ec1.PNG)

## Summary
  In summary there is no correlation between a positive review (5 stars) and whether the customer was paid.  In fact customers who were not paid actually had a higher 5 star percentage (52%).

  For further analysis it would be beneficial to see how many paid users received helpful votes.  If users are not finding the Vine reviewers feedback helpful, Vine may reconsider reimbursing users that do not provide helpful feedback.
