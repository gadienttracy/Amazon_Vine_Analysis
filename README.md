# Amazon_Vine_Analysis
## Purpose
  The purpose of this analysis was to create an ETL of dataframes from a large dataset and upload them to a SQL server.  Additionally, analysis was preformed on a specific dataframe to determine paid vs. unpaid Amazon reviewers and whether it had an impact on their review (bias).
## Results
  -"How many Vine reviews and non-Vine reviews were there?"
    When determining whether reviewers were paid or not for their reviews the "vine" column was filtered for "Y" or "N"

  -"How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?"
    The dataframes were then filtered based on their 5 star reviews.


  -"What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?"
    From the above information the percent of 5 star reviews could then be determined


## Summary
  In summary there is no correlation between a positive review (5 stars) and whether the customer was paid.  In fact customers who were not paid actually had a higher 5 star percentage (52%).

  For further analysis it would be beneficial to see how many paid users received helpful votes.  If users are not finding the Vine reviewers feedback helpful, Vine may reconsider reimbursing users that do not provide helpful feedback.