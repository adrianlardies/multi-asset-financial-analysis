﻿# Investing in the Future: Bitcoin, Gold and S&P 500 in the Global Economic Context

<p align="center">
<img src="https://i.ibb.co/YW02V3j/img-a3sun-Aybl-Gc-H0-JOLb-Kz-Mk.jpg" alt="Investment Graph" width="50%">
</p>


## Introduction

In today’s financial landscape, investments in assets like Bitcoin, Gold, and the S&P 500 are gaining popularity, especially among younger generations and tech-savvy investors. This project aims to analyze the historical performance of these assets in relation to key economic factors such as global inflation, Federal Reserve interest rates, and the Volatility Index (VIX). Our objective is to provide insights into how these assets perform in different economic scenarios and to assess their potential as long-term investments.

## Data Sources

We utilized the following datasets for our analysis:

- **Bitcoin Prices**: Daily historical data on Bitcoin’s price evolution, known for its high volatility and speculative nature.
- **Gold Pricess**: A traditional safe-haven asset used as a hedge against inflation and economic instability.
- **S&P 500 Index**: The benchmark index for U.S. stocks, offering a broader picture of market performance.
- **Additional Economic Data**: 
  - Global Inflation Rates (CPI)
  - U.S. Federal Reserve Interest Rates
  - Volatility Index (VIX)
  - Major global economic events and crises that influence these assets' performance.

### Challenges

- **Incomplete Data**: Some datasets had missing or inconsistent values, requiring cleaning and interpolation techniques to standardize and fill gaps.
- **Volatility**: Bitcoin's extreme price fluctuations added complexity to the analysis, requiring special attention to visualize trends effectively.

## Key Questions

1. **How do Bitcoin, Gold, and the S&P 500 perform in the face of rising inflation and interest rates?**
   - **Conclusion**: All three assets react differently, with Bitcoin showing higher sensitivity to interest rate changes, while Gold remains more stable in times of high inflation.

2. **Is Bitcoin a better long-term investment compared to Gold and the S&P 500?**
   - **Conclusion**: Bitcoin offers higher returns but with significantly more risk. Gold provides stability, and the S&P 500 offers consistent growth in the long run.

3. **What is the relationship between market volatility (VIX) and these assets?**
   - **Conclusion**: Bitcoin reacts more sharply to spikes in volatility (VIX), while Gold and the S&P 500 display more moderate movements.

## Methodology

### 1. Problem Definition and Hypothesis Formulation
We hypothesized that Bitcoin, due to its speculative nature, would outperform Gold and the S&P 500 in high-growth periods, while Gold would act as a safe haven during crises. Additionally, we tested the impact of inflation, interest rates, and market volatility on these assets.

### 2. Data Collection and Cleaning
Data was gathered from sources like Yahoo Finance and FRED (Federal Reserve Economic Data). The cleaning process involved filling missing values, standardizing time series data, and handling inconsistencies across different datasets. We employed forward-filling techniques and resampling to align the data to monthly intervals for clearer analysis.

### 3. Exploratory Data Analysis (EDA)
We used various visualizations to explore the relationships between asset prices and economic variables. Key events like the COVID-19 market crash, subsequent recovery, and interest rate hikes were annotated to provide context to the price movements of these assets.

### 4. Data Analysis and Hypothesis Testing
We conducted an in-depth comparative analysis, including:
   - **Price Evolution**: Time series plots of Bitcoin, Gold, and S&P 500, highlighting key events like the Bitcoin halving and Federal Reserve rate hikes.
   - **Investment Simulation**: A simulation of $100 monthly investments into Bitcoin, Gold, and the S&P 500, tracking their cumulative growth over time.
   - **Volatility and Correlation Analysis**:  Heatmaps and bubble charts visualizing correlations between asset prices and macroeconomic indicators like VIX and interest rates.

### 5. Visualization
The visualizations include:
   - **Logarithmic Price Graphs**: Showcasing Bitcoin’s volatility against Gold and S&P 500, highlighting key economic events.
   - **Stacked Investment Growth**: Illustrating how $100 monthly investments into these assets would evolve over time.
   - **Bubble Charts**: Showing the impact of VIX and interest rates on asset prices.
   - **Correlation Heatmaps**: Presenting the relationships between these assets and macroeconomic factors.

## Key Findings and Conclusions

1. **Bitcoin’s Growth and Volatility**: Bitcoin outperformed both Gold and the S&P 500 in terms of long-term growth, though with much higher volatility, especially during market downturns.
2. **Gold as a Safe Haven**: Gold remains a stable asset, particularly during times of high inflation or market instability. It shows strong resilience when interest rates rise and market volatility spikes.
3. **S&P 500 as a Consistent Growth Asset**: While more stable than Bitcoin, the S&P 500 continues to offer consistent returns, making it an attractive option for risk-averse investors.
3. **Impact of Interest Rates and Volatility**: Bitcoin is highly sensitive to changes in interest rates and spikes in market volatility (VIX), while Gold tends to act as a hedge, and the S&P 500 reacts moderately to both.

## Further Questions

- Will future regulation slow down Bitcoin's growth potential?
- How will the role of Gold evolve as cryptocurrencies become more mainstream in the coming decades?

## Data Sources and Links

- **Kaggle**: [Bitcoin Historical Data](https://www.kaggle.com/datasets/priyamchoksi/bitcoin-historical-prices-and-activity-2010-2024), [Gold Historical Data](https://www.kaggle.com/datasets/adinishad/gold-data), [S&P500 Historical Data](https://www.kaggle.com/datasets/joebeachcapital/dow-jones-and-s-and-p500-indices-daily-update)
- **Yahoo Finance API**: [Yahoo Finance](https://finance.yahoo.com/)
- **FRED, Federal Reserve Economic Data**: [FRED, Federal Reserve Economic Data](https://fred.stlouisfed.org/)
- **Kanban/Trello Board**: [Trello](https://trello.com/invite/b/66decedff8bb5a8443a07fc3/ATTIb1957222f84eca47832af64264746b4fAC12FA55/goldvsbitcoin)
- **Presentation**: [Gamma](https://gamma.app/docs/Invirtiendo-en-el-Futuro-Bitcoin-Oro-y-SP-500-en-el-Contexto-Econ-5532lg92eba4itm)

---

This README outlines the key steps taken during the project, providing insight into our analysis and decision-making process, as well as possible future directions for improvement.
