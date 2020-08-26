# (Ford GoBike System Data)¶
> Bashayer Alshehri (1 Aug, 2020)

This project was completed as part of Udacity's Data Analyst Nanodegree certification.

## Dataset
> Ford GoBike System Data for 2018
you can find the dataset here : https://www.lyft.com/bikes/bay-wheels/system-data


> This data include about '1863721' records and 15 features.
The feature are :
- duration_sec  ----->  int64
- start_time  ----->  object
- end_time----->object
- start_station_id----->float64
- start_station_name----->object
- start_station_latitude----->float64
- start_station_longitude----->float64
- end_station_id----->float64
- end_station_name----->object
- end_station_latitude----->float64
- end_station_longitude----->float64
- bike_id----->int64
- user_type----->object
- bike_share_for_all_trip----->object
- Month----->object
- Most variables numeric (int,float),but the variables 'start_time','end_time','start_station_name','end_station_name' ,'user_type','bike_share_for_all_trip','Month' are string.

## Summary of Findings

> Univariate:
- People using the bikes for a short-time durational trips (around 4.5 mins).
- October is the most month that people use bikes, the lowest month is January.
- The Subscriber is the most frequent than the customer.

> Bivariate:
- There was a constant limit throughout the year and it was about 15,000 seconds.
- June and July had the longest trips during those months.
- November and December had fewer trips that lasted as long.
- Almost all of the seasons were close to each other and most of the trips reached 24 mins.
- The heatmap plot shows that there are lots of negative correlation and few strong correlation.

> Multivariate:
- Customer through all of the months has longer trips duration than subscriber.
- Sunday and Saturday in the first months of the year the rush time was approximate about 35 minute to 40 minute.

## Key Insights for Presentation
> The heatmap plot shows that there are lots of negative correlation and few strong correlation. Sunday and Saturday in the first months of the year the rush time was approximate about 35 minute to 40 minute,October is the most month that people use bikes, the lowest month is January.
