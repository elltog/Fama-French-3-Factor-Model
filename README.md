# Fama-French-3-Factor-Model

This project looks at how a U.S. mutual fund actually performed, using the Fama French Three Factor Model and comparing it with CAPM. I pulled daily price data from Yahoo Finance, converted them into monthly returns, and ran regressions to see how much of the fund's performance can be explained by market movements, company size, and value factors.

Fund price data: Yahoo Finance

Fama-French factors: Kenneth R. French Data Library (https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html)



Note: One result worth being upfront about, alpha came out positive in both models, but it wasn't statistically significant in either. CAPM gave α = 0.0045 (p = 0.456), and the three factor model brought it down to α = 0.0022 (p = 0.675). In plain terms, the fund didn't generate returns that couldn't be explained by its factor exposures alone. That's not a failur  of the analysis. It's actually the more interesting finding. ARKK's outperformance over this period seems to be largely explained by its high market beta 1.59 and a strong negative HML loading, in other words, it was aggressive and growth tilted, and that paid off in a bull market. Not alpha. Factor exposure.
