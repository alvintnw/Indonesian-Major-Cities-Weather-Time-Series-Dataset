# Indonesian-Major-Cities-Weather-Time-Series-Dataset

* **City Coordinates Dictionary:** Defines a list of major Indonesian cities along with their specific latitude and longitude coordinates.
* **Dynamic Date Range:** Utilizes the `datetime` module to automatically calculate and set a historical time window covering the past 7 days up to yesterday.
* **Open-Meteo Archive API:** Sends an HTTP request to the Open-Meteo historical archive endpoint to fetch hourly meteorological variables (such as `temperature_2m`, `relative_humidity_2m`, `precipitation`, and `wind_speed_10m`).
* **Data Structuring & CSV Export:** Maps the retrieved hourly arrays into clean, structured tabular rows using Pandas and exports them into the `indonesia_weather_timeseries.csv` file, which automatically triggers a download when executed inside Google Colab.
