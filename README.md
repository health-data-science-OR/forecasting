[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/health-data-science-OR/forecasting/master)   
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4332600.svg)](https://doi.org/10.5281/zenodo.4332600)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.11+](https://img.shields.io/badge/python-3.11+-blue.svg)](https://www.python.org/downloads/release/python-3110+/)
[![License: MIT](https://img.shields.io/badge/ORCID-0000--0003--2631--4481-brightgreen)](https://orcid.org/0000-0003-2631-4481)

# 📊 Forecasting Health Service Demand

A practical course on forecasting methods for health service demand, part of the **HPDM097: Making a Difference with Health Data** module.

> 🚧 Note I maintain and update this repository once a year and update materials around December time.

## 📖 Overview

This repository contains hands-on materials for learning and applying forecasting techniques to healthcare data. Through six progressive computer labs, you'll master essential forecasting methods from naive benchmarks to advanced neural networks, all demonstrated with real-world health service applications.

### What You'll Learn

- Time series fundamentals and exploratory data analysis
- Naive forecasting methods and benchmark models
- Cross-validation strategies for time series
- ARIMA model development and diagnostics
- Facebook Prophet for daily/seasonal patterns
- Neural network architectures for forecasting (Keras & PyTorch)
- Best practices for model evaluation and selection

## 🚀 Quick Start

### Prerequisites

- Python 3.11 or higher
- Basic understanding of Python, pandas, and NumPy
- Familiarity with matplotlib for visualization
- Basic statistics knowledge (recommended)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/health-data-science-OR/forecasting.git
   cd forecasting
   ```

2. **Create the conda environment**
   ```bash
   conda env create -f binder/environment.yml
   conda activate hds_forecast
   ```

3. **Launch Jupyter**
   ```bash
   jupyter lab
   ```

## 📚 Course Structure

### 🔧 Pre-Course Materials (Recommended)

Get up to speed with essential date and time series handling:

- **Handling Dates**: Working with temporal data in NumPy and pandas
- **Time Series Exploration**: Visualizing trends, seasonality, and patterns with pandas and matplotlib

### Lab 1: Foundations of Forecasting

**Topics**: Loading time series data, naive forecasting methods, baseline models

**Materials**:
- Code-along: Loading time series into pandas
- Code-along: Implementing naive benchmarks
- Exercises: Naive forecasting practice

**Key Skills**: Data loading, simple forecasting models, establishing baselines

### Lab 2: Model Validation

**Topics**: Time series cross-validation, train-test splits, forecast evaluation

**Materials**:
- Code-along: Cross-validation techniques
- Exercises: Implementing time series CV

**Key Skills**: Proper evaluation methods, avoiding data leakage, model comparison

### Lab 3: ARIMA Models

**Topics**: Autoregressive Integrated Moving Average models, stationarity, model diagnostics

**Materials**:
- Code-along: ARIMA introduction and implementation
- Exercises: ARIMA modeling practice

**Key Skills**: Statistical forecasting, parameter selection, residual analysis

### Lab 4: Facebook Prophet

**Topics**: Handling seasonality, holidays, trend changes in daily data

**Materials**:
- Code-along: Prophet lecture and introduction
- Exercises: Prophet application to health data; Revisiting ARIMA (Regression with ARIMA errors)

**Key Skills**: Automated forecasting, interpretable components, robust to missing data

### Lab 5: Neural Networks Introduction

**Topics**: Feedforward networks, deep learning fundamentals, autoregressive architectures

**Materials**:
- Code-along: Deep Learning 101
- Exercises: Autoregressive networks in Keras (Part 1)
- Optional: PyTorch implementation, OLS preprocessing

**Key Skills**: Neural network basics, model architecture design, training procedures

### Lab 6: Advanced Neural Networks

**Topics**: Advanced architectures, hyperparameter tuning, ensemble methods

**Materials**:
- Exercises: Autoregressive networks in Keras (Part 2)
- Optional: PyTorch advanced implementation

**Key Skills**: Model optimization, regularization, production deployment

## 🛠️ Key Technologies

- **pandas** & **NumPy**: Data manipulation and time series handling
- **matplotlib** & **seaborn**: Visualization
- **statsmodels**: ARIMA and statistical models
- **Prophet**: Facebook's forecasting library
- **Keras/TensorFlow**: Deep learning (primary framework)
- **PyTorch**: Alternative deep learning framework (optional track)

## 📊 Example Applications

All examples use real-world health service scenarios:
- Emergency department attendances, reattendances, and admissions forecasting
- Ambulance dispatches
- Forecasting monthly and daily level data

## 🤝 Contributing

Contributions are welcome! Please feel free to:
- Report bugs or issues
- Suggest improvements to exercises
- Add additional examples or datasets
- Improve documentation

## 📄 Citation

If you use these materials in your research or teaching, please cite:

```bibtex
@software{monks_2023_10370697,
  author = {Monks, Thomas},
  title = {Forecasting health service demand in python},
  month = dec,
  year = 2023,
  publisher = {Zenodo},
  doi = {10.5281/zenodo.4332600},
  url = {https://doi.org/10.5281/zenodo.4332600}
}
```

## 📧 Support

- **Issues**: Open an issue on GitHub for bug reports or questions
- **Module**: Part of HPDM097 at University of Exeter
- **Author**: Thomas Monks

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Related Resources

- [health-data-science-OR organization](https://github.com/health-data-science-OR)
- [Forecasting: Principles and Practice](https://otexts.com/fpp3/) (recommended textbook)
- [Prophet documentation](https://facebook.github.io/prophet/)
- My online Python book: https://www.pythonhealthdatascience.com

## 🌟 Acknowledgments

Developed for the Making a Difference with Health Data module. Special thanks to all contributors and students who have helped improve these materials.

***

**Latest Release**: v5.0.0 (March 10, 2025)