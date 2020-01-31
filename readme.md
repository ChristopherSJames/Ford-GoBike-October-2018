# Ford Gobike Exploration
## by Christopher James


## Dataset

This dataset contains information on the 201458 Ford Gobike rides taken in October 2018. Attributes of these rides include duration in seconds, latitude and longitude for the
start and end locations, whether they were subscribers or just one-off customers, if they were part of a financially restricted program called "bike share for all", and others.
I engineered a column that indicated what hour of the day the ride started to aid in my analysis. The link for the dataset can be found
[Here](https://s3.amazonaws.com/baywheels-data/index.html). The feature documentaion of this dataset can be found [Here](https://www.lyft.com/bikes/bay-wheels/system-data). 


## Summary of Findings

To begin my analysis, I found that after plotting the chart in a log scale and cropping out some outliers, the distribution of the duration of the rides was unimodal
and most lasted between 300 to 1000 seconds. I found that when plotting the distribution of the ride start time by hour, the results are bimodal. There is a rapid
ramp up to the first peak at 9 AM, a moderate regression and plateau until the second peak at 6 PM, followed by a gradual decline. There are few night time riders.
I also found that the vast majority of users are subscribers rather than customers. The exact opposite occured with members of the bike program. The vast majority
are not apart of it. There were no meaningful differences in ride duration based on the hour the ride started. During the 9 AM and 6 PM peaks and those surrounding
them, subscribers were responsible for the lion's share of the growth, while customers increased only moderately, percentage-wise. Customers had a median ride duration
nearly double that of subscribers. Bike share participants had a median ride duration somewhat less than non-participants. Non-participants also generated the majority
of the growth surrounding and during the peak periods. When broken down by hour started, customers were responsible for most of the rides with the longest durations.
There were no meaningful differences in ride duration between bike share participants and non-participants when broken down by hour.


## Key Insights for Presentation

For this presentation, I focused mostly on the effect the user type and starting hour had on ride count and ride duration. I started out by showing the distribution of rides broken down by each the duration of the ride and the user type. I then showed the ride distribution by both
of those features together. I showed the median ride duration by user type and then bike share status. Finally, I showed on a scatterplot the 
makeup of different ride durations broken down by both starting hour and user type.
