ID: Security Id
Date: Rebalance Date
ROE: Return on Equity Factor
QES_GSECTOR: Sector Code
FRTN1P: Forward One month return

Jupyter notebook that does the backtesting of the data using the ROE factor. 
Neutralize the factor based on QES_GSECTOR. Use 20 bins and go long on the top 5% of stock 
and short on bottom 5%. 



- Pie chart showing fraction of stock in each sector. You can use the last month to do this. 
- The Long/Short cumulative return over the one year period using ROE factor and QES_GSECTOR for neutralization. 
- Information Coefficient over the one year period
