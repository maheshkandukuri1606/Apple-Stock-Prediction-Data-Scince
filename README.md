# Apple-Stock-Prediction-Data-Scince

# First part - Data exploration
The first part is to analyze the dataframe and observe correlation between variables.


# second part clustering
The goal of this playground is to predict the trip duration of test set. We know that some neighborhoods are more congested. So, I used K-Means to compute geo-clusters for pickup and drop off. Cluster

# Third part - Cleaning and feature selection
I have found some odd long trips : one day trip with a mean spead < 1km/h.
Outliners I have removed these outliners.

I also added features from the data available : means for clusters.

# Forth part - Prediction
I compared Random Forest and XGBoost.
Current Root Mean Squared Logarithmic error : 0.391

Feature importance for RF & XGBoost

# Time series 

I implemented ARIMA for time series 
