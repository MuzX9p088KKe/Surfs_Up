# Surfs_Up: Weather Patterns and Trends Analysis

## Analysis Overview

The purpose of this analysis was to determine the viability of an ice cream and surf shop on Oahu. To that effect, weather data from the island was processed in order to determine whether temperatures would be favorable throughout the year and qualify as "ice cream weather."

The summary statistics for the temperatures from the months of June and December were extracted in order to compare seasonal trends.

## Results

After extracting the temperatures of interest from the dataset, the following summary statistics were assembled:

![June_stats](https://user-images.githubusercontent.com/76575162/123558026-cad5c300-d759-11eb-961b-76aa01eea3e3.png)
![Decemeber_stats](https://user-images.githubusercontent.com/76575162/123558047-dcb76600-d759-11eb-8e79-bf77e787be66.png)

From the summary of each month's temperatures, the following observations were made:

-  The amount of temperatures observed is about 10% lower in December compared to June. While this most likely would not cause significant issues due to the large sample size, it may mean that some extreme temperatures may have been missed.
-  The mean temperature over the months of June and December varied by less than 5°F, meaning the mean temperatures were fairly consistent.
-  The standard deviation was a bit higher in December, showing that December is a month in which temperatures had a higher variance.
-  The minimal temperatures were 64°F in June compared to 56°F in December. This would greatly affect the amount of ice cream sales, as temperatures around 56°F would likely cause the ice cream demand to be quite low and would likely not be good for surfing either.
- The maximal temperatures were 85°F in June compared to 83°F in December. While this is much hotter than the lowest December temperature, it does not seem to be too hot for prospective customers to be out surfing and would be ideal ice cream weather also.

## Summary

As demonstrated through this analysis, the ice cream and surf shop on Oahu may turn out to be a good venture, at least according to weather data. The average temperatures over the months of June and December seem pretty close, meaning there would be a good chance that the shop would see consistent business throughout the year. The biggest issue that was unearthed through the analysis would be the wider variance in temperatures in December and likely most winter months. This may cause the shop to be less profitable over the course of these few months, but probably will not see enough of a decrease in sales to have an out-of-season period. 

A deeper analysis may help gauge the impact of the lower temperatures periods and quantify the amount of time the business would see a noticeable decrease in sales. 

Another helpful query would be to filter the count for the amount of days within a certain temperature range. To make this query even more useful, the temperature data could be paired with the precipitation data to filter out rainy days as rain would potentially adversely impact sales, even on a day within the ideal temperature range.

Limiting the scope of this analysis may also provide too narrow a dataset, so adding the months of Mars and September as representatives of other seasons would provide valuable insights. However, since such queries would actually be quite easy to add, analyzing the entire year may be something to consider either using the temperature summary stats or the method mentioned above, painring it with precipitation data.


