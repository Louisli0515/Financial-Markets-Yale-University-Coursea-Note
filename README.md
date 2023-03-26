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

* Originally the term referred to a medical procedure to test for cardiovascular fitness.
* OFHEO(Office of Federal Housing Enterprise Oversight) started testing firms' ability to withstand economic crisis before the 2008 crisis.

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

### Insurance

#### Fundamental Insurance Principles and Issues
* **Risk Pooling** is the source of all value in insurance.
* **Moral Hazard** dealt with partially by deductions and co-insurance.
* **Selection Bias** dealth with by group policies, by testing and referrals and by mandatory government insurance.

#### Risk Pooling
* If n policies, each has independent probability p of a claim, then the number of claims follows the binomial distribution. The standard deviation of the fraction of policies that result in a claim is $$\sqrt{\frac{p(1-p)}{n}}.$$
* Law of large numbers: as $n$ gets large,  standard deviation approaches 0.

#### Connecticut Life and Health Insurance Guaranty Association
* Founded 1972 by Connecticut legislature.
* Maximum death benefit $500,000 and maximum cahs value insurance $500,000.
* You can't increase coverage by buying multiple policies.
* It's not big enough, if you were buying life insurance for your family, $1 million minimum.

#### China Insurance Protection Fund
* Policyholder's losses that are no more than 50,000 yuan (US$7500) will be fully covered by the fund
* For losses in excess of that number, the fund covers 90% of the extra for individual policyholders and 80% for corporate policyholders.

#### The Health Maintenance Organisation Act of 1973
* Required employers with 25 or more employees to offer federally certified HMO options.
* Designed to overcome moral hazard problem, doctors earning fees for procedures make more money if people are sick.

#### U.S. Emergency Medical Treatment and Active Labor Act (EMTALA) 1986
* Requries hospitals and ambulance services to provide care to anyone needing emergency treatment
* An "unfunded mandate".

#### U.S. Patient Protection and Affordable Care Act 2010 (Obamacare)
* Penalty for individuals not buying insurance.
* Penalty for companies not buying insurance for their employees.
* Insurance companies may not disallow for preexisting conditions, or drop people who get sick.

#### TRIA, 2002
* Before 11/09/2001, insurers generally did not exclude terrorism risk, which they then saw as inconsequential.
* After 2001, insurers wanted these exclusions.
* US Terrorism Risk Insurance Act of 2002 (TRIA) required to insurers to offer terrorism insurance for three years.
* Government agreed to pay 90% of insurance industry losses above a deductible of $100 billion.
* December 2005, TRIA renewed for two more years, and in 2007 for 7 more years. In 2015, the act was renewed again to 2020.

### Eggs in One Basket

#### An Alternative to Insurance: Portfolio Management
* Diversification of ownership
* If people are all calculating with the same data, all wanting to hold portolios on the frontier, then they all want to hold the same portfolio.
* So that **HAS TO BE THE MARKET PORTFOLIO**.

#### Portfolio Diversification
* All that should matter to an investor is the performance of the entire portfolio.
* **Mean** and **Variance** of portfolio matter.
* **Law of large numbers** means that spreading over many independent assets reduces risk, has no effect on expected return.

### CAPM

#### Capital Asset Pricing Model (CAPM)
* CAPM asserts that all investors hold their optimal portfolio.
* Consequence of the mutual fund theorem: All investors hold the same portfolio of risky assets, the tangency portfolio.
* Therefore the CAPM says that the tangency portfolio equals the market portfolio.

#### Investment Companies as Providers of Diversification
* Investment trusts (before 1940s)
* Mutual funds
* Closed end investment companies
* Unit investment trusts

#### Equity Premium Puzzle
* US Geometric average real stock market return 1802-2012 : 6.6%.
* US Geometric average real short-term government return 1802-2012: 2.7%.
* Equity premium = 6.6% - 2.7% = 3.9%.

#### International Evidence
* Medial real stock market appreciation rate for 39 countries 1926-1996: 0.8% per year.
* Real stock market appreciation rate for US 1926-1996: 4.3% per year.
* US equity premium may reflect a selection bias.

### Beta
* Apple has beta at about $1.5 > 1$, showing its strength in the market.
* Gold ahs a negative $\beta$. So when market is doing good, gold might not have a good return, but when market is during a recession, gold might have a good return.

### CAPM and Diversification

* $r_{i} = r_{f}+\beta_{i}(r_{\text{market}} - r_{f})$

### Short sales
* Brokers can enable you to hold a negative quantity of a tradable asset: they borrow the security and sell it, escrow the proceeds, you receive the proceeds, owe the security.

### Calculating the Optimal Portfolio

#### A Portfolio of a Risky and Riskless Asset
* Invest $x$ dollars into the risky asset and $1-x$ dollars into the riskless asset.
* The Risky asset returns $r_{1}$ while Riskless asset returns $r_{f}$.
<img width="823" alt="port" src="https://user-images.githubusercontent.com/128298224/227740406-2d761495-ae10-4a33-a4c0-37f716a8b726.png">

* Expected value of the portfolio is $$r = xr_{1}+(1-x)r_{f}.$$
* Portfolio Variance is $$x^{2}\text{Var}(\text{return1}).$$
* Portfolio Standard Deviation is $$\sigma = \left|\frac{r-r_{f}}{r_{1}-r_{f}}\right|\sigma(\text{return1}).$$

#### A Portfolio of 2 Risky Assets
* Portfolio Expected Value is $$r = x_{1}r_{1}+(1-x_{1})r_{2}.$$
* Portfolio Variance is $$x_{1}^{2}\text{Var}(\text{return1})+(1-x_{1})^{2}\text{Var}(\text{return2})+2x_{1}(1-x_{1})\text{Cov}(\text{return1},\text{return2}).$$

### Efficient Portfolio Frontier
<img width=75% height=75% alt="frontier" src="https://user-images.githubusercontent.com/128298224/227741098-67be4c4b-3914-4908-aa50-a87ee2097cd6.png" >

<img width=75% height=75% alt="oil" src="https://user-images.githubusercontent.com/128298224/227741344-89684553-8469-425f-8b83-9cd5fb622a67.png" >

### Gordon Growth Model

* Myron Gordon says $$PV = \frac{x}{r-g} = \frac{x}{1+r}+\frac{x(1+g)}{(1+r)^{2}}+....,$$ where $r$ is the rate of discount, $g$ is the growth rate and $x$ is the revenue production in the first year.
* For example in 2000, the best thing to invest was railroads not dot-com stocks because they failed to use the formula.

## Module 2

### Invention takes time

* Financial Innovation is a pillar of our civilisation.

### Limited Liability

* Divide up an enterprise into shares, and no shareholder is liable for more than he or she put in.

### Moss' Theory about Limited Liability

* David Moss points out that limited liability was not a good idea: it created agency problems for stockholders, who might pursue risky strategies at bondholders' expense.
* Lottery effect: with limited liability, an investment in a corporation was a throwaway item, like a lottery ticket.
* Investor overestimation of miniscule probability of loss beyond initial investment discouraged investment.
* Allowed for investors to hold a highly diversified portfolio.

### Inflation Indexed Debt

* Indexed debt first attempted in Massachusetts, 1780, to help finance Revolutionary War.

### Real Estate Risk Managment Device

* Value of homes is a major source of risk.
* Short stock market to protect you.
