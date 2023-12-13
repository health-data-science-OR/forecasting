# Changes

## v4.0.1
* PATCH: hds_pytorch updated to use forecast-tools 0.2.1

## v4.0.0

* ENV: Updated hds_forecast to python 3.10 and latest package Dec 2024
* ENV: notebooks updated to work woth forecast-tools v0.2.1
* ENV: created separate hds_pytorch virtual environment to support pytorch notebooks in python 3.8 and pytorch 1.4
* ENHANCEMENT: added coverage metrics notebooks to lab 1 additional materials
* PATCH: minor updates fixing notebooks to work with data stored on github.
* PATCH: minor updates to notebooks to account for updates to packages.

## v3.0.1
* Renamed conda environment: hds_forecast_2023 -> hds_forecast

## v3.0.0

* Upgraded conda environment to latest version of libraries
* Prophet -> Holidays no longer supports 'England'.  Upgraded to 'UK'
* ARIMA -> models now take `X` rather than `exogenous`
