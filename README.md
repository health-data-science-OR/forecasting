[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/health-data-science-OR/forecasting/master)

# Making a difference with health data:
## Forecasting health service demand

> Forecasting practical materials for **Making a difference with health data** module.

**Dependencies**

Please use the provided conda environment

    conda env create -f environment.yml

    conda activate hds_forecast

# Syllabus

## 1. Time series in python

### 1.1 Lecture Notebooks

* Handling dates in Python: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/01_basics/lectures/1_Lecture_DateTimes.ipynb)

* Exploring time series: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/01_basics/lectures/2_Lecture_exploring_ts.ipynb)

### 1.2 Practicals

## 2. Naive models and forecast accuracy

* Naive benchmarks: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/01_basics/lectures/3_Lecture_naive_benchmarks.ipynb)

* Point forecast error: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/01_basics/lectures/4_Lecture_ForecastError.ipynb)

* Prediction intervals [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/01_basics/lectures/5_Lecture_prediction_intervals.ipynb)

* Transformations: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/01_basics/lectures/6_Lecture_transformation.ipynb)

* Time series cross validation: 

### 3. ARIMA and Prophet

* ARIMA Exercise: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/02_arima/arima_exercises.ipynb)

* Prophet Exercise: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/03_prophet/prophet_exercises.ipynb)

* Respiratory admissions case study: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/04_resp_case_study/forecasting_respiratory_admissions.ipynb)

### 4. Neural Networks Primer: time series regression

* Autoregressive OLS: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/05_autoregression/autoregression1.ipynb)

### 5. Neural Networks for time series

#### 5.1 Keras/Tensorflow Implementations

* Autoregressive Neural Networks Part 1: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/06_neural_networks/feedforward/keras/autoregression_keras_part1.ipynb)

* Autoregressive Neural Networks Part 2: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/06_neural_networks/feedforward/keras/autoregression_keras_part2.ipynb)

#### 5.2 PyTorch Implementations

* Autoregressive Neural Networks Part 1: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/06_neural_networks/feedforward/pytorch/autoregression_pytorch_part1.ipynb)

* Autoregressive Neural Networks Part 2: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/health-data-science-OR/forecasting/blob/master/06_neural_networks/feedforward/pytorch/autoregression_pytorch_part2.ipynb)