# Project-Group6: Rainfall Prediction

## Data required and its properties
### Variables for Rainfall Prediction

| **Variable Name**       | **Description**                                                                | **Type**         | **Units**              | **Example Values**              | **Availablity**              |**Resolution** |
|-------------------------|--------------------------------------------------------------------------------|------------------|------------------------|---------------------------------|------------------------------|------------|
| `Min temperature`       | Air temperature at the observation point (Night time temprature)               | Continuous       | °C                     | 25.6, 30.2                      |IMD Gridded data              |      |
| `Max temperature`       | Air temperature at the observation point (Day time temprature)                 | Continuous       | °C                     | 25.6, 30.2                      |IMD Gridded data              |      |
| `humidity`              | Atmospheric moisture content                                                   | Continuous       | %                      | 45, 85                          |                              |      |
| `wind_speed`            | Speed of the wind near the surface                                             | Continuous       | m/s                    | 3.5, 12.0                       |                              |      |
| `wind_direction`        | Direction of the wind in degrees from north                                    | Continuous       | Degrees (0-360)        | 90, 270                         |                              |      |
| `pressure`              | Atmospheric pressure at sea level                                              | Continuous       | hPa                    | 1013, 1005                      |                              |      |
| `precipitation`         | Amount of rainfall in a specific time period                                   | Continuous       | mm                     | 0, 12.5                         |                              |      |
| `cloud_cover`           | Percentage of sky covered by clouds                                            | Continuous       | %                      | 10, 75                          |                              |      |
| `solar_radiation`       | Amount of solar energy received per unit area                                  | Continuous       | W/m²                   | 800, 1000                       |                              |      |
| `latitude`              | Latitude of the observation station                                            | Continuous       | Degrees (°)            | 37.7749, -33.8688               |✔️                            |      |
| `longitude`             | Longitude of the observation station                                           | Continuous       | Degrees (°)            | -122.4194, 151.2093             |✔️                            |      |
| `altitude`              | Elevation above sea level                                                      | Continuous       | Meters (m)             | 150, 500                        |DEM                           |      |
| `past_rainfall`         | Rainfall amount recorded in a prior time period                                | Continuous       | mm                     | 5, 25                           |                              |      |
| `season`                | Current season or time of year                                                 | Categorical      | N/A                    | "Summer", "Winter"              |                              |      |
| `weather_events`        | Major weather events like thunderstorms or cyclones                            | Categorical      | N/A                    | "Thunderstorm", "None"          |                              |      |
| `soil_moisture`         | Moisture content in the soil (useful in some models)                           | Continuous       | %                      | 15, 40                          |                              |      |

---
Elevation dataset


![image](https://github.com/user-attachments/assets/cef0d0cb-de54-4fad-bafa-dbb9a91a8e60)
