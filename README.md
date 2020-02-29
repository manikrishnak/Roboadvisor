**Roboadvisor**

**Technology used:** Python, SQL, ML and finance analytics

[Project White Paper](Portfolio_Robo_Advisor_White_paper_MSBA_2019.pdf)

Today we have many robo advisors in the market replacing the conventional financial advisors. Most of these robo-advisors deal in 
index or mutual funds and rarely in stocks. This is where our product steps in to capitalize on this huge untapped potential. 

By analyzing the three main financial documents of a company: the balance sheet, income statement and cash flow statement we have adopted
a two step process to identify stocks for our value and growth portfolio. The first step of the process is to find out the intrinsic 
value of a stock using the discounted cash flow method. Once a fair value for a stock is established using the company's past five years 
data and projecting for the next five years, the fair value thus obtained will be compared against the current stock price to see if a 
given stock is currently trading under its fair value; if yes, we would pick such stocks which have strong fundamentals and are currently 
not trading up to their potential for various reasons. On these short listed stocks, are further narrowed down using few more technical 
indicators to arrive at the final list.
 
Once the stocks are identified, we applied the modern portfolio theory and Sharpe ratio along with the optimization engine from the 
library CvxOpt to find the weightage that needs to be allocated for each of the stocks in value and growth portfolio. The value and growth 
portfolio's are rebalanced every three years while we annually gather the financial data from the companies and monitor the performance
closely.

While on one hand we programmatically apply the formulas to create value and growth portfolio's, on the other hand  we have an
AI portfolio that is generated by feeding the three same financial documents to our ML algorithm along with feeding other features like
the S&P return, recession factor to name a few; our ML model is able to generate a portfolio that is likely to produce better than the 
S&P index. The model has an accuracy of 75%.

*Added few sample code files, since the project is being developed further*


