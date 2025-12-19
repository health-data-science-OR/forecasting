# Changes

## v5.1.0

### Changed

* Autoregression: `05_autoregression` -> `04_autoregression`
* Neural networks: `06_neural_networks` -> `05_neural_networks`

### Removed

* `04_resp_case_study`: removed as no longer part of taught course.

## v5.0.0

### Changed

* ENV: Updated `hds_forecast` to python 3.11 and latest compatible packages July 2024 (note tensorflow set to 2.15 to match Google Colab).
* ENV: Now uses `forecast-tools` v0.3.0

### Fixed

* NN: `sliding_window` patch to include final window (loop + 1) [#30](https://github.com/health-data-science-OR/forecasting/issues/30)
* NN: Notebooks patched to include code to check and then create `output` directory if it does not exist
* PRE-REQS: notebooks fixed to download data from Github URL. [#6](https://github.com/health-data-science-OR/forecasting/issues/6)
* LAB2: Exercise 1.4 fixed to use correct prediction horizon [#24](https://github.com/health-data-science-OR/forecasting/issues/24)
* WEEK1 EXTRA: Patched to download dat from Github URL [#16](https://github.com/health-data-science-OR/forecasting/issues/16)

## v4.0.1
* PATCH: hds_pytorch updated to use forecast-tools 0.2.1

## v4.0.0

* ENV: Updated hds_forecast to python 3.10 and latest package Dec 2023
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
