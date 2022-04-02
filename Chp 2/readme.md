This chapter goes over the overall structure for a machine learning project. This includes:
1. Business Intelligence and how the project serves the business
2. Getting the data to work with 
3. Analyze the data and use visualization techniques to assist and gain insights.
4. Data preparations and data cleansing
5. Selecting the model (or models) appropriate for the data and problem at hand to train with
6. Tune the model (Ex. model parameters)
7. Verify solution and present to business
8. Launch and maintain solution.

This chapter using a housing dataset in California in 1990 and the chapter focuses on how to complete the above checklist and the ways of measuring the accuracy of the model. Some forms of performance mentioned for regression are Mean absolute error (MAE), Mean squared error (MSE) and then the root of those two (RMSE & RMAE). The author talks about splitting the data into a training set and a testing split. This is done to avoid future bias based on when you want to train the model on new data and how to make the sets ACTUALLY random and how to verify is some of the data is skewed. There is a section about how data preparation and visualization can be done using numpy, pandas and matplotlib in python and then wrapping it all together under a pipeline for the model in Scikit learn and finally evaluating the accuracy of the model after fine tuning. 
