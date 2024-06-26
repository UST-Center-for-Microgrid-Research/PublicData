# ReadMe
This spreadsheet compares solar microgrid data to various weather data including UV index, solar radiation, relative humidity, temperature, AQI (Air Quality Index), PM2.5, and PM10.
The solar data is recorded from a 48kW array on the roof of the FDC building on the UST campus.

The project that produced this data was made possible in whole or in part by a grant from the Minnesota Department of Commerce through the Minnesota Renewable Development Account, which is financed by Xcel Energy ratepayers.

## Weather Data
The data for UV Index, solar radiation, relative humidity, and temperature is from the weatherbit API (https://www.weatherbit.io/api/historical-weather-api).
The weather data is in standard Imperial units. The most grandular weather data available in the API was hourly, that is what is used within these data sets. 

  -  June 16th and 17th were sunny

## Air Quality Data
The data for AQI, PM2.5, and PM10 is from the OpenWeather API (https://openweathermap.org/api/air-pollution).
Units for PM2.5 and PM10 are in μg/m^3. 

## Time
The 24 hour times shown are represented in UTC, with local time as UTC-5 during daylight savings (summer), and UTC-6 during standard time.
