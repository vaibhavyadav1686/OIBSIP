# CAR PRICE PREIDCTOR

This was the third task under this internship

## PROBLEM STATEMENT

The price of a car depends on a lot of factors like the goodwill of the brand of the car, features of the car, horsepower and the mileage it gives and many more. Car price prediction is one of the major research areas in machine learning. 


## METHODOLOGY

I have used Python library pandas and numpy for data manipulation, matplotlib and seaborn for data visualisation, plotly for plotting graphs and sklearn for building ML models and tesing their accuracy.

We need to go through the data to check for any missing values which may cause discrepancies. 

Now we plot a distribution plot to know more about the data (which prices are more common than others). We also plot a correlation heatmap to know which factors to base our model on (the ones more closely correlated are selected).

We split the data into training and testing data. We use the Decision Tree Regressor for building our model as we have multiple factors and a more continous dataset. This algorithm shall prove to be more effective.

## RESULTS

This model gives us an accuracy of 100%.
