# midbootcamp_project
Exploration of the factors driving use of BiciMAD

Between March and June 2020 the air quality in Madrid improved noticeably due to the COVID-19 lockdown banning all non-essential travel. This drastic improvement demonstrates the impact we have on our environment and also how quickly we can improve our environment with certain measures. As traffic is the main contributor to NO2 pollution, clean transportation is really important for improved air quality. The BiciMAD e-bike sharing service is an ideal choice for clean transportation as it is easily accessible throughout the city and also provides a component of exercise for the users. 

My intent was to determine what factors drive the daily use of the BiciMAD service.


I used open data from Madrid EMT providing the following info: 

_id:  unique id for each trip

User_day_code:  unique code for each user, only valid for same date

Idplug_base:  number of the base where the bike was deposited

User_type:  0: unknown, 1: annual pass holder, 2: occasional user, 3: biciMad worker

Idunplug_base:    number of the base where the bike was taken from

Travel_time:  time of trip in seconds

Idunplug_station:    station id where the bike was taken from

ageRange: 0: unknown, 1: 0-16, 2: 17-18, 3: 19-26, 4: 27-40, 5: 41-65, 6: 65 or older

Idplug_station:   station id where bike was deposited

unplug_hourTime:  unplug time in date and hour


I determined that time and weather factors were influential to the use of the service, but it is clear that other unrecorded factors were driving use as well. 
I would have liked to have more data regarding demographics of the users and more info about the stations such as the connections to other types of transportation networks and socioeconomic status. 

