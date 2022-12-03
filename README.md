# Repository for documenting Portfolio Optimisation process learnt

 The data (ESG Top 100 Stocks.csv) in this repository is provided as part of an individual assignment in the Financial Analytics module taught in the Singapore Management University(SMU)'s School of Computing and Information Systems(SCIS). 
 
 The Jupyter Notebook (Portfolio Optimisation with pyfolio) contain Python codes on the process to optimising asset portfolio (specifically optimising portfolio that consists on Environmental,Social and Corporate Governance(ESG) stocks in this case) depending on the indiviual's investment goal and risk appetite, which typically is about minimising risk and maximising returns. 

Here is a brief outline of the content in the Jupyter Notebook:
- Summary Statistics on the top 100 ESG stocks 
- Initial ESG stocks selection
- Calculating metrics such as returns, volatility, risk-adjusted returns (Sharpe Ratio) beta value and Pearson's Correlation Coefficient on ESG stock price data
- Finding the Efficient Frontier (refer to Modern Portfolio Theory) using Monte Carlo Simulation and select optimal portfolio on the Efficient Frontier based on best risk-adjusted return or lowest volatility
- Do additional manual adjustments to the weightages of the selected portfolio after analysing the metrics of individual stocks (in the selected portfolio)
- Using Python package pyfolio (https://github.com/quantopian/pyfolio) to calculate and visualise the metrics of the adjusted portfolio efficiently

Note: Please put the 2 files together in the same folder!
