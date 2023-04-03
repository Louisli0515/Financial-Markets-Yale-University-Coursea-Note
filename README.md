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

### Shares and Dividends

#### Meaning of Shares and Market Cap

* My ownership of company equals my shares divided by total shares.
* Splits are essentially meaningless.
* If the company pays a dividend, the value of the share should go down by the amount of the dividend per share.
* If the company does something to increase the value of the company without increasing the number of shares, my shares gain value.
* It is all in the ratio, total value of company divided by total number of shares. If you affect numerator and denominator equally, then there is no effect on price per share.

### Common vs. Preferred Stock

* Common stock: dividend is at discretion of firm, subject to legal restrictions.
* Preferred stock: Specified dividend does not have to be paid, but firm cannot pay dividend on common stock unless all past preferred stock dividends are paid.
* Corporate bonds: Firm is contractually obligated to pay coupons and there is a maturity date when principal must be paid.
* US bought preferred shares in corporations to bail them out.

### Corporate Charter

#### The Basic Corporate Charter Says All Common Shareholders Treated Equally

* Charter does not say that the firm ever has to raise debt. Board decides.
* Charter does not say that the firm ever has to pay dividends. Board decides
* Charter does not say that the firm ever has to repurchase shares. Board decides.
* Charter does not say that the firm ever has to issue warrants, convertible debt, anything else
* But the shareholders elect the board.

#### Berle and Means

* Separation of ownership and control.
* "Ownership is so widely scattered that working control can be maintained with but a minority interest."
* The "quasi-public corporation" is constrained by law to serve other interests.

#### Classes of Shares

* Berkshire Hathaway. A Class have voting rights, B do not.
* New York Times, Class A has less voting rights than Class B, which allows descendants of Adolph Ochs still to control.
* Facebook: Mark Zuckerberg owns 28% of its shares but 57% of its voting shares.

### Corporations Raise Money

#### How do Corporations Raise Money?

* This dilutes existing shareholders, since they now own a smaller fraction of the company, but offsetting that, it creates new earning power for the company.
* Shareholders at a meeting could ideally vote on whether they think the prospective profits are worth the dilution, and prospective purchasers of the issue could ponder whether they feel the diluted shares are worth purchasing.

#### Why do they call it Equity

* Equity means equal share.

### Dilution

#### Dilution

* If the company gives away new shares, my shares become worth less; that is dilution.
* If the company sells new shares at market price, that generally does not lower the value of my shares because the company has the money.
* If the company issues a stock dividend at $5\%$, then that lowers the value of my orginal shares by factor $\frac{1}{1.05}$, but I am not worse off since I have an additional $\frac{0.05}{1.05}$ of value in the new shares.

### Share Repurchase

#### Share Repurchase

* The opposite comes when a firm buys its own shares on the market.
* The value of the firm should go down by the amount they spent.
* I as a shareholder, however, now own a larger share of the company.
* If the firm repurchases shares instead of paying dividends, then my shares do not lose value, the company loses value but I have a bigger share in it.

#### Reasons for Share Repurchase

* Tax break for investors (obsolete in sense that tax rate on cap gains = that on dividends, but cap gains tax can be postponed).
* Firms' unwillingness to cut dividends, uncertainty that current earnings will continue.
* Price pop after a repurchase. Buybacks taken as a signal. But price pops are fading.
* Now investors sometimes view repurchase as a sign that firm is 'old economy'. NASDAQ firms less likely to repurchase shares, as if they think value is too high.

### PDV of Expected Dividends

#### Price as PDV of Expected Dividends

* If earnings equal dividends and if dividends grow at long-run rate $g$, then by growing consol model $P = \frac{E}{r-g},\quad P/E = \frac{I}{r-g}.$
* So efficient markets theory purports to explain why P/E varies across stocks in terms of $r$ and $g$.
* Efficient markets denies that any rule works other than simple diversification.
* Value investing says invest in low P/E.

### Why Do Firms Pay Dividends?

#### Why do firms pay dividends?

