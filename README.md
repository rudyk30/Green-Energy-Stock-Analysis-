
## Overview and Purpose of Project ##

The purpose of this project was to refactor or edit the Green Stocks VBA code to loop through all the data one time, allowing Steve to analyze the entire stock market, rather than a handful of stocks. In addition, we want to determine if refactoring the code made the script run faster or slower than the original VBA script that was written. Overall, the purpose is to make this code more readable, efficient, and useful for Steve. 

## Results ##

Stocks performance in 2017 was significantly better than stock performance in 2018. In 2017, the average return on a stock was 67%, with 11/12 stocks having a return >0% and 3 stocks having a return >100%. 

<img width="234" alt="Refactored_2017_Results" src="https://user-images.githubusercontent.com/101602688/160930853-1b956825-0e9f-4f4e-bdea-c1898daeacab.png">
 

2018 was a significantly worse year in terms of stock performance. Only 2 out of the 12 stocks had a positive return, compared to 11 in 2017. 

<img width="228" alt="Screen Shot 2022-03-30 at 4 06 39 PM" src="https://user-images.githubusercontent.com/101602688/160930932-9b930c4e-4d9f-47c2-88b1-d8ac0797acf5.png">


To confirm if our refactored code made the script more efficient, we compare the execution time of the 2017 and 2018 stock analysis script in the original VBA code to our refactored code. See results below:

#### Original 2017 Execution Time ####
<img width="421" alt="Original_2017_RunTime" src="https://user-images.githubusercontent.com/101602688/160930981-9777f3d1-389b-4cc0-8ed7-108abbddbfa7.png">

#### Original 2018 Execution Time ####
<img width="422" alt="Original_2018_RunTime" src="https://user-images.githubusercontent.com/101602688/160931001-d10012f4-dce3-44e8-93e2-49ce05382b99.png">

#### Refactored 2017 Execution Time ####
<img width="420" alt="Refactored_2017_RunTime" src="https://user-images.githubusercontent.com/101602688/160931027-e8abc5da-f0d6-4c87-915e-fe6b994976ee.png">

#### Refactored 2018 Execution Time ####
<img width="422" alt="Refactored_2018_RunTime" src="https://user-images.githubusercontent.com/101602688/160931045-be624665-9571-42d9-9a53-37777918bb0b.png">


It is clear the refactored code execution time was faster, proving the new code is more efficient to run. The execution times for the refactored script were significantly faster than the original script, showing the refactored code will be easier to run for larger sets of data. 

## Summary ##

### Advantages and Disadvantages of Refactoring Code ###

A major advantage of refactoring code is it is much easier to identify errors or mistakes made in the code itself. In addition, it makes code much more efficient and streamlined, which will allow it to handle larger sets of data. Refactoring makes it easier to change code in the future as well, as the code is in a more readable and concise format. A disadvantage of refactoring is if you don't fully understand the original code, it will be hard to find ways to make it more streamlined. Refactoring is also a tedious process that is fairly time consuming. It is risky as well, if working with a large script you are at risk of causing permanent damage to code that already works. 

### How do these pros and cons apply to refactoring the original VBA script? ###

When refactoring the original VBA script for this challenge, it was fairly time consuming and a tedious process. At times I had to completely start as I started to get lost in the code. However, after refactoring, the code was much easier to read and understand. In addition, it made the code more efficient, and the script executed much faster as evidenced by the improvement in run times. 



