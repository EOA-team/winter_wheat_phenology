# Meteorological data for WOFOST simulations

This repository contains the meteorological data per grid cell required to run WOFOST and determine the sowing date.
The data is provided for each grid cell of the simulation on a daily basis, extracted from the [MeteoSwiss](https://www.meteoswiss.admin.ch/#tab=forecast-map) gridded data
product (1 by 1 km resolution, same grid cell layout as used for the simulations).

Since a revision of the of the Ordinance on Meteorology and Climatology (MetV; SR 429.11) in March 2023, the data should be made available free-of-charge as open-governmental data. The publication of the MeteoSwiss products as open-governmental data is currently [work in progress](https://github.com/MeteoSwiss/publication-opendata). From 2025 onwards, users should be able to pull the data from MeteoSwiss directly.

To allow users to reproduce our results, the extracted data is made available as CSV files using Git's large file storage (LFS). Many thanks to [MeteoSwiss](https://www.meteoswiss.admin.ch/#tab=forecast-map) for the permission to do so 🙏.

| File Name | Description | Unit |
| --------- | ----------- | ---- |
| RhiresD_1971-01-01-2020-12-31.csv | Daily precipitation sum (midnight to midnight) | mm |
| TmaxD_1971-01-01-2020-12-31.csv | Daily maximum air temperature 2m above ground | deg C |
| TminD_1971-01-01-2020-12-31.csv | Daily minimum air temperature 2m above ground | deg C |
