# Introduce:
Taxi services play an important role in the daily commute for people in NYC, according to Wikipedia 1.6% of the overall population rely on taxis for their daily traveling.

With the increasing use of taxis companies try to provide their services as fast as possible. These services do come at a cost as they collect data and analyze it to find the factors that affect the trip durations, which then help in predicting the same.

### Currently four algorithms have been utilised to predict trip_duration which include Linear Regression, Decision Tree Regressor, XG Boost Regressor, Hist Gradient Boosting Regressor.
### From which Hist Gradiennt Boosting Regressor has given the best results in terms of r2_score and RMSE.
### Problem statement:
* Build a machine learning model to predict the duration of NYC taxi trip.

### Conclusion:
* Distance calculated using the haversine function plays an important role in predicting the trip durations.

* Rest of the features showed moderate to very little linear correlation with the dependent variable.

* The best algorithm in this case is Hist Gradient Boosting Regressor.

* The untuned model was able to explain 68% of the variance on the test set, while the tuned model explained 74% of variance on the test set which is a good improvement.

* The least RMSE on test set by the Hist Gradient Boosting Regressor was 3.249991 which is comparatively lower when compared with rest of the models.

### Future Scope:
* As this data set is of only almost 6 months and I think there should be more data for more than a year and also some more features should be there so that we can train our models with more significant information that will help our model to learn more efficiently so that we can get more higher performance from Machine Learning Models.
* And also we can extract more information about this data by getting more features so that we can explore more about this kind of data.

### End note:
In this project we covered various aspects of the Machine learning development cycle. We observed that the data exploration and variable analysis is a very important aspect of the whole cycle and should be done for thorough understanding of the data. We also cleaned the data while exploring as there were some outliers which should be treated before feature engineering. Further we did feature engineering to filter and gather only the optimal features which are more significant and covered most of the variance in the dataset. Then finally we trained the models on the optimum featureset to get the results.
