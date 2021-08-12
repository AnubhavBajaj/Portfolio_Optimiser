# Portfolio_Optimiser


Selected Stocks are:- Shree Cement, Bajaj Auto, IndusInd Bank, Eicher Motors, Maruti Suzuki , Titan

Risk Free return rate as - 0.07 or 7%
### How did you choose the stocks?

Criteria for selection - No Corporate Actions like Bonus, Splits and Rights;

Criteria for optimising portfolio - No short selling

and Expected Return(we have taken CAGR as return) greater than 0 for each stock
### What is the impact of increasing the number of stocks in the portfolio?

Adding stocks from 1->5 increases possible values of reward and risk ratio thereby giving more freedom to an investor 6-15 as number of stock is sweet region to minimize risk for max return and 15-24 more or less generalises portfolio as market portfolio and beyond is simply over generalisation and becomes inefficient portfolio.
### Why are calculating the weights by optimization and not giving equal weightage to every stock?

In order to minimise risk and maximise expected return and giving equal weightage isn't an affective way.
### Which parameters are you using to check the accuracy of your model?

Sharpe Ratio, Treynor Ratio, Expected Return and Variance

## Process of Optimising Portfolio based on historical data
* Collecting data
* Calculating return, standard deviation of returns and Covariance of returns
* Simulate many portfolio weights.
* Based on metrics such as Sharpe ratio,Treynor ratio select Porfolio weights
* Based on weights calculated above we test return of these portfolio on current data

## Markowitz Bullet
![homepage](https://github.com/AnubhavBajaj/Portfolio_Optimiser/blob/main/Markowitz%20bullet.png)
* RED star: Maximum Sharpe Ratio portfolio
* GREEN star : Minimum variance portfolio
* YELLOW star : Highest Treynor Ratio portfolio
* CYAN star : Highest return portfolio