* Even when there was a stronger tax advantage to capital gains, firms paid dividend.
* Framing matters. Dividends framed as income.

#### Dividend Signalling

* By raising dividends, firm shows it can court bankruptcy.
* Problem: alternative signalling methods are cheapter taxwise.

#### Lintner Model of Dividends

* $DIV_{t} - DIV_{t-1} = p(\tau\times EPS_{t} - DIV_{t-1}).$
* $\rho=$ adjustment rate, $0 < \rho < 1$.
* $\tau=$ taget ratio, $0 < \tau < 1$, $$DIV_{t} = \rho\tau\sum_{k=0}^{\infty}(1-\rho)^{k} EPS_{t-k}.$$

#### General Public Utilities Corp

* Proposed to substitute stock dividends for cash dividends, and offered to sell the stock dividend for any stockholder for minmal transaction cost.
* Direct saving to shareholder: $4 million a year.
* Intense negative shareholder reaction.

## Module 4

### History of Mortgage Lending

* Verb mortgage means commit property as collateral for a loan. Could mortgage your soul to the devil.
* Chinese documnets usually prescribed fines, including fines on relatives for failing to pay in Tang dynasty.

### Commercial Real Estate Vehicles

#### Real Estate Partnerships as the Major Example of a DPP

* For accredited investors
* Real estate limited partnerships represent the most important example of a Direct Participation Program (DPP), a class of investments that also includes oil and gas exploration programs and equipment leasing programs.
* "Direct partcipation" DPPs are "flow-throw vehicles" and investors can deduct program losses on personal taxes.
* "Tax shelters" until the Tax Reform Act of 1986: losses used to offset "passive income". Now, genuine businesses.
* DPPs escape the corporate profits tax
* Internal Revenue Service (IRS) requirements, notably limiation of life.

#### Limited Partnership Structure

* General partner runs the business, does not have limited liability
* General partner must own at least 1%.
* Limited Partners are passive investors, with limited liability, rights to vote, can replace general partner.
* General partner or associate usually runs the offering to sell units to investors.

#### REITs

* Real Estate Investment Trusts (REITs) were created by US Congress in 1960 to allow small investors access to real estate investment.
* Before 1960, public companies that owned real estate would be considered businesses, for which their earnings would be subject to corporate profits tax. Until 1960, real estate was typically owned by partnerships, not suitable for small investors.

#### Restrictions on REITs

* 75% of assets must be in real estate or cash.
* 75% of income must be from real estate.
* 90% of their income must be from real estate, dividend, interest & capital gains.
* 95% of income must be paid out.
* No more than 30% of income from sale of properties held less than 4 years.

#### Real state is scarce

* It had something to do with the free market revolution that started in Britain with Margaret Thatcher and in the United States with Ronald Reagan, and then in China with Deng Xiao Ping.

### Mortages part 1

#### Fedral Housing Administration

* Established by Roosevelt in 1934
* Required 15-year loans
* Insures the lender against loss

### Mortages part 2

<img width = 50% height = 50% src =https://user-images.githubusercontent.com/128298224/229347627-140f5d1f-e673-423e-b2cb-2b17da280520.png>

#### Kinds of Mortgages

* Conventional, fixed rate mortgage.
* Adjustable rate mortage (ARM). An adjustable rate mortgage (ARM) is a type of mortgage loan where the interest rate fluctuates periodically based on a specific index, such as the London Interbank Offered Rate (LIBOR) or the prime rate. 
* Price level adjusted mortgage (PLAM) payment adjusted to inflation so constant in real terms. A Price Level Adjustable Rate Mortgage (PLARM) is a type of mortgage loan where the interest rate is adjusted based on changes in the price level index. The price level index is a measure of inflation that tracks changes in the overall price level of goods and services in an economy.
* Dual rate mortgages (DRAMs) same as PLAM but interest rate floats. A dual-rate mortgage is a type of home loan where the interest rate changes based on a pre-determined schedule. The interest rate typically starts at a fixed, lower rate for an initial period of time, such as five or seven years, and then adjusts to a higher rate for the remainder of the loan term.
* Shared appreciation mortgages (SAMs)
* First mortgages: on purchase of home.
* Home equity loans.

