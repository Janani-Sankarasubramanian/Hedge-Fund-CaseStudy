# Hedge-Fund-CaseStudy

What if we were to fundamentally transform the way hedge funds operate? If we could find a way for hedge funds to invest in equities that are less risky, but still provide a higher return, we are helping investors eliminate a part or all of their risk. This project's main aim is to address this problem by performing a risk analysis on several equities using various factors used to measure the financial health of an equity.

### Data collection
Used Quantopian.com and its libraries to import stock market data.

### Features

I considered factors such as P/E ratio P/E growth ratio, EPS for several past quarters, market capitalization, Sharpe ratio and market sentiment through Twitter. All the ratios are calculated for an adjusted closing price of an equity. I used a Morningstar fundamental data field called normalized_basic_eps since it is a more accurate representation of a company's recent quaterly earnings.  The normalized EPS excludes one-time and unusual expenses and acts as a measure for a company's true earnings.  By relying on the accuracy of the factors used to measure a company's fundamentals, we perform due diligence for the investor, reducing a part of the risk.
