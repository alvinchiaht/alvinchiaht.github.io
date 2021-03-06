---
layout: post
title:  "Time Series Forecasting for Train Ridership"
date:   2019-10-03 12:43:33 +0800
categories: project
---

We developed a model to predict Amtrak train ridership and formulated a strategy to optimise number of trains to be deployed at a given period.

The dataset comprised the total number of train riders per month between 2005 to 2018. The trend line for the dataset exhibited seasonality and non-stationarity.

Modelling was performed using (1) seasonal ARIMA and (2) exponential smoothing method with RMSE and MAE as evaluation criteria. Time series cross validation was employed to validate the model.

Exponential smoothing method was recommended as it provided good accuracy and a conservative estimate of train ridership, placing priority on commuter experience.

[Check Out My Project!](https://github.com/alvinchiaht/project/blob/master/Time_Series_Train%20Ridership.nb.html)
