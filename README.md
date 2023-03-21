# Financial-Markets-Yale-University-Coursea-Note
My own note about Financial Market module at Yale University

## Module 1 

### Introduction
Financial institutions are a pillar of civilized society, directing resources across space and time to their best uses, supporting and incentivizing people in their productive venture, and managing the economic risks they take on.

### Good and Evil

Finance is a Technology, for Good or Evil.

* All technologies can be used or misued.
* Developing world is more interested in finance technology than in our paltry foreign aid or empty sympathies
* The most successful people in finance end their lives as philanthropists.

### VaR

* VAR in finance means two things, variances and "value at risk", but when the A isn't capitalized, it means at risk.
* Value at risk is usually quoted in units of $ for a given probability and time horizon.
* 1% one-year VaR of $10 million means 1% chance that a portfolio will lose $10 million in a year

### Stress Tests

Originally the term referred to a medical procedure to test for cardiovascular fitness.

OFHEO(Office of Federal Housing Enterprise Oversight) started testing firms' ability to withstand economic crisis before the 2008 crisis.

### S&P 500

* Hang in the investment.

* **Standard deviation** of Apple capital gain in decade shown is 12.8% a month, while **standard deviation** of S&P 500 return in decade shown is 4.7%.
* Apple is more variable than S&P 500. Apple overeact to what happens in the aggregate stock market.

### Beta
* The CAPM (Capital asset pricing model) implies that the expected return on the ith asset is determined from its beta.
* Beta($\beta$) is the regression slope coefficient when the return on the ith asset is regressed on the return on the market.

### Market Risk versus Idiosyncratic Risk
* By construction, the residuals or error terms in a regression are uncorrelated with the fitted or predicted value.
* The variance of the return of a stock is equal to its beta squared times the variance of the market return (systematic risk) plus the variance of the residual in the regression (idosyncratic risk).

### Distribution and outliers

![WeChat Image_20230321114731](https://user-images.githubusercontent.com/128298224/226597202-37155cc3-35a9-481a-8852-57d4421c6eeb.jpg)

This is the normal distribution with standard deviation of 1 and 3, but this is not common in finance.

![WeChat Image_20230321115112](https://user-images.githubusercontent.com/128298224/226597995-20c9ee30-11cb-426c-8c43-6cabdfacc9b5.jpg)

This is the comparison between Cauchy distribution and Normal distribution.

### Central Limit Theorem

* Averages of a large number of independent identically distributed shocks are approximately normally distributed.
* Can fail if the underlying shocks are fat tailed or if the underlying shocks lose their independence.

![Comparison-of-standard-normal-distribution-and-standard-Cauchy-distribution](https://user-images.githubusercontent.com/128298224/226598562-5799fa6c-97c7-43c2-82a6-4ed4f9bf8412.png)

Cauchy distribution is actually a fat tail distribution, and it looks quite similar to Normal distribution.

### Covariance

* Risk is determined by **covariance**. 
* We need stocks that are independent, so lower the covariance.
* $\beta_{i} = \frac{\text{Cov}(r,r_{\text{market}})}{\text{Var}(v_{\text{market}})}$.
* Market demands higher returns from higher beta stock.
