# Forecast-Project

## Overview

Forecast plays a big role in management decisions. It helps the decision makers to understand how the company is going to grow if it keeps operating in the currently way so, the management team can plan the future or make changes if the forecast’s results are below expectations. With this type of analysis, it is possible to identify and fix a variety of problems such as: stock planning, staff, marketing budget, seasonality, demand levels and much more.

Before start choosing the forecasting technique and the tool to be used, it is important to understand the goal of the analysis and what decisions are going to be taken with its results. The forecaster needs work with the manager to understand what is expected, the level of accuracy needed and also, which data is available.

## About the project

This project consists in a 12 months Forecast for a B2B company that wants to know how the sales numbers are expected to be, in a specific time frame.
The final product of this analysis is a spreadsheet because it is simple, easy to understand, fast and easy to make changes (in case you want to test different hypothesis).
This project was based in the dataset available on Kaggle on this [link](https://www.kaggle.com/datasets/olistbr/marketing-funnel-olist?resource=download), along with a random report extracted from **Google Analytics** platform.

After extracting the data, it was transformed in a format that would make it easier for manipulating, using the function **TRANSPOSE** to populate the main spreadsheet.
The dataset downloaded was composed by two files that was joined using **Python** and you can see the code [here](https://github.com/belabarbosa/Forecast-Project/blob/0edf563c45d713cd91d16e3ffd650adf1b13dea3/Forecast%20Project%20code_Leads%20Data%20Analysis.ipynb).

## The Forecast

#### Forecasting Methods
  1. Exponential Smoothing
  2. Linear Regression


#### Acuracy Metrics
  - Bias Forecast Error
  - Mean Absolute Percentage Error (MAPE)
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)

In order to minimaze the error for the analysis, I used the **Solver** in Microsoft Excel.

## Insights

- **Paid leads**: The number of leads from paid ads will continue to grow, with Google Search being responsable for more than 90% of it.

- **Organic leads**: The leads coming from organic channels are responsable for about 80% of the total sales. The company should continue to invest in organic campaings (SEO, blog, social, public release), in order to maintain this growth.

- **Historial data**: It would be interesting to study the events that promoted the growth on the number of direct_traffic and organic leads from 2017-12 and beyond to see if it is possible to replicate this result.

## See this project

To see the final project click [here](https://github.com/belabarbosa/Forecast-Project/blob/44b88f032bc11176aa24f3df20b45dd6624080a1/Forecast.xlsx). 

And if you have any comments or suggestions to improve this project, please feel free to contact me on [my Linkedin](www.linkedin.com/in/irbarbosa)
