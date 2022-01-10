# Stock Analysis

## Overview of Project

### Purpose
The purpose of this analysis is to help Steve, how is looking to compare a handful of green energy stocks, and how they performed in 2017 and 2018. With this information, he wants to help diversify his parents' investment portfolio. 

Furthermore, this analysis will be look at two different ways of accomplishing this task, to find a more efficient way to do so. Therefore, both the original code and refactored code will be referred to in this analysis.

## Results

### Stock Performance Analysis
To compare twelve green stock performances in 2017 and 2018, **Ticker Starting Prices** and **Ticker Ending Prices** were pulled through a macro in excel, using the following code in the refactored code:
![Ticker Starting and Ending Prices](https://github.com/baileyvo/stock-analysis/blob/main/Resources/Starting_Ending_Prices.png)

The **Ticker Starting Prices** and **Ticker Ending Prices** were then used to generate **Return** matched to the proper **Ticker** using the following refactored code:
![Return](https://github.com/baileyvo/stock-analysis/blob/main/Resources/Returns.png)

This generated returns for the stock in **2017**:

![Stock Performance 2017](https://github.com/baileyvo/stock-analysis/blob/main/Resources/Stock_performance_2017.png)

and **2018**:

![Stock Performance 2018](https://github.com/baileyvo/stock-analysis/blob/main/Resources/Stock_Performance_2018.png)

These results show a few things:
- **2017** was an extremely good year for green stocks, with DQ, ENPH, FSLR, and SEDG all showing over 100% returns
- **2018** was not as good of a year for green stocks, with only ENPH and RUN showing positive returns
- DQ, Steve's parents' preferred stock, shows a negative return for 2018, therfore may not be a good investment, and especially should not be the sole investment in their portfolio
- Overall, **ENPH** seems to be the best investment, as the only stock that showed positive returns in 2017 and 2018

### Execution Time Comparison
To compare the execution time of the original code to the refactored code, the following command was used:
![Execution Time Comparision](https://github.com/baileyvo/stock-analysis/blob/main/Resources/Execution_Time_Comparison.png)

The initial code had a run time of 1.5625 secs for 2017 and 1.773438 secs for 2018. The refactored code had a run time of 0.2109375 secs for 2017 and 0.25 secs for 2018, as can be seen in the images below:

![2017 Execution Time](https://github.com/baileyvo/stock-analysis/blob/main/Resources/VBA_Challenge_2017.png)	![2018 Execution Time](https://github.com/baileyvo/stock-analysis/blob/main/Resources/VBA_Challenge_2018.png)

## Summary

### Advantages of Refactoring Code
Refactoring code does not change what the code accomplishes. However, it the refactored code is more efficient and/or more clear than the original code.

###Pros and Cons
On pro of refactoring this code was that it ran faster, which is especially important as data sets get larger or as the code becomes more complicated. Another pro was it allowed me to go back and better annotate the code, making it more consumable to a reviewer.