### PMI, CMOs, CDOs

#### Private Mortgage Insurance (PMI)
* Private Mortgage Insurance (PMI) is a type of insurance that protects lenders in the event that a borrower defaults on their mortgage loan. PMI is typically required by lenders when a borrower makes a down payment of less than 20% of the home's purchase price.
* Companies, such as MGIC, insure Fannie & Freddie against losses on their mortgages.
* Controversy: with recent real estate price increases, LTV(Loan to value ratio) has declined below 80% for many homeowners still paying for mortgage insurance. The PMIs don't notify them.

#### Collateralized Mortgage Obligations (CMOs)

* Collateralized Mortgage Obligations (CMOs) are a type of investment security that is created by pooling together individual mortgage loans and then dividing the pool into smaller pieces or tranches that are sold to investors.
* CMOs divide the cash flow of a mortgage pass-through security into a number of tranches in terms of prepayment risk.
* Sequential-pay CMOs (first created 1983): First tranche receives first principla payments, after it is paid off the second tranche receives principal payments.

#### Collateralized Debt Obligations (CDOs)

* Collateralized debt obligation, commonly known as CDO, is a type of structured financial product that pools together a diverse portfolio of debt securities and creates different tranches or slices of varying levels of risk and return. These securities are then sold to investors.
* Hold securities, typically mortgage securities as their assets.
* Typically hold subprime mortgages.
* CDOs divide the cash flow into a number of tranches in terms of default risk.
* CDO debt crisis 2007.
* Criticism of rating agencies for not downgrading them.

### Post Crisis Regulation

#### A Fix Begun in Europe

* 5% mortgage originator must hold 5% of mortgages, European parliament.
* Qualifying Residential Mortgages (QRMs) are exempt from requirement in USA.

#### Requirements for QRM

* Regular periodic payments that are substantially equal;
* No negative amortization, interest only or ballon features;
* A maximum loan term of 30 years;
* Total points and fees that do not exceed 3 percent of the total loan amount, or the applicable amounts specified for small loans up to $100,000;
* Payments underwritten using the maximum interest rate that may apply during the first five years after the date on which the first regular periodic payment is due;
* Consideration and verification of the consumer's income and assets, including exmployment status if relied upon, and current debt obligations, mortgage-relateed obligations, alimony and child support;
* Total DTI (Debt to Income ratio) ratio that does not exceed 43%.

### The Bubble Part 1

<img width = 50% height = 50% src = https://user-images.githubusercontent.com/128298224/229348992-f8941e2f-3987-45b8-abe0-82a8764856e2.png>

### The Bubble Part 2

#### Evidence of Feedback Mechanism

<img width = 50% height = 50% src =https://user-images.githubusercontent.com/128298224/229349254-6c5a4305-062b-4ce6-af8b-dc44d5e7140d.png>

* Real Estate is the Best Investment

### The Bubble Part 3

#### There will be a new bubble after 2007 crash

* There will be a new bubble after 2007 crash in the housing markets, especially in some emerging markets like China.
* The housing values in Guangzhou are more expensive than in Manhattan, but the average salary is not the half of the Manhattan's.
* Parents are helping out. The total value of land in China is high relative to their GDP, and the price to rent is high.
* It is difficult for Chinese to invest abroad, there are limits on how much they can put abroad. There's a fear of corruption in China, a fear of being taken advantage of, so they might tend to prefer investments in a house that they can see. Xi Jin Ping is trying to combat corruption, but there is still a public perception.
* Save money and buy a house for the son, so that he can impress young woman.
* All kind of Chinese facotrs that has been driving home prices up there.

### Regulation Overview

#### Business Wants Regulation

* Without regulation, people are forced to dothings in a competitive system that they think are bad for society.
* Forced to lowest common denominator.
* Analogy to having a referee at a sports referee.
* Players hate referees, but without them they know game would deteriorat into something ugly.

