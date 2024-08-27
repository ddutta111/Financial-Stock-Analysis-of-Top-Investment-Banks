# Financial Stock Analysis of Top Investment Banks_Python

## Overview

This project is an exploratory data analysis (EDA) of the stock prices of six major investment banks listed on the New York Stock Exchange (NYSE) from January 2011 to January 2023. The analysis focuses particularly on the COVID-19 pandemic period (2020-2022) to understand its impact on the financial sector.

## Dataset: Investment Banks Analyzed

J.P. Morgan & Chase Co. (JPM)

Morgan Stanley (MS)

UBS

Barclays Bank Plc (BCS)


Goldman Sachs (GS)

HSBC

## Data Collection

Stock data for each bank was downloaded using the yfinance library. The data spans from January 1, 2011, to January 1, 2023.

Required Libraries: yfinance, pandas, numpy, matplotlib, seaborn, plotly, cufflinks

## Data Preparation
**Data Download:** Stock data for the six banks was downloaded and stored in separate DataFrames, with each DataFrame named after the bank's ticker symbol.
**Data Merging:** The individual DataFrames were concatenated into a single DataFrame bank_stocks using pd.concat().
**Column Naming:** The columns were structured to include the bank ticker and stock information (Open, High, Low, Close, Adj Close, Volume).

## Exploratory Data Analysis (EDA)
**Key Analyses Conducted:**

**1.Maximum Closing Prices:** Identified the maximum closing price for each bank's stock throughout the entire period.

**2.Stock Returns:** Calculated daily returns for each stock and stored them in a new DataFrame returns.

**3.Best and Worst Days:** Determined the best and worst single-day returns for each stock.

**4.Risk Assessment:** Analyzed the standard deviation of returns to identify the riskiest stock over the entire period and specifically during the COVID-19 pandemic.

**5.Visualizations:**

**Pair Plot:** Compared stock returns across banks using Seaborn's pair plot.

**Distributions:** Created distribution plots for the returns of J.P. Morgan (riskiest) and UBS (least risky) during the COVID period.

**Line Plots & Cluster Maps:** Additional visualizations using Plotly and Cufflinks.

**Usage**
You can explore the analysis by running the provided Jupyter Notebook, which is also compatible with Google Colab. To open in Colab, click the "Open In Colab" button at the top of this README.

## Conclusion
This analysis provides insights into the stock performance of top investment banks over a decade, with a special focus on the impact of the COVID-19 pandemic. The findings highlight the volatility and risk associated with bank stocks during economic downturns.

## Author

Debolina Dutta

LinkedIn: (https://www.linkedin.com/in/duttadebolina/)
