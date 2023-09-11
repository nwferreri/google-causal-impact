# Google Causal Impact - Volkswagen CO2 Scandal

## Question

What effect did the 2015 CO2 scandal have on the price of Volkswagen stock?

## Data

Using [`yfinance`](https://pypi.org/project/yfinance/), stock data was pulled for Volkswagen and several other companies in different industries.

A correlation matrix was created to assess the comparable stocks.<br>
![image](https://github.com/nwferreri/google-causal-impact/assets/112211174/609c8e29-f40d-40e1-8a45-f7104506f26b)<br>
META and AMZ were dropped due to low correlation with VW.

## Analysis

[Google Causal Impact](https://github.com/WillianFuks/tfcausalimpact) was used to analyze the stock data.

With a training period from January 2015 through August 2015 and a treatment period across September 2015, the following charts were produced:<br>
![image](https://github.com/nwferreri/google-causal-impact/assets/112211174/d7a30b3c-c8bd-4e54-bd4f-1603aec636fc)

## Conclusions

The analysis clearly shows a negative impact of the CO2 scandal on the price of Volkswagen stock.  On average, the decrease in price was about 20% compared to the price prior to the scandal.
