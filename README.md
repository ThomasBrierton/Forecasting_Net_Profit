# Forecasting Net Profit for MercadoLibre - Time Series Analysis

This project utilizes time series analysis to forecast MercadoLibre's net profit and to look for patterns in search traffic, stock price, and to find their correlation. This information is usefull for stock traders and for MercadoLibre's management team. 

---

## Technologies

This project uses [Google Colab](https://colab.research.google.com/?utm_source=scs-index) and the standard Python 3.8 libraries. This project requires the following libraries and/or dependencies:

- [Pandas](https://pandas.pydata.org/) - a software library designed for open source data analysis and manipulation.
- [hvplot](https://hvplot.holoviz.org/) - provides a high-level plotting API built on HoloViews that provides a general and consistent API for plotting data in all the abovementioned formats.
- [holoviews](https://holoviews.org/) - HoloViews is an open-source Python library designed to make data analysis and visualization seamless and simple.
- [Prophet](https://facebook.github.io/prophet/) - Prophet is a forecasting procedure implemented in R and Python. It provides completely automated forecasts.
- [matplotlib](https://matplotlib.org/) - Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python. Matplotlib makes easy things easy and hard things possible.
- [numpy](https://numpy.org/) - NumPy brings the computational power of languages like C and Fortran to Python, a language much easier to learn and use.
- [datetime](https://docs.python.org/3/library/datetime.html) - The datetime module enables data to be manipulated by date and times.

---

## Installation

The following dependencies must be installed before running the application:
```
!pip install pystan
!pip install fbprophet
!pip install hvplot
!pip install holoviews
```
---

## Methods

To complete this analysis, the following steps were performed:

1. Import and prepare the data.
2. Find patterns in MercadoLibre's search traffic and mine the data for seasonality.
3. Find the correlation between MercadoLibre's sctock price and search traffic.
4. Use Prophet to create a time series model, fit the model, and forecast MercadoLibre's net profit. 
5. Use holoviews to visualize the results.

---

## Analysis

The following photo shows the trends for MercadoLibre's closing stock price and search traffic.

![](https://github.com/ThomasBrierton/Forecasting_Net_Profit/blob/main/Photos/Screen%20Shot%202022-03-20%20at%208.25.28%20PM.png)

The following photo shows MercadoLibre's forecasted total sales for the next quarter.

![](https://github.com/ThomasBrierton/Forecasting_Net_Profit/blob/main/Photos/Screen%20Shot%202022-03-20%20at%208.24.52%20PM.png)

---

## Contributors 

Thomas Brierton and UCB

---

## License

MIT