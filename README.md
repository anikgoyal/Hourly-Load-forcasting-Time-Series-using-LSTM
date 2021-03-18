# Hourly-Load-forcasting-Time-Series-using-LSTM:
To forecast the hourly load for the utility for a specific month on hourly basis

# Data:
Hourly historical load data of the utility are provided (Load_History.csv). The historical data file contains the data from the 1st hour of 01-01-2008 to the 24th hour of 30-11-2011

# Notes:
1. Used google colaboratory for this project and keras for model building.
2. A LSTM model is used to learn the time series where for training every 5 days of previous year is used to predict the 1 day of current month.
Example: 1-01-2008 to 5-01-2008 is used to predict the load of 01-01-2009 
3. The reason behind above is energy consumption has some pattern like daily, weekly as well as seasonal patterns. So these can be used as features for predicting. 
4. The timestamps for each hour (as given in the dataset) is coverted into hour_of_day, day_of_week, quarter_of_year, month_of_year, year, day_of_year, day_of_month, for better insight of the data and then they are used for training.
5. Images in the report file illustrates the relation.

# Future Work:
1. The prediction can be improved by increasing the layers/ improving the architecture used. 
2. Since many features are used for training, PCA can be applied to select the important features (features with maximum variance). So that the training becomes fast and most accurate.

# Please reach out @ if you have new idea/ suggestion
anikatwilsonia@gmail.com
