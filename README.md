# Monte-Carlo_Simulation
## Introduction to the project
Business valuation is a process and a set of procedures used to estimate the economic value of an owner’s interest in a business. The value of an asset is the present value of its expected returns. In order to calculate the value of a company we need to know its expected cash flows and its required rate of return. Company’s future cash flow could be estimated by forecasting future earnings on the basis of company’s historical earnings and the expected growth of both the firm and the market. The required rate of return that is used to discount the company’s estimated future cash flow has to reflect the risk of those cash flows
Most commonly used method for the company evaluations is Discounted Cash Flow (DCF), Internal Rate of Return (IRR), Economic Value Added (EVA). Many of these traditional models need to consider one parameter that called free cash flow. When estimating this parameter, the prior models are short of accurate method. For example, when estimating free cash flow we often calculate ROI to get future growth rate then calculate the FCF year by year. Obviously, the application of this method lack operability. Because of this weakness, this kind of model usually used in the field of education only. Monte Carlo simulation precisely solve this problem. This model improve the traditional methods and enhanced the operability by thousands of simulation tests.
Monte Carlo simulation also called random simulation, was put forward by American scientists in 1940s. The method obtain the approximate results by statistical analysis and stochastic simulation of random variables. Take DCF model as an example, if the free cash flow of the investment project in the future is expressed as a random variable with a certain probability distribution, we can improve the accuracy of traditional model according to the probability distribution of these random variables. Under the manual condition, it is difficult for people to operate thousands of tests. In this case, people prefer to use matlab in the application of Monte Carlo simulation.
### In terms of the project we will make the below assumptions:
- Tax Rate: 20%
- Discount Rate: low value of 5% and a hign value of 10%. .
- Perpetual Growth Rate: 3% (The perpetuity growth rate is typically between the historical inflation rate of 2-3% and the historical GDP growth rate of 4-5%).
- EV/ EBITDA multiple from 2019: 5x, which is equal to 623.4 / 123.10. We are using this data due to the negative EBITDA in 2020.
- Price per share: CHF 96.65
- Current Price per share: CHF 140.40
- Shares Outstanding: 4,479,637.00
- Market capitalization 2020: CHF 431.9M
- Market capitalization 2019: CHF 623,4M
- For the project, the data used consistts of the financial statements of a Swiss company (which were public). The company is listed on the Swiss Stock Exchange. In terms of the project the company name will not be revealed (just not to create any issue for them).
Also, in terms of the calculations going forward in the project development we will add some more assumptions which to support the calculations and the utilization of Monte Carlo Simulation method regarding the Company evaluation.
### Parameters of the analysis:
1. Timespan - more than 5 years historical data (financial statements), 18 years historical sales data and 5 years prediction.
2. Additional calculations based on the predictions.
3. Company Financial Statements.
4. Excel model with the Discounted Cash Flow calculation which will be used for the simulations.
### Resorces used in the project:
- The financial data used from a Company website - are acquired from the Company website since they are pubic. I do not like to share the Company name since my calculations migth affect them.
- Finance support data is used from https://corporatefinanceinstitute.com/resources/knowledge/valuation/dcf-formula-guide/
- Article "Python in Audit - Revenue Forecasting Using Monte Carlo Simulation" from www.eloquens.com (https://www.eloquens.com/tool/l9VVSMBB/rizwan-ahmed-surhio/python-in-audit-revenue-forecasting-using-monte-carlo-simulation)
- Videos from Youtube.com - Monte Carlo Simulation using Python (Part 1): Concepts, First Simulation and Monte Carlo Simulation using Python (Part 2): Simulation, Plots, Formating.
- Article "How to assess the value of a company, combining discounted cash flows method and a Monte-Carlo simulation in Python?" from https://www.linkedin.com/pulse/how-assess-value-company-combining-discounted-cash-anthony/.
- Theoretical Data from https://corporatefinanceinstitute.com/ and https://www.investopedia.com/.

### The results of the analysis and the conclusions can be find in the Jupyter Notebook
