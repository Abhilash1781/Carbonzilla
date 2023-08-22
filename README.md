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

![FB Prophet Predictions](https://github.com/Abhilash1781/Carbonzilla/assets/72621930/d7a9f8bf-c4a0-4cca-b603-93da12da38e0)




