<h1 align="center">
	<b> Stock Trading Algorithm </b>
</h1>

<p align="center"> <i> 
In this Repo, we like three things: Programming, Visual Data, and Returns
	</i>
<p> 
	

## Description

<div> 
I set out to test my skills and see how well I can perform against the market beased on historical data of a few key selected stocks. Armed with rudimentary knowledge of programming and trading, how well can a person do against the 7% average annual return of the S&P 500?
</div> 
	
## What To Know


	  
<div> 
	<p> Those who wish to follow should have a basic understanding of the following principles
	<p align="center"> <b> Jupyter Notebook <br /> Pandas <br /> Simple Moving Averages <br /> Python <br /> MPL Finance <br /> QuandL API </b> </p>

</div>

If you have any experience with the above tools or libraries, then you are more than prepared to explore this repository. Remember, our goal is to use rudimentary knowledge of both programming and trading to beat 7% annual returns.

## How Do We Analyze Stocks? 

The way I went about analyzing stocks was centered around one principle: *Cross-Over's of Simple Moving Average's (S.M.A's).*

Given weekly data, we looked at 20, 50, and 200 moving day average's and found a linear regression ribbons representing their price behavior. Then, we analyzed the visual charts according to a few basic rules

<br />
<br />

<p align="center"> 
	<b> <i>
	When the 20 day moving average falls below the 50 day moving average, the stock will fall <br />
	<br /> When the 50 day moving average falls below the 200 day moving average, the stock will fall <br />
	<br /> When the 200 or 50 day moving average cross above the 20 day moving average, the stock will rise <br />
	<br /> When the 200 day moving average crosses above the 50 day moving average, the stock will rise <br />
		</i> </b>

</p>

<br />
<br />

Based on these simple rules, I found every instance of a cross over period and whether they were periods of purchasing (green) or holding/selling (white), and compared against the average return across the same period.

## How did it go?


When backtested within a hypothetical porfolio of 1 million dollars across a few selectede stocks from the time of 2015-01-11 to 2017-11-11, we resulted in a 40% overall gain across 2.9 years, exceeding the 7% S&P 500 Return

## Final Comments

*Stonks Go BRRRRR*
