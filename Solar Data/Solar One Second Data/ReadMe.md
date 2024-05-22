# ReadMe
This spreadsheet compares solar microgrid data to various weather data including UV index, solar radiation, relative humidity, temperature, AQI (Air Quality Index), PM2.5, and PM10.
The solar data is recorded from a 48kW array on the roof of the FDC building on the UST campus.

The project that produced this data was made possible in whole or in part by a grant from the Minnesota Department of Commerce through the Minnesota Renewable Development Account, which is financed by Xcel Energy ratepayers.

## Weather Data
The data for UV Index, solar radiation, relative humidity, and temperature is from the weatherbit API (https://www.weatherbit.io/api/historical-weather-api).
The weather data is in standard Imperial units. The most grandular weather data available in the API was hourly, that is what is used within these data sets. 

Data in this folder was collected for a variety of weather conditions: 

  -  April 19th, 20th, and 21st were cloudy and rainy
  -  June 13th was sunny
  -  June 14th and 15th had high levels of wild fire smoke with hazardous air quality
  -  June 16th and 17th were sunny
  -  June 18th was cloudy
  -  June 19th was partially cloudy
  -  June 20th and 21st were sunny

## Air Quality Data
The data for AQI, PM2.5, and PM10 is from the OpenWeather API (https://openweathermap.org/api/air-pollution).
Units for PM2.5 and PM10 are in μg/m^3. 

## Time
The 24 hour times shown are represented in UTC, with local time as UTC-5 during daylight savings (summer), and UTC-6 during standard time.
