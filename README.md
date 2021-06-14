# Time-Series-Forecasting

A Python based approach of time series analysis of search trend data.

Analysis begins with conversion of Google hourly search trend CSV into hvplot for visual reference.

Online traffic for the month of May 2020 is compared to the median monthly traffic volume, deteremined by indexing of year / month, grouping by index, summation, and median function.

Seasonality of online traffic is attempted to be determined by days of the week, hours of the day, and weeks of the year.

A correlation effect is then sought out by comparing lagged search trends, stock volatility, and hourly stock return to the original values of closing prices and search trends.

The project culminates in a time series model created with FaceBook Prophet, using a prediction of 80 days / 2000 hours in the future, to estimate the value of the company's stock price and search trend pattern.


---

## Technologies

This analysis runs on Google Collab, an online coding resource that alllows for real time collaboration with others, and with the following add-ons:

* [PyStan](https://pystan.readthedocs.io/en/latest/) - For data analysis and prediction

* [FB Prophet](https://pypi.org/project/fbprophet/) - For forecasting of time series data

* [hvPlot](https://hvplot.holoviz.org/) - For creation of graphs

* [HoloViews](https://holoviews.org/) - For futher visualization


---

## Installation Guide

Before running the analysis, the following packages must be run/installed in Google Collab:

*  !pip install pystan
*  !pip install fbprophet
*  !pip install hvplot
*  !pip install holoviews


---

## Example

For a visual reference as to how the analysis was performed, please refer to the below:

![Holiday Period Search Trend](Images/mercado_trends_winter_holiday_period.PNG)

![Search Trend Heatmap](Images/mercado_trends_heatmap.PNG)

![Comparison of Close Price and Search Trend](Images/first_half_2020_shared.PNG)


---

## Contributors

Santiago Rosas

