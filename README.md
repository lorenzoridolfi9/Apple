# Apple revenue forecast :apple:
### This repository contains the R code notebook and related datasets to analyze the historical series of Apple revenues from 1970 to 2021. Finally, there is also a report outlining the results achieved by the forecast analysis and related personal interpretations.

### Goal :dart:
The objective of the following paper is to provide as accurate an estimate as possible of the values that Apple's company revenues will take over the next twelve months, with the intent of understanding what growth will be generated in the following year. the following year.

### Dataset :bar_chart:
I constructed the dataset by searching for three macroeconomic variables that could influence the demand trends for the goods sold by Apple. The variables are as follows:

Variables | Description
-|-
CPI Net Food Energy | Inflation as measured by the consumer price index 
Financial Rate Consumer Loans | Financial rate index on personal loans at commercial banks
USA Consumer Trust | Consumer confidence index

### Process of analysis :chart_with_upwards_trend:
The analysis process was carried out by individually considering the chosen variables described above. For each variable, the process was divided into the following stages:
1. Data transformation stage: the time series was made stationary through a process of differentiation of degree 1
2. ARMA(p,q) best model search phase: this phase involved the use of PACF and ACF graphs for the initial identification of the orders p (AR processes) and q (MA processes). The choice of the best model was made by analyzing the values of the information criteria (AIC and BIC), which were used to compare the various models tested. The choice fell on the model with the lowest AIC
3. Prediction step for Y-2022, for each variable chosen
4. Multiple linear regression step for estimating sales revenue

More information on the results obtained can be found in the final report!



