## **Time Series Forecasting and Linear Regression Modeling**
### **Objective:** 
In this assignment, I use time series analysis and linear regression modelling tools to predict future movements in value of the Japanese Yen versus the U.S Dollar

### **Key Findings:**
#### Time Series
1.  The ARMA model predicts that returns for the Yen should remain steady in the future
2. The ARIMA forecasts that the value of the Yen will increase in the short term. 
3. The GARCH anticipates that volatility will raise in the next few days.

##### Conclusion: 
Based on the models presented in the time series forascasting notebook, a person looking to profit in short term investements should buy the Yen at the current value and expected returns. But unfortunaly, further testing and remodeling should be conducted. The p-values for both the ARMA and ARIMA models are greater than 0.05. Furthermore, the GARCH model does achieve a p-value below 0.05, making previous variance a good predictor for current risk. However, the graph shows an upward movement for the short term. 

#### Linear Regression 
In this analyis I used historical settle prices data to train and fit the model and then tested it with data it had not seen before. After the analysis, I concluded that model was able to perform good with out of sample data. 