### Within Firm Regulation Part 1

#### The Board of Directors

* The Board of Directors act like a regulator.
* Outside directors represent a broader community.
* Society functions to quarantine people with personality disorders, and people derive reputations.
* Putting outsiders of known reputations on a board is a singal to outsiders of regulation.

#### Tunneling

* Tunneling = Expropriation by minority shareholders.

### Within Firm Regulation Part 2

#### How Tunneling is Achieved

* Asset sales
* Contracts, as for prices paid for inputs
* Excessive executive compensation
* Loan guarantees
* Expropriation of corporate opportunities
* Dilutive share issues
* Insider trading

### Local Regulation

#### Banking Regulation

* Belonged to states until the National Banking Act of 1863.

#### Blue Sky Laws

* Regulates the offering and sale of securities to protect the public from fraud, regulates brokers and advisors.

### National Regulation Part 1

#### Local Regulation Failed

* Securities and Exchange Commission (SEC) part of Roosevelt's New Deal, 1934.
* Initially viewed by business as a radical, almost socialist, institution. Peculiar that it started in US, imitated by other countries.

#### Public vs. Private Securities

* Motive was repeated examples of exploitation of minority or unobservant shareholders.
* Public securities: undergo approved process of issuance under SEC surveillance.

#### Hedge Funds

* For wealthy investors only
* Those structured as 3c1s can take no more than 99 investors, and they must be "accredited investors" as defined by the SEC which means income of $200,000 or investable assets of $1,000,000 (SEC proposal in 2006 to raise to $2,500,000 did not happen)
* Those structured as 3c7s can take 500 investors, but they must be "qualified purchasers" as defined by the SEC, individuals with net worth of at least $5 million or institutions with net worth of at least $25 million.

#### Securities and Exchange Commission (SEC) Rules

* Every broker must register with SEC.
* Every stock exchange must register.
* Every security issue must register.
* Registration does not literally mean SEC approval.

### National Regulation Part 2

#### Insiders vs. Outsiders

* Insiders are people with special access to information about a company.
* Inside information represents wealth.
* SEC tries to define access to this wealth, by disclosure rules.
* Regulation FD 2000: requires that when a company tells any material fact to an analyst, it must immediately tell the public.
* Some argue that inside trading is good because insider traders compete each other and they might not earn a lot profit after all. 

#### Front Running and Decimalization

* Front-Running occurs when a broker buys shares in front of a large order that will boost stock price.
* Decimalization on NYSE and Amex begain January 29, 2001.
* Decimalization favors front-running.

#### Financial Accounting Standards Board

* FASB officially recongnised as authoritative by SEC in 1973. Though SEC has statutory right to make accounting standards, perfers private sector do it.

#### Earnings Definitions

* GAPP Define "Net Income" which is the bottom line, traditionally and "operating income", revenue minus cost of doing business
* Operating earnings, Core Earnings, Pro Earnings, EBITDA, and Adjusted Earnings are not GAAP.
* FASB is at work on developing new definitions, but this takes years.

### National Regulation Part 3

#### The 2008 Financial Crisis as Result of Regulatory Failure before Crisis

* Many home buyers were put into unsuitable mortgages, later to default.
* Leverage ratio of the financial sector was allowed to reach historically high levels.
* Banks and governments used off-balance-sheet accounting to conceal liabilities.

### International Regulation

#### Bank for International Settlements

* Created 1930 by Hague Agreements.
* Has 57 member central banks, who are in turn national regulators.

#### G20

* Group of Twenty Finance Ministers and Central Bank Governors (G-20, G20, Group of Twenty)
* Founded 2008

#### Financial Stability Board

* Created by G20, April 2009

#### Final Thoughts

* Regulation has to continually change through time as technology changes.
* World economy dominates more and more, and so regulation will shift to international.

## Module 5

### Forwards and Futures Markets

#### Public Lack of Appreciation of Derivative Markets

* A derivative market is a market in another market. There is some 'underlying market'.

### Forward Contracts

#### Forward Contract

