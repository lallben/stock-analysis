# stock-analysis
## Overview:
Steve is a recent financial graduate aiming to help his parents with researching the performance of the stocks that they own. He also wants them to diversify their stock holding. In order to do this, he needs to be able to organise and summarise the raw data that he downloads to show the stock performance of a variety of stocks over different years. He would like:<br>
- The analysis be an automated process so that he does not spend time coding.<br>
- To be able to see the performance of all the stocks for a particular year.
## Results: 
### Analysis of stock performance over 2017 & 2018:
![Results of Analysis for 2017](https://github.com/lallben/stock-analysis/blob/main/Resources/stock_analysis_2017.png)
![Results of Analysis for 2018](https://github.com/lallben/stock-analysis/blob/main/Resources/stock_analysis_2018.png)<br>
It appears that the stock ***'DQ'***, currently held by Steve's parents has consistently given negative returns over the two years while ***'ENPH'*** & ***'RUN'*** have consistently done well despite a huge downturn in almost all the stocks being analysed. Steve should recommend adding the two stocks to the portfolio of his parents to diversify their current holdings.
### Time taken to Execute code for 2017 & 2018:
- ***With Original Code:***<br>
![Execution time for original code](https://github.com/lallben/stock-analysis/blob/main/Resources/original_code_time_2017.png)
![Execution time for original code](https://github.com/lallben/stock-analysis/blob/main/Resources/original_code_time_2018.png) <br>
- ***With Refactored Code:***<br>
![Execution time for refactored code](https://github.com/lallben/stock-analysis/blob/main/Resources/VBA_Challenge_2017.png)
![Execution time for refactored code](https://github.com/lallben/stock-analysis/blob/main/Resources/VBA_Challenge_2018.png)<br>
As can be seen, there was a significant decrease in the time taken to execute the code after it had been refactored. There was almost a 90% decrease in execution time!<br>
## Summary:
### <i> Advantages or disadvantages of refactoring code.</i>
Refactoring a code that was used previously for a similar project is advantageous in that it cuts down time. Howeever, the challenge with refactoring is always being aware of the logic and ensuring that the new code factors in the changes that you need. Refactoring does not mean that you do not need to think through the logic, because if you are not careful you may end up spending more time debugging and it may have been better to just start from scratch.<br>
### <i> Pros and Cons of refactoring the original VBA script.</i>
In specific reference to this challenge, the refactoring was done to incorporate the use of arrays which was not the case in the original VBA script. Incorporating the arrays resulted in a marked increase in the speed of execution of the code. This is a distinct advantage and a definite pro, as it enables analysis for data that can be very large particualrly when it comes to dealing with data relating to the performance of stocks.<br>
The one con or disadvantage to the refactoring the original VBA code to incorporate arrays was that the number of lines in the code increased. This can be seen if you compare the length of the code lines:
- ***Original Code***<br>
![Original code for calculations only](https://github.com/lallben/stock-analysis/blob/main/Resources/original_code_lines.png)<br>
- ***Refactored Code***<br>
![Refactored code for calculations only](https://github.com/lallben/stock-analysis/blob/main/Resources/refactored_code_lines.png)<br>
So you can see that adding the arrays definitely increased the number of lines on the code because of the initialisation of the various arrays, however it did make the code efficient.
