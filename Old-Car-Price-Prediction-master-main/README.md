# Old-Car-Price-Prediction-master
In this project, I have used the Kaggle data from cardekho.com and predicted the selling price of old second-hand cars.
various libraries used are: Pandas, Seaborn, Matplotlib and Sklearn 
1) Firstly I have done data cleaning by removing all the null and missing values, changing string values into integer form.
2) Correlations among various models are found and plotted in a form of a heat map.
3) Separated dependent and independent variables and further divided them in training and testing sets with a ratio of 1:5
4) Used extreme tree regressor to get most important features
5) Did hyperparameter tuning by initializing the parameters with different values and then using randomizedSearchCV to choose the best parameters
6) Used Random forest Regressor to predict the final values 
7) Plotted the difference between the test set and predicted values on the gaussian plot 

Results:- the predicted values are very close to test set values and the gaussian plot had a peak around zero