* Forward is just a contract to deliver at a future date (exercise date or maturity date) at a specified exercise price.
* Example: Rice farmer sells rice to warehouser.
* Example: Foreign Exchange forward. Contract to sell pounds for yen.
* Both sides are locked into the contract, no liquidity.

#### FX Forwards and Forward Interest Parity

* FX Forward is like a pair of zero coupon bonds.
* Therefore, forward rate reflects interest rates in the two currencies.
* Forward Interest Parity: $$\text{forward exchange rate}(Y/$) = \text{spot exchange rate}(Y/$)\times\frac{1+r_{Y}}{1+r_{$}}.$$

#### Forward Rate Agreements

* Promises interest rate on future loan.
* L = actual interest rate on contract date
* R = contract rate
* D = days in contract period
* A = contract amount
* B = 360 or 365 days $$\text{Settlement} = \frac{(L-R)\times D\times A}{(B\times 100)+L\times D}.$$

### Future Contract

#### Futures Contracts

* Futures contracts differ from forward contracts in that contractors deal with an exchange rather than each other, and thus do not need to access each others' credit.
* Futures contracts are standardized retail products, rather than custom products.
* Futures contracts rely on margin calls to guarantee performance.

### Rice Futures

#### First Futures Market:Osaka

* Begun at Dojima, Osaka, Japan in 1670s. World's only futures market until 1860s.
* Dojima was centre for rice trade, with 91 rice warehouse in 1673. Rice is the underlying primary market.
* Dojima futures exchange had precise definitions of quality, delivery date and place, experts who evaluated rice quality, and clearinghouses for contracts. These are derivatives.

### Buying, Selling and Settlement

#### Buying or Selling Futures

* When one 'buys' a futures contract, one agrees with the exchange to a daily settlement procedure that is only loosely analogous to buying the commodity. One must post initial margin with the futures commission merchant.
* Same as when one 'sells' a futures contract, no intention of selling the commodity. Again, post margin.

#### Daily Settlement

* Every day, the exchange defines a price called the 'settle' price, which is essentially the last trade on that day.
* Every day until expiration a buyer's margin account is credited with the amount: change in settle price $\times$ contract amount.
* If contract is cash settled, on the last day the margin account is credited with $\times$ contract amount.
* If contract is physical delivery, on last day buyer must receive commodity.

### Fair Value in Futures Contracts

#### Fair Value in Futures Contract

* r = interest rate
* s = stoarge cost
* r+s = cost of carry
* Futures price is normally above cash price (contango), otherwise, 'backwardation'. $$P_{\text{future}} = P_{\text{spot}}(1+r+s).$$

### Oil Future

#### Oil Futures

* Crude light sweet oil contract size: 10000 barrels, open interest 431,000 contracts. Physical delivery.
* Brent crude, North Sea contract.

<img width = 50% height = 50% src = https://user-images.githubusercontent.com/128298224/229482514-9699fc9c-2d36-4c59-8a2d-5392c7b75647.jpg>

#### OPEC

* Organisation of Petroleum Exporting Countries established 1960 by Iran, Iraq, Kuwait, Saudi Arabia and Venezuela.
* OPEC is weak today because of conflict in middle east, hence low oil prices.

#### Government Oil Reserves

* In 2000, President Clinton established a 2 million barrel heating oil reserve in New York and New Haven to help stabilise US heating oil prices. US consumption of heating oil about 100 million barrels a year.

### SPI & FFR Futures

#### Stock Price Index Futures

* Cash settlement rather than physical delivery.
* Settlement is $250*(Index_{t}- Futures_{t-1}).$
* Fair value: $$F = P+P(r-y),$$ where F = fair value futures price, P = Stock price index, r = financing cost (interest rate), y = dividend yield.

#### Federal Funds Futures Market

* Created by Chicago Borad of Trade (CBOT) 1988.
* Show timing of expected actions of Federal Open Market Committee.
* One-month-ahead forecast errors typically in the ten to twenty basis point range.

### Options Overview

#### Options

