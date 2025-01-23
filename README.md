
# NZ mutual fund study

An in-depth analysis of NZ mutual funds portfolio. The code for following variables and setups can be found: 
a) Cleaning, organising and merging fund level datasets, i.e. portfolio holdings information (stock name, holdings date, weight of holdings, number of shares, name of shares, ticker of holdings), fundid, time series of monthly fund returns, monthly netassets, star ratings, expense ratio or total cost ratio, acive shares, fund types, inception date and liquidation info, index related to fund and monthly index returns, fund parent company, fund type - open end, pension funds or kiwisaver funds, equity style box, fund benchmark, investor returns. 

b) Collecing, organising, cleaning and merging holdings level data - stock, bond, index or ETF ticker, name, listed country, exchange listed, business sector and name, country of headquarters, RIC code (refinitiv ticker) and SEC id (morninstar ticker), time series of holdings monthly price(OHLCV), monthly returns, market capitalisation ESG score and ESG controversy score - Refintiv, environment, social and governance pillars score - Refinitiv.

c) Market related variables - SMB, HML, MOM, RF, Market RF, EPU index, NZX50 returns.

d) Variables calculated in the code - all variables are calculated per month per year:

 1) value weighted ESG returns, 2) value weighted non ESG returns, 3) value weighted fundreturns (in the sample), 4) total capital deployed in ESG holdings by funds per month per year, 5) total weight of ESG holdings in the fund per month per year, 6) ESG tilt, 7) ESG flows 8) Fund flow 9) rolling volatility 10) Tracking error 11) absolute returns {12) Timing skills of the funds 13) Picking skills of the fund} - ESG holdings and overall. 14) Total equity holdings of the fund 15) Total ESG rated equity holdings of the fund 16) Total component holdings of the fund 17) Ratio of total ESG rated holdings to total equity holdings 18) Ratio of ESG holdings to total component holdings 19) NZ listed stocks 20) non NZ listed stocks 21) total holdings - {numbers, capital deployed, weight and fund flow} which have ESG score greater than 75 {22) fund trading value 23) fund trading return} - ESG stocks 24) ch4 alpha 25) capm alpha 26) idiosyncratic volatility 27) VAR {28) ch4 alpha 29) capm alpha} - predicted values (t+ 1, 3, 6, 9, 12) 30) extreme funds - returns wrt index 31) rankings of funds in the sample depending on different variables 32) calculations of {ESG - Non ESG} for different variables to do comparative studies 33) fund trading return 34) fund trading value {35) fund trading value and trading returns} - for ESG holdings with ESG scores greater than 75 scores and less than 25 scores 36) high minus low varaibles 37) quintile 1 and 5 funds for comparative studies 
## Acknowledgements

I would like to thank followings for the funding and project supervision:

 - [Department of Economics and Finance, AUT Business School](https://www.aut.ac.nz/research/academic-departments/economics-and-finance)
 - [Project supervisor, Dr. Prasad Hegde](https://academics.aut.ac.nz/prasad.hegde)


## Appendix

Data:

- Morningstar Research
- Refinitiv
- Yahoo finance

Research paper references: Coming soon


# Master code files for all the programs is attached in sas file.





## 🛠 Skills
SAS, Stata, SQL, Statistics, Data visualisation, Web Scraping, Data extraction, Data modelling, Database.


## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.

