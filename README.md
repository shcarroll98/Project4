# Project4
S&P STOCK GROWTH PREDICTORS
TEAM MEMBERS: Chris Wiggs, Shannon Carroll, Trevor Lochan, Khadija Collymore, Samantha Panzini-Taysi

## Investing in your financial education is the first step toward achieving your goals. Whether you’re looking to build wealth, save for the future, or simply gain a better understanding of the financial markets, WeDone is here to guide you every step of the way.

## Unlock Your Financial Future with WeDone
Are you ready to take control of your financial destiny? We believe that financial literacy is the key to successful investing. Our mission is to empower young investors with the knowledge and tools they need to navigate the complex world of finance with confidence.
Why Choose WeDone?
Comprehensive Education: We seek to demystify the market, offering in-depth insights to market forces such as Price-to-Earnings (P/E) ratio, volatility, EBITDA, and more. 
Proven Stock Price Predictor: Our cutting-edge stock price predictor sets us apart from the competition. Our best model has ~75% accuracy, our predictive model helps you make informed investment decisions. Leveraging advanced algorithms and historical data, our tool provides valuable insights into market trends and potential investment opportunities.

## Datasource overview
S&P 500 Data - Updated Daily
2010-2013 recession years 
Merged Company dataset with Stock dataset with SQL Alchemy
AWS S3 Object Storage to make the large dataset shareable

## Price to Earnings Ratio 
P/E Ratio (Price to Earnings Ratio): The P/E ratio is a measure of a company's current share price relative to its earnings per share (EPS). A higher P/E ratio generally suggests that investors are willing to pay more for the company's earnings, often indicating optimism about future growth prospects.
                
## Methodology for Calculating P/E Ratio
Calculated as the current share price divided by the earnings per share (EPS)

## Median P/E Ratio
Computed the median P/E ratio for each industry to identify typical valuations.When we calculate the median P/E ratio for a particular industry, we're finding the middle value of all the P/E ratios for companies within that industry. Unlike the mean (average), which can be influenced by extreme values, the median represents the middle value when all values are sorted in ascending order. So, the median P/E ratio gives us a more robust measure of the typical valuation within the industry.

Recommendations based on findings
Diversify Investments: Consider spreading investments across industries with high P/E ratios to mitigate risks.
Growth Potential: Focus on industries with higher median P/E ratios for potential high growth returns. Market Trends: Stay updated on market trends that might impact P/E ratios. Valuation Considerations: Balance between high P/E (growth stocks) and low P/E (value stocks) based on risk appetite.

## Decision Tree - Revenue Growth 
20% used for training, 80% used for training
100 decision trees
R^2 = .24       RMSE = .029
Using this decision tree model, revenue growth can only be used to explain 24% of the variance in stock price growth and volatility. The model only explains a small portion of variability in stock returns.

## A Closer Look - The Tech Sector
![bar graph](https://github.com/shcarroll98/Project4/blob/main/Graphs/price%20diff.png)
## Double click: Electronic gaming and multimedia
An RMSE of 0.38377 indicates that, on average, the difference between the predicted values and the actual values is about 0.38377 units. A RMSE of 0.38377 indicates a moderate level of error.

## Conclusions
Our best model has an accuracy of 79% which is better than the market average for similar models.
AltIndex
Most accurate stock predictor for 2024; Uses alternative data (social media, website analytics)
AI converts data into risk-averse stock picks
72% win rate, 21% average 6-month gains
Danelfin
AI stock predictor covering NYSE, NASDAQ, and European markets
158% growth (2017-2022), compared to S&P 500's 70% growth
Provides AI ranking scores and daily top-10 picks
Alpha Picks by Seeking Alpha
Operational since December 2009
25% average annualized returns from 'Strong Buy' recommendations




