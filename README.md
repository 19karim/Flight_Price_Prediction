
Flight Price Prediction

Overview:

This repository contains data and analysis for predicting flight prices using machine learning algorithms. Three algorithms, namely Linear Regression, Decision Tree, and Random Forest, were implemented and compared for their predictive accuracy. Among these algorithms, Random Forest yielded the best accuracy, which was then used to predict flight prices for test data.

Data:
The dataset provided contains the following columns:

Airline: Name of the airline.
Date_of_Journey: Date of the flight journey.
Source: Departure city.
Destination: Arrival city.
Route: Flight route.
Dep_Time: Departure time.
Arrival_Time: Arrival time.
Duration: Duration of the flight.
Total_Stops: Total number of stops during the flight.
Additional_Info: Additional information about the flight.
Price: Price of the flight ticket (target variable).

Analysis:

The following machine learning algorithms were implemented for flight price prediction:

Linear Regression: A basic regression algorithm that models the relationship between the independent variables and the target variable linearly.

Decision Tree: A tree-based algorithm that splits the data into subsets based on the value of the independent variables.

Random Forest: An ensemble learning method that constructs multiple decision trees and merges them to improve predictive performance.

Results:

After training and evaluating the models on the train data, it was found that Random Forest achieved the highest accuracy among the three algorithms. Therefore, Random Forest was chosen as the final model for predicting flight prices.

The Random Forest algorithm was then used to predict flight prices for the test data.

Conclusion:

The Random Forest algorithm demonstrated superior performance in predicting flight prices compared to Linear Regression and Decision Tree algorithms. By accurately predicting flight prices, airlines and travelers can make informed decisions regarding ticket pricing and booking.
