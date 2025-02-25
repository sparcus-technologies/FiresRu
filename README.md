# FiresRu Dataset

# Dataset Overview

This dataset contains meteorological and environmental data related to various types of fires. Each record includes information about the fire type, geographical location, and environmental conditions at the time of observation collected for 13 consecutive months. 

## Data Structure

The dataset has the following columns:

| Column Name            | Description                                                  |
|-----------------------|--------------------------------------------------------------|
| `type_name`           | The type of fire (5 fire types)                             |
| `type_id`             | A numerical identifier for the type of fire                 |
| `lon`                 | Longitude of the observation location                        |
| `lat`                 | Latitude of the observation location                         |
| `temperature_c`       | Temperature in degrees Celsius                               |
| `precipitation_mm`    | Precipitation in millimeters                                 |
| `relative_humidity`   | Relative humidity percentage                                 |
| `wind_speed_ms`       | Wind speed in meters per second                              |
| `solar_radiation`     | Solar radiation measurement (units not specified)           |

## Dataset Structure

The dataset includes the following key components:

- **Temporal Information**: Date and time of the observations (`dt`)
- **Categorical Classification**: Fire types classified by `type name` and `type id`
- **Geographical Coordinates**: Longitude and latitude
- **Meteorological Parameters**:
  - Temperature (°C)
  - Precipitation (mm)
  - Relative Humidity (%)
  - Wind Speed (m/s)
  - Solar Radiation

## Data Summary

- **Total Observations**: 26,681 unique records
- **Geographical Coverage**: 
  - Longitudes: 20.37°E to 175.87°E
  - Latitudes: 41.71°N to 70.33°N

### Temperature

- **Range**: -34.88°C to 31.94°C
- **Mean Temperature**: Approximately 17.89°C
- **Median Temperature**: 19.08°C

### Precipitation

- **Mean Precipitation**: 0.46 mm
- **Median Precipitation**: 0.04 mm
- **Maximum Recorded Precipitation**: 25.85 mm
- **75th Percentile Precipitation**: 0.30 mm

## Fire Type Distribution

The fire events are categorized into five distinct types, represented by both type name and numerical identifiers (`type id`). The dataset reveals an uneven distribution among these fire types, indicating a typical class imbalance challenge.

## Importance of the Dataset

The FiresRu dataset serves as a valuable resource for studying the relationship between meteorological conditions and various types of fire events in the region. The comprehensive nature of the included meteorological parameters allows for in-depth analysis of the environmental conditions associated with different fire types, which is crucial for fire prediction and management strategies.

## References

For additional details, refer to Table 1 and Figure 1 in the accompanying research paper.
