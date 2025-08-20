# indonesia-earthquake-extremes

This repository contains the dataset used in the study **"Risk Analysis of Extreme Earthquake Events in Indonesia Using Sub-Sampling Block Maxima"**.  
The dataset is based on daily earthquake records and is prepared for extreme value analysis.

## Contents
`earthquake_id_2000_2024.csv` → main dataset including event ID, date, time, latitude, longitude, magnitude, magnitude type, depth, phase count, and location.

## Data Sources
- USGS (United States Geological Survey)

## Variables

- **time**: Event occurrence time in UTC (ISO 8601 format).
- **latitude**: Epicenter latitude in decimal degrees.
- **longitude**: Epicenter longitude in decimal degrees.
- **depth (km)**: Earthquake focal depth in kilometers.
- **mag**: Reported earthquake magnitude.
- **magType**: Type of magnitude scale, e.g.:
  - **Mw**: Moment Magnitude (standard global scale, based on seismic moment).
  - **mwc**: Moment Magnitude computed from Centroid Moment Tensor (CMT) solutions.
  - **mb**: Body-wave Magnitude (based on short-period P waves, effective for small-to-moderate earthquakes).
  - **Ms**: Surface-wave Magnitude (based on surface waves, useful for shallow large earthquakes).
- **nst**: Number of seismic stations used in the solution.
- **gap**: Azimuthal gap between seismic stations (degrees).
- **dmin**: Closest distance from epicenter to a seismic station (degrees).
- **rms**: Root mean square error of the travel-time residuals.
- **net**: Seismic network identifier (e.g., us = USGS).
- **id**: Unique earthquake identifier (event ID).
- **updated**: Last update timestamp for the event information.
- **place**: Textual description of the earthquake location.
- **type**: Event type (e.g., earthquake, quarry blast, etc.).
- **horizontalError (km)**: Uncertainty in epicenter horizontal location.
- **depthError (km)**: Uncertainty in focal depth.
- **magError**: Uncertainty in magnitude estimate.
- **magNst**: Number of stations contributing to magnitude.
- **status**: Review status (e.g., automatic, reviewed).
- **locationSource**: Agency providing the location.
- **magSource**: Agency providing the magnitude.

## License
This dataset is released under the [MIT License](LICENSE).

## Citation
If you use this dataset, please cite:  
*"Risk Analysis of Extreme Earthquake Events in Indonesia Using Sub-Sampling Block Maxima", [Author Names], 2025.*