* Calls, a right to buy
* Puts, a right to sell
* With options, one pays money to have a choice in the future.
* Essence of options is not that I buy the ability to vacillate, or to exercise free will. The choice one makes actually depends only on the underlying asset price.
* Options are truncated claims on assets.

#### Terms of Options Contract

* Exercise date
* Exercise price
* Definition of underlying and number of shares.

### Why Options exist

#### Why Have Options? A. Theoretical

* Theoretical Reason: Kenneth Arrow argued that a major source of economic inefficiency is the absence of markets for risks.
* Stephen Ross argued that financial options have a central place in the form of "completing the market".

#### Why Have Options? B. Behavioral

* Salience and Attention.
* People buy insurance, do not want to give up up side of investment.
* Peace of mind, with put option.

### Ubiquity of Options

#### Ubiquity of Options

* Limited Liability makes stocks into an option, gives peace of mind.
* Mortgages involve an option to default (in non-recourse states).
* Mortgages have a prepayment option. When you sell, you do not have to buy your way out of the mortgage.

#### Options Exchanges

* Chicago Board Options Exchange, a spinoff from the Chicago Board of Tradae 1973, traded first standardised options.
* Futures exchanges trade options on futures.

### Put/Call parity

#### Put-Call Parity Relation

* Put option price - call option price = present value of strike price + present value of dividends - price of stock
* Price of  stock = call price + pdv strike + pdv dividends - put price
* For European options, this formula must hold, otherwise there would be arbitrage profit opportunities.

### Using Options to Hedge

#### Using Options to Hedge

* To put a floor on one's holding of stock, one can buy a put on same number of shares.
* Alternatively, one can just decide to sell whenever the price reaches the floor.

## Module 6

### Investment Banks Introduction

#### Difference in US between Investment Banks and Commercial Banks

* Investment banks do not accept deposits, and have not been regulated as banks.
* Investment banks traditionally are not members of the Fedral Reserve System and do not normally access discount window.
* Investment banks underwrite of securities rather than make loans.

#### Investment Banks

* Traditional US bulge-brack firms: First Boston (acquired by Credit Suisse), Goldman Sachas (now a bank holding company), Merrill Lynch (now part of Bank of America), Morgan Stanley, Salomon Brothers (merged into Citicorp), Lehman Brothers (bankrupt 2008)
* Originally were usually partnerships, but partnership form has been disappearing, resulting in greater risk taking and crisis.

### The Underwriting Process

#### Underwriting of Securities

* Issuance of shares and corporate debt
* Seasoned issue versus IPO
* Underwriter provides advice for issuer, distribution of securities, sharing of risks of issue, and stabilisation of aftermarket.
* Underwriter also 'certifies' the issue by putting its reputation behind the issue.

#### Moral Hazard Problem Mitigated by Investment Banks

* Firms have incentive to issue shares when they know their earnings are only temporarily high.
* This problem can be "solved" by resorting to bank loans instead of new equity.
* Problem can also be solved by issuing security with an investment bank that has a reputation to protect.
* Studies show that investment banks that repeatedly underprice or overprice issues suffer a market share loss afterwards.

#### Two Basic Kinds of Offerings

* Bought deal: The underwriter agrees to buy all shares that are not sold.
* Best efforts: The underwriter says that if the issue is not sold, deal collapses

#### The Underwriting Process I

* Prefiling period.
* Advise issuers about their choices.
* Agreement among underwritiers, designates manager, fees.
* Filing of registration statement with SEC, begins cooling-off period.
* Cooling off period - distribute preliminary prospectus, nothing else.

#### The Underwriting Process II

* Call prospective clients for indication of interest.
* Due diligence meeting between underwriter and corporation.
* Decide on offering price.
* Dealer agreement, dealers purchase from underwriters at a discount from public price.

#### Stabilization

* A form of market manipulation by the underwriter near the time of the issue that is permitted by SEC.
* Underwriting syndicate legally allowed to conspire to 'fix' prices in market until entire issue is sold out.

### IPOs

#### Initial Public Offerings

* Price tends to jump up immediately after an IPO is issued.
* Apparently leave money upon the table.

