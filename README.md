# Financial-Markets-Yale-University-Coursea-Note
My own note about Financial Market module at Yale University. The professor is Robert J.Shiller who won the ***Nobel Memorial Prize in Economics*** in 2013.

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

<img width=75% height=75% src = https://user-images.githubusercontent.com/128298224/226597202-37155cc3-35a9-481a-8852-57d4421c6eeb.jpg>

This is the normal distribution with standard deviation of 1 and 3, but this is not common in finance.

<img width=50% height=50% src = https://user-images.githubusercontent.com/128298224/226597995-20c9ee30-11cb-426c-8c43-6cabdfacc9b5.jpg>

This is the comparison between Cauchy distribution and Normal distribution.

### Central Limit Theorem

* Averages of a large number of independent identically distributed shocks are approximately normally distributed.
* Can fail if the underlying shocks are fat tailed or if the underlying shocks lose their independence.

<img width=50% height=50% src = https://user-images.githubusercontent.com/128298224/226598562-5799fa6c-97c7-43c2-82a6-4ed4f9bf8412.png>

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

### Forecasting

#### Real Estate Risk Managment Device

* Value of homes is a major source of risk.
* Short stock market to protect you.

#### The Efficient Markets Hypothesis

* Random Walk Hypothesis: every step is random according to Karl Pearson.

#### Random Walk & AR-I Models

* Random Walk: $$x_{t} = x_{t-1}+\varepsilon_{t}.$$
* First-order autoregressive (AR-I) Model: $$x_{t} = 100 + \rho(x_{t-1} - 100) + \varepsilon_{t}.$$ where $-1<\rho<1.$
* Random walk as approximate implication of unpredictability of returns.
* Similarity of both random walk and AR-I to actual stock prices.

<img width="367" alt="comparison" src="https://user-images.githubusercontent.com/128298224/228534306-0c3a4ada-cfa7-417a-aade-8013fd53e221.png">

* Here is the comparison between two models and we see that AR-I model has a tendency to come back to the starting point, while random walk not.

### Intuition of Efficiency

* Whatever stock market does is right. Trust the prices you see.
* Weak form market efficiency: prices incorporate information about past prices.
* Semi-strong form: incorporate all publicly available information.
* Strong form: all information, including inside information.

### Price as PDV

#### Price as PDV of Expected Dividends

* If earnings equal dividends and if dividends grow at long-run rate $g$, then by growing consol model $$P = \frac{E}{r-g},\quad \frac{P}{E} = \frac{I}{r-g}.$$ This is called the Gordon Model.
* Efficient markets theory purports to explain why $P/E$ (**price earning ratios**) varies across stocks.
* Low $P/E$ does not mean that the stock is a 'bargain', it only means that earnings are rationally forecasted to decrease in the future.
* Efficient markets denies that any rule works.

#### Reasons to Think Markets Ought to Be Efficient

* Marginal investor determines prices.
* Smart money dominates trading.
* Survival of fittest.

#### Doubting Efficiency

* The experience of living through a crash makes it obvious that human emotions play an important role. 
* Their confidence diminshes as he talks to people or hears from the news.
* Stock market prices go down in advance of recession (two reasons): Market causes the recession; Market is a fortune-teller.

### Introduction to Behavioral Finance

#### History of Behavioral Finance

* Adam Smith: people have desire for praise.
* But don't enjoy being praised for something they didn't do.
* As people mature, if they mature successfully, the desire for praise morphs into a desire for praiseworthiness.

### Prospect Theory

#### Prospect Theory

* Two elements, value function(replace utility function) and weighting function(replace probability).
* Elements replace utility function and probabilities in expected utility theory which has dominated economic thought.
* People tend to gamble over the loss or they worry too much about small details instead of the big idea. (Because you are not an engineer who tries to consider every aspect of the invention you created)

#### Prospect Theory Value Function

