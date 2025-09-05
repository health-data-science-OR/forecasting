[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/health-data-science-OR/forecasting/master)   
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4332600.svg)](https://doi.org/10.5281/zenodo.4332600)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/release/python-3100+/)
[![License: MIT](https://img.shields.io/badge/ORCID-0000--0003--2631--4481-brightgreen)](https://orcid.org/0000-0003-2631-4481)

# HPDM097: Making a difference with health data:
## Forecasting health service demand

> Forecasting practical materials for **Making a difference with health data** module.

**Dependencies**

Please use the provided conda environment

```
conda env create -f binder/environment.yml
```

```
conda activate hds_forecast
```

## Citation:

```
Monks, T. (2023). forecasting health service demand in python. Zenodo. https://doi.org/10.5281/zenodo.4332600
```

```tex
@software{monks_2023_10370697,
  author       = {Monks, Thomas},
  title        = {forecasting health service demand in python},
  month        = dec,
  year         = 2023,
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.4332600},
  url          = {https://doi.org/10.5281/zenodo.4332600}
}
```


## Syllabus

### **RECOMMENDED** Pre-course material

These notebooks offer a refresher in the basics of date handling in numpy, pandas and matplotlib.  

* Handling dates in numpy and pandas: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/01_basics/lectures/1_Lecture_DateTimes.ipynb)

* Exploring time series with pandas and matplotlib: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/01_basics/01_lecture_notebooks/2_Lecture_exploring_ts.ipynb)

### Computer Lab 1: The basics of forecasting: part 1

#### 1.1 Code along notebooks

These notebooks **accompany** the exercises.  They provide example code to help you solve the exercises.

* Loading time series data into pandas: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/01_basics/01_code_along_notebooks/pandas_time_series.ipynb)

* Naive benchmarks: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/01_basics/01_code_along_notebooks/ca_benchmark_forecasts.ipynb)

#### 1.2 Exercises

* Naive forecasting exercises [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/01_basics/01_practicals_notebooks/Practical_1.ipynb)

### Computer Lab  2: The basics of forecasting: part 2

#### 2.1 Code along notebooks

* Introduction to cross validation [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/01_basics/01_practicals_notebooks/Practical_2_SOLUTIONS.ipynb)

#### 2.2 Exercises

* Time series cross validation [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/01_basics/01_practicals_notebooks/Practical_2.ipynb)

### Computer Lab 3: Forecasting using ARIMA models

#### 3.1 Code along notebooks

* Introduction to ARIMA Exercises: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/02_arima/arima_exercises_SOLUTIONS.ipynb)

#### 3.2 Exercises

* ARIMA Exercise: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/02_arima/arima_exercises.ipynb)

### Computer Lab 4: Forecasting daily data using Facebook Prophet

#### 4.1 Code along notebooks

* Prophet introductory lecture: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/03_prophet/03_code_along_notebooks/prophet_code_along_SOLUTIONS.ipynb)

* Introduction to Prophet Exercises: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/03_prophet/03_practicals_notebooks/prophet_exercises_SOLUTIONS.ipynb)

#### 4.2 Exercises

* Prophet Exercises: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/03_prophet/03_practicals_notebooks/prophet_exercises.ipynb)

### Computer Labs 5. An introduction to feedforward neural networks

#### 5.1. code along lecture notebooks

* Deep Learning 101: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/06_neural_networks/deep_learning_101/lecture_deeplearning_101.ipynb)
  
#### 5.2 Exercises

* Autoregressive Neural Networks with KERAS. Part 1: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/06_neural_networks/feedforward/keras/autoregression_keras_part1_STUDENT.ipynb)

#### 5.3. Optional self study material

* Preprocessing and autoregressive OLS: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/05_autoregression/autoregression1.ipynb)

* Autoregressive Neural Networks PYTORCH. Part 1: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/06_neural_networks/feedforward/pytorch/autoregression_pytorch_part1.ipynb)

### Computer Lab 6: Feedforward neural networks for time series

#### 6.1 Exercises
* Autoregressive Neural Networks KERAS Part 2: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/06_neural_networks/feedforward/keras/autoregression_keras_part2_STUDENT.ipynb)

#### 6.2 Optional self study material

* Autoregressive Neural Networks PYTORCH Part 2: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/06_neural_networks/feedforward/pytorch/autoregression_pytorch_part2.ipynb)