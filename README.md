# VaR-with-Variance-Covariance-Method
Value at risk(VaR) is a statistical measure that represents the maximum loss of a portfolio over a specified period for a given confidence level. Risk Managers use VaR to understand and control the level of risk exposure to a specific position or whole portfolio and use them to measure firm-wide risk exposure. The two main components of Var are: 

1. Confidence Interval
2. Time Period

Var is expressed as a dollar amount and confidence level. For ex, “There is a 5% probability that the portfolio will lose $Y over the next X days.”

There are three main ways of computing VaR 
1. Variance-Covariance(Parametric Method)
2. Historical Simulation(Non-Parametric Method)
3. Monte-Carlo Simulations

In this notebook, I have calculated the VaR of a portfolio consisting of 5 stocks:
1. Vanguard Total Bond Market Index Fund ETF('BND')
2. SPDR S&P 500 ETF Trust ('SPY')
3. SPDR Gold Trust ('GLD')
4. Invesco QQQ Trust ('QQQ')
5. Vanguard Total Stock Market Index Fund ETF ('VTI')

Using the Parametric Method, I have calculated 5-day VaR at 90%, 95% and 99% Confidence Intervals. For this purpose, I have used 15-year return data.

In Parametric or Variance-Coavriance Method, we assume that the return distribution is normally distributed around the mean of bell-shaped probability distribution. It is also assumed that the standard deviations of asset returns and the correlation among the assets remain constant. This method is best suited when the return distributions are known and can be reliability estimated. 

I also experimented this method in google sheets. The link is attached below
https://docs.google.com/spreadsheets/d/1BR29gwGVVlvs_QmiFaDlkfMxSybTvrEHEzyKvca7-fY/edit?usp=sharing 

I have taken the help of various resources available online to do the project. Playlists of Var available on youtube such as those of Mehul Mehta and Ryan O’Connell along with many more have been tremendously helpful. 



