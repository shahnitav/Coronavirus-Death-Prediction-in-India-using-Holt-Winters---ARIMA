# Coronavirus-Death-Prediction-in-India-using-Holt-Winters-and-ARIMA

COVID-19 has taken the world by storm after first being reported in Wuhan, China in December-2019. Since then, there has been an exponential growth in the number of such cases around the globe. As of 29th April 2020, the total reported cases reached 3,218,183 out of which 228,029 have died. India has been able to contain the spread of the virus due to strict lockdowns in place nationwide. With a lot of researchers working on mitigating this pandemic, there are a lot of datasets available to work on. Using the 
[COVID19India case_time_series dataset](https://api.covid19india.org/csv/ "COVID19India.org"), we use the daily update of the ‘Total Deceased’ patients in India and perform Time Series Forecasting on the dataset using the Holt-Winters and ARIMA Methods. At present, the model is predicting the number of deceased patients 10 days form 29th April i.e. 9th May to be around 2000. Forecasting is invaluable in allowing us to better understand the current situation and plan for the future. In this project, I provide statistical forecasts for the confirmed deaths due to COVID-19 using robust time series models Holt-Winters & ARIMA. 

### Requirements 
1. Python 3+ 
2. Jupyter Notebook 
3. pandas 
4. matplotlib
5. statsmodels
6. numpy
7. pmdarima

Holt- Winters prediction: 

![alt text](https://github.com/shahnitav/Coronavirus-Death-Prediction-in-India-using-Holt-Winters-and-ARIMA/blob/master/Holt_Winters_pred.png "Coronavirus Death Prediction by Holt Winters Method")

ARIMA prediction: 

![alt text](https://github.com/shahnitav/Coronavirus-Death-Prediction-in-India-using-Holt-Winters-and-ARIMA/blob/master/ARIMA_pred.png "Coronavirus Death Prediction by ARIMA Method")

