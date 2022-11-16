# (Ford GoBike System Data)
## by (Hatem Hassan ElDaly)


## Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area during Feburary 2019 in CSV format.

> But first some wrangling to data were made before exploring the data:

* Drop all Nan values from the table
* Change (user_type, member_gender) columns into category type
* Change (start_time, end_time) into datetime
* Change (bike_share_for_all_trip) into boolean
* Change (start_station_latitude, start_station_longitude, end_station_latitude, end_station_longitude, bike_id) into string
* Create new columns(start_hour_of_the_day, start_day_of_the_week, Start_date, member_age, duration_min)
* Drop outliers in member_age


## Summary of Findings

> Majority of users are male users and most rides happening during weekdays are short rides happens between 8am and 5pm while during weekend longer rides among all users

## Key Insights for Presentation

> Average age among all users and genders are the same between 30 and 40, we should try to focus more on the younger groups