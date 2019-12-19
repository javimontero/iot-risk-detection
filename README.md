<div align="center">
  <img src="img/AbiBird_Lockup_KYellow.svg" height=“250"><br>
</div>

#  IoT sensor data visualisation
## Elder people activity sensor data analysis
Data analysis coming from IOT sensor AbiSensor from company [AbiBird](https://abibird.com.au)

Sensor data from **AbiSensor** IoT devices is analysed in this repository. **AbiSensor** primary function is to track activity of older person in their house, alerting if something abnormal happens.

The dataset consist of RAW anonymised data coming from 6 different **AbiSensor** devices (from company [AbiBird](https://abibird.com.au)). The sensors are installed in 3 different houses. Each house has 2 sensors in different locations.

The analysis shows different behaviour patterns like bed time, naps, inference of visits, activity evolution across the week, etc. 

## Feature aggregation
### Weather data
How does weather affect the activity of elders? I have incorporated weather data from [Meteosat API](https://api.meteostat.net) stations.
### Daylight duration
Does the daylight duration affect the people activity. Taking into account the location and date I calculate the astronomical ephemeris regarding sunset and sunrise times, to get the total light hours.
