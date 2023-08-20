# DA-Assignment
Stock market prediction as a part of Data Analytics Assignment <br>

Link to the competition hosted on Kaggle: https://www.kaggle.com/competitions/pes-ec-dataanalytics-assign/overview/description
 <br>

<b> Holt Winters Method as a part of forecasting: </b> <br>
The target variable is analysed carefully and when decomposed trend and seasonality are observed. Hence, the above model is used for forecasting. All variations of the model have been tried out to obtain the best results. <br>

<b>Linear Regression as a part of regression </b> <br>
Linear regression is used because the correlation between the variables is high. Dropping out highly correlated variables, performing PCA gave higher rmse values. Hence all the variables were considered to train the model.Out of all the regression models that were used, linear regression gave the lowest rmse value. A pipeline was used with StandardScaler for preprocessing
<br>

<h4> Conclusion</h4>
the regression model performs better than the forecasting model with a lower rmse on the test data. This might also be due to the fact that forecasting models take into account only the previous values but regression looks at the other independent variables like Open, High, Low and Volume. This would help in making better predictions. The Regression pipeline is used to make the final submission due to the above mentioned reasons.

