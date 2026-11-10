# VEQT vs ATD
A small Python project comparing one individual stock, in this case Alimentation Couche Tarde (ATD.TO), against VEQT which is an all-equity ETF that holds thousands of companies worldwide. 

I'm learning Python for finance from scratch. I wanted to check whether picking individual stocks actually beats simply holding the index, doing this through looking at both risk and return. 

## Key findings 
Over one year (from October 2025 to October 2026), ATD and VEQT ended up almost tied: ATD returned about 15.69% and VEQT around 15.51%. But ATD's daily price swings were about 2.1 times larger than VEQT's. 

**Verdict:** ATD delivered the same reward for roughly twice the risk, so on a risk-adjusted basis, simply holding VEQT was the better choice this year. 

## Files
- **veqt_vs_atd.ipynb**: the main project. Start here. It fetches the data, checks that both investments cover the same dates, calculates returns and volatility, plots the comparison and gives the verdict.
- **learning.ipynb**: my practice notebook from learning the basics, kept as a record of how I got to the final product. 

## How to run it
You'll need Python and these libraries:

```
pip install yfinance pandas matplotlib
```

Then open **veqt_vs_atd.ipynb** and use **Run All**. The data is fetched
live from Yahoo Finance, so the numbers will change depending on when
you run it.