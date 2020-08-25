# (Ford GoBike System Data)¶
Bashayer Alshehri (1 Aug, 2020)


## Dataset

This data include about '1863721' records and 15 features.
The feature are :
duration_sec  ----->  int64
start_time  ----->  object
end_time----->object
start_station_id----->float64
start_station_name----->object
start_station_latitude----->float64
start_station_longitude----->float64
end_station_id----->float64
end_station_name----->object
end_station_latitude----->float64
end_station_longitude----->float64
bike_id----->int64
user_type----->object
bike_share_for_all_trip----->object
Month----->object
Most variables numeric (int,float),but the variables 'start_time','end_time','start_station_name','end_station_name' ,'user_type','bike_share_for_all_trip','Month' are string.

## Summary of Findings

> Univariate:
- people using the bikes for a short-time durational trips (around 4.5 mins).
- oct is the most month that people use bikes, the lowest month is jan.
- the Subscriber is the most frequent than the customer.

> Bivariate:
- There was a constant limit throughout the year and it was about 15,000 seconds.
- June and July had the longest trips during those months.
- November and December had fewer trips that lasted as long.
- Almost all of the seasons were close to each other and most of the trips reached 24 mins.
- The heatmap plot of numeric variables, there is lots of negative correlation and few strong correlation

> Multivariate:
- customer through all of the months has longer trips duration than subscriber.
- Sunday and Saturday in the first months of the year the rush time was approximate about 35 minute to 40 minute.

## Key Insights for Presentation
-  Sunday and Saturday in the first months of the year the rush time was approximate about 35 minute to 40 minute.
