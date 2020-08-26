# (Ford GoBike System Data)¶
> Bashayer Alshehri (1 Aug, 2020)

## Introduction :

- Bay Wheels is a regional public bicycle sharing system in California's San Francisco Bay Area. It is operated by Motivate in a partnership with the Metropolitan Transportation Commission and the Bay Area Air Quality Management District.Bay Wheels is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States. It was established as Bay Area Bike Share in August 2013. As of January 2018, the Bay Wheels system had over 2,600 bicycles in 262 stations across San Francisco, East Bay and San Jose.

- In June 2017 the system was officially re-launched as Ford GoBike in a partnership with Ford Motor Company. After Motivate's acquisition by Lyft, the system was renamed to Bay Wheels in June 2019.The system is expected to expand to 7,000 bicycles around 540 stations in San Francisco, Oakland, Berkeley, Emeryville, and San Jose.

- In this project I aim to practice Data Visualization which's an important step in Data Analysis, The Dataset that I used is the Ford GoBike System Data for 2018

- you can find the dataset here : https://www.lyft.com/bikes/bay-wheels/system-data

> This project was completed as part of Udacity's Data Analyst Nanodegree certification.

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
