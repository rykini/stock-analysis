# stock-analysis

## Overview of Project
The project is to analyze on a number of different stocks in year 2017 and 2018. Two scripts are created in VBA to output some intuitive information about the stocks. 

## Results

### Analysis of data
Below is the analysis our macro creates. There are twelve tickers. The 'Total Daily Volume' is a sum of volumes in each year. To get the 'Return' value, the ticker's ending price is divided by the ticker's starting price of the year, then substracted by 1. The colomn is color-coded, green means the ticker had a growth in the given year, and red indicates there was a loss. 

![fig1](Resources/All_Stocks_2017.PNG)
![fig2](Resources/All_Stocks_2018.PNG)

We can tell easily from the color that in 2017, the majority hade a positive growth, only one ticker ('TERP') had a negative return. Whereas in 2018, only two tickers ('ENPH' and 'RUN') were growing, all the other tickers were having a negative return. 

### Execution time of scripts
Two different scripts are used to perform the analysis, the original one and the refactored one. The original script loop over the rows 12 times, each time it is looking for data for one ticker. But in the refactored script, since the data is ordered by tickers, we only loop over the rows once, which saves a lot of time, shown below.

![fig3](Resources/VBA_Challenge_2017.PNG)
![fig4](Resources/VBA_Challenge_2018.PNG)




## Summary