#### Poor Long-Run Performance of IPOs

* Although average IPO earns a +16% return on the first day, this return tends to be offset over the next three years.

### Goldman Sachs and John Whitehead

* "Making money - always and no exeptions - was a principle of Goldman Sachs.

### The Prudent Person

#### Employment Retirees Income Secuirty Act: Prudent Man

* With the care, skill, prudence and diligence under the circumstances then prevailing that a prudent man acting in a like capacity and familiar  with such matters would use in the conduct of an enterprise of a like character and with like aims.

#### Financial Advisors

* Anyone who advises others on the value of securities or advisability of investing or who publishes analysis.
* Exclude banksers, lawyers, reporters, professors.
* Exclude Broker Dealers whose advice is only incidental to their business.

#### Financial Planners

* Comprehensive planning for life, rather than just picking stocks.
* Not regulated, not licensed in most countries.
* Certified Financial Planner (CFP) designation, awarded by Certified Financial Planner Board of Standards.

### Mutual Funds and ETFs

#### Mutual Fund History

* First mutual funds appeared Holland, 1770s Eendraght Maak Magt
* In 1920s, many investment companies bilked small investors.
* Massachusetts Investment Trust (MIT) in 1920s had only one class of investors, published portfolio, redeemed on demand.
* Investment Company Institute

#### ETFs vs. Mutual Funds

* First Exchange Trade Fund: Standard & poors Depositary Receipts, AMEX 1993
* SPDRs hold portfolio of S&P index
* Management fee: low, like 12 basis points.

### Brokers and Dealers

#### Brokers

* Brokers act on behalf of Others as their Agent for which they earn a Commission.

#### Dealers

* A Dealer always act for Himself, in other words as a Principal in the transaction for which he makes a Markup.
* Stands ready to buy and sell at posted prices, bid and asked, profit from bid-asked spread rather than commission.
* Analogy to antiques dealers.

#### Why are there Virtually no Real Estate Dealers?

* Dealers pay ordinary income on capital gains in US. Real estate has to be held for a substantial time between sales anyway, so you could qualify for long-term capital gains if not a dealer.

#### Good & Bad Broker Behavior

* Good brokers do not churn.
* SEC penalises "rogue brokers" who churn.

### Exchanges

#### Traditional Four Markets

* First Market: NYSE
* Second Market: NASDAQ National Market
* Third Market: NASDAQ small cap
* Fourth Market: Large institutions trade amongst themselves without the use of a securities firm

#### Why Does Listing Matter?

* Chinese investors tend to trade stocks that are locally listed, by Yale's former student Ning Zhu.
* Stocks co-move more with co-listed stocks.
* No information advantage.

### Limited Order Book

#### Limit Order Book

<img width = 50% height = 50% src = https://user-images.githubusercontent.com/128298224/229552460-bd594b96-14c2-466c-ae82-322e8700128b.jpg>

### High Frequency Trading

#### High Frequency Trading

* Computer programs can trade algorithmically.
* Trades can be flashed for a millisecond, and only computers will respond.
* Speed of transmission matters.
* Fully automated markets gaining ground over less automated markets such as NYSE.

### Payment for Order Flow

#### Payment for Order Flow

* Brokers drum up orders, deal with customers.
* Brokers sell the order flow to crossing networks, who profit from the order flow.
* Firms must also report statistics on their order-execution quality.

#### Kinds of Orders

* Market Order 
* Limit Order
* Stop Loss Order: Market orders dangerous for thinly-traded stocks; ECNs may not allow market orders.

### Government debt

#### Carmen Reinhart on Sovereign Default

* Public misunderstands default - rarely do governments repudiate entire debt.
* More common is that governments inflate the currency.
* Other hotspots for default today: Ukraine, Puerto Rico.

#### Reinhart-Rogoff Tally of Defaults

<img width = 50% height = 50% src = https://user-images.githubusercontent.com/128298224/229557567-d161030f-832d-4995-a145-2a3fbe84d9b8.jpg>
