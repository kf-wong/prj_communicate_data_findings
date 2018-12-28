# Ford GoBike System Data Exploration
## by Kevin Wang


## Dataset

The dataset includes the trip data from January to Noverber in 2018 based on the original csv files provided by [Ford GoBike](https://www.fordgobike.com/system-data).<br>
There are total 1,732,358 trip's records, which include the 16 features: duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude, end_station_longitude, bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip.

These variables includes following main data types:<br>
**Numeric**: duration_sec, start_station_id, start_station_latitude, start_station_longitude, end_station_id, end_station_latitude, end_station_longitude, bike_id, member_birth_year<br>
**String**: start_station_name, end_station_name<br>
**Datetime**: start_time, end_time -> format: YYYY-mm-dd HH:MM:SS.ffff<br>
**Categorical**: user_type(Subscriber, Customer), member_gender(Male, Female, Other)<br>


## Summary of Findings

From the exploration I found that the busy hours that most trips are taken are 8am-9am and 5pm-6pm in the workdays. But for weekends, the time between 12pm-14pm are have the most number of trips. The bike usage is active from May to October.

The main user of this bike sharing system are registered members as they have much more number of trips compared with casual user(customer). The members and casual users have different usage pattern for bikes. The members like to use bikes on the time of go to work and back from work on the weekdays. While for the casual users, the number of trips gradually increase from 9am to the 5pm and then drop gradually from 5pm. And casual users take more trips on the weekends compared with the weekdays. The casual users have longer trip duration than the members'. But there is one truth that is appliable for member and casual users: people spend more time on the bike trips on the weekends than the weekdays and that indicates people take the riding as one activity in the weekends.

When taking the gender as the consideration on bike usages, I found that the male users have the most number of trips compared with the female and other gender users. But there is an clear indication that female users have the longer trip duration than the male users. 


## Key Insights for Presentation

The casual users have longer trip duration than the members' trip duration. But both members and casual users spend more time on bike riding on the weekends than the weekdays and that shows people seems to take riding as one outdoor activity in the weekends.

There is also an clear indication that female users have the longer trip duration than the male users.