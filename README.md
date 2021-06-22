This is to predict the fares of flight for flight booking based on the past data we have in the dataset

The dataset is downloaded from kaggle open repository

I have done data-preprocesssing for cleaning the data.
Then have done label encoding and further have balancing the data using SMOTE technique
I have used ensemble technique viz. ExtraTreeRegressor and RandomForestRegressor
then have gone for hypertunning paramater using RandomSearchCV

By doing the deployment, we have to input the date and time of the departure and arrival of the flight
and also the name of flight and its total stops.

At the result, it will give you the fare of your flight journey
