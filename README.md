# Do Games Actually Move the Market?
### A data analysis project by Lavanya Kamble

---

I've always been curious about the point where culture and markets intersect - where something as subjective as a review score becomes a number that might, just maybe, move a stock price.

This is an exploratory data analysis project investigating whether critic reception and sales performance of major video game releases correlate with short-term stock price movement in their parent publishers. The publishers under the microscope are **EA**, **Takes Two**, and **Ubisoft** - three of the largest Western publishers with consistent release histories across the period of interest.

It started as a question I couldn't find a clean answer to, so I built one!

## The Questions

1. Do games with strong Metacritic scores produce positive abnormal returns in the launch window?
2. Does sales performance add explanatory power beyond review scores alone?
3. And the interesting one - does the market already know? Are heavily anticipated franchises 
   already priced in before launch day?

## Stack

- Python: pandas, numpy, matplotlib, seaborn, scipy
- RAWG Video Games Database API: game titles, release dates, Metacritic scores
- yfinance (yahoo finance): daily adjusted stock prices
- Jupyter Notebook

## Structure
```
games_x_stock.ipynb   # main analysis notebook
figures/              # saved plots
data/                 # generated CSVs (gitignored)
requirements.txt      # dependencies
```

## Status

Work in progress. Analysis covers 2013–2025.

> Lavanya Kamble | *BSc Computer Science, Royal Holloway University of London*
