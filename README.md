# Flight Fare Prediction:

This is to predict the fares of flight for flight booking based on the past data we have in the dataset

The dataset is downloaded from kaggle open repository

I have done data-preprocesssing for cleaning the data.
Then have done label encoding and further have balancing the data using SMOTE technique
I have used ensemble technique viz. ExtraTreeRegressor and RandomForestRegressor
then have gone for hypertunning paramater using RandomSearchCV

By doing the deployment, we have to input the date and time of the departure and arrival of the flight
and also the name of flight and its total stops.

At the result, it will give you the fare of your flight journey

## How to execute this file:

1. Download the folder which contains all the files viz., ipynb file, app.py, flight fare.xlsx,Test.xlsx, styles and templates folder, etc.
2. open the ipynb file in your jupyter notebook or which ever dataframe you use, just execute the file and the pickle file will be created
3. now execute app.py in flask api app and run it, you will get a link
4. Copy that link and paste on your browser
5. you will get a window for flight journey detail entry


## Terms of Flight Details:

#### 1.Departure date:
when your journey starts, put the date and time of your journey of starting place
#### 2.Arrival date:
when will your jouney ends, put the date and time of your journey to destination place
#### 3.Source:
From where the journey starts
#### 4.Destination:
To where your journey ends
#### 5.Stopage:
Total number of stops in between your journey
#### 6.Which Airline you want to travel?
Select the Airline of your choice
#### *Click on submit button

### Output:
#### Your Flight Price is: *Amount*

![flight_fare_output](https://user-images.githubusercontent.com/80784102/123382928-2401f300-d5b0-11eb-99dc-a2894516ca03.png)

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### What is the Random Forest algorithm?
 
Random forest is a supervised ensemble learning algorithm that is used for both classifications as well as regression problems. But however, it is mainly used for classification problems. As we know that a forest is made up of trees and more trees mean more robust forest. Similarly, the random forest algorithm creates decision trees on data samples and then gets the prediction from each of them and finally selects the best solution by means of voting. It is an ensemble method that is better than a single decision tree because it reduces the over-fitting by averaging the result.

![rf](https://user-images.githubusercontent.com/80784102/123381055-d7b5b380-d5ad-11eb-8cfa-e3ada5526f8e.png)
    
   As per the majority voting, the final result is 'Blue'
### Why the name “Random”?

Two key concepts that give it the name random:

A random sampling of training data set when building trees.

Random subsets of features considered when splitting nodes.   

*In our model, we have splitted the nodes, hence RandomForest, you can also use XGBOOST, Gradientboost technique, KNN*

    
  
