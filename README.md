# Alabama Fire Forecasting Dataset (2012–2024)

This repository hosts a multivariate time series dataset for monthly fire forecasting in Alabama. It combines fire metrics from VIIRS active fire data with climate variables from the Climate Engine API (TerraClimate product).

## Overview

- **Geographic Coverage**: Alabama, United States
- **Temporal Range**: January 2012 – December 2024
- **Temporal Resolution**: Monthly
- **Use Case**: Fire count forecasting using multivariate modeling approaches

## Data Sources

- **VIIRS Active Fires**: For fire count and Fire Radiative Power (FRP)
- **Climate Engine / TerraClimate**: For environmental and climatic variables

## File

- `data.csv`: Contains monthly observations from January 2012 through December 2024, with fire and climate variables.

## Variables

| Column Name  | Description |
|--------------|-------------|
| `date`       | Monthly timestamp (YYYY-MM-DD) |
| `fc`         | Fire count (number of VIIRS active fire detections) |
| `sfrp`       | Sum of Fire Radiative Power (FRP) |
| `mfrp`       | Mean Fire Radiative Power (FRP) |
| `aet`        | Actual evapotranspiration |
| `cwd`        | Climatic water deficit |
| `et0`        | Reference evapotranspiration (FAO Penman-Monteith) |
| `pet_thorn`  | Potential evapotranspiration (Thornthwaite method) |
| `ppt`        | Precipitation |
| `pwd`        | Precipitation water deficit |
| `rad`        | Solar radiation |
| `soil`       | Soil moisture |
| `tmax`       | Maximum temperature |
| `tmin`       | Minimum temperature |
| `vp`         | Vapor pressure |
| `vpd`        | Vapor pressure deficit |
| `wind`       | Wind speed |

## License

This dataset is released under the MIT License. Users are free to use, modify, and share the data with proper attribution.

## Acknowledgments

- VIIRS Active Fire data provided by NASA/NOAA
- Climate variables derived from the TerraClimate dataset via the Climate Engine API
- Dataset compiled for research on multivariate fire forecasting in the Southeastern United States
