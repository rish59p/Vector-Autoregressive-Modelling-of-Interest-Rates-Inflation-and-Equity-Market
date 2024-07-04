# Modeling Interest Rates, CPI, and SENSEX 50 using Vector Auto-Regressive Methods
##Project Overview

This project aims to model the relationships between interest rates, Consumer Price Index (CPI), and the SENSEX 50 index using Vector Auto-Regressive (VAR) methods. The project includes establishing Granger causality, variance decomposition, and impulse response functions. Additionally, seasonality adjustments are applied using filters to ensure accurate analysis.
Objectives

    Model the dynamic relationships between interest rates, CPI, and the SENSEX 50 index.
    Establish Granger causality between the variables.
    Perform variance decomposition to understand the contribution of each variable to the others.
    Analyze impulse response functions to observe the impact of shocks.
    Apply filters to adjust for seasonality in the data.

##Data Description
###Variables:

    Interest Rates: The yield on government securities, reflecting the cost of borrowing.
    Consumer Price Index (CPI): A measure of inflation tracking changes in prices paid by consumers for a basket of goods and services.
    SENSEX 50 Index: Represents the performance of the top 50 companies listed on the Bombay Stock Exchange.

###Data Sources:

    Interest Rates: Government of India data.
    CPI: Government of India data.
    SENSEX 50 Index Prices: Yahoo Finance.

###Time Period:

    The data covers multiple years, capturing monthly observations for all variables.

##Methodology
###Data Preprocessing

    Import and clean the data to ensure consistency and completeness.
    Apply filters to adjust for seasonality in the CPI and SENSEX 50 index data.

###Stationarity Testing

    Conduct Augmented Dickey-Fuller (ADF) tests to ensure stationarity of the time series.

###VAR Model Fitting

    Determine the optimal lag length for the VAR model using criteria like AIC and BIC.
    Fit the VAR model to the time series data.

###Granger Causality Tests

    Conduct Granger causality tests to determine if one time series can predict another.

###Variance Decomposition

    Analyze the variance decomposition to understand the contribution of shocks to the forecast error variance of each variable.

###Impulse Response Functions

    Generate impulse response functions to observe the impact of a shock to one variable on the other variables over time.

##Results

    Granger Causality: Results indicate the predictive relationships between interest rates, CPI, and the SENSEX 50 index.
    Variance Decomposition: Insights into the proportion of forecast error variance attributed to each variable.
    Impulse Response Functions: Visualization of the dynamic impact of shocks to one variable on the others.

##Conclusion

The project successfully models the interrelationships between interest rates, CPI, and the SENSEX 50 index using VAR methods. The Granger causality, variance decomposition, and impulse response analyses provide valuable insights into the dynamics of these economic indicators. Seasonality adjustments ensure the accuracy and reliability of the results.
