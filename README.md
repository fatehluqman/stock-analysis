![VBA_Challenge_2018](https://user-images.githubusercontent.com/62673123/125004513-8aeec580-e00e-11eb-90c9-6804e41e66b9.PNG)
# stock-analysis

## Overview of Project

The purpose of the project is to analyze stocks for a set of companies for multiple years of 2017 and 2018. The analysis involved tracking the total daily volume and yearly return for each stock. 
The initial project was to analyze the stock for DQ for 2017, but eventually expanded to additional companies for 2017 and eventually to 2018. 

## Results

### Stock performance between 2017 and 2018

For the most part the performance in stock between 2017 and 2018 was drastic.  in 2017 all but one company had positive returns, however this flipped in 2018 has all but two companies had negative returns. 
ENPH was one of two companies that showed positive returns for 2018 and had positive returns for 2017. Even though ENPH had positive returns each year, the return from 2017 to 2018 did decrease.  
RUN was the second company that had positive returns each year, however RUN returns increased from 2017 to 2018. Both companies also increased their daily volume Year over Year indicated both were traded more often.
TERP was the only company that had negative return in 2017.  TERP return in 2018 remained negative however the return in 2018 was not as bad as 2017. 

### Execution times between original script and refactored script

The results of the refactored code were significant improved performance over the original code. The original code ran between .929 seconds to .933 seconds compared to the refactored code at just .30 seconds. 
It was interesting to note that the refactored code when ran for both 2017 and 2018 ran at the same time, however the original code for 2018 ran slightly faster than for 2017.
![VBA_Challenge_2018](https://user-images.githubusercontent.com/62673123/125004557-a4900d00-e00e-11eb-8f16-0bdf02fde0a0.PNG)
![VBA_Challenge_2017](https://user-images.githubusercontent.com/62673123/125004563-a8bc2a80-e00e-11eb-8f30-73baeb01d842.PNG)

## Summary

### Advantages/Disadvantages of refactoring code

The key advantage of refactoring code is improved performance and organized code that allows for easier debugging.  Refactoring is a way to restructure the code, so it preforms better and is easier to view, without changing its functions.
Disadvantages of refactoring are the time it takes to rewrite the code and during which new bugs could be introduced. 

### Pros/Cons of refactored original VBA script
There were two advantages to refactoring the code for this project.  First the refactored code ran faster reducing the time to run the program from nearly 1 second to about 1/3 of a second.  
The second advantage was that the formatting sub routine was included in the refactored code, where in the original code this was separate and needed to eb run separately to format the data accordingly.   
![green_stock_2017](https://user-images.githubusercontent.com/62673123/125004576-b07bcf00-e00e-11eb-9109-5e4fa2771ae8.PNG)
![green_stock_2018](https://user-images.githubusercontent.com/62673123/125004585-b40f5600-e00e-11eb-851b-f351a45480d7.PNG)
