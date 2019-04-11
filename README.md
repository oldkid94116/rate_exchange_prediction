# rate_exchange_prediction

Capstone project g88

Capstone Project: 
Long Short Term Memory (LSTM) Recurrent Neural Network Model to predict foreign currency exchange rate based on 
two countries central bank interest rates and U.S. import/export.

File eu_mf_prod.ipynb used LSTM model to predict EU/USD exchange rate based on US Central Bank interest rate and EU Central Bank interest rate as well as US import / export energy.

Prediction results from weekly data set 2001 to 2017: </br>
----------------------------------------------------- </br>
1 Week		Average	Prediction	Error </br>
12/4/2017	12/8/2017	0.847	0.8467	-0.00035 </br>
2 week				
12/11/2017	12/15/2017	0.8494	0.8443	-0.006 </br>
3 week				
12/18/2017	12/22/2017	0.8442	0.8528	0.0101 </br>
4 week				
12/25/2017	12/29/2017	0.8395	0.854	0.017 </br>
5 week				
1/1/2018	1/5/2018	0.8308	0.8538	0.0269 </br>
6 week				
1/8/2018	1/12/2018	0.8322	0.8534	0.0249 </br>
7 week				
1/15/2018	1/19/2018	0.8174	0.8531	0.0418 </br>
8 Week				
1/22/2018	1/26/2018	0.8092	0.8552	0.053789 </br>


File: </br>
./Forex_preprocess.ipynb (Preprocess test data for Forex_model) </br>
./Forex_model.ipynb (Constructing test model module) </br>
./data (data files) </br>
./urls (links used to download data) </br>
 </br>
./eu.ipynb (first working LSTM model with only 1 feature time series its own self) </br>
./Results.ipynb (records for testing with different hyperparameters of LSTM model) </br>
 </br>
./eu.ipynb (first working LSTM Model fitting with multiple features or dimensions) </br>
./eu_mf_prod.ipynb (final working LSTM Model with Demo data set) </br>
./Results.ipynb (recorded all test results from eu_mf_prod.ipynb) </br>
 </br>
./MA_RMSE.ipynb (used for calculating base line model Moving Average 4 weeks and calculation of RMSE for both models) </br>


Work In Progress: </br>
==================================================================== </br>
System Environment: </br>
  Only testing environment setup. </br>
Dataset Readiness: </br>
  Coding: </br>
    Completed for testing dataset cleaned and ready for model. </br>
    LSTM Model completed (phase I) </br>
 </br>
Application Development: </br>
  Coding for main application: Completed (phase I) </br>
 </br>
Dedug: </br>
  Done </br>
 </br>
Deployment for Training and testing Dataset: </br>
  Dataset Readiness: Completed </br>

