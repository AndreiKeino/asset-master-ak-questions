#  asset-master.net is a website for the portfolio optimization.

## to ask a question or to report a bug or to leave a feedback on website 
# https://asset-master.net/ 
## either:

## - choose 'Issues' tab, then click on the 'New issue button'
## or
## - go to https://github.com/AndreiKeino/asset-master-ak-questions/issues 
##   then click on the 'New issue button'

The following features supported at the moment:

Stock data timeframe (period): Daily. Why is this essential?

Ability to choose the time horizon for optimization / statistics calculation

View the expected return / volatility for all stocks included in the list for optimization.

Save/Load the portfolio settings to/from a file.

Export optimization report to XLSX.

Expected returns calculation:

- Mean historical return.
- Exponentially weighted mean historical return.
- CAPM estimate of returns.
Covariance matrix calculation:

- Fix non-positive semidefinite matrices.
- Sample covariance.
- Semicovariance.
- Exponentially weighted covariance.
- Shrunk covariance matrices:
- manual shrinkage
- Ledoit Wolf shrinkage
- Oracle Approximating shrinkage
- Black-Litterman allocation.

The optimization methods:

Mean-Variance optimization.

- minimum of volatility
- maximum of Sharpe ratio
- maximum of the quadratic utility, given some risk aversion
- maximum of return for a given target risk
- minimum of risk for a given target return

Semivariance optimization.

- minimum of semivariance
- maximum of the quadratic utility, given some risk aversion
- maximum of return for a given target risk

CVaR and CDaR optimization.

- minimum of CVaR or CDaR
- maximum of return for a given CVaR or CDaR
- minimum of CVaR or CDaR for a given target return

- All of these methods support L2 regularization also.

