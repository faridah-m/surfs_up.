# surfs_up.
# Overview
Working with Temperature data to determine if a Surf and Ice Cream shop is viable year long. Using an sqlite as out dataset, we created an app in flask to return queries, retrieving the recent temperature data from the months of June and December, then converted those queries into Pandas DataFrames, in order to graph that data using MatPLotLib.

# Results
![Image](https://github.com/faridah-m/surfs_up./blob/main/June_Summary_Stats.PNG)
![Image](https://github.com/faridah-m/surfs_up./blob/main/December_Summary_Stats.PNG)

- June's average temperature was 74.9 degrees, December's was 71 degrees. Slight difference between June and December with both above standard room temperature.
- The minimum temperature recorded for June was 64, in December it was 56. While the June low should be fine for surf, it may not be the best case for selling ice cream
- However, these low temperatures do not occur very frequently. With a standard deviation of around 3 for both months, We know that the temperatures rarely fall too far from their mean. It will be consistenly temperate for a significant portion of the year.

# Summary
Although the temperatures in June are, on average higher than those in December, neither month frequently records temperatures below what would be considered comfortable for selling ice cream or surfing. Temperature is just one weather factor that could influence the business - additional queries could be run to determine precipitation, wind, or even atmospheric pressure, as those factors would also go in to a decision about surfing or buying ice cream. The data we are working with does not contain all weather factors that could influece the final decision, however it does give a good indication that temperature wise, there shouldn't be any issues. 
