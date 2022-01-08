# An Analysis of Stocks
 
**Overview of Project**

The purpose of this project was to help my client analyze the stock market over the last few years.  The current file has 2 years of data for 12 stocks in it but would like to enhance his research and compare more stocks.  To do this, it required refactoring of the current VBA code provided so that the data runs efficiently and the output is executed quickly.

**Results**

After refactoring the code and running the program successfully, I was able to reduce the time to run the program. It is surprising to see the amount of time that was reduced to run the program with the refactoring.  Below are screenshots showing the before and after run time for the stock analysis for each year.


![](/Resources/2017_Prior.png)
- Image of run time for 2017 analysis before refactoring.


![](/Resources/VBA_Challenge_2017.png)
- Image of run time for 2017 analysis after refactoring.


![](/Resources/2018_Prior.png)
- Image of run time for 2018 analysis before refactoring.


![](/Resources/VBA_Challenge_2018.png)
- Image of run time for 2018 analysis after refactoring.



It was surprising to see the significant change year of year in the stocks as you can see in the images below.  For the ease of review, I have put 2017 and 2018 stocks side by side.  Out of all 12 stocks in 2017, there was only one that had a negative return which is ticker TERP.  Originally, the client was researching the ticker DQ which had the highest return out of all the stocks in 2017 but the lowest daily volume.  In 2018, all but two stocks had a negative return.

![](/Resources/VBA_Comparison.png)

**Summary**

Refactoring code has its advantages and disadvantages.  Refactoring allows the developer to improve code and make it easier to understand and as shown in the challenge, it helps run the program faster.  The disadvantages can be the time put into refactoring and the end result being the same as we just witnessed.  Although we were able to reduce the time it took to run the program, we still had the same result.  Also, refactoring could introduce a bug which would also take more time to debug the code.

The advantage of refactoring the stock analysis was that we reduced the time to run the stock analysis.  Another and rather important advantage was that it made it easier for me to understand by breaking down the steps and putting in comments to explain the purpose of the code.  The disadvantage for refactoring the code was that the result of the coding resulted in the same output.  Unless we were going to add a lot more stocks to the analysis, I do not think the time put into refactoring was worth it.  

