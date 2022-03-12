# stock-analysis
Stock Analysis utilizing VBA

## Project Overview

Our client, Steve, inquired about stock return. We ran a report outlining the return on total daily
volume for 12 stocks requested. This anaylsis was designed to identify successful return, revealing 
which stock would be the best for investment.


## Project Results

As shown below, it is clear in running this analysis that the stock with the most consistent return is ENPH. 
Where as it did not have the highest return in 2017 it still showed over 100% with an 81.9% return in 2018. 
In comparison ENPH shows the most promise. A second stock also showed a high positive return value in 2018, 
but a very low positive return value in 2017. We can deduce that the stock to invest in is ENPH. 
![VBA Challenge 2017](resources/VBA_Challenge_2017.png)
![VBA Challenge 2018](resources/VBA_Challenge_2018.png)

## Project Summary

Initially the original code ran between 2.2 and 4.3 seconds for returned values, by refactoring the code
we were able to see a fraction of a second return. This allows for immediate disply with no screen interruption.
However, some disadvantages we may run into is the time it takes to test the refactored code to ensure it is 
running properly. Refactoring while more efficient in time running may take longer to develop and debug. 