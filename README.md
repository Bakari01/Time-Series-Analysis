# Time Series Analysis of Typhoid Incidence

## Project Description
This project is a time series analysis of typhoid incidence in Nigeria. 
The data used is from the World Health Organization (WHO) and the Nigerian Centre for 
Disease Control (NCDC). The data is from 2003 to 2015. The data is monthly and the 
analysis is done on a monthly basis. 

## Data Description
The data is from the World Health Organization (WHO) and the Nigerian Centre for Disease Control (NCDC). The data is from 2009 to 2018. The data is monthly and the analysis is done on a monthly basis.

## Methodology
The methodology used in this project is the Box-Jenkins methodology. The Box-Jenkins methodology is a three stage process. The stages are identification, estimation and diagnostics. The identification stage is where the data is analyzed and the model is chosen. The estimation stage is where the parameters of the model are estimated. The diagnostics stage is where the model is checked for adequacy.
Also forecasting using Prophet package was done and the performance was compared to the one for the Box-Jenkins methodology. 
Time series analysis was performed using Python programming language with the help of libraries like pandas, numpy, statsmodels, matplotlib, seaborn, and scikit-learn.


## Model
The model chosen for this project is the SARIMA(2,0,3)(1,0,0)[12] 
model. The model is a seasonal ARIMA model. The model is a seasonal ARIMA model because the data is monthly seasonal. The model is a SARIMA(2,0,3)(1,0,0)[12] model because the model has a seasonal component and a non-seasonal component. The seasonal component is the SARIMA(2,0,3) component and the non-seasonal component is the SARIMA(1,0,0) component. The SARIMA(2,0,3) component is the seasonal ARIMA component and the SARIMA(1,0,0) component is the non-seasonal ARIMA component. The SARIMA(2,0,3) component is the seasonal ARIMA component because the seasonal ARIMA component has a seasonal AR component, a seasonal MA component and a seasonal differencing component. The SARIMA(1,0,0) component is the non-seasonal ARIMA component because the non-seasonal ARIMA component has a non-seasonal AR component, a non-seasonal MA component and a non-seasonal differencing component. The SARIMA(2,0,3)(1,0,0)[12] model is the best model because the model has the lowest AIC value. The AIC value of the SARIMA(2,0,3)(1,0,0)[12] model is 59.

## Results
The results of the analysis are shown in the notebook. The results show that the model is adequate and can be used to forecast the incidence of typhoid in Nigeria. The results also show that there was an decrease in typhoid incidence in Nigeria from 2003 to 2015.
The model also achieved an RMSE score of 4 on an unseen (test) data. 

## Conclusion
The conclusion of the analysis is that the model is adequate and can be used to forecast the incidence of typhoid in Nigeria. 
Based on the results, it can be concluded that there was an decrease in typhoid incidence in Nigeria from 2003 to 2015. 

## Recommendations
Based on the results, it can be recommended that the Nigerian government should continue to educate the public on the importance of good hygiene and sanitation. The Nigerian government should also continue to provide clean water for the public. The Nigerian government should also continue to provide vaccines for typhoid. 

## References
1. https://www.who.int/news-room/fact-sheets/detail/typhoid
2. https://www.who.int/gho/epidemic_diseases/typhoid/en/
3. https://www.who.int/immunization/monitoring_surveillance/burden/estimates/Incidence/en/

## Author
Bakari Hamisi
```
