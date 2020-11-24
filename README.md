# Predictive-Equity-Analytics-TRI-SIGNAL-Machine-Learning-Project
Equity price prediction machine learning models are hindered by presence of noise in data which degrades predictive accuracy as a function of noise level which varies over time. Noise in external data sets or contained in a data lake presents an additional time varying noise source. Practitioners can use TRI-SIGNAL predictive equity analytics Signals {1,2,3} 4,000+ data set to overcome the effects of noise in equity price series on machine learning models as starting data set to create predictive models with consistent high predictive power. Create customized predictive equity models by combing additional external data sets with TRI-SIGNAL Signals {1,2,3} for causality attribution modeling or to create complex deep learning machine learning models. 


Each trade day prior to market open IHA Consultants generates predictive equity analytic signals (1,2,3) for over 4,000 U.S. equities that are predictive for the current trade day available with subscription. IHA Consultants supplies the complete prior trade day TRI-SIGNAL predictive equity analytics data file free of charge (but with required agreement to release of liability) for use under the licensing terms of the Predictive Equity Analytics TRI-SIGNAL Machine Learning Project

Prior trade day TRI-SIGNAL predictive equity analytic data files can be downloaded at https://ihaconsultants.com/f1/401k_f1_login.php. <br/><br/> Login information as follows: <br/> &nbsp;&nbsp;&nbsp;<b>Username(email address):</b> 'equity_researcher' <br/>  &nbsp;&nbsp;&nbsp;<b>Password:</b> 'tri_signal_12_2020' <br/> &nbsp;&nbsp;&nbsp;<b>Select Report to Download:</b> '1' - TRI-SIGNAL: DEEP ANALYTICS DATA SET PRIOR DAY.  

A template Excel user interface macro file is available for download using the link below. The Excel macro file has vba code for data file retrieval, stock filtering and graphical output to the 'Graphs' tab of the Excel file. An original copy of the data is stored on the 'Original Data' tab and a working copy with filters applied is found in 'Sheet1' tab.  Module_1 of the vba code is where you will find the TRI-SIGNAL filtering and graphing routines. The other modules contain standard portfolio theory vba code. 

Download TRI-SIGNAL Predictive Equity Analytics Excel v200 macro file here: https://ihaconsultants.com/f1/401k_f1_login.php

<h2>TRI-SIGNAL Signals {1,2,3} Signal Descriptions</h2>

Signal 1 and Signal 3 are used for reliable prediction with accuracy greater than 85% for future 1 to 3 trade-day stock price behavior. Signal 2 can be thought of as either representing the result of a well-executed marketing plan (temporary higher level of demand that abates in short order with no lasting correlation) or statistical noise (persistent but inconsistent correlation.)

Signal 1 and Signal 3 are jointly predictive for stock selection and timing of increase. Signal 1 and Signal 3 are each independently predictive when used as sole predictor. Predictive accuracy is increased by using both Signal 1 and Signal 3 for predictive rule construction.

<h2>Signal 1 – Stock Series Event Signal has Occurred</h2>
Signal 1 is a stock price series event signal that represents a probable change in behavior from the most current price series data. Signal 1 signal strength ranges from 0 to 1.1. Signal 1 signal strength greater than or equal to 0.6 is considered significant in that a stock price event has occurred and analysis is warranted to determine trade action. The higher the Signal 1 signal strength the greater the significance.

Signal 1 strength greater than or equal to 0.6 indicates when a stock price series is likely to change behavior as compared to most recent behavior. For example, a stock price series that was moving horizontally is predicted to move up or more down in future 1 to 3 trade-days . Other examples include a stock price series that was moving down and is now predicted to start moving up or moving horizontally. Lastly, a stock price series that was moving up and now is predicted to move down or move horizontally.

Signal 3 analysis (level and recent trend) is required to determine the predicted future price direction behavior.

<h2>Signal 3 – Stock Series Direction Signal</h2>
Signal 3 is a stock price direction change signal that represents a probable change in behavior from the most current price series behavior. Signal 3 signal strength ranges from 0 to 1.12 and changes are measured relative to the average 121 trade-day value. Signal 3 average is typically found to be in the set {0.9, 0.95, 0.97}depending on the particular stock or sector. Signal 3 stock price direction change is measured by comparing the most recent value to the average or using the most recent signal 3 trend. 

Signal 3 greater than the 121 trade-day average or most recent signal 3 trend increasing and “near the average” signifies probable stock price increase in future 1 to 3 trade-days. Signal 3 less than the 121 trade-day average or most recent signal 3 trend decreasing and “near the average” signifies probable stock price decrease in future 1 to 3 trade-days.

<h2>Predictive Rule Construction</h2>
Using Excel, filtering of 4,000+ equities for Signal 1 and Signal 3 for joint predictive rule construction proceeds with selection of stocks with Signal 1 greater than or equal to 0.6 (all stocks with “stock event”) and Signal 3 greater than or equal to 0.97 (stocks with predicted future 1 to 3 trade-day price appreciation.) There is an automated routine that produces predictive rule application as a report as well in graphical form. 

Users are free to tweak provided template predictive rules or develop customized predictive rules.


We illustrate automated Optimal TRI-SIGNAL Buy/Sell Predictive Rules using Agilent Technologies (A) stock price series.

<img src="https://github.com/mz27514/Predictive-Equity-Analytics-TRI-SIGNAL-Machine-Learning-Project/blob/main/tri_signal_signals_123_description.png" />

<b>Contact Information</b> 
This site is maintained by <img src="https://github.com/mz27514/Predictive-Equity-Analytics-TRI-SIGNAL-Machine-Learning-Project/blob/main/iha_logo_email.png" />IHA Consultants Inc. Please contact us at https://ihaconsultants.com.
