# Carbonzilla
This project focuses on designing a forecasting model which forecasts CO2 emissions (metric tons per capita) around the world from 2021-2030.

## Objective
The title of the project is a creative amalgamation of "Carbon" and "Godzilla", depicting colossal impact of carbon dioxide (CO2) emissions on our environment. It aptly highlights the overwhelming nature of CO2's adverse consequences, from climate change to pollution, emphasizing the urgent need for environmental conservation and sustainability.

## Dataset
The dataset encompasses a span of three decades, spanning from the year 1990 to 2019, providing comprehensive insights into the "Metric Tons of CO2 emissions per Capita".

Link to the dataset:
https://www.macrotrends.net/countries/WLD/world/carbon-co2-emissions

## Results
Following models were implemented to forecast CO2 emissions:
1) LSTM (Long Short-Term Memory)
2) XG Boost Regressor
3) FB (Facebook) Prophet

The models were then compared using the following performance metrics:
1) R2 Score
2) MSE - Mean Squared Error
3) RMSE - Root Mean Squared Error
4) MAPE - Mean Absolute Percentage Error

![Performance Analysis](https://github.com/Abhilash1781/Carbonzilla/assets/72621930/a889503a-65f3-4c98-bf4b-a2b3d30da1ee)


![Results](https://github.com/Abhilash1781/Carbonzilla/assets/72621930/4fb1d2ad-0a6c-4c0b-9174-c06e4b137cab)


The FB Prophet model outperformed all other models with an R2 Score of 0.97 and a RMSE of 0.05.
Hence we considered the same model for forecasting from 2021-2030.


## Forecasting
![FB Prophet Forecasting](https://github.com/Abhilash1781/Carbonzilla/assets/72621930/12104227-fef8-4b58-92ff-d7f80a212083)

Here,
1) 'ds': The timestamp in the time series.
2) 'y': The actual observed values of the time series data.
3) 'yhat_lower': The lower bound of the predicted values.
4) 'yhat_upper': The upper bound of the predicted values.

It forecasts that by the year 2030, the CO2 emissions (metric tons per capita) around the world will 4.28.
![FB Prophet Predictions](https://github.com/Abhilash1781/Carbonzilla/assets/72621930/47b4e312-a94c-45f9-9a91-2a6535884cfb)