![valuefunction](https://user-images.githubusercontent.com/128298224/228864014-b7bc9ec2-e3d1-4508-a740-c64d59da31b1.jpg)

#### Prospect Theory Weighting Function

<img src=https://user-images.githubusercontent.com/128298224/228866343-f8a93d64-fd4a-4325-baf0-6af018dcb9fe.jpg width=50% height=50%>

### Logical Fallacies

#### Wishful Thinking Bias

* People exaggerate probability that their team will win.
* People exaggerate probability that the candidate they favor will win.

#### Overconfidence in friends and leaders

* Every central bank head is thought to be a genius, at least for a while.

#### Cognitive Dissonance

* Mental conflict that occurs when one learns one's beliefs are wrong, avoidance behavior.
* Ads for recently purchased cars (Once you bought the car, you tend to read more about the ads of your purchased cars instead of other cars because you are tryting to make you feel better.)
* If the stock price of your purchased stock goes down, you might feel you were wrong at first, but then just ignored it as you never bought.
* Displosition effect

#### Will Goetzmann and Nadav Peles Cognitive Dissonance and Mutual Fund Investors

* Found that even badly performing mutual funds retain some investors.

### Brain

#### Mental Compartments

* Shefrin & Statman: Investors have a 'safe' part of their portfolio that they will not risk, and a 'risky' part of their portfolio that they can have fun with.
* Option salespeople use these tactics: buy a put option on a single stock.

#### Attention Anomalies

* Attention is fundamental aspect of human intelligence and its limits.
* Social basis for attention.
* Inability to account for one's attention.
* "No arbitrage assumption" of financial theory: No ten-dollar bills lying around. Does not require everyone is paying attention.

#### Anchoring

* Examples: stock prices anchored to past values, or to other stock prices in same country. Do splits to keep at $30?

#### Representativeness Heuristic

* People judge by similarity to familiar types, without regard to base rate probabilities.
* Tendency to see patterns in what is really random walk.
* Stock price manipulators try to create patterns to fool investors. Short a stock and create a head & shoulders.

#### Disjunction Effect

* Inability to make a decision that is contingent on future information.
* reaction of stock market to news, make stock strategies to trade on news.

### Magical Thinking

#### Magical thinking

* Stock market responses to events may have similar origins.

#### Quasi Magical Thinking 

* Ellen Langer: People bet more on coin not yet tossed.

### Pseronality Disorders

#### Culture and Social Contagion

* Suicide rates differ across countries for no more reason than different cultural themes.

#### Antisocial Personality Disorder

* Identity: egocentric, self-esteem from personal gain.
* Self-direction: absence of prosocial internal standards.
* Lack of empathy, incapacityfor intimacy.
* Manipulative, deceitful, callous, hostile.
* Irresponsible, impulsive, risk-taking

## Module 3

### Fedral Funds and Interest Rates

* The following is the Fedral Funds Rate: Shortest-Term Interest Rate in U.S.
<img width=50% height=50% src =https://user-images.githubusercontent.com/128298224/229288172-d241b0cd-413e-4cbf-92e5-b01430ae31b4.jpg>

* The following is the EONIA (European Over Night Index Average is European Counterpart to Fed Funds) 

<img width = 50% height = 50% src = https://user-images.githubusercontent.com/128298224/229288445-763e908d-bb3a-4cce-bd3b-1017fcef574f.jpg>

#### Why negative interest rate?

* Too much cash need insurance because they are feared to be stolen, also trucks and other costs like big valut.
* Therefore they want consumers to spend more moeny

#### Causes of Interest Rates

* Usually 3% - 5%.

### Compound Interest

#### Compound Interest

* If annual rate is $r$, compounding once per year, balance = $(1+r)^{t}$ after $t$ years.
* If compounded twice per year, balance is $(1+\frac{r}{2})^{2t}$ after $t$ years.
* If compounded $n$ times per year, balance is $(1+\frac{r}{n})^{nt}$ after $t$ years.
* Continuous compounding, balance is $e^{rt}$. (Taking the limit of the above formula.)

### Discount Bonds

#### Discount Bonds

* No coupon payments, just principal at maturity date (conventionally, $ \$100$).
* Initially sold at a discount (less than $ \$100$) and price rises through time, creating income
* Term $T$, Yield to Maturity (YTM) $r$, $$P = \frac{1}{(1+r)^{T}},\quad P =\frac{1}{(1+\frac{r}{2})^{2T}}.$$

#### Present Discounted Value (PDV)

* PDV of a dollar in one year = $\frac{I}{I+r}.$
* PDV of a dollar in $n$ year = $\frac{I}{(I+r)^{n}}.$
* PDV of a stream of payments $x_{1},...,x_{n}.$

#### Conventional Bonds Carry Coupons

* Conventional BOnd Issued at par (100), coupons every six months.
* Term is time to maturity $$P_{t} = c(\frac{1}{r}-\frac{1}{(1+r)^{T}}\frac{1}{r})+\frac{100}{(1+r)^{T}},$$ and $$P_{t} = \frac{c}{2}(\frac{1}{r/2}-\frac{1}{(1+r/2)^{2T}}\frac{1}{r/2})+\frac{100}{(1+r/2)^{2T}}.$$

### Consol and Annuity

#### Consol and Annuity Formulas

* Consol pays constant quantity $x$ forever
* Growing consol pays $x(1+g)^{t-1}$ in $t$.
* Annuity pays $x$ from time $1$ to $T$: $$\text{Consol PDV} = \frac{x}{r},\quad\text{Growing Consol PDV} = \frac{x}{r-g},\quad\text{Annuity PDV} = x\frac{1-\frac{1}{(1+r)^{T}}}{r}.$$

#### Growing Consol Formula

* The Growing Consol formula is from Jacob Bernoulli

### Forward Rates and Expectation Theory

#### Forward Rates

* Forward rates are interest rates that can be taken in advance using term structure. $$(1+r_{2})^{2} = (1+r_{1})(1+f_{2}), \quad (1+r_{k})^{k} = (1+r_{k-1})^{k-1}(1+f_{k}).$$

### Inflation

#### Inflation and Interest Rates

* Nominal rate quoted in dollars, real rate quoted market baskets (price index).
* Nominal rate usually greater than real rate $$(1+r_{money}) = (1+r_{real})(1+i),\quad r_{money}\approx r_{real}+i.$$

### Leverage

#### Leverage and its Discontents

* The start of the 2008 world financial crisis had to do with home buyers in U.S. and elsewhere borrowing to buy homes.
* China today is a highly leveraged economy, arousing concerns.
* Debt leads to bankruptcies, possible world crises.

#### The Debt-Deflation Theory of Great Depressions -- Irving Fisher

* Deflation redistributes real wealth from debtors to creditors.
* Creditors tend to be more cautious.

### Market Capitalization by Country

#### Market Capitalization
* United States has the largest stock market.

### The Corporation

#### Board of Directors

* In U.S., Board is commonly chaired by CEO, but CEO is hired by the Board.
* In Germany, firms have two boards of directors. There is the Aufsichtsrat (Supervisory Board) and the Vorstand (Management Board).

#### For-Profit vs. Non-Profit

* For-profit corporation is owned by shareholders, equal claim after debts paid, subject to corporate profits tax.
* Non-profit is not owned, self-perpetuating directors. Not subject to corporate profits tax.
* For-profit exists to benefit shareholders, non-profit does not.
* So for-profit has a price per share, non-profit does not.

### Shars and Dividends

#### Meaning of Shares and Market Cap

* My ownership of company equals my shares divided by total shares.
* Splits are essentially meaningless.
* If the company pays a dividend, the value of the share should go down by the amount of the dividend per share.
* If the company does something to increase the value of the company without increasing the number of shares, my shares gain value.
* It is all in the ratio, total value of company divided by total number of shares. If you affect numerator and denominator equally, then there is no effect on price per share.
