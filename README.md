# bikeshare_pollution

### Join bike-sharing data with pollution data to map stations with high AQI

---

*CityBikes API contains bikeshare data from around the world from various companies and cities. OpenWeatherMap API houses weather, pollution data from around the world. This project aims to pull live AQI data for bikeshare stations listed in CityBikes API.*

---

#### Data Sources/Tools:
* [CityBikes API](https://api.citybik.es/v2/)
* [OpenWeatherMap API, Air Pollution](https://openweathermap.org/api/air-pollution)
* [Gmaps library](https://jupyter-gmaps.readthedocs.io/en/latest/)
* [Google Places API](https://developers.google.com/maps/documentation/places/web-service)

#### Steps:
- [x] Pull all 'networks' from the *CityBikes* API
- [x] Use network IDs to pull all stations from *CityBikes* API
- [x] Pull AQI data from OpenWeatherMap using lat/lon for each station
- [x] Map stations above AQI threshold (AQI = 5) using Gmaps library (needs Google Places API enabled)

