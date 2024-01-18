## Flight-Fare-Prediction
Flight ticket prices can be something hard to guess, today we might see a price, check out the price of the same flight tomorrow, it will be a different story. We might have often heard travelers saying that flight ticket prices are so unpredictable. That’s why we will try to use machine learning to solve this problem. This can help airlines by predicting what prices they can maintain.<br/>
### Data Preprocessing:<br/>
•	Checking basic informations of the dataset.<br/>
•	Checking for the null values, there are some null values so in this case we are dropping it because they are very less in numbers.<br/>
•	There are some features like departure time, arrival time, duration which our machine learning algorithm is unable to understand so we need to extract basic information like hours and minutes which we are storing in new columns.<br>
•	Similarly, we must extract the journey day and journey month column from Date_of_Journey column.<br>
•	There are some categorical features like Airline,Total_Stops, Source, Destination all this feature must be encoded this process is called as one hot encoding.<br>
•	Checking Feature importance of the data.<br>
•	Now, data is ready to passed to machine learning algorithm.<br>
•	So, Splitting data into train and test.<br>
### Model building:
Trained Machine learning models:<br>
Almost all the regression machine learning algorithm we have tried on the same dataset to get the maximum accuracy, which are:<br>
1.	Linear Regression<br>
2.	KNeighbors Regressor<br>
3.	DecisionTree Regressor<br>
4.	Random forest Regressor<br>
5.	XGBoost Regressor<br>
6.	Gradient boosting <br>

 The ML solution using Random Forest Regressor for flight fare prediction has shown promising results with a maximum R2 score of 89. This indicates that the model has a high level of accuracy in predicting flight fares.


