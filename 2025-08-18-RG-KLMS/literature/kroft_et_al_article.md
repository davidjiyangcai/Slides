## Imperfect Competition and Rents in Labor and Product

## Markets: The Case of the Construction Industry∗

### Kory Kroft† Yao Luo‡ Magne Mogstad§ Bradley Setzler¶

### First version: March 2020. This version: July 2023

```
Abstract
Existing work on imperfect competition typically focuses on either the labor
market or the product market in isolation. In contrast, we analyze imperfect
competition in both markets jointly, showing theoretically and empirically that
focusing on one market in isolation may result in a limited or misleading picture
of the degree and impacts of market power. Our empirical setting is the US
construction industry. We develop, identify and estimate a model where con-
struction firms imperfectly compete with one another for workers in the labor
market and for projects in both the private market and the government mar-
ket, where government projects are procured through auctions. Our analyses
combine the universe of business and worker tax records with newly collected
records from government procurement auctions. We use the estimated model
to quantify the markdown of wages and the markup of prices, to show that
the impacts of an increase in market power in one market are attenuated by
the existence of market power in the other market, and to quantify the rents,
rent-sharing, and incidence of procurements in the US construction industry.
```
∗The opinions expressed in this paper are those of the authors alone and do not reflect the views
of the Internal Revenue Service or the US Treasury Department. This work is a component of a
larger project on income risk in the United States, conducted through the SOI Joint Statistical
Research Program. We thank Victor Aguirregabiria, David Autor, El Hadi Caoui, Lancelot Henry
de Frahan, Sabrina Howell, Larry Katz, Peter Kuhn, Tom Meling, Aviv Nevo, Matt Notowidigdo,
Elena Prager, Juan Carlos Suarez Serrato, John van Reenen, Owen Zidar, and participants at ASSA,
Booth, CESifo, Cornell, Cowles Foundation, Hebrew University, Houston, IZA, LSE, Maryland,
Microsoft Research, MIT, NBER IO, NBER Summer Institute, Northwestern, Penn State, Rice,
Simon Frasier, SITE Labor, SITE IO, SUFE IO, Toronto, UBC, UCL, and Zurich for valuable
comments. We thank Abdelrahman Amer, Tommaso Alba, Huishi Chen, JoonHwan Cho, Stephen
Claassen, Cheok In Fok, Yingcheng Luo, Eric Mackay, Chester Madrazo, Marc-Antoine Schmidt,
and Stephen Tino for valuable research assistance. Kroft and Luo acknowledge funding from the
SSHRC Insight Grant. Mogstad and Setzler acknowledge funding from NSF Grant SES-
and the Norwegian Research Council.†

‡Department of Economics, University of Toronto; NBER. E-mail: kory.kroft@utoronto.ca.
§Department of Economics, University of Toronto. E-mail: yao.luo@utoronto.ca.
Department of Economics, University of Chicago; Statistics Norway; NBER; IFS. E-mail:
magne.mogstad@gmail.com.¶
Department of Economics, Pennsylvania State University; NBER. E-mail:
bradley.setzler@gmail.com.


## 1 Introduction

Researchers and policymakers are keenly interested in measuring the degree of imper-
fect competition in the US economy and in understanding how it affects the outcomes
of workers and firms. Existing work on imperfect competition typically focuses on
either the labor market or the product market in isolation. In contrast, we analyze
imperfect competition in both markets jointly, showing theoretically and empirically
that focusing on one market in isolation may result in a limited or misleading picture
of the degree and impacts of market power.
Our empirical setting is the US construction industry, where we seek to quantify
the markdown of wages and the markup of prices, show that the impacts of an increase
in market power in one market are attenuated by the existence of market power in
the other market, and quantify the rents, rent-sharing, and incidence of government
procurements for construction projects. To do so, we develop, identify and estimate
a model where construction firms imperfectly compete with one another for workers
in the labor market and for projects in both the private market and the government
market, where government projects are procured through auctions. Our analyses
combine the universe of business and worker tax records with newly collected records
from government procurement auctions.
In Section 2, we present the model. The labor market side of the model builds
on work by Rosen (1986), Boal and Ransom (1997), Bhaskar et al. (2002), Manning
(2003), Card et al. (2018), and Lamadon et al. (2022). Competitive labor market
theory typically assumes that firms are wage-takers so that the labor supply facing
a given firm is perfectly elastic. To allow the firm-specific labor supply curve to be
imperfectly elastic so that the firm may have wage-setting power, we let workers have
heterogeneous preferences over the non-wage job characteristics or amenities that
firms offer. We assume that firms do not observe the idiosyncratic taste for amenities
of any given worker. This information asymmetry implies that employers cannot price
discriminate with respect to workers’ reservation wages. Instead, if a firm faces higher
demand for its products and wants to hire more labor, it needs to offer higher wages
to all workers. As a result, the equilibrium allocation of workers to firms creates rents
to employers and workers, where rents refer to the excess return over that required
to change a decision, as in Robinson (1933) and Rosen (1986).

```
1
```

The firm side of the model consists of two types of product markets in which the
construction firms may participate: the private market and the government market,
the latter of which procures projects through auctions. Incorporating both types of
product markets not only gives a more accurate representation of firms’ production
choices in the construction industry, but also facilitates identification of key model
parameters through the use of data on the bids and outcomes of procurement auctions.
The firm’s behavior is specified as a two-stage problem. In the first stage, firms bid for
a government project procured through a first-price sealed-bid auction. The project
specifies the amount of output that must be produced. At the end of the first stage,
firms learn the outcome of the auction. If a firm wins the auction, it receives the
winning bid amount as revenue and commences production. In the second stage,
the firm chooses inputs to maximize profit from total production, including projects
in both the private market and the government market. We allow the firm-specific
demand curve in the private product market to be imperfectly elastic. As a result,
the firm may earn rents due to price-setting power in the private product market and
because there may be a limited number of bidders in the procurement auction.
In our model, a firm is defined to have “double market power” if it can profitably
set both the price above the marginal cost and the wage below the marginal revenue
product of labor.^1 In Section 3, we theoretically examine the implications of this
double market power for the outcomes and behavior of workers and firms. We first
characterize the determinants of the markdown of wages and markup of prices in
the presence of double market power. We show that not only upward-sloping labor
supply but also downward-sloping product demand are relevant and distinct sources
of labor market power, as measured by the markdown of wages relative to the value
of the marginal product of labor. Similarly, product market power, as measured by
the markup of prices relative to the cost of production, is determined not only by the
elasticity of product demand but also the elasticity of labor supply.
Next, we show that the impacts of an increase in market power in one market will
beattenuatedby the existence of market power in the other market. The intuition is

(^1) Our “double market power” result resembles classical double marginalization, in which consumer
prices reflect the interaction of the markups that arise at each stage of production along a vertical
supply chain. Our result, however, applies to a single firm that has market power both in the product
market and the labor market.
2


straightforward: In response to an increase in labor market power, the firm wants to
lower the wage it pays by reducing employment and, thereby, output. However, the
firm will choose to reduce employment and output less if it is facing downward-sloping
demand, as lower output increases the price it can charge and, thus, the marginal
revenue product of labor. Similarly, if the firm experiences an increase in product
market power, it wants to increase the price it charges by reducing output and,
thereby, employment. However, the firm will choose to reduce output and employment
less if it is facing upward-sloping labor supply, as lower employment decreases the wage
it has to pay and, thus, the marginal cost of labor.
Motivated and guided by the theoretical results in Section 3, the remainder of the
paper seeks to identify and estimate the model in order toquantifythe double market
power and its implications for the outcomes and behavior of workers and firms in the
US construction industry.
As explained in Section 4, our analyses are based on a matched employer-employee
panel data set, which is formed by combining the universe of US business and worker
tax records for the period 2001-2015. Firm data contain information on sales, profits,
intermediate inputs, and industry. Worker data contain information on the number
of workers and their earnings. We merge the employer-employee panel data set with
a new data set that we assembled with information on US procurement auctions.
The resulting data set covers billions of dollars in procurement contracts awarded to
thousands of firms. Importantly for our identification strategy, we observe the identity
and bid of each firm in an auction, not only that of the winner. Comparing the firms
that win a procurement auction to those that lose (but bid similarly), we assess how
employment and wages change if a firm wins a procurement contract. We find that, on
average, winning a procurement auction leads to a 2% increase in earnings per worker
in the post-auction time period. At the same time, the number of employees in the
firm increases, on average, by about 8%. The evidence that winning a procurement
auction causes the firm to bid up wages and hire more workers is at odds with the
textbook model in which the labor supply curve facing the firm is perfectly elastic.
Instead, it is consistent with the notion that firms face upward-sloping labor supply
curves and, therefore, have wage-setting power in the labor market, as we allow in
our model.

#### 3


In Section 5, we demonstrate how the model parameters are identified from the
data. The primary challenge to identify the firm-specific labor supply elasticity is
unobserved shifts to labor supply that may affect both employment and wages. We
employ and compare several alternative approaches to overcome this identification
challenge, drawing especially on institutional features of procurement auctions. One
approach compares winners and losers with close bids in the (price-only) auctions in
order to isolate exogenous demand shocks that shift the winning firms along their
labor supply curves.^2 In another approach, we leverage that there is a time delay
between a firm placing a bid in the procurement auction (based on estimated costs)
and commencing production on the procurement project, so that the auction bid
may not depend on the firm-specific labor supply shock that is realized at the time
of production.^3
The primary challenge to identify the relevant technology parameters is firm-
specific productivity shocks, which are unobserved correlates of both inputs and out-
put. We overcome this identification challenge by taking advantage of the monotonic-
ity of auction bids with respect to productivity. This monotonicity allows us to use
data on bids to control for unobserved productivity differences across firms in the
production function estimation. To recover the product demand elasticity, we extend
the price markup estimator under Leontief production, recently used by de Loecker
et al. (2020), to account for the wage markdown. We also show that the technology
and product demand parameters are over-identified and use the additional moment
condition to assess the model.
In Section 6, we present the estimates of the model parameters. We find that
firms have significant wage-setting power with an estimated firm-specific labor supply
elasticity of about 3.5 to 4.1. This estimate indicates that, if an US construction firm
aims to increase the number of employees by 10%, it needs to increase wages by

(^2) A small number of papers have used research designs that compare winners and losers of pro-
curement auctions. They estimate how government purchases affect employment during an economic
crisis (Gugler et al., 2020) and firm dynamics and growth (Ferraz et al., 2015, Hvide and Meling,
2020). None of these studies use these comparisons to draw inference about imperfect competition
or rents, nor do they use these comparisons to identify and estimate an economic model of firm and
worker behavior.
(^3) Similar timing assumptions are used in the large literature on production function estimation
(see the discussions by Ackerberg et al. 2015 and Gandhi et al. 2020).

#### 4


around 2.4-2.9%. Another finding is that firms have significant price-setting power in
the private product market with an estimated product demand elasticity of 7.3. The
estimate suggests that, in order for a firm to increase output by 10% in the private
market, it must reduce the price of its product by about 1.4%. We also find that
the production function exhibits (approximately) constant returns to scale over labor
and capital.
In Section 7, we use the estimated model of the construction industry to quantify
key implications of double market power. In Section 7.1, we show that double market
power generates a total markdown of wages of more than 30% relative to the value of
the marginal product of labor, and a total markup of prices of more than 40% relative
to the cost of production. To gauge the importance of analyzing imperfect competition
in both markets jointly, we compare these results to the markdown and markup
estimates one would obtain if one only focused on labor market power or product
market power in isolation. We find that, if one assumed a perfectly competitive
product market, then our estimates of the labor supply elasticity would imply that
the wage is only 20% below the value of the marginal product of labor. Conversely, if
one assumed a perfectly competitive labor market, then our estimates of the demand
elasticity would imply that the price is only 16% above the cost of production.
Next, in Section 7.2, we use our model to perform counterfactuals that quantify the
extent to which impacts of an increase in market power in one market are attenuated
by the existence of market power in the other market. If the labor supply elasticity
of a given firm is reduced by half, our estimates suggest the firm employs 12% fewer
workers and decreases wages by 6%. By comparison, if the firm did not have price-
setting power in the product market, we find that it would employ 22% fewer workers
and decrease wages by 11%.
In Section 8, we conclude our empirical analyses with a quantification of the rents,
rent-sharing, and incidence of procurements in the US construction industry. We find
that imperfect competition leads to worker rents per year of around $11,600 per
worker, while firm rents per year (as measured by profits) amount to about $43,
per worker. Comparing worker rents to firm rents, we see that more than three-fourths
of total rents are captured by firms. Although winning a procurement contract crowds
out some private market production, it increases total output, employment, and rents.

#### 5


We find that 40% of these additional rents are captured by workers.
Our paper is primarily related to a large literature on imperfect competition,
rents, and inequality in the labor market, reviewed by Manning (2011), Card et al.
(2018), Card (2022), and Lamadon et al. (2022), but differs in several important
ways. First, our paper differs from much of the existing literature in that we fully
specify an equilibrium model and identify and estimate the model parameters. This
allows us to not only measure the current size and share of the rents earned by firms
and workers, but also to understand the underlying mechanisms and to quantify
how the outcomes and behavior of firms and workers would change if market power
increased or decreased. A second salient difference from the literature is that we
analyze imperfect competition in both the labor and product market jointly.^4 Our
theoretical and empirical findings highlight how studies that focus on either the labor
market or the product market in isolation may result in a limited or misleading
picture of the degree and impacts of imperfect competition. Third, much of this
existing work is trying to measure imperfect competition in the entire labor market,
paying little attention to the large heterogeneity in technology and market structure
across industries.^5 In contrast, we focus on the construction industry, paying closer
attention to the structure and the functioning of the relevant markets. We leverage
institutional features of the construction industry for our identification arguments, for
understanding and modeling the behavior of firms, and for estimating the incidence
of government procurements.
Our paper also relates and contributes in several ways to the empirical literature
on auctions, reviewed by Athey and Haile (2007). First, we present and solve an
auction model with incomplete information about unobserved productivity (rather
than costs). This allows for a flexible relationship between the probability of winning
the auction and other firm outcomes that depend on productivity, such as employ-
ment and output. Second, our paper also contributes by quantifying how winning
a procurement auction affects the firm’s total production and whether it crowds-in

(^4) An exception is MacKenzie (2021), who considers the gains from international trade if there is
labor and product market power.
(^5) Notable exceptions include Azar et al. (2021) and Lamadon et al. (2022). They study imperfect
competition in the entire US labor market, but account for imperfect substitutability across markets
using a nested-logit structure on preferences. See the discussion by Card (2022).

#### 6


or crowds-out activity in the private market. Third, our work complements existing
papers on auctions by taking into account how bidding behavior depends on market
power, both in the labor market and in the private product market. Fourth, our paper
shows how bids in procurement auctions can be used to construct a control variable
that we use to address the problem of unobserved productivity in the estimation of
production functions.^6
Lastly, our paper relates to a growing body of empirical work that estimates the
pass-through and incidence of firm-specific shocks, reviewed by Card et al. (2018).
An early example is van Reenen (1996), who studies how innovation affects firms’
profits and workers’ wages. He also investigates patents as a source of variation, but
finds them to be weakly correlated with profits. Building on this insight, Kline et al.
(2019) study the incidence of patents that are predicted to be valuable and Howell and
Brown (2020) study the incidence of R&D grants. A related literature on skill-biased
technical change has examined the wage and productivity effects of the adoption of
new technology in firms (see Akerman et al., 2015, and the references therein).

## 2 A Tractable Model of Imperfect Competition in

## Both Labor and Product Markets

In this section, we develop a model in which construction firms compete with one
another for projects in the product market and for workers in the labor market. We
allow for imperfect competition, in the form of monopolistic competition in the prod-
uct market and monopsonistic competition in the labor market. The production side
of the model incorporates two types of product markets in which construction firms
may participate: the private market and the government market, where government
projects are procured through auctions.

### 2.1 Worker Preferences and Labor Supply

Workeriin yearthas the following preferences over being employed at a firmj:

```
Uit(j,Wjt) = logWjt+ logGjt+ηijt, (1)
```
(^6) For reviews of the literature on production function identification, see Ackerberg et al. (2015)
and Gandhi et al. (2020).
7


where Wjt represents earnings, Gjt represents the common value of firm-specific
amenities, andηijtcaptures workeri’s idiosyncratic tastes for the amenities of firm
j.^7 Since we allow amenities to be unobserved to the analyst, they can include a
wide range of characteristics, such as distance to the firm from the worker’s home,
flexibility in the work schedules, effort required, workplace safety, and so on.
Our specification of preferences allows for the possibility that workers view firms
as imperfect substitutes. The termGjtgives rise to vertical employer differentiation:
some employers offer good amenities while other employers offer bad amenities. The
termηijtgives rise to horizontal employer differentiation: workers are heterogeneous
in their preferences over the same firm. The importance of horizontal differentiation
is governed by the variability across workers in their idiosyncratic taste for a given
firm. We parameterize the distribution ofηijtas i.i.d. Type-1 Extreme Value (T1EV)
with dispersionθ≥ 0.^8 Whenθis larger, horizontal employer differentiation becomes
relatively more important.
We consider an environment with monopsonistic competition in a spot market for
labor, making three key assumptions. First, firms do not observe the idiosyncratic
taste for amenities of any given worker ηijt. This information asymmetry implies
that employers cannot price discriminate with respect to workers’ reservation wages.
Instead, if a firm wants to hire more labor, it needs to offer higher wages to both
marginal and inframarginal workers. Second, we assume all workers are homogenous
in skill. This assumption is motivated by the fact that we find no evidence of changes
in worker quality in response to winning a procurement auction.^9 Third, we assume
firms are “strategically small” in the sense that each firm views itself as infinitesimal
within the market.^10

(^7) We specify workers’ preferences as log-additive in wages and amenities. Recent work by Dube
et al. (2022) considers a model in which log wages and amenities are non-separable. While economi-
cally interesting, non-separability is empirically challenging as the labor supply curve will no longer
be iso-elastic.
(^8) We only require thatηijtis independently distributed across firms and workers within each
cross-sectiont;ηijtmay be arbitrarily persistent within a worker-firm pair over time.
(^9) As long as worker quality does not change in response to winning a procurement auction, it is
straightforward to extend the model and the empirical analysis to allow for differences in worker
quality (see Lamadon et al., 2022). 10
The strategically-small firm assumption has been relaxed in the models considered by Berger
et al. (2022), Chan et al. (2023), and Jarosch et al. (2023). However, identification is difficult in
models with strategic interactions in the wage-setting. Recent papers by Roussille and Scuderi
8


Given these assumptions, the number of workers who accept a job at firmj at
timetfor a posted wage offerWjtisLjt= (WjtGjt/Ξt)^1 /θ, whereGjtcaptures the
vertical differentiation due to firm-specific amenities andΞtcaptures aggregate labor
supply factors in the relevant market.^11 In the baseline analysis, we consider the entire
US construction industry to be the relevant labor market. We also perform several
specification checks to show that our findings are robust to alternative definitions of
the labor market.
Our empirical analysis focuses on the inverse labor supply curve facing firmjat
timet, which is given by
Wjt=LθjtUjt, (2)

whereUjt ≡ Ξt/Gjt. The labor supply elasticity facing the firm is 1 /θ, so labor
supply becomes more inelastic when idiosyncratic tastes are more dispersed. Given
the assumption of strategically-small firms, the marginal wage changes at one firm do
not impact aggregate labor supply factors (that is,∂W∂Ξjtt ≈ 0 ).
For the empirical analysis, it is useful to decomposelogUjtinto an aggregate com-
ponent, a firm-specific fixed component, and a firm-specific time-varying component.
Denotingujt≡logUjt,gjt≡logGjt, andξt≡log Ξt, it follows thatujt=−gjt+ξt.
Furthermore, we can write−gjt≡ψj+νjt,which is without loss of generality since we
can simply defineψj≡E[−gjt|j]andνjt≡−gjt−ψj. Then, denotingwjt≡logWjt
andℓjt≡logLjt, log wages are given by

```
wjt=θℓjt+ujt=θℓjt+ψj+νjt+ξt. (3)
```
Letting∆indicate differences over time, changes in log wages are thus

```
∆wjt=θ∆ℓjt+ ∆νjt+ ∆ξt, (4)
```
where the time-invariant componentψjdoes not appear in differences over time.
Equation (4) highlights that wages change over time for three reasons. All else
equal, the firm needs to pay higher wages to hire more workers, as captured byθ∆ℓjt;
the firm must pay higher wages to keep the same number of workers if it experiences

(2022) and Sharma (2022) test for strategic interactions in wage-setting, but do not find evidence of
such interactions.

(^11) Formally,Ξt≡Wt/Ltθ, whereLtis the total number of workers in the market andWt≡
P
j′(Wj′tGj′t)^1 /θis the price index of labor.
9


a negative shock to labor supply, as captured by∆νjt; and the firm needs to pay more
to keep the same number of workers if aggregate labor supply declines or the price
index of labor rises, as captured by∆ξt.

### 2.2 Firm Technology and Product Demand

The production side of the model incorporates two types of product markets in which
construction firms may participate: the private market and the government market,
where government projects are procured through auctions. It is important to account
for the government market for three reasons. First, it provides a more accurate
representation of firms’ production choices. Second, it lets us draw policy implications
regarding the incidence of government expenditure on construction projects. Third,
variation in bidding for procurement projects will be important to identify key model
parameters.
We begin by specifying the production technology, before describing the private
product market, taking the outcomes of the government market as given, and then
discuss optimal bidding in the government market. Following Ackerberg et al. (2015),
the production function (in physical units) is
Qjt= min{ΩjtLβjtLKjtβK,βMMjt}exp(ejt), (5)

whereΩjtdenotes total factor productivity (TFP),Kjtdenotes capital,Mjtdenotes
intermediate inputs, andejtrepresents measurement error. We assume that firms can
rent capital at constant pricepK. While the assumption of a rental market for capital
is standard in the literature, it may be a fairly good description of the construction
industry, which heavily utilizes rental equipment and machinery. We also assume the
market for intermediate inputs is competitive with constant pricepM.
Our Leontief functional form in equation (5) imposes strong complementarity be-
tween labor and intermediate inputs, while allowing for substitutability between labor
and capital. This assumption may be relatively reasonable for the construction in-
dustry, where greater capital expenditure (i.e., renting more efficient equipment and
machinery) may substitute for labor, but labor cannot take the place of concrete,
asphalt, wood, and other materials required to construct a bridge or road.^12 The

(^12) The Leontief functional form appears broadly consistent with the standard construction cost

#### 10


Leontief functional form implies a zero elasticity of substitution between labor and
intermediate inputs. As an alternative, in Online Appendix C, we solve, identify, and
estimate the model with a Cobb-Douglas production function, which has elasticity
of substitution of unity and thus allows for substitutability between labor and in-
termediate inputs.^13 As shown in Section 6.2, the key empirical results are broadly
similar when using the Cobb-Douglas production function, implying that the Leontief
functional form is not crucial to our findings.
Given the technology in equation (5), the construction firms may choose to pro-
duce in two product markets. The first is the market for private projects, which
we denoteH. Specifically, firmj at timetposts a pricePjtH at which it is willing
to produce in the market for private projects. Consumers have idiosyncratic prefer-
ences over producers. Consumeri’s utility from purchasing from firmjat timetis
UijtH =−logPjtH+ωijt.We parameterize the distribution ofωijtas i.i.d. T1EV with
dispersion 0 ≤ε≤ 1. Whenεis larger, horizontal producer differentiation becomes
relatively more important, asωijthas greater variability.
Given these assumptions, the quantity purchased from firmjat tfor a posted
pricePjtH can be expressed asQHjt =

#### 

```
PjtH
```
```
− 1 /ε
א, where≡ א
```
#### P

```
j′
```
#### 

```
PjH′t
```
```
− 1 /ε
is the
```
aggregate price index. Rearranging,PjtH=pH

#### 

```
QHjt
```
−ε
, wherepHא ≡−εand− 1 /εis
the product demand elasticity.^14 This implies private market revenues are

```
RHjt=PjtHQHjt=pH
```
#### 

```
QHjt
```
```
 1 −ε
```
. (6)

DenotingrHjt≡logRHjtandqjtH≡logQHjt, it follows that

```
rjtH= logpH+ (1−ε)qjtH, (7)
```
estimation handbook (RSMeans, 2008). This handbook provides task-specific construction cost
estimates for the typical crew (labor and equipment needed) per unit of material. While crew
choices may vary depending on the contractor, material input requirements are fixed for each task. 13
Castro-Vincenzi and Kleinman (2022, p.27) review the literature estimating the elasticity of
substitution between intermediate materials and labor. All of the papers find an elasticity of sub-
stitution between 0 and 1, which are the lowest (Leontief) and highest (Cobb-Douglas) elasticities
that we consider.

(^14) In the private product market, we assume firms are “strategically small” in the sense that they
view themselves as infinitesimal within the market (i.e.∂P∂אjtH≈ 0 ). Thus,∂logQ
Hjt
∂logPjtH=−^1 /ε, so−^1 /εis
the price elasticity of demand. This product demand curve and “small” firm assumption are assumed
by Dixit and Stiglitz (1977) and a large subsequent literature on monopolistic competition.

#### 11


so 1 −εcan be interpreted as the revenue elasticity of output in the private market.^15
In addition to the private product market, firms may participate in the market for
government projects, denoted byG. Output for the government market is denoted
QGjt. Firm j produces total output Qjt = QHjt+QGjt simultaneously across both
markets using the production function in equation (5). We denoteDjt= 1if firm
j receives a procurement contract att andDjt = 0otherwise. If firmj does not
receive a procurement contract (Djt = 0), it does not produce in the government
market (QGjt = 0). If firmj receives a procurement contract (Djt = 1), it must
produce exactlyQGin the government market (QGjt=QG), whereQGis set by the
government. The quantity produced by firmjin the government market can then be
expressed asQGjt=QGDjt. The allocation of procurement contracts to firms as well
as the revenues received from procurement projects are determined through first-price
sealed-bid auctions, which we describe below.

### 2.3 Firm’s Problem and Optimal Behavior

We model firm behavior as a two-stage problem which we solve backwards. In the
first stage, a firm submits a bid for a government project that is procured through a
first-price sealed-bid auction. The project specifies the amount of output that must be
produced within a given time frame. At the end of the first stage, the firm learns the
auction outcome. If the firm wins the auction, it receives as revenue the winning bid
amount. In the second stage, the firm chooses inputs to maximize profit from total
production, taking as given the outcome of the procurement auction. Production in
both private and government projects occurs simultaneously at the end of the second
stage.
We now solve for the optimal private market behavior of firmj if it receives a
procurement contract in the government market as well as if it does not. Denote
profit excluding procurement revenue byπ 1 HjtifDjt= 1andπH 0 jtifDjt= 0. In order
to obtain a procurement contract, firms place bids in auctions. Denote firmj’s bid in
yeartbyZjt. Total profit is thenπ 1 jt=Zjt+π 1 Hjtif the firm receives a procurement
contract, andπ 0 jt=π 0 Hjtotherwise. Observed profit isπjt=π 1 jtDjt+π 0 jt(1−Djt).

(^15) Our derivations in the text focus onε > 0. Online Appendix B provides derivations with perfect
competition,ε= 0. As discussed in Section 6.2,ε= 0is at odds with our empirical findings.

#### 12


GivenQGandDjt=d, the firm’s second stage problem is to hire laborLdjt, purchase
intermediate inputsMdjt, and rent capitalKdjtto maximize profits,

```
πHdjt=RHdjt−WdjtLdjt−pMMdjt−pKKdjt, (8)
```
ford= 0, 1 , subject to the labor supply curve (equation 2), the production function
(equation 5), the private market revenue curve (equation 6), the price of intermediate
inputs (pM), the price of capital (pK), and that the government project is fulfilled by
the procured firm (Q 1 jt≥QG).
We now use the firm’s first-order conditions to characterize the firm’s private
market behavior. The first-order condition for capital implies a composite production
function, Qjt= min{ΦjtLρ
jt,βMMjt}exp(ejt), (9)
whereΦjt≡Ωjt[ββKL(1+pθK)Ujt]βKis composite TFP,ρ≡(1 +θ)βK+βLis the composite
returns to labor, andejtreflects independent measurement error in output.^16 We
refer to Online Appendix A.1 for the derivation of the composite production function
in equation (9).
Given the composite production function, the first-order condition for intermediate
inputs implies
Xjt=pM
βM
Qjt=pM
βM
LρjtΦjt, (10)

where Xjt ≡ pMMjt denotes expenditure on intermediate inputs. Letting xjt ≡
logXjtandφjt≡log Φjt, and definingκX≡log (pM/βM), it follows that

```
xjt=κX+ρℓjt+φjt. (11)
```
Thus, our model implies a closed-form relationship between expenditure on interme-
diate inputs and labor, which will prove useful for identifyingρ.
Combining the product demand curve in equation (7) with the first-order condition
for intermediate inputs in equation (11) yields

```
rjt=κR+ (1−ε)xjt+ (1−ε)ejt if Djt= 0, (12)
```
(^16) One way to motivate that the measurement errorejtis independent is to suppose that firms
choose intermediate inputs in the second stage of periodtbefore they observe the idiosyncratic shock
to output at the end of periodt, as assumed by Ackerberg et al. (2015) and a large literature in
industrial organization.

#### 13


whereκR ≡ logpH+ (1−ε) log (βM/pM), which shows that revenues are log-linear
in intermediate input expenditures, with coefficient 1 −ε, among firms that are only
producing for the private market (Djt= 0).
The first-order condition with respect to labor implies the following relationship
between private market revenues and expenditures on labor and intermediate inputs:

```
RHdjt(1−ε)
Qdjt
QHdjt =
```
```
1 +θ
βL Bdjt+Xdjt, (13)
```
whereBjt≡LjtWjtdenotes the firm’s wage bill. This equation will prove useful for
identifyingεandβL. The derivation of this equation and several important implica-
tions of the first-order conditions for labor are reported in Online Appendix A.2; we
briefly summarize implications here.
One implication of the first-order condition for labor is that both winners and
losers of procurement contracts always produce strictly positive output for the private
market (QHdjt> 0 ,d= 0, 1 ). This follows from the fact that firms have market power
(ε > 0 ), which implies that the marginal revenue in the private market is strictly
greater than marginal cost as private market output approaches zero. For the same
reason, total production is strictly greater if the firm receives a procurement contract
versus if it does not (Q 1 jt> Q 0 jt). Another implication is that the government project
crowds-out private projects for firmj (QH 1 jt < QH 0 jt) if1 +θ > ρ, and conversely,
crowds-in private projects (QH 1 jt> QH 0 jt) if1 +θ < ρ. To see why this is the case,
note that winning a government project increases the total output level. This requires
more employment to achieve a greater level of production. Due to the upward-sloping
labor supply curve, greater employment leads to higher costs of labor, determined by
1 +θ. On the other hand, greater scale would induce greater private production if
there is increasing return to scale (in labor and capital),ρ > 1. Thus, the magnitude
of1+θrelative toρdetermines if receiving a procurement contract leads to crowd-out
or crowd-in of private market output for firmj.

### 2.4 Firm’s Optimal Bidding for Government Procurements

To complete the model, we now specify how procurement contracts are allocated to
firms and the determination of procurement revenues. Firms choose bids in considera-
tion of their opportunity costs. The opportunity cost of receiving a procurement con-

```
14
```

tract from the government is the difference in private market profits between receiving
no government contract and receiving a government contract. Formally, denote the
opportunity cost byσujt(φjt)≡π 0 Hjt−π 1 Hjt, where the notation emphasizes that firm
productivityφjtis the only source of heterogeneity in the opportunity cost, condi-
tional on amenitiesujt.^17 The opportunity cost of winning a procurement contract is
strictly positive,σujt(φjt)> 0 , as the firm would have received positive revenues if it
sold the output quantityQGto the private market instead of the government market.
In the procurement auction, bidders observe common information about the size of
the project,QG, the number of bidders,I, and the amenities of each bidding firm,ujt.
The distribution of TFP conditional on amenities,(φjt|ujt=u)∼F ̃u(·), is assumed
to be i.i.d. and known by all firms, and induces an i.i.d. distribution of opportunity
costsσu(φjt)∼Fu(·).^18 Revenue from winning the auction is the winning bid,Zjt.
The difference between the benefit and the opportunity cost of winning an auction
with bidZjtis thusZjt−σu(φjt). Conditional on amenitiesujt=u, a firm with TFP
φjtchooses the optimal bidZjtto solve
maxZjt (|Zjt−{zσu(φjt))}
payoff

```
Pr (| Djt{z= 1|Zjt)}
probability of winning
```
#### .

The first term is the payoff to winning an auction, which is increasing inZjt, while
the second term is the probability of winning an auction, which is decreasing inZjt.
Thus, the firm faces the usual trade-off in an auction between profits if one wins and
the probability of winning.
The firm’s optimal bidding strategy in the procurement auction is

```
su(φjt) =σu(φjt)δu(φjt),whereδu(φjt)≡1 +
```
```
Rσ ̄
σu(φjt)[1−Fu( ̃σ)]
```
I− (^1) dσ ̃
σu(φjt) [1−Fu(σu(φjt))]I−^1

#### . (14)

We can interpretδu≥ 1 as the bid markup relative to the opportunity cost. When
δu= 1, each firm’s optimal bid equals its opportunity cost, so each firm makes zero
economic profit from receiving a procurement contract. As the number of auction

(^17) The profit function for auction winners depends also on the size of the government projectQG, so
the opportunity cost also depends on 18 QG. For notational convenience, we suppress this dependence.
We require that TFP is i.i.d. across firms within each cross-sectiont, though TFP may be
arbitrarily persistent within a firm over time.

#### 15


participantsI declines,δurises, so firms that receive procurement contracts extract
greater profits in the government market when there is less competition. SinceZjt
exceedsσu(φjt)due to finiteIand the bidding strategysu(φjt)is strictly increasing in
the opportunity costσu(φjt), equation (14) defines the unique symmetric equilibrium
(Milgrom and Weber, 1982; Maskin and Riley, 1984).^19 The winner of the auction is
determined as

```
Djt= 1{su(φjt)< su(φj′t), ∀j′̸=jsuch thatj,j′∈Jι},
```
whereJιis the set of firms participating in auctionι. This expression makes clear
that the winner of a procurement contract is selected on TFP.
Before proceeding, it is useful to note that we have assumed auctions are sym-
metric. Though this assumption will not be crucial for our identification strategy
discussed below, it is convenient for expositional and computational purposes, as
symmetric auctions are easier to solve. Furthermore, symmetry is a standard as-
sumption in the empirical auction literature (Athey and Haile, 2007). Nevertheless,
in our empirical application, we provide a robustness check which relaxes this sym-
metry assumption.

### 2.5 Worker and Firm Rents

Given the specification of the labor and product markets above, we can now define the
surplus or rents that firms and their workers accrue. We focus both on the total rents
from production for the private market (in the absence of procurement projects) and
the additional rents generated from receiving a procurement contract or, equivalently,
the incidence of government procurement.
In our model, the equilibrium allocation of workers to firms creates surpluses or
rents for inframarginal workers, defined as the excess return over that required to
change a decision, as in Rosen (1986). The rents of workeri,Vit, derived from the
current choice of firm,j, are defined implicitly by,

(^19) One potential concern is that firms may collude to achieve bid revenues greater than those
predicted by our first-price sealed-bid auction model. In Online Appendix Figure A.1, we apply the
collusion test of Chassang et al. (2022) to each of the 28 states in our data separately, finding no
evidence of collusion.

#### 16


```
Uit(j,Wjt−Vit) = maxj′̸=j Uit(j′,Wj′t).
```
This definition of rents captures that the average worker choosing firmj may be
far from the margin of indifference and would maintain the same choice even if her
current firm offered significantly lower wages.
Given our specification of preferences (equation 1), we prove in Online Appendix
A.3 that it is possible to aggregate the rents across workers to get the measure of the
total worker rents at firmj,Vjt, if it offers wageW, as follows,

```
Vjt(W) =
WjtLjt(W)
1 + 1/θ =
```
```
Bjt(W)
1 + 1/θ
```
whereLjt(W)is the number of workers in firmjand periodtif it offers wageW
(determined by equation 2), andBjt(W)≡WLjt(W)is the corresponding wage bill.
Intuitively,Vjt can be interpreted as the workers’ willingness-to-pay to stay at the
current firmj, which is greater when the labor supply curve is steeper (i.e., whenθ
is greater).^20
When analyzing the incidence of procurements, recall that there are two potential
wage offers: W 0 jt if the firm loses the procurement auction, and W 1 jt if the firm
wins the procurement auction. DefiningV 0 jt≡Vjt(W 0 jt)andV 1 jt≡Vjt(W 1 jt), the
incidence of procurements on workers,V∆jt, is given by,

```
V|{z}∆jt
Incidence
```
```
≡ |{z}V 1 jt
Rents for winners
```
```
− |{z}V 0 jt
Rents for losers
```
```
=B^1 1 + 1jt−B/θ^0 jt
| {z }
Incidence
```
#### ,

whereB 0 jt ≡Bjt(W 0 jt)andB 1 jt ≡Bjt(W 1 jt). Furthermore, we can measure the
incidence for “incumbents” (i.e., workers who accept both offered wagesW 0 jt and
W 1 jt by firmj) versus “new hires” (i.e., workers who accept offered wageW 1 jtbut
reject offered wageW 0 jtby firmj). For an incumbent worker, it is clear from the
definition of rents above that the incidence is simply the wage gain,W 1 jt−W 0 jt. Thus,
the total incidence of procurements on all workers in the firm can be decomposed as,

(^20) Note thatBjtis a function of 1 /θ, so these expressions do not imply that rents increase for
workers as labor supply becomes more inelastic. When we quantify the impacts of a change in
market power below, we will show that worker rents decrease when labor supply becomes more
inelastic due to the wage bill decrease.

#### 17


```
V|{z}∆jt
Incidence
```
=L| 0 jt(W (^1) {zjt−W 0 jt})
Incidence for incumbents
+W 1 jt(L 1 jt−L 0 jt)−B^1 jt1 +−Bθ^0 jt
| {z }
Incidence for new hires

#### ,

whereL 0 jt≡Ljt(W 0 jt)andL 1 jt≡Ljt(W 1 jt); see Online Appendix A.3 for additional
details. Thus, the incidence for incumbents is the wage change multiplied by the
number of incumbent workers. The incidence for new hires is the wage bill of new
hires minus the wage bill required to make them indifferent between the new and
initial firm choices.
As our measure of firm rents, we use profits. There are three relevant measures
of profits. First,π 0 jt is the profit that the firm captures from production for the
private market if it does not receive a procurement contract. Second,π 1 jtis the profit
the firm captures from joint production for the government and private markets if it
receives the procurement contract. Third,π∆jt≡π 1 jt−π 0 jtis the additional rents
earned by the firm from receiving the procurement contract. They are related by

```
|{z}π^1 jt
Firm rents for winners
```
```
= |{z}π 0 jt
Firm rents for losers
```
```
+ |{z}π∆jt
Incidence on firms
```
#### .

It is important to observe that profits do not necessarily represent ex-ante rents for
the employer. Suppose, for example, that each employer initially invests in amenities
offered to the workers by deciding on the firm’s location or working conditions. Work-
ers’ heterogeneous preferences over those amenities give rise to wage-setting power,
which employers can use to extract additional profits or rents. Thus, the existence
of such ex-post rents could simply be returns to costly ex-ante choices of amenities.
Additionally, profits from procurement projects may in part reflect a fixed cost of
entry to the auction, e.g., the cost of obtaining a license. While the presence of a
fixed entry cost will affect the interpretation of profits, it is possible to show that it
will not affect identification of model parameters.

## 3 Double Market Power and its Implications

In our model, a firm is defined to have “double market power” if it can profitably
set both the price above the marginal cost and the wage below the marginal revenue
product of labor. We now theoretically examine the implications of this double market

#### 18


power for the wage-setting and price-setting decisions of the firm. We first characterize
the total markdown of wages and total markup of prices in the presence of double
market power. Next, we show that the impacts of an increase in market power in one
market will be attenuated by the existence of market power in the other market.
As these theoretical results may be of interest in markets other than the con-
struction sector, we consider a version of the model from Section 2 that allows for
a more flexible production function and omits the government market for procure-
ments. In the empirical analyses in Sections 5-8, however, we return to the model of
the construction industry in Section 2, quantifying the double market power and its
implications.

### 3.1 Markdown of Wages and Markup of Prices

As in the previous section, we suppose that the firm maximizes profits (equation
8) subject to the labor supply curve (equation 2) and the product demand curve
(equation 6). However, we remove the government market and allow for a flexible
production function,Qjt=fjt(Ljt,Mjt,Kjt), that generalizes equation (5).
Consider, for now, the case wherefjthas positive elasticity of substitution between
labor and other inputs. Denoting the marginal revenue product of labor by MRPLjt≡
∂(PjtQjt)
∂Ljt and the marginal cost of labor by MCLjt≡

∂(WjtLjt)
∂Ljt , the first-order condition
is,
(1| −ε)×{zPjtMPLjt}
MRPLjt

```
= (1 +| θ){z× Wjt}
MCLjt
```
#### (15)

where MPLjt≡ ∂L∂jtfjt(Ljt,Mjt,Kjt)denotes the marginal product of labor. Rear-
ranging the first-order condition, we have the following result:

Lemma 1.The optimal markdown and markup are given by,

```
Wjt=
```
```
zmarkdown}| {
(1 +θ)−^1 ×MRPLjt and Pjt=
```
```
zmarkup}| {
(1−ε)−^1 ×MCLMPLjt
jt
```
#### (16)

Lemma 1 confirms the usual intuition that less elastic labor supply (greaterθ) leads
to a greater markdown of wages, and less elastic product demand (greaterε) leads to
a greater markup of prices.

#### 19


What is not directly evident from Lemma 1 is how the labor supply and product
demand elasticities interact to determine the wage-setting and price-setting decisions
of the firm. The following proposition highlights these interactions by expanding the
MRPL and MCL in Lemma 1:

Proposition 1.The optimal wage satisfies,

```
Wjt =
```
```
zmarkdown}| {
(1 +θ)−^1 ×
```
```
inverse markupz }| {
| {z (1−ε) }
double markdown
```
```
× P|jtMPL{z jt}
value of MPL
```
#### (17)

and the optimal price satisfies,

```
Pjt=
```
```
zmarkup}| {
(1−ε)−^1 ×
```
```
inverse markdownz }| {
| {z(1 +θ) }
double markup
```
```
× MPLWjt
| {zjt}
prod.-adjusted wage
```
#### (18)

A key insight from Proposition 1 is that not only upward-sloping labor supply but also
downward-sloping product demand are relevant and distinct sources of labor market
power, as measured by the markdown of wages relative to the value of MPL. Similarly,
product market power, as measured by the markup relative to the productivity-
adjusted wage, is determined not only by the elasticity of product demand but also
the elasticity of labor supply.
To provide intuition for Proposition 1, we illustrate the double markdown and
double markup in Figure 1. Figures 1a-1b focus on the markdown of wages. In
Figure 1a, there is no product market power (ε = 0), so MRPL and the value of
MPL are identical and there is no markup. In this case, the only markdown of the
wage is the usual markdown,(1 +θ)−^1 , and the optimal employment and wage are
given by(L 0 ,W 0 ). In Figure 1b, there is product market power (ε > 0 ), generating a
wedge between MRPL and the value of MPL whose size is determined by the inverse
markup. As a result of this wedge, MRPL intersects MCL at lower labor and wage
levels(L 1 ,W 1 ). Thus, we see that the wage is marked down further below the value
of MPL if there is product market power.
Figures 1c-1d provide an analogous illustration of the double markup of prices.
In Figure 1c, there is no labor market power (θ = 0), so MCL and the wage are

```
20
```

identical and the only markup is(1−ε)−^1. In Figure 1d, there is labor market power
(θ > 0 ), generating a wedge between MCL and the wage whose size is determined by
the inverse markdown, leading to an additional markup relative to the wage.
We now extend the double market power results from Proposition 1 to the case of
a Leontief production function in which labor and materials are perfect complements,
following equation (5). Under perfect complementarity, optimal intermediate mate-
rials will adjust in response to a change in labor, resulting in an extra term in the
marginal cost that accounts for the price of and returns to intermediate materials:

```
(1| −ε)×{zPjtMPLjt}
MRPLjt
```
```
= (1 +| θ{z)×Wjt}
MCLjt
```
```
+ βpM
M
```
```
MPLjt
| {z }
Leontief adjustment
```
Accounting for the Leontief adjustment in the first-order condition, we have the fol-
lowing:

Proposition 2.The optimal wage and price satisfy,

```
Wjt =
```
```
zmarkdown}| {
(1 +θ)−^1 ×
```
```
inverse markupz }| {
| {z (1−ε) }
double markdown
```
```
× P|jtMPL{z jt}
value of MPL
```
```
− (1 +θ)−^1 ×βpM
M
```
```
MPLjt
| {z }
Leontief adjustment to wage
```
#### (19)

```
Pjt =
```
```
zmarkup}| {
(1−ε)−^1 ×
```
```
inverse markdownz }| {
| {z (1 +θ) }
double markup
```
#### ×

```
Wjt
|MPL{zjt}
prod.-adjusted wage
```
```
+ (1−ε)−^1 ×
pM
| {z βM}
Leontief adjustment to price
```
#### (20)

When interpreting Propositions 1 and 2, it is useful to observe that our assump-
tions give constant labor supply and product demand elasticities across firms within
the construction sector. Allowing for heterogeneous labor supply or product demand
elasticities would be economically interesting but make identification difficult. For
example, such an extension may allow markups and markdowns to vary across firms
and potentially be correlated. This could have important implications for analyses
of misallocation: If the firms with greater markups also have greater markdowns,
misallocation may be amplified.

#### 21


```
MCL
```
```
Wage
```
```
MRPLε= 0 = P × MPL
```
```
Markdown
W 0
```
```
L 0
Labor
```
```
Wage, Marginal Cost or Revenue
```
```
(a) Markdown without Product Market Power
```
```
MRPLε> 0
```
```
MCL
```
```
Wage
```
```
P×MPL
InverseMarkup
```
```
MarkdownDouble
Markdown
W 1
```
```
L 1
Labor
```
```
Wage, Marginal Cost or Revenue
```
```
(b) Markdown with Product Market Power
```
```
Price
```
```
MCL
MPL=
```
```
W
MPL
```
```
MRPL
MPL Markup
```
```
P 0
```
```
L 0
Labor
```
```
Price or Marginal Cost
```
```
(c) Markup without Labor Market Power
```
```
Price
```
```
W
MPL
```
```
MCL
MPL
MRPL
MPL Markup
```
```
MarkdownInverse
```
```
DoubleMarkup
```
```
P 1
```
```
L 1
Labor
```
```
Price or Marginal Cost
```
```
(d) Markup with Labor Market Power
Figure 1: Visualizing the Double Markdown and Double Markup
```
Notes: This figure visualizes how wages are marked down and prices are marked up due to the inter-
action between labor and product market power. It is constructed by simulating the solution to the
firm’s problem, omitting the procurement auctions. For simplicity, we parameterize the production
function asQjt= ΦjtLjt, although the results in the text hold for more general production functions.
In subfigures a-b, the curve labeled Wage is the inverse labor supply curve, and the marginal cost of
labor curve is related to the wage curve by MCL= (1 +θ)×Wage. The curve labeled P×MPL is the
value of MPL, which is related to the MRPL by MRPL= (1−ε)×P×MPL. In subfigures c-d, the
curve labeled Price is the inverse product demand curve, and the productivity-adjusted MRPL curve
is related to the price curve byMRPLMPL = (1−ε)×Price. The curve labeledMPLW is the productivity-
adjusted wage, which is related to the productivity-adjusted MCL byMCLMPL= (1 +θ)×MPLW.

#### 22


### 3.2 Expected Impacts of Changes in Market Power

We showed, in Proposition 1, that the presence of double market power matters for
both the total markdown of the wage and the total markup of the price. A natural
question is whether and how the presence of double market power affects the expected
impact of an increase in labor market power or an increase in product market power.
To analyze this question, we need to be able to isolate the impact of a change in
market power in a given market, all other things being equal.
At first glance, it may seem that the impact of product (or labor) market power
on prices (or wages) can be studied by simply changingε(orθ) in equation (18) (or
17), holding all other terms fixed. However, such an approach would give a misleading
answer. An increase inεhas two distinct impacts: It both reduces the level of demand
the firm is facing at any given price (a level effect, reflected by a behavioral response in
the wage and MPL terms in equation 18), and it increases the profitability of pricing
above marginal cost, since demand becomes less sensitive to price changes (a market
power effect, changing the markup term in equation 18). Similarly, an increase in
θ reduces the supply of labor the firm is facing at any given wage (a level effect,
reflected by a behavioral response in the price and MPL terms in equation 17), and it
raises the gains from marking down wages, since labor supply becomes less sensitive
to wage changes (a market power effect, changing the markdown term in equation
17). Thus, increasingε(orθ) is not the appropriate way to study a ceteris paribus
increase in product (or labor) market power.
Instead, we will increase market power in the labor (or product) market by per-
forming a compensated rotation of the labor supply (or product demand) curve. The
compensated rotation eliminates the level effect, and thus isolates the impact of a
change in market power in a given market, all other things being equal.^21 In the
labor market, this is done by increasing the inverse labor supply elasticity from an
initial valueθInitto a higher valueθNew, while making sure that labor supply at the
initial wage is the same atθNewas it was atθInit (by changing the location param-
eter in labor supplyU). Similarly, the compensated rotation in the product market

(^21) Our compensated rotation is closely related to Slutsky’s definition of the substitution effect in
demand analysis, which is defined with respect to the (hypothetical) income compensation that
ensures initial consumption is still feasible after a price increase.

#### 23


increases the inverse product demand elasticity from an initial valueεInitto a higher
valueεNew, while ensuring that product demand at the initial price is identical atεNew
as it was atεInit(by changing the location parameter in product demandpH).
In Figures 2a-2b, we use the compensated rotation to show the expected impact
of an increase in labor market power and how it depends on the presence or absence
of product market power.^22 The initial inverse labor supply elasticity isθInit > 0 ,
initial employment isLInit, and initial wage isWInit. In Figure 2a, product demand
is perfectly elastic (ε= 0). When the inverse labor supply curve rotates from the
initial curve labeled WageInit(corresponding toθInit) to the less elastic curve labeled
WageNew(corresponding toθNew), the corresponding marginal cost of labor curve rises
from the initial curve labeled MCLInitto the new curve labeled MCLNewthrough the
relationship MCL= (1 +θ)×Wage. Since the first-order condition equates MRPL
and MCL, and MCL is higher for all values of labor as labor market power increases,
it follows that the firm finds it profitable to reduce labor. Since the wage curve is
upward sloping, a reduction in labor reduces the wage.
In Figure 2b, we perform exactly the same analysis as in Figure 2a, except that the
firm now has product market power. To introduce product market power, we rotate
the product demand curve by increasingεfrom zero to a positive value, and then
change the location parameterpHsuch that the initial optimum is identical to Figure
2a. Next, we rotate the labor supply curve to increase labor market power. The
expected impact of increased labor market power is qualitatively similar to Figure
2a: the MCL rises at all values of labor, so MRPL and MCL are equalized by a
smaller choice of labor and wages. However, in contrast to Figure 2a, the output
price rises as output declines in Figure 2b due toε > 0 , so the MRPL is higher at the
new optimal choice of labor in Figure 2b.
While thequalitativeeffects of increased labor market power are similar in Figures
2a and 2b, themagnitudeof the expected decrease in labor and wages is stronger in
Figure 2a due to the absence of product market power. The intuition for this result
is straightforward: In response to an increase in labor market power, the firm wants
to lower the wage it pays by reducing employment and, thereby, output. However,

(^22) The graphical results in Figures 2a-2b are accompanied by formal results in Online Appendix
D.

#### 24


the firm will choose to reduce employment and output less if it is facing downward-
sloping demand (ε > 0 ), as lower output increases the price it can charge and, thus,
the marginal revenue product of labor. By contrast, in Figure 2a, the output price
remains constant as output falls, giving the firm no product market power to exploit,
and a greater reduction in labor is required in order for MRPL and MCL to be
equalized, leading to a greater decline in the wage.
In Figures 2c-2d, we use the compensated rotation to show the expected impact of
an increase in product market power and how it depends on the presence or absence of
labor market power. The initial inverse product demand elasticity isεInit> 0 , initial
employment isLInit, and initial price isPInit. In Figure 2c, labor supply is perfectly
elastic (θ = 0). When the inverse product demand curve rotates from the initial
curve labeled PriceInit(corresponding toεInit) to the less elastic curve labeled PriceNew
(corresponding toεNew), the corresponding productivity-adjusted MRPL curve falls
from the initial curve labeledMRPLMPLInitto the new curve labeledMRPLMPLNew through the
relationshipMRPLMPL = (1−ε)×Price. Since the first-order condition equates MRPL and
MCL, and MRPL is lower for all values of labor as product market power increases,
it follows that the firm finds it profitable to reduce labor. Since the price curve is
downward sloping, a reduction in labor raises the price.
In Figure 2d, we perform exactly the same analysis as in Figure 2c, except that
the firm now has labor market power. To introduce labor market power, we rotate
the labor supply curve by increasingθfrom zero to a positive value, and then change
the location parameterU such that the initial optimum is identical to Figure 2c.
Next, we rotate the product demand curve to increase product market power. The
expected impact of increased product market power is qualitatively similar to Figure
2c: the MRPL falls at all values of labor, so MRPL and MCL are equalized by a
smaller choice of labor and higher prices. However, in contrast to Figure 2c, the wage
falls as output declines in Figure 2d due toθ > 0 , so the MCL is lower at the new
optimal choice of labor in Figure 2d.
While thequalitative effects of increased product market power are similar in
Figures 2c and 2d, themagnitudeof the expected decrease in labor and increase in
price relative to the initial optimum is stronger in Figure 2c due to the absence of labor
market power. The intuition for this result is straightforward: if the firm experiences

#### 25


an increase in product market power, it wants to increase the price it charges by
reducing output and, thereby, employment. However, the firm will choose to reduce
output and employment less if it is facing upward-sloping labor supply (θ > 0 ), as
lower employment decreases the wage it has to pay and, thus, the marginal cost of
labor. By contrast, in Figure 2c, the wage remains constant as employment falls,
giving the firm no labor market power to exploit, and a greater reduction in output is
required in order for MRPL and MCL to be equalized, leading to a greater increase
in prices.

## 4 Data and Descriptive Evidence

### 4.1 Data Sources, Key Variables, and Sample Selection

Our empirical analyses are based on a matched employer-employee panel data set for
the period 2001-2015. The data set is formed by first linking business tax returns to
worker-level tax returns, then merging this linked data set with procurement auction
records.

Tax returns for firms and workers. Our business tax return data include balance
sheet and other information from Forms 1120 (C-corporations), 1120S (S-corporations),
and 1065 (partnerships). We link the business tax returns to Form W-2 (direct
employee) and 1099 (independent contractor) worker-level tax returns, defining the
highest-paying firm in a given year as the worker’s primary employer. Our baseline set
of workers consists of prime-aged W-2 employees who are full-time equivalent (FTE)
workers, by which we mean that their annual earnings from the primary employer
are greater than the annualized full-time minimum wage in the year. Because firms
sometimes use independent contractors, we also consider a broader measure of the
workforce that includes any FTE independent contractors from Form 1099.^23

(^23) In Panel D of Online Appendix Table A.3, we show that the labor supply elasticity estimates do
not materially change if we include or exclude independent contractors from the estimation sample.

#### 26


```
MCL MCLInit
New
```
```
WageInit
```
```
WageNew
```
```
MRPLε= 0
```
```
WεN=e 0 w
```
```
WεN>e 0 w
```
```
WInit
```
```
LεN=e 0 w LεN>e 0 w LInit
Labor
```
```
Wage, Marginal Cost or Revenue
```
(a) Change in Labor Market Power
without Product Market Power

```
MCL MCLInit
New
```
```
WageInit
```
```
WageNew
```
```
MRPLε> 0
```
```
WεN=e 0 w
```
```
WεN>e 0 w
```
```
WInit
```
```
LεN=e 0 w LεN>e 0 w LInit
Labor
```
```
Wage, Marginal Cost or Revenue
```
```
(b) Change in Labor Market Power
with Product Market Power
```
```
MRMPPLLInit
MRMPPLLNew
```
```
PriceInit
```
```
PriceNew
```
```
MCLθ= 0
MPL
```
```
PθN=e 0 w
PθN>e 0 w
PInit
```
```
LθN=e 0 w LθN>e 0 w LInit
Labor
```
```
Price, Marginal Cost or Revenue
```
(c) Change in Product Market Power
without Labor Market Power

```
MRMPPLLInit
MRMPPLLNew
```
```
PriceInit
```
```
PriceNew
```
```
MCLθ> 0
MPL
```
```
PθN=e 0 w
PθN>e 0 w
PInit
```
```
LθN=e 0 w LθN>e 0 w LInit
Labor
```
```
Price, Marginal Cost or Revenue
```
```
(d) Change in Product Market Power
with Labor Market Power
Figure 2: Expected Impacts of Changes in Market Power
```
Notes: Subfigures a-b present the expected impacts of increasing labor market power, while sub-
figures c-d present the expected impacts of increasing product market power. For simplicity, we
parameterize the production function asQjt= ΦjtLjt, although the results in the text hold for
more general production functions. In both subfigures a-b, we consider the compensated rotation
of the Wage curve (i.e. the inverse labor supply curve) around the initial choices(LInit,WInit). In
subfigures a-b, we denote the MRPL curve (in blue) by MRPLε> 0 for the case with product market
power and MRPLε=0for the case without product market power. In both subfigures c-d, we consider
the compensated rotation of the Price curve (i.e. the inverse product demand curve) around the
initial choices(LInit,PInit). In subfigures c-d, we denote the productivity-adjusted MCL curve (in
blue) byMCLMPLθ>^0 for the case with labor market power andMCLMPLθ=0for the case without labor market
power.

```
27
```

The key variables that we draw from the business tax returns are revenues, inter-
mediate input expenditures, profits, and NAICS industry codes.^24 Revenues include
those from business operations, excluding non-business-operation revenues such as
dividends and capital gains. We follow de Loecker et al. (2020) in measuring inter-
mediate input expenditures by the cost of goods sold, which includes variable costs
associated with intermediate goods, transportation, and storage while excluding costs
associated with overhead, durables, and labor.^25 Our measure of profits is earnings
before interest, taxes, and depreciation (EBITD), which we construct following Kline
et al. (2019).
The key variables we draw from worker-level tax returns are the number of employ-
ees in the firm and their earnings for the primary sample of workers. We also consider
the number of employees and earnings when including independent contractors in the
sample. Using the panel structure of the employer-employee data, we consider three
measures of the earnings of the workers: mean earnings among all workers currently
employed at the firm; mean earnings among stayers, which we define as workers em-
ployed at the same firm consistently fromnyears prior to the procurement auction
untilnyears after; and mean earnings of new hires at the firm.

Information on procurement auctions. We obtain the new data set on pro-
curement auctions from Bid Express (BidX.com), a service that facilitates online
bidding for a number of states; state-specific Department of Transportation (DOT)
websites; and submitting FOIA requests to state governments. The procurement
projects broadly involve the construction and landscaping of local roads, bridges, and
highways. Observations in this data set are at the auction-firm level, with variables
on firm’s name and address as well as the firm’s bid and the auction date. In total,
we recover the auction records from the DOTs of 28 states.^26 Construction firms
bid in auctions in other states, so our auction sample includes construction firms

(^24) Detailed information about the variables in the tax data is provided in Online Data Supplement
S.3. 25
A potential concern is that firms in some industries (manufacturing and mining) include labor
costs in the cost of goods sold. However, we consider firms in the construction industry, which do
not (IRS Pub. 334). 26
Online Appendix Table A.1 provides a summary of the procurement auction data sources. Online
Data Supplement S.1 provides step-by-step instructions on obtaining and preparing the auction
records.
28


from nearly every state.^27 Our data show that these 28 DOTs allocated $383 billion
through 155,768 distinct auctions involving 16,697 bidders in 2010. There are more
auctions than firms, and the same firms may compete in multiple auctions. One po-
tential concern is that this results in collusion to achieve bid revenues greater than
those predicted by our first-price sealed-bid auction model. In Online Appendix Fig-
ure A.1, we apply the collusion test of Chassang et al. (2022) to each of the 28 states
in our data separately, finding no evidence of collusion in any state.
The DOTs are responsible for determining the nature of the project, including
the blueprints, a detailed list of tasks to be performed or items to be constructed,
quality guidelines and standards, and expected or required time to completion. This
information is publicly available in the solicitation for bidders posted by each DOT.
The awarding of a contract has two steps. The first step is qualification. In
order to submit a bid, a firm must be pre-qualified by the DOT, which considers
three aspects of the firm.^28 First, the DOT reviews financial statements (containing
information about revenues, assets, and liabilities) to determine the firm’s ability
to potentially complete the project. Second, the DOT considers the experience of
the firm by reviewing information on previously completed projects and its current
equipment and facilities. Third, the DOT may also deny pre-qualification if the firm
has been found engaging in bid rigging or if it has systematically failed to comply
with labor or safety regulations. Once approved, the firm is awarded a license to bid.
The second step is the sealed-bid auction, in which a qualified firm submits a bid
without observing the bids of the other firms. Nearly all the auctions we consider are
first-price auctions, where the procurement contract is awarded to the bidder with
the lowest price.^29

(^27) In our data from BidX, we observe the firm’s business address as well as the address of the
procurement project. In the BidX data, we find that 80% of bids are placed in auctions in the firm’s
home state and 21% of bids are placed in auctions in the firm’s home commuting zone. In Panel E
of Online Appendix Table A.3, we provide robustness checks in which we control for auction-specific
or commuting zone-specific interactions in the effects, finding little sensitivity of the estimates. 28
Each state provides a detailed set of instructions for pre-qualification to bid, which is pub-
licly available. For example, for Illinois, see https://idot.illinois.gov/assets/uploads/files/doing-
business/laws-&-rules/highways/construction/rules.pdf.
(^29) A small fraction of the auctions consider dimensions in addition to price. One example is
California, where 4% of the auctions consider both price and expected time to completion (Lewis
and Bajari, 2011). Institutional details on procurement auctions with a secondary dimension of

#### 29


We observe the bid of each firm for a given auction, not only the winner.^30 In
the empirical applications discussed below, we will focus on recipients of procurement
contracts who win a procurement auction for the first time att. The mean pro-
curement revenues for these first-time auction winners is $2.7 million. We compare
them to non-recipients that had never won an auction beforetand placed a bid in
the auction attbut lost. These sample restrictions are useful as they ensure that
neither winners nor losers of auctions experience a procurement demand shock in the
pre-period.

Merged data from tax returns and procurement auctions. To merge the
auction data to the tax records, we use a fuzzy matching approach based on the
firm’s name and location. For six states, we were able to not only obtain the name
and address but also the federal Employer Identification Number (EIN) of the firm,
allowing us to perform an exact match to tax records. We trained the algorithm
on these six states before applying it to the other 22 states.^31 We also provide an
out-of-sample validation analysis in which we test the performance of the matching
algorithm on publicly available pension data tax filings, finding that it performs well.
Furthermore, we verify that our labor supply elasticity estimate does not change
materially if we restrict the sample to the six states matched on EIN.
Online Appendix Table A.2 displays the sample sizes of firms and workers that
participate in auctions in the year 2010. In 2010, our sample includes almost 8,000
unique firms that generate over $150 billion in annual revenues and employ about
360,000 full-time workers. Nearly all the firms are recorded as being in the construc-
tion industry. As a share of the national construction industry (as recorded in the
2010 tax records), our sample of 8,000 firms accounts for 12% of sales, 12% of em-
ployment, 10% of EBITD, 12% of intermediate input expenditures, and 13% of wage

bidding are provided in Online Appendix E.4. 30
In the event that the firm that wins the procurement contract hires a contractor to complete the
work, this will be captured in our measure of labor that includes contractors from Form 1099. In
the event that the firm that wins the procurement contract passes the contract to a subcontractor,
the completed work is sold to the primary contractor as intermediate inputs and thus captured in
our intermediate inputs measure. Institutional details on the role of subcontracting in procurements
are provided in Online Appendix E.5. 31
Online Data Supplement S.2 explains how we trained and validated the linking algorithm used
to merge the auction records to the tax returns.

#### 30


payments. In a robustness check discussed in Section 6.1, we provide estimates for
the entire construction industry, not only those firms that participate in procurement
auctions.

### 4.2 Impacts of Winning a Procurement Auction

Before taking the model to the data, it is useful to describe how employment and
wages change if a firm wins a procurement contract. To estimate these impacts, we run
regression models which compare firms that are first-time winners of a procurement
auction in yeart(Djt= 1) to firms that bid in the auction in yeartbut lose (Djt= 0),
before and after the auction. Letedenote an event time relative totandyjt+edenote
an outcome for firmj. For each event time e =− 4 ,..., 4 , our baseline regression
model can be expressed as,

```
yjt+e=
```
#### X

```
e′̸= ̄e
```
(^1) e′=eμte′
| {z }
event time fixed effect

#### +

#### X

```
j′
```
(^1) j′=jψj′t
| {z }
firm fixed effect

#### +

#### X

```
e′̸= ̄e
```
(^1) e′=eDjtλte′
| {z }
treatment status by event time
+ |{z}εjte
residual

#### , (21)

whereλteis the impact of winning a procurement contract on the outcome variable
for a particular pair(e,t)ande ̄=− 2 is the omitted event time.^32 The inclusion of
firm fixed effects controls for any differences between winners and losers of auctions
in their time-invariant characteristics (for example, fixed differences in composition
of the workforce, amenities, or productivity), while the inclusion of event time fixed
effects controls for any aggregate shocks experienced during this time interval.
Although the inclusion of fixed effects adjusts for differences across firms in levels,
one could still be concerned that the auction winners in the treated group would
have experienced different changes in outcomes over time than losers in the control
group even in the absence of winning the auction. In particular, a firm is likely to
bid less (and, thus, more likely to win the auction) if it experiences an increase in its
productivity. To address this issue, it may be useful to restrict the sample used in
estimating equation (21) to the control group of firms that make similar bids to the
treated firms.

(^32) We will be estimatingλtefor alltandeand then average acrosst, using the delta method to
compute standard errors (which are clustered at the firm leveljto account for serial correlation).
By doing so, we avoid the problem pointed out by Callaway and Sant’Anna (2020) that cohorts can
be negatively weighted in pooled cohort two-way fixed-effect estimators of treatment effects.
31


To be concrete, define the loss margin asτjt≡(Zjt−Z∗ι)/Zι∗for a firmjthat bids
in auctionιat timet, whereZι∗is the winning bid in auctionι. When estimating
equation (21), we restrict the sample to exclude the firms with large values ofτjt.
On the one hand, if we restrict the estimation sample so that the control group only
includes firms with sufficiently small values ofτjt, equation (21) can be interpreted
as a local regression discontinuity design (RDD) that compares the firms that win
the auction to the firms that almost win the auction.^33 On the other hand, if we
include all auction losers in the control group (no restriction onτjt), then equation
(21) becomes a difference-in-differences (DiD) design, comparing growth over time
for the winners and losers of auctions. Empirically, restricting the control group to
almost-winners (smallτjtonly) tends to have little effect on the point estimates, but
sometimes leads to noticeably less precise estimates because the sample size becomes
smaller.

Winning a procurement auction. We begin by describing the treatment asso-
ciated with winning the procurement auction. Online Appendix Figure A.2 presents
DiD and RDD estimates from equation (21) for two such outcomes from the procure-
ment auctions: Subfigure a plots the share of firms that are first-time winners of a
procurement auction, and subfigure b plots the share of firms that win a procurement
auction in the relative year.
Mechanically, both treated and control units have no wins prior toe= 0, so the
effect is zero fore < 0 for both subfigures. Whene = 0, the treated group wins
a contract for the first time and the control group bids for a contract but loses, so
the treatment effect is mechanically one for both subfigures. The mean winnings for
first-time winners whene= 0are $2.7 million. Fore > 0 in subfigure a, we see that
some control units win auctions, with around 15% of control units winning their first
auction whene = 1and around 5% whene = 4. This means the losers continue
to bid and partially catch up to the winners in terms of the probability of having
won an auction. However, as shown in subfigure b, treated units are somewhat more
likely than control units to win any procurement auction one > 0. Treated firms are

(^33) Formally, the choice ofτjtplays the same role as the choice of bandwidth when using the uniform
kernel implementation of RDD. In the empirical analysis, we consider a range of different choices of
τjt.

#### 32


around 13-21% more likely to win at least one auction ate= 1and around 8-14%
more likely ate= 4.
Taken together, the evidence in Online Appendix Figure A.2 suggests that winning
the auction leads to a sharp and instantaneous increase in revenue, and that auction
winning is only weakly positively correlated over time. This implies that we can
reliably infer short- and long-run responses to winning a procurement contract by
comparing the effect estimates across different event times.

Impacts on employment and wages across time. In Table 1, we summarize the
overall impacts of winning a procurement auction on employment and earnings. To
do so, we aggregate the event-specific effects estimates into a post-treatment period.
This is done by averaging the event-specific estimates across event timese∈{ 0 , 1 , 2 }.
We compare the DiD design (no restriction onτjt) and three specifications of the
RDD design (excluding firms withτjtabove 0.3, 0.2, and 0.1, respectively).
In the first panel of Table 1, we find that the number of employees in the firm
increases, on average, by 7-8%. The DiD and RDD estimates for earnings and employ-
ment are economically similar and never statistically distinguishable. In the second
panel of Table 1, we consider the earnings for all workers in the sample. We find that,
on average, winning a procurement auction leads to about a 2% increase in earnings
per worker in the post-treatment period when using DiD or RDD approaches. Fur-
thermore, both the DiD and RDD estimates show no evidence of differential trends in
the wages and employment of the treated and control groups prior to the procurement
auction.
The evidence suggesting that winning a procurement auction causes the firm to
bid up wages and hire more workers is at odds with the textbook model in which
the labor supply curve facing the firm is perfectly elastic. Instead, it is consistent
with the notion that firms face upward-sloping labor supply curves and, therefore,
have wage-setting power in the labor market. Indeed, as shown formally in the next
section, we can recover the slope of the firm-specific labor supply curve, and thus
the degree of imperfect competition in the labor market, from the employment and
earnings impacts of winning a procurement auction. The estimated 2% increase in
earnings per worker relative to a 7-8% increase in employment is consistent with a
firm-specific labor supply elasticity of 3.5-4.1.

```
33
```

In the above estimation, we consider all of the workers in our sample. In the third
panel of Table 1, we instead present the average impacts for all stayers in the firm,
defined as the sample of employees who stay in the same firm before and after the
auction announcement. We find approximately the same 2% average gain in earnings
when restricting the sample to stayers only. It is reassuring to find that the estimated
effect on earnings barely changes when restricting the sample to stayers.

Heterogeneity across time. A natural question is how the effect estimates on
earnings and employment vary over time. For example, adjustment costs may lead to
smaller responses in the shorter-run than the longer-run. In Online Appendix Figure
A.3, we examine this by comparing the effect estimates across event times.
In the year that the winner of the procurement auction is announced (e = 0),
employment increases by around 6% in the winning firm (Appendix Figure A.3a).
At the same time, earnings per worker increase by about 1.5% (Appendix Figure
A.3b). Over time, the estimates tend to grow modestly after the year of winning, and
remain relatively stable in subsequent years. By event year 2, the gain in employment
is around 8% and the gain in earnings per worker is more than 2%.
Appendix Figure A.3 also reports effect estimates for each event time in the pre-
period (e < 0 ), offering placebo tests for the null hypothesis that winning had no
effect prior to the announcement of the winner. For none of these placebo tests are
we able to reject the null hypothesis of no effect in the pre-period at the 5% level of
significance.

Heterogeneity across workers. We now examine in greater detail the hetero-
geneity in earnings and employment impacts across workers, allowing us to assess the
sensitivity of the key findings in Table 1.
In the baseline stayers estimates in Table 1, we defined stayers as workers employed
by the same firm during event times {-2,...,2}. In Online Appendix Figure A.4a, we
vary the definition of a stayer by expanding and contracting the stayer window, always
finding an increase in earnings of around 2% across definitions.
In Online Appendix Figure A.4b, we instead restrict the sample to workers who
have been employed at the firm for a certain number of years prior to the auction
(“tenure”). If the worker moves to a new firm, we use the earnings at the new firm as

#### 34


their outcome. We find a consistent 2% increase in earnings per worker, regardless of
tenure.
Our baseline sample of stayers consists of prime-aged W-2 employees who are FTE
workers, by which we mean that their annual earnings from the primary employer
are greater than the annualized full-time minimum wage in the year. In Online
Appendix Figure A.4c, we investigate the sensitivity of the estimated earnings effects
to changing the FTE definition. When we strengthen the FTE restriction up to 150%
of the baseline definition, we still find about a 2% increase in earnings per worker.
In addition to keeping worker composition fixed by focusing on stayer or tenured
samples, it is also possible to directly investigate the effect on the mean earnings of
new hires after they are hired in the new firm. We do this by applying the DiD and
RDD estimators of equation (21) to a panel of the mean earnings paid to new hires in
a given year. As shown in Online Appendix Table A.4, we find about a 1-2% increase
in the earnings of new hires in the post-treatment period for the winning firms. These
estimates are comparable to the earnings effects for incumbents, and the differences
across these groups are never statistically different. However, the statistical precision
is limited due to the small number of new hires, so we are reluctant to make strong
claims about the exact impact on new hires.
In principle, it is also possible to directly investigate composition changes for new
hires by using the prior earnings of new hires at their previous firms as a proxy for
worker quality.^34 As shown in Online Appendix Table A.5, both our DiD and RDD
estimates find that worker quality does not significantly change in the post-treatment
period for the winning firms. However, the standard errors are too large to rule out
meaningful changes in worker composition.

## 5 Identification of Model Parameters

We now show how the model laid out in Section 2 can be taken to the data described
in Section 4.

(^34) In theory, the wages in the previous firm reflect both worker quality and the amenities the firm
offers. Thus, the earnings in the previous firm are an imperfect proxy for worker quality.

#### 35


```
Design: DiD RDD
Proximity: Any 0.3 0.2 0.1
Log Employment
Impact: Before Treatment -0.015 -0.018 -0.024 -0.021
(0.016) (0.017) (0.017) (0.020)
Impact: After Treatment 0.083 0.079 0.079 0.065
(0.019) (0.020) (0.021) (0.025)
Unique Firms (ate= 0) 6,033 5,246 4,865 4,274
Log Earnings per Worker: All Workers
Impact: Before Treatment 0.002 0.002 0.001 -0.002
(0.007) (0.007) (0.008) (0.009)
Impact: After Treatment 0.020 0.022 0.020 0.019
(0.008) (0.008) (0.009) (0.010)
Unique Firms (ate= 0) 6,033 5,246 4,865 4,274
Log Earnings per Worker: Stayers
Impact: Before Treatment 0.003 0.002 0.001 0.002
(0.006) (0.006) (0.006) (0.007)
Impact: After Treatment 0.023 0.023 0.021 0.019
(0.006) (0.006) (0.007) (0.007)
Unique Firms (ate= 0) 5,492 4,784 4,453 3,929
```
```
Table 1: Impacts of Winning a Procurement Auction
```
Notes: This table presents estimates of the impacts of winning a procurement auction on employment
and earnings per worker in the post-treatment and pre-treatment time periods. Event time ̄e=− 2 is
the omitted event time. The pre-treatment and post-treatment periods are formed by averaging the
event-specific estimates across event timese∈{− 4 ,− 3 }ande∈{ 0 , 1 , 2 }, respectively. Employment
and earnings per worker are measured in log units. Earnings per worker are either measured for
the sample of all workers in the firm or the sample of stayers, where stayers are defined as workers
employed by the same firm duringe∈ {− 2 ,..., 2 }. Proximity refers to the largest value ofτjt
permitted in the sample. Additional specifications are provided in Online Appendix Table A.3.

### 5.1 Labor Supply Elasticity

Recall from equation (3) that the inverse labor supply curve is given bywjt=θℓjt+ujt,
where we decompose the unobservable determinants of labor supply asujt =ψj+

```
36
```

ξt+νjt. Our goal is to identify the labor supply elasticity, 1 /θ.
To see why this is challenging, consider a cross-sectional regression ofwjtonℓjt.
This regression may result in a biased estimate ofθbecause bothwjtandℓjtdepend
on time-invariant firm-specific determinants of labor supply (ψj). To address this
issue, one might consider eliminatingψj by taking differences over time, denoted
by∆. Furthermore, the aggregate labor supply shocks (∆ξt) can be eliminated by
including time fixed effects in this regression.^35 However, the resulting estimates ofθ
may still be biased due to firm-specific unobserved labor supply shocks (∆νjt).
To address the possibility that∆νjtco-varies with∆wjtand∆ℓjt, we take advan-
tage of the data on procurement auctions. Given this data, one possible identifying
assumption is that∆νjtdoes not co-vary with the probability of winning an auction,
motivating the following DiD estimand:

Proposition 3. Under the exogeneity assumption that the auction winner Djt is
independent of the labor supply shock∆νjt, and the rank condition Cov[∆ℓjt,Djt]̸= 0,

```
θDiD≡CovCov[∆[∆wℓjt,Djt]
jt,Djt]
```
```
=θ.
```
Proof. By equation (4),

```
θDiD=Cov[θ∆ℓjt,Djt]
|Cov[∆{zℓjt,Djt]}
=θ
```
```
+Cov[∆νjt,Djt]
|Cov[∆{zℓjt,Djt]}
=0
```
```
+Cov[∆ξt,Djt]
|Cov[∆{zℓjt,Djt}]
=0
```
```
=θ,
```
where the second term on the right-hand side is zero becauseDjtis independent of
∆νjt, and the third term is zero because∆ξtis the same for all firms in each period
t.

The identifying assumption of Proposition 3 may hold if firm-specific labor supply
shocks are unpredictable at the time of bidding, and therefore do not influence the
probability of winning. In our context, there is typically a time delay between the
procurement solicitation for bids and the commencement of production on the gov-
ernment project. If the firm cannot predict its firm-specific labor supply shock from

(^35) In a specification check presented in Section 6.1, we fully interact the event time with a local
market identifier, which allows the aggregate labor supply shocks to vary across firms in different
local markets.
37


the time of the procurement solicitation to the time that it actually needs to hire
workers,∆νjtshould be independent ofZjtand therefore also independent ofDjt.
It is useful to observe what is and is not restricted under Proposition 3. First of
all, the proposition does not impose any additional restrictions on the relationships
among the variables(Zjt,Djt,φjt,ψj,ξt). In other words, it does not restrict how bids,
TFP, time-invariant firm-specific labor supply determinants, and market-wide labor
supply shocks co-vary. Second, the proposition permits Var[∆νjt]> 0 , so it allows
for firm-specific labor supply shocks. This is less restrictive than much of the existing
literature on identifying the labor supply curve, which requires that firm-specific labor
supply determinants are constant within the estimation window (see the discussion
by Lamadon et al. 2022). Third, since both the control and treated firms participate
in the auction, the proposition still holds if bidders choose to participate due to
(expectations over) firm-specific labor supply shocks. For example, both the treated
and control firms had to qualify to bid in the auctions, which may, in part, depend
on the amenities they offer, as discussed in Section 4.1. However, any qualification
criteria apply to the treated and control firms, so they should not generate differences
in amenities between winning and losing auction bidders.
A key restriction in the assumptions underlying Proposition 3 is that, even though
both treated and control firms meet the qualifications for bidding, the treated firms
may bid a lower amount because they (expect to) have an increase in labor supply
relative to control firms. To address this concern, we will use the RDD estimator
that compares firms that win the price-only auction to firms that make similar bids
and almost win the auction. If differences in bids reflect differences in∆νjt, then we
would expect firms that make similar bids to also have similar∆νjt, which motivates
the following RDD estimand:

Proposition 4.Consider the ratio of RDD estimators defined by,

```
θRDD(τ)≡EE[∆[∆wℓjt|τjt= 0]−E[∆wjt|^0 < τjt≤τ]
jt|τjt= 0]−E[∆ℓjt|^0 < τjt≤τ]
```
#### ,

whereτspecifies the maximum proximity to the discontinuity and the conditioning on
ιis implicit. Under the rank conditionE[∆ℓjt|τjt= 0]̸= limτ→ 0 +E[∆ℓjt| 0 < τjt≤τ],
limτ→ 0 +θRDD(τ)recoversθ.

#### 38


Proof. Since bids of winners and losers converge asτ→ 0 +,

```
lim
τ→ 0 +
θRDD(τ) =θ+ lim
τ→ 0 +
```
```
E[∆νjt|τjt= 0]−E[∆νjt| 0 < τjt≤τ]
E[∆ℓjt|τjt= 0]−E[∆ℓjt| 0 < τjt≤τ]
=θ,
```
where the second term is zero because, by independence ofDjtand∆νjtconditional
onZjt,E[∆νjt|Djt= 1,Zjt] =E[∆νjt|Djt= 0,Zjt], which impliesE[∆νjt|τjt= 0] =
limτ→ 0 +E[∆νjt| 0 < τjt≤τ].

While the RDD estimand relies on weaker assumptions than the DiD estimand,
one still may be concerned about biases. One possible source of bias is simultaneity:
winning the auction may have a causal impact on the labor supply the firm is facing.
For example, as a result of winning the auction, firms may not only bid up wages to
hire more workers but also purchase or produce better amenities, which may in and
of itself attract more workers. To address this concern, Online Appendix H provides
a sensitivity check where we examine how the key conclusions regarding the labor
supply curve would change if amenities became a greater or smaller share of total
compensation in response to winning a procurement contract.

### 5.2 Firm Technology

Our goal in this subsection is to identify the composite returns to laborρ in the
production function (equation 9). Givenρ, it will be straightforward to recover the
other technology parameters, as discussed below. We do not observe output quantity
Qjt, making it difficult to estimate the production function in equation (9) directly.
Our approach instead makes use of the first-order conditionxjt= κX+ρℓjt+φjt
from equation (11), which shows thatρrelates log intermediate expenditurexjtand
log laborℓjt. The identification challenge is that log TFP,φjt, is an unobserved
determinant of intermediate input expenditures in equation (11), andℓjt depends
directly on TFP, as shown in Online Appendix A.2. Thus, a regression ofxjtonℓjt
will fail to recoverρdue to the correlated unobservableφjt.
To address this identification challenge, we will invert the bidding strategy to
control for TFP. Given the equilibrium bidding strategyZjt=sujt(φjt)from equation
(14), wheresis monotonic in φjtgiven ujt,we can write the inverse equilibrium
bidding strategy asφjt=s−ujt^1 (Zjt). Monotonicity ensures thats−ujt^1 is unique andφjt

#### 39


is pinned down by the bidsZjt, conditional on the amenitiesujt. Given any consistent
estimatorθbofθ, an estimator forujtis

```
bujt=wjt−θlbjt.
```
We then have the following result:

Proposition 5.Consider a regression ofxjtonℓjtcontrolling for(ubjt,Zjt), i.e.,

```
ρb≡Cov[xjt,ℓjt|ubjt,Zjt]
Var[ℓjt|bujt,Zjt]
```
#### . (22)

Given thatθbrecoversθand the rank condition Var[ℓjt|bujt,Zjt]> 0 ,ρbrecoversρ.

Proof. By equation (11),

```
ρb=Cov[ρℓjt,ℓjt|bujt,Zjt]
| Var[ℓjt{z|bujt,Zjt] }
=ρ
```
```
+Cov[φjt,ℓjt|bujt,Zjt]
| Var[ℓjt{z|bujt,Zjt] }
=0
```
```
=ρ,
```
where the second term is zero because Cov[φjt,ℓjt|bujt,Zjt] =Cov[φjt,ℓjt|ujt,φjt]by
the uniqueness ofφjt=s−ujt^1 (Zjt)and thatujtrecoversubjtsinceθbrecoversθ. To see
why the rank condition is expected to hold in our context (and, indeed, we find that
it holds in the data), note that ifε > 0 , thenℓjtdepends directly onDjtin the firm’s
problem, all else equal. From equation (14),Djtdepends not only onujt,φjt, but also
on the realized competitors’ bids in the auction. Competitors’ bids are unknown to
the firm at the time it bids and thus not captured by the optimal bidding function.

In practice, we implement this control function approach by controlling for auction
fixed effects as well as third-order polynomials inlogZjtandbujt. The results do not
change materially if we increase the polynomial order.

### 5.3 Product Demand Curve

Our goal in this subsection is to identify the elasticity of the product demand curve,
− 1 /ε, introduced in equation (6). To do so, we rely on the first-order conditions for
labor (equation 13) and for intermediate inputs (equation 12) among the firms in the

#### 40


construction industry that do not currently receive procurement contracts (Djt= 0
firms).
Rearranging equation (13) and conditioning on Djt = 0 firms, the first-order
condition for labor implies,
inverse markupz }| {
(1−ε) =

```
inverse markdownz }| {
(1 +θ) sβL
L
```
```
+sM, (23)
```
which allows us to express the inverse price markup in terms of the inverse wage
markdown, the labor share of revenue (sL≡Bjt/Rjt), and the intermediates share of
revenue (sM≡Xjt/Rjt), and the output elasticity of labor (βL).
Rearranging equation (12) and conditioning on Djt = 0 firms, the first-order
condition for intermediate inputs implies,
inverse markupz }| {
(1−ε) =CovVar[r[jtx,xjt|Djt= 0]
jt|Djt= 0]

#### , (24)

Equations (23) and (24) provide two equations in two unknowns,εandβL, allowing
us to simultaneously recoverεandβL.
The above identification argument forεfollows the logic of the markup estimator of
de Loecker et al. (2020) for the case where the production function is Leontief, except
our expression accounts for imperfect competition in the labor market (θ > 0 ). This
shows that the markup estimator of de Loecker et al. (2020) can be easily corrected
for labor market power in the Leontief case using a plug-in estimate ofθ.

### 5.4 Over-identifying Restriction

Above, we demonstrated how(ρ,βL,ε)can be exactly identified. We now show how an
additional moment can be used to over-identify(ρ,βL,ε)and, thus, directly examine
the validity of the model. Among firms that receive procurement contracts, the firm’s
first-order condition in equation (13) implies

```
Λjt=κΛ+ρℓjt+φjt+ejt if Djt= 1. (25)
```
whereΛjt≡ 1 −εεrHjt+ log

```
1+θ
βLBjt+Xjt
```
#### 

andκΛ≡log(1−ε) +log 1 −pHε. The derivation
is provided in Online Appendix A.4. Givenθ, for any candidate values of(βL,ε), we
can construct the left-hand side variable. Furthermore, note that for any candidate

```
41
```

value ofρ, we can rearrange equation (11) to recover log TFP as

```
φbjt(ρ)≡xjt−κX−ρℓjt.
```
We can then construct the covariance betweenℓjtand the left-hand side of equation
(25), which is a moment equation that depends only on the unknown parameters
(ρ,βL,ε), the TFP estimatesφbjt(ρ), and the data. Thus, in addition to equations
(22), (23), and (24), equation (25) gives us a fourth equation that must be satisfied
by the true values of(ρ,βL,ε). In practice, we estimate(ρ,βL,ε)simultaneously in
equations (22), (23), (24), and (25) using GMM, and then check how the estimates
change if we do not use (25).

### 5.5 Identification of Remaining Parameters

We now show how to recoverβK,βM/pM, andpH given that we already knowθ,ρ,
βL, andε. From the definition ofρ, we recoverβKasβK= (ρ−βL)/(1 +θ). From
equation (11), we recoverβM/pMas

```
log(βM/pM) =E[ρℓjt−xjt], (26)
```
where we normalizeE[φjt] = 0without loss of generality. Rearranging equation (12),

```
logpH=E[rjt−(1−ε)xjt|Djt= 0]−(1−ε) log (βM/pM), (27)
```
where we normalizeE[ejt|Djt= 0] = 0without loss of generality.

### 5.6 Rents and Incidence

We now show how to recover the total rents, baseline rents, and the incidence of
procurement on firms and workers, focusing on the sample of firms with procurement
contracts (Djt= 1). From the expressions in Section 2.5 and given that we identified
θabove, we can characterize rents and incidence for workers if we recoverB 0 jtand
B 1 jt, as well as rents and incidence for firms if we recoverπ 0 jtandπ 1 jt, for each(j,t).
For firms withDjt= 1, we observeB 1 jtandπ 1 jt, so the only remaining challenge is
to recoverB 0 jtandπ 0 jt.
To recoverB 0 jtandπ 0 jt, we use the profit-maximizing first-order condition with

#### 42


respect to labor for the case in which the firm loses the procurement contract (d= 0),
which is

```
ρpH(1−ε) Φ^1 jt−εLρ 0 (jt^1 −ε)−^1 = (1 +θ)κUUjtLθ 0 jt+ρβpM
M
```
```
ΦjtLρ 0 −jt^1 , (28)
```
whereκU ≡ ββKL(1 +θ) + 1. The derivation of equation (28) is provided in Online
Appendix A.2. We identify(θ,ρ,ε,pH,βM/pM)above, and recoverUjtusingbujtand
Φjt usingφbjt(ρ). Thus, we can numerically solve equation (28) to obtainL 0 jtfor
each(j,t). GivenL 0 jt, it is straightforward to recoverB 0 jtandπ 0 jtusing the firm’s
constraints (equations 2, 8, 9, 10).

## 6 Estimates of Model Parameters

In this section, we combine the identification arguments in Section 5 with the data
described in Section 4 to estimate the parameters that govern labor supply, firm
technology, and product demand.

### 6.1 Labor Supply Elasticity and Wage Markdown

We now implement the estimatorsθDiDandθRDDdescribed in Section 5.1. For each
of these estimators, the numerator (or denominator) is given by the estimated impact
of winning a procurement auction on log earnings per worker (or log number of
employees). These estimated impacts are reported in the first and fourth columns of
Table 1 for the DiD and RDD estimators, respectively. In Figure 3, we present the
labor supply elasticity, 1 /θ, and the wage markdown relative to the MRPL,(1 +θ)−^1 ,
implied by these estimated impacts.
Figure 3 shows that the estimates of the labor supply elasticity range from 3.5 to
4.1 depending on whether we use the RDD or DiD approach. The labor supply elas-
ticity estimates indicate that, if a US construction firm aims to increase the number
of its employees by 10%, it needs to increase wages by 2.4-2.9%. Our estimates are
broadly comparable to existing work. Lamadon et al. (2022) estimate a labor supply
elasticity of 4.6 and Suárez Serrato and Zidar (2016) estimate a labor supply elastic-
ity of 4.2, while Card et al. (2018) pick 4.0 as the preferred value in their calibration
exercise. A related literature using experimentally-manipulated wage offers for small
tasks or survey experiments typically finds labor supply elasticities ranging from 3.0

```
43
```

to 5.0 (Caldwell and Oehlsen, 2018; Dube et al., 2020; Sokolova and Sorensen, 2021).

Specification checks. We now show that our conclusions about the labor supply
curve are robust to a number of specification checks.
Our model assumes that the labor supply elasticity is the same for all construction
firms. One potential concern is that firms that bid in auctions differ from the rest
of the construction industry. In order to investigate this possibility, we consider the
estimator of Lamadon et al. (2022, LMS), which uses the lagged value-added change
as the instrument in the DiD estimator in equation (21). The LMS estimator can be
justified either if firm-specific unobserved labor supply determinants are fixed over
the estimation window, or if TFP shocks are more persistent than firm-specific labor
supply shocks.^36 Importantly, value-added shocks are defined for all firms in the
construction industry, not only for firms that participate in auctions, so they can be
used to assess the representativeness of the subsample of firms that participate in
auctions. The bars labeled “LMS Design” and “LMS Design, Control CZ” in Online
Appendix Figure A.5 show that, when applying the LMS estimator to the entire
construction industry (with or without controlling for local labor market shocks, as
proxied by commuting zone), the labor supply elasticity and markdown estimates are
nearly the same as our RDD and DiD estimates.
Another potential concern is that, if labor enters the firm slowly over time rather
than immediately when the new wage is posted, the short-run relation between wages
and quantity of labor may understate the labor supply elasticity. Our estimates
in Figure 3 report averages across three event years. Online Appendix Figure A.5
provide estimates separately across event years. We find approximately the same
labor supply elasticity estimate in each event time, suggesting adjustment costs are
relatively unimportant in our setting.
Another challenge when estimating the labor supply curve is skill-upgrading.
Earnings per worker could increase for the winning firm in part because they hire more
productive workers. The results presented in Figure 3 suggest that skill-upgrading is
empirically unimportant for our estimates of the labor supply elasticity: we find little
difference between estimates using stayers versus all workers in the firm. In Online

(^36) Proposition 6 of Online Appendix F.1 provides the formal conditions for identification using the
LMS estimator.
44


```
0
```
```
1
```
```
2
```
```
3
```
```
4
```
```
5
```
```
6
```
```
7
```
```
DiD: All WorkersRDD: All Workers
DiD: Stayers RDD: Stayers
```
```
(a) Labor Supply Elasticity, 1 /θ
```
```
0.5
```
```
0.6
```
```
0.7
```
```
0.8
```
```
0.9
```
```
1.0
```
```
DiD: All WorkersRDD: All Workers
DiD: Stayers RDD: Stayers
```
```
(b) Wage Markdown relative to MRPL,(1 +θ)−^1
Figure 3: Main Estimates of the Labor Supply Elasticity and Wage Markdown
```
Notes: This figure presents the main estimates of the labor supply elasticity, 1 /θ, and wage markdown
relative to MRPL,(1 +θ)−^1. It uses the DiD and RDD estimands defined in Propositions 3 and 4,
respectively. In the estimation, earnings per worker are either measured for the sample of all workers
in the firm or the sample of stayers. The largest proximity permitted in the RDD estimation is 0.1.
Specification details, sample definitions, and sensitivity checks are discussed in the text.

Appendix Figure A.6a, we show that this conclusion is insensitive to the number of
years that the worker is a stayer.
A final specification check is motivated by the potential concern that procurement
contracts might be awarded in local labor markets with worse labor supply shocks,
which could induce a correlation between local aggregate labor supply shocks and
procurement contracts.^37 In a specification check presented in Figure A.5, we fully
interact the event time with a local market identifier, which allows the aggregate labor
supply shocks (ξt) to vary across firms in different markets. We define the set of firms
in the same commuting zone or that bid against each other in the same auction as
belonging to the same market.^38 We find similar labor supply elasticity estimates in
either case, indicating local labor market shocks are not an important confounder in

(^37) Note that the estimates based on Proposition 4 are not subject to this concern, as local aggregate
labor supply shocks are expected to be the same on average between winners and almost winners of
auctions. 38
Online Appendix F.3 provides implementation details for the specifications that are interacted
with the commuting zone or auction identifier.
45


our estimation.

Regulations on amenities and pay in the construction industry. There are
a number of regulations governing the construction industry that may raise concerns
for our research design. We now consider these concerns in turn.
One potential concern is that some states have prevailing wage laws that could
force firms that win a state government procurement auction to increase the wages of
incumbent workers, independently of whether or not they hire new workers. State pre-
vailing wage laws require that construction workers employed by private construction
firms on state-funded construction projects be paid at least the wages and benefits
paid to similar workers in the same location where the project is located. We inves-
tigate if these laws affect our estimates in two ways.
First, we examine whether the estimates are substantially different among states
that have prevailing wage laws for state contracts. In Online Appendix Table A.6,
we find for this sample very similar estimated impacts of winning a procurement
contract on employment as well as on earnings per worker, both for stayers and for
all workers in the firm. As a result, the implied labor supply elasticity and markdown
estimates are not materially different for states with prevailing wage laws than for
the population of firms at large.
Second, we use repeals of state prevailing wage laws in a difference-in-differences
analysis at the state-level to examine how wage and non-wage compensation are
impacted by prevailing wage laws. For outcome measures, we use state-level survey
data on the components of worker compensation from the Economic Census of the
Construction Sector, which is available at five-year frequency from 1977-2017. These
components include both wages and non-wage fringe benefits.^39 During this time
interval, 15 states repealed their prevailing wage laws. In Online Appendix E.2, the
difference-in-differences estimates for repeals suggests that prevailing wage laws have
little effect on total compensation, wages, non-wage fringe benefits, or the share of
total compensation from non-wage fringe benefits.
Other than prevailing wage laws, another potential concern is that winning a

(^39) The Economic Census of the Construction Sector data are described in Online Appendix E.1.
Voluntary fringe benefits – which is the component of non-wage compensation that the firm can in
principle adjust – account for only one-tenth of total compensation in the construction industry.

#### 46


procurement contract improves workplace safety, which is arguably a key non-wage
attribute of jobs in the construction industry. For two reasons, we do not believe
this is a particularly relevant concern in practice. First of all, a review of workplace
safety standards from the key governing body, the Occupational Safety and Health
Administration (OSHA), indicates that construction workplaces are highly-regulated
for worker safety, with numerous licenses and regulations related to the type of tasks
being performed. However, as discussed in Online Appendix E.3, these regulations
apply to all firms in the construction industry, not specifically to firms that win a
procurement auction.
Consistent with the fact that safety regulations are not specific to firms that
win procurement contracts, we find no effect of winning a procurement auction on
measures of violations of safety regulations. To estimate these effects, we run the same
regression specification as in equation (21), but now using safety violations and safety
investigations as the outcome variable, as measured in publicly available data from
OSHA. As shown in Online Appendix Table A.7, we find fairly precisely estimated
zero effects of winning a procurement auction on the probability of a safety violation
and on the probability of a safety investigation.
While the above specification checks find that the amenities that are measured
in these datasets do not change materially in response to winning an auction, we
admittedly cannot rule out changes to amenities that are not observed in our data.
Therefore, Online Appendix H provides a sensitivity check where we examine how
the key conclusions would change if winning a procurement auction actually did
have a causal effect on amenities. We show that, if amenities increase by the same
percent as earnings, then amenity changes do not introduce a bias in the estimate of
θ. This is because log compensation and log earnings increase by the same amount
if amenities increase by the same percent as earnings, so log earnings changes are a
valid proxy for log compensation changes. However, log compensation could in reality
increase more (or less) than log earnings, so the estimate ofθusing earnings may be
downward-biased (or upward-biased). In Online Appendix Figure A.11, we examine
how differential changes in earnings and total compensation may bias our estimates
of the labor supply elasticity. We find that, even in the rather extreme case in which
log compensation increases by 20% more (or less) than log earnings due to amenity

#### 47


responses, the labor supply curve is upward sloping with an elasticity that would be
close to our baseline estimates in Figure 3.

Sensitivity to labor hours and full-time status. A potential concern in our
data is that we only observe earnings changes, not changes in hourly wages. If part
of the earnings change is due to an increase in hours, then we overstate the wage
increase relative to the labor increase, leading to a downward-biased estimate of the
labor supply elasticity, 1 /θ. We now investigate this possibility.
One natural way to increase hours is to promote part-time workers to full-time
status. However, part-time employment is rare in the construction industry: in 2015,
13.9% of all US private sector workers were part-time but only 4.6% of construction
industry workers were part-time (BLS, 2021). To better understand the relationship
between full-time employment status and annual earnings, we analyze CPS ASEC
cross-sectional random samples of the US labor force, which include measures of hours
worked and annual earnings. In the 2001-2015 ASEC samples, 6.4% of construction
workers are part-time employed, compared to 11.9% across all industries. When
imposing in the ASEC samples our FTE restriction that annual earnings from the
primary employer are greater than the annualized full-time minimum wage, only 4.4%
of the remaining construction sample is part-time employed, compared to 7.1% across
all industries. Thus, the FTE restriction removes about 30% of part-time employees
from the ASEC samples.
Nevertheless, one may worry that promotions from part-time to full-time employ-
ment in response to winning a procurement contract explain our estimated increase
in earnings per worker. To investigate this, we consider again the stayers sample de-
scribed above. Since stayers are defined as workers who were already FTE before the
procurement contract was received and remained FTE after, stayers could not have
been promoted from non-FTE to FTE status in response to winning the procure-
ment contract. We find almost the same estimates for the stayers sample as we do
for the full sample of workers, suggesting that promotion from part-time to full-time
status does not drive our results. However, it could be that our baseline FTE sam-
ple includes some part-time workers with relatively high hourly wages. In the bars
labeled “125% FTE” and “150% FTE” in Online Appendix Figure A.5, we strengthen
the FTE restriction up to 125% and 150% of the baseline definition, respectively,

```
48
```

with additional choices provided in Online Appendix Figure A.6e. Transitions from
part-time to full-time status should become less likely as the FTE restriction rises.
We find that the estimate is insensitive to raising the FTE restriction, suggesting we
have successfully ruled out part-time to full-time promotions with the baseline FTE
restriction. It is not surprising that part-time employment does not confound our
estimates, given how rare part-time employment is in the construction industry.
The other natural way to increase hours is over-time pay for incumbent full-time
workers. When thinking about the plausibility that our estimates are driven by over-
time pay, it is useful to observe that the effects of receiving a procurement contract
persist over several years. In Figure A.3, we find that the change in earnings due
to receiving a procurement contract (which is the numerator ofθDiDandθRDD) is
positive, statistically significant, and relatively stable over the four years after the
firm wins the auction, whereas the typical procurement project lasts for less than one
year. Thus, it is unlikely that over-time pay to meet a short-lived increase in product
demand explains our estimated increase in earnings.
While the evidence from the US data indicate that the increase in earnings is
not due to increased hours worked, the most compelling evidence would come from
directly estimating annual earnings versus hourly wage responses in data with ad-
ministrative measures of each worker’s labor hours. Labor hours data is not available
from the IRS, nor is it available in other nationally representative employer-employee
panel data from the US (e.g., LEHD).^40 To overcome this challenge, we consider data
from Norway. Norway provides a rare opportunity, as it is one of the few countries
where the hours worked by each employee are reported to the government. We restrict
the Norwegian sample to the construction industry and workers who satisfy the same
FTE restriction as we impose in the US data.^41
To determine whether or not labor hours responses confound wage responses to

(^40) Only Minnesota, Oregon, Rhode Island, and Washington State collect labor hours data as part
of their unemployment insurance records, representing a small fraction of the US workforce and a
small fraction of states covered by our procurement auction records. This hourly wage data is not
available through the IRS. For other papers using IRS data (without information on hours) to study
wage-setting and labor markets, see e.g., Kline et al. (2019), Song et al. (2019), Yagan (2019), and
Guvenen et al. (2021).
(^41) Online Data Supplement S.4 provides details on the Norwegian data sources and sample con-
struction.

#### 49


firm shocks in Norway, we apply the LMS estimator (discussed above) to recover the
pass-through from revenue shocks to annual earnings and hourly wages. We find that
the elasticity of annual earnings and hourly wages to revenue shocks are 0.092 and
0.091, respectively, while the elasticity of hours to revenue shocks is 0.001. Thus,
the labor supply elasticity is nearly identical when estimated using annual earnings
versus hourly wages.

### 6.2 Firm Technology and Product Demand Parameters

We use GMM to jointly estimate(ρ,βL,ε)based on equations (22), (23), (24), and
(25). The estimates and standard errors are reported in Panel B of Table 2.
We estimateβLto be 0.50 andρto be 1.09. The value ofβLimplies that a 100%
increase in a firm’s employment results in 50% more output, all else equal. The value
ofρimplies that, if a firm has 100% more labor than another firm, we expect it to
produce 109% more output, not holding all else equal. The larger firm will optimally
have greater utilization of capital and intermediate inputs. Sinceρ≡(1 +θ)βK+βL,
these estimates imply thatβKis about 0.47 (see Panel C in Table 2). The returns to
scale over labor and capital,βL+βK, is about 1.0, which is comparable to the range
of estimates from 1.0 to 1.2 by Levinsohn and Petrin (2003).
As discussed in Section 2.3, the government project crowds-out private projects
(QH 1 jt< QH 0 jt) since we estimate that1 +θ > ρ. To see why this is the case, note that
winning a government project increases the total output level. In turn, more employ-
ment is required to achieve a greater level of production. Due to the upward-sloping
labor supply curve, greater employment leads to higher costs of labor, determined
by1 +θ. On the other hand, greater scale induces greater private production under
composite economies of scale,ρ > 1. Since we estimate1 +θ > ρ, it is optimal for a
firm to cut its production for the private market if it receives a procurement contract.
We quantify the crowd-out effect when discussing incidence in the next section.
In the private product market, we estimate thatεis 0.14, so the product demand
elasticity− 1 /ε is about− 7. 3. This implies that, in order for a firm to increase
output by 10%, it must reduce its price by about 1.4%. The price markup(1−ε)−^1
is about 1.16, which implies that the price is 16% more than the relevant marginal
cost reflecting both labor and intermediate inputs. Online Appendix Figure A.8

#### 50


```
Panel A. Worker Preference Dispersion and Wage Markdown
Parameter and Identifying Moments Data
Inverse Labor Supply Elasticityθ:
DiD Estimand (Prop 3) θDiD 0.245 (0.086)
RDD Estimand (Prop 4) θRDD 0.286 (0.092)
Wage Markdown 1/(1 +θ)
DiD Estimand (Prop 3) 1 /(1 +θDiD) 0.803 (0.055)
RDD Estimand (Prop 4) 1 /(1 +θRDD) 0.777 (0.059)
Panel B. Technology and Product Demand Parameters
Baseline Estimates using Over-identified GMM
Parameters Data
Composite returns to labor (eqs 22-25) ρ 1.089 (0.017)
Marginal returns to labor (eqs 22-25) βL 0.499 (0.192)
Inverse product demand elasticity (eqs 22-25) ε 0.137 (0.015)
Alternative Estimates using Exactly-identified System
Parameters Data
Control function estimation using bids (eq 22) ρ 1.057 (0.015)
Markup and labor share relationship (eq 23) βL 0.514 (0.209)
Intermediate inputs to revenues ratio (eq 24) ε 0.137 (0.008)
Panel C. Remaining Parameters for Price, Scale, and TFP
Parameter and Identifying Moments Data
Scale of log output price (eq 27) logpH =E[rjt−(1−ε)(logβpMM+xjt)|D= 0] 12.801 (0.053)
Scale of log amenities (̂ujt) E[ujt] =E[bjt]−(1 +θ)E[ℓjt] 10.075 (0.000)
Scale term for intermediates (eq 26) logβpMM =ρE[ℓjt]−E[xjt] -11.722 (0.047)
Marginal returns to capital βK = (ρ−βL)/(1 +θ) 0.474 (0.161)
Interquartile range of log TFP (φ̂jt) IQR(φjt) = IQR(xjt−ρℓjt) 0.918 (0.001)
Table 2: Estimates of the Structural Parameters
```
Notes: This table summarizes identifying equations and provides estimates of several model pa-
rameters. DiD and RDD estimates of the inverse labor supply elasticity,θ, and wage markdown
relative to MRPL,(1 +θ)−^1 , are provided in Panel A. Over-identified and exactly-identified esti-
mates of(ρ,βL,ε)are provided in Panel B, where we equally weight the moments in over-identified
GMM. Estimates of the remaining parameters are provided in Panel C. Specification details, sample
definitions, and sensitivity checks are discussed in the text.

estimates heterogeneity in 1 −εacross Census regions, finding little variation. Though
we do not find directly comparable estimates of the price elasticity of demand from
the construction industry, some estimates from the literature suggest our estimate is
within a reasonable range. Goldberg and Knetter (1999) estimate demand elasticities
for German beer to be− 2. 3 to− 15. 4. Goldberg and Verboven (2001) estimate demand
elasticities for foreign cars to be− 4. 5 to− 6. 5.

#### 51


Sensitivity analyses. We now apply several sensitivity checks to our GMM esti-
mates of(ρ,βL,ε)to verify that our results are not driven by model assumptions. In
Panel B of Table 2, we provided baseline estimates from over-identified GMM. In order
to directly examine the validity of the model, we can instead estimate the parameters
using direct estimation of the exactly-identified system, dropping the over-identifying
restriction discussed in Section 5.4.^42 Using this approach, we estimate thatρis 1.06,
βLis 0.51, andεis 0.14, which are nearly the same as the baseline estimates.
Our baseline analyses have assumed that the price parameters(pH,pK,pM)do not
vary over time. While time-varying price parameters would lead to the same model
equations in Section 2, the regression intercepts in equations (22), (24), and (25)
would have year subscripts, which suggests controlling for year fixed effects in these
regressions. When doing so, we find that the GMM estimates of (ρ,βL,ε)remain
identical, so accounting for time-variation in the price parameters does not affect our
results.
The Leontief production function is motivated by institutional features of the
construction industry and allows us to derive a linear relationship betweenxjtandℓjt
(equation 11), but one may worry that it is misspecified. Although misspecification
in the production function would not affect the estimated labor supply elasticity or
total rents, it could affect the estimates ofρandεas well as analyses of the incidence
of procurement. In Online Appendix C, we solve, identify, and estimate the model
with a Cobb-Douglas production function. In this case, we estimate thatρis 1.08 and
− 1 /εis− 5. 04 , which are similar to the estimates based on the Leontief production
function. We also find similar estimates of the incidence of procurement on firms and
workers. Thus, the functional form of the production function does not drive our
results.
In Section 2.3, we discussed the assumption that auctions are symmetric, which
leads to a closed-form expression for the optimal bidding strategy. While the identifi-
cation strategies forθ,βL, andεdo not rely on auction symmetry, we used symmetry
to recoverρin Proposition 5. If auctions were not symmetric, inverting the bid-

(^42) In particular, equation (22) provides a direct estimate ofρ, equation (24) provides a direct
estimate ofε, and equation (23) provides a plug-in estimate ofβLgiven the direct estimates ofε
andρ.

#### 52


ding function to control for TFP would require not only controlling for a firm’s own
amenity term and bid but also the amenities of all other bidders in the auction. As
a sensitivity check, we re-estimateρwhen controlling for a polynomial in the average
amenities of all other firms in the same auction, finding a nearly identical estimate
ofρ. Thus, the assumption that auctions are symmetric does not drive estimates of
key model parameters.

Remaining model parameters. For the few remaining model parameters, the
identifying equations and estimates are provided in Panel C of Table 2. These in-
clude the private market price index parameterpH(using equation 27), the scale of
amenitiesE[ujt](usingbujt), the returns to intermediate inputs relative to marginal
costβM/pM (using equation 26), the returns to capitalβK (using the definition of
ρ), and the interquartile range of TFP (usingφbjt(ρ)).^43 Although the magnitudes of
these parameters are perhaps not of interest on their own, they are needed to perform
model simulations.^44

## 7 Quantifying the Importance of Double Market Power

We now use the estimated model to quantify double market power and its implications
for the outcomes and behavior of workers and firms in the US construction industry.

### 7.1 The Double Wage Markdown and Double Price Markup

We use the estimates in Table 2 to quantify the double markdown of wages and double
markup of prices. The results are presented in Table 3. We consider both RDD and
DiD estimates ofθ. Drawing on equation (19), the double markdown of the wage
is about 0.69 when using the DiD estimator forθ and about 0.67 when using the
RDD estimator forθ. Thus, the wage is 31-33% below the value of MPL. Drawing on

(^43) The estimates of parametersβKandE[ujt]depend on the estimate ofθ. In Panel C of Table 2,
we present the estimates usingθDiD. When instead usingθRDD, the estimate ofβKis 0.46 instead
of 0.47 and 44 E[ujt]is 9.96 instead of 10.08, which are very similar.
For example, the simulation exercises below use the TFP interquartile range when simulating
optimal bids as a function of TFP dispersion from equation (14). One potential concern is that the
distribution of TFP varies over time, so our interquartile range estimate may be overstated due to
pooling across years. Online Appendix Figure A.7 estimates the TFP interquartile range separately
by calendar year, finding little evidence of changes over time.

#### 53


```
Panel A. Components of the Double Markdown of the Wage
Markdown Inverse Markup Double Markdown
(1 +θ)−^1 (1−ε) (1 +θ)−^1 (1−ε)
UsingθDiD: 0.803 0.863 0.693
UsingθRDD: 0.777 0.671
Panel B. Components of the Double Markup of the Price
Markup Inverse Markdown Double Markup
(1−ε)−^1 (1 +θ) (1−ε)−^1 (1 +θ)
UsingθDiD: 1.159 1.245 1.443
UsingθRDD: 1.286 1.491
```
```
Table 3: Estimates of the Double Markdown and Double Markup
```
Notes: This table summarizes our estimates of double market power. The first column of Panel A
provides our estimate of the wage markdown relative to MRPL,(1 +θ)−^1 , using either the DiD or
RDD estimand, while the first column of Panel B provides our estimate of the price markup relative
to marginal cost,(1−ε)−^1. The second column provides the inverse of these markup and markdown
terms. The third column uses Proposition 2 to define the double markdown in Panel A and the
double markup in Panel B.

equation (20), the double markup of the price is 1.44 when using the DiD estimator
forθand 1.49 when using the RDD estimator forθ. Thus, the price is 44-49% above
the (productivity-adjusted) wage.
To gauge the empirical relevance of the double markdown, it is useful to compare it
to the markdown estimate that one would obtain if ignoring product market power. If
one assumed a perfectly competitive product market, then the only markdown would
be(1 +θ)−^1 and one would conclude that the wage is only 20-22% below the value of
MPL. Conversely, if one assumed a perfectly competitive labor market, then the only
markup would be(1−ε)−^1 and one would conclude that the price is only 16% above
the (productivity-adjusted) wage.

### 7.2 Estimated Impacts of Changes in Market Power

We quantify the impacts of a change in market power in a given market, all other
things being equal, using the approach laid out in Section 3.2 and the model estimates
from Table 2. We focus on a typical firm, by which we mean the median-TFP firm.

#### 54


In Figure 4a, we predict the impacts of increased labor market power if the firm
did not have product market power. This is done by increasing the inverse labor
supply elasticity from our estimated value to a higher value, while making sure that
labor supply at the initial wage is the same (by changing the location parameter in
labor supplyU). For each outcome, we find a monotonic relationship across values
of the labor supply elasticity. When the labor supply elasticity of a given firm is
reduced by half, the firm employs 27% fewer workers and decreases wages by 16%.
Expenditure on inputs declines by 39% for labor, 25% for capital, and 25% for inter-
mediate materials.^45 Output is reduced by 25% and prices are constant (sinceε= 0),
so revenue declines by 25%. Despite these reductions in the firm’s activities, profit
rises 10% due to the increased markdown of wages.
In Figure 4b, we predict the impacts of increased labor market power given our
estimate of product market power, thus providing our best prediction of the impacts
that increased labor market power would have on the outcomes of the US construc-
tion industry. As before, outcomes are monotonic across values of the labor supply
elasticity. However, the impacts of the increase in labor market power are substan-
tially attenuated by taking into account that the firm has product market power and,
thus, it was profitable to initially set the price above the marginal cost.
When the labor supply elasticity of a given firm is reduced by half, the firm is
less willing to cut wages by lowering employment. Due to its product market power,
the firm only reduces employment by 15% and only cuts wages by 9%. Expenditures
decrease by 23% for labor, 6% for capital, and 11% for intermediate materials. Output
decreases by 11%, prices rise by 2%, revenue decreases by 9%, and profits increase by
1%.
Figures 4c-4d perform the same exercises as in Figures 4a-4b, except we now in-
crease product market power. This is done by increasing the inverse product demand
elasticity from our estimated value to a higher value, while making sure that product
demand at the initial price is the same (by changing the location parameterpH). In
Figure 4c, we assume the firm does not have labor market power. When the product
demand elasticity of a given firm is reduced by half, the firm will then employ 47%

(^45) Intermediate material expenditure is not shown in the figure because it must change in proportion
to output due to the Leontief production function.

#### 55


```
−30
```
```
−20
```
```
−10
```
```
0
```
```
10
```
```
2.0 2.5 3.0 3.5
Alternate Labor Supply Elasticity 1 θ
```
```
Change (%)
```
```
WageLabor OutputCapital ProfitPrice
```
(a) Impacts of Labor Market Power
without Product Market Power (ε= 0)

```
−30
```
```
−20
```
```
−10
```
```
0
```
```
10
```
```
2.0 2.5 3.0 3.5
Alternate Labor Supply Elasticity 1 θ
```
```
Change (%)
```
```
WageLabor OutputCapital ProfitPrice
```
```
(b) Impacts of Labor Market Power
with Product Market Power (Trueε)
```
```
−40
```
```
−20
```
```
0
```
```
20
```
```
−7 −6 −5 −4
Alternate Product Demand Elasticity − 1 ε
```
```
Change (%)
```
```
WageLabor OutputCapital ProfitPrice
```
(c) Impacts of Product Market Power
without Labor Market Power (θ= 0)

```
−40
```
```
−20
```
```
0
```
```
20
```
```
−7 −6 −5 −4
Alternate Product Demand Elasticity − 1 ε
```
```
Change (%)
```
```
WageLabor OutputCapital ProfitPrice
```
```
(d) Impacts of Product Market Power
with Labor Market Power (Trueθ)
Figure 4: Estimated Impacts of Changes in Market Power
```
Notes: This figure presents expected impacts of increased labor or product market power, using
the approach defined in Section 3.2. To do so, it simulates from the model defined in Section 2
for the typical firm, evaluated at the parameter estimates provided in Table 2. In subfigures (a,b),
we increase labor market power through compensated changes inθ, while in subfigures (c,d), we
increase product market power through compensated increases inε. In subfigures (a,c), we assume
there is only market power in the indicated market, while in subfigures (b,d), we assume market
power in both labor and product markets is characterized by our preferred estimates. Each simulated
outcome is expressed as a percent change relative to the value observed in the data.

fewer workers while wages are unchanged (sinceθ= 0). By comparison, the use of
labor only declines by 39% and wages only fall by 13% when we, in Figure 4d, take
into account that the firm has labor market power and, thus, was profitably setting
wages below MRPL. Incorporating labor market power also leads to a modest atten-

#### 56


uation of the predicted impact of increased product market power on output, prices,
intermediate materials, and profits.

## 8 Rents and Incidence of Government Procurements

In this section, we use the estimates of model parameters to infer the rents, rent-
sharing, and incidence of procurements in the US construction industry. We here
focus on firms that currently have a procurement contract so that we can characterize
the incidence of procurements for the firms that are actually impacted.
Table 4 provides our main results on rents and incidence. The first column of
Table 4 presents the actual firm and worker outcomes. We focus on firms that receive
a procurement contract (Djt= 1) and provide estimates for the typical firm, by which
we mean the median-TFP firm. The typical firm employs about 25 workers and pays
them an annual wage of $59,100. This amounts to an annual wage bill of about
$1.5 million. Using the expression for incidence on worker rents in Section 2.5, this
implies that worker rents are about $11,600 per worker, which amounts to 20% of
their average earnings. Comparing revenues to expenditures on all inputs, firm rents
(i.e. profits) amount to about $43,100 per worker. Comparing worker rents to firm
rents, 79% of total rents are captured by firms.
We now investigate how these results would change if the median-TFP firm in-
stead had above-median or below-median TFP. To do so, we assign alternative TFP
quantiles to this firm without changing any other primitives of the model, then re-
solve the model to obtain this firm’s alternative outcomes and rents.^46 The results are
provided in Figure 5. The x-axis displays the alternative draw of TFP assigned to the
firm (as a percentile in the population TFP distribution). In Figure 5(a), the y-axis
presents the firm’s labor, wage, wage bill, output, and profits, and in Figure 5(b),
the y-axis presents the total rents of the firm, total rents of its workers, and workers’
share of total rents. Each y-axis value is expressed as a percent change relative to the
actual value for the median-TFP firm (reported in the first column of Table 4).

(^46) To solve the model for firms that currently receive procurement contracts, we must account for
the optimal markups in the bids, requiring that we integrate across the distribution of opportunity
costs (equation 14). To overcome the computational challenge, we implement the quantile repre-
sentation method proposed by Luo (2020); implementation details are provided in Online Appendix
I.

#### 57


```
Actual Counterfactual Change due to procurements
outcomes no procurements Level Relative
Labor market
Ljt Employment (workers) 24.7 12.8 11.9 92.7%
Wjt Wage ($1,000) 59.1 50.4 8.8 17.4%
Bjt Wage bill ($1,000) 1,459.6 645.2 814.4 126.2%
Intermediate markets
Xjt Intermediate inputs ($1,000) 4,715.1 2,308.6 2,406.5 104.2%
pKKjt Capital rentals ($1,000) 1,724.7 762.4 962.3 126.2%
Total production
Qjt Output (quantity) 38.3 18.7 19.5 104.2%
Rjt Revenue ($1,000) 8,962.1 4,541.6 4,420.5 97.3%
Private production
QHjt Output (quantity) 13.7 18.7 -5.1 -27.0%
RHjt Revenue ($1,000) 3,460.7 4,541.6 -1,080.9 -23.8%
Rents
Vjt Worker rents ($1,000/worker) 11.6 5.1 6.5 126.2%
πjt Firm rents or Profits ($1,000/worker) 43.1 33.4 9.6 28.7%
Table 4: Outcomes of Firms and Workers and the Incidence of Procurement
```
Notes: For the median-TFP firm in the sample of firms that received procurement contracts (Djt=
1 ), this table presents the observed values of various outcomes (column 1) as well as outcomes that
would have been experienced if the firm had not received a procurement contract (column 2) using
the approach of Section 5.6. It presents the differences between columns 1 and 2 in levels (column
3) and in percent changes (column 4).

We find that, when the firm is more productive (above-median TFP), it chooses
to produce more output, which requires hiring more workers. Since the labor supply
curve is upward-sloping, it must bid up wages to increase employment, which also
increases the wage bill. If TFP is set to the 75th percentile, the firm employs 12%
more labor, pays 3% higher wages, and spends 15% more on labor. It produces 65%
more output and earns 74% more profits. By contrast, if TFP is set to the 25th
percentile, it produces 26% less output and earns 37% lower profit. If TFP is set
below the 25th percentile, the firm also hires more workers and pays greater wages
than with median TFP. This is because it needs to produce the minimum output
specified by the government in the procurement contract,QG, and must compensate
for low productivity by hiring more labor than it would with median TFP.^47 Since firm

(^47) Online Appendix Figure A.9 provides a similar analysis but for the majority of firms that do not
currently have a procurement contract and thus have no incidence of procurements. We find that
wages, employment, the wage bill, and rents are monotonically increasing in TFP when shutting

#### 58


```
−50
```
```
0
```
```
50
```
```
100
```
```
150
```
```
200
```
(^20) Percentile in TFP Distribution of Firms 40 60 80
Outcome relative toMedian TFP Firm (%)
Labor Wage Wage bill Output Profits
(a) Outcomes of Workers and Firms
−50
0
50
100
150
200
(^20) Percentile in TFP Distribution of Firms 40 60 80
Outcome relative toMedian TFP Firm (%)
Total RentsFirms Total RentsWorkers Total RentsWorkers Share
(b) Total Rents of Workers and Firms
Figure 5: Outcomes and Rents for Alternative TFP Percentiles
Notes: In this figure, we assign alternative TFP quantiles to the median-TFP firm in theDjt= 1
sample without changing any other primitives of the model, then re-solve the model to obtain this
firm’s alternative outcomes and rents. The x-axis displays the alternative TFP assigned to the firm
(as a percentile in the population TFP distribution). Each y-axis value is expressed as a percent
change relative to the actual value for the median-TFP firm (reported in the first column of Table
4).
rents increase more than worker rents as TFP increases, the share of rents captured
by workers is decreasing in TFP. This result complements the recent literature on
product market competition which has found that more productive firms have higher
markups and lower labor shares (Autor et al., 2020; de Loecker et al., 2020). We
account for both labor and product market power in a constant-elasticity framework
and find a lower rent share to workers at more productive firms.
Last, we investigate the incidence of government procurements on firms and work-
ers. The second column of Table 4 provides our estimates of the outcomes that would
have prevailed if the firm had not received a procurement contract using the approach
of Section 5.6. The difference between columns 1 and 2 is the incidence of a procure-
ment contract on the outcomes of the firm and its workers, which are both presented
in absolute level changes (column 3) and changes relative to the case in which the
firm does not receive a procurement contract (column 4). We find that receiving a
procurement contract induces it to hire 12 more workers (nearly doubling the firm’s
down the government market, confirming that the non-monotonicity in these outcomes in Figure 5
is due to the constraint thatQ 1 jt≥QG.

#### 59


workforce) and pay each of its workers about $8,800 more in wages (a 17% increase),
increasing its wage bill by about $0.8 million. Worker rents increase by about $6,500
per worker (more than double the baseline rents). Using the decomposition of in-
cidence in Section 2.5, 70% of worker rents generated by the procurement contract
accrue to incumbent workers rather than new hires.
In response to receiving the procurement contract, the median firm increases ex-
penditure on intermediate inputs by $2.4 million (about double the baseline) and
capital rental by nearly $1.0 million (more than double the baseline). Total output
approximately doubles. Government demand crowds out private market production,
with private market output decreasing by about 27%. Total revenues increase by
$4.4 million, while private market revenues decrease by about $1.0 million. Com-
paring revenues to expenditures on all inputs, firm rents (i.e. profits) increase by
$9,600 per worker. Thus, 40% of the rents generated by government procurement is
captured by workers, and workers receive a larger share of the rents for the marginal
procurement contract than for the baseline output if only operating in the private
product market.

## 9 Conclusion

Existing work on imperfect competition typically focuses on either the labor market
or the product market in isolation. In contrast, we analyzed imperfect competition
in both markets jointly, showing theoretically and empirically how the impacts of
market power in one market depend on market power in the other market. Our
context was the US construction industry. We developed, identified and estimated
a model where construction firms imperfectly compete with one another for workers
in the labor market and for projects in both the private market and the government
market, where government projects are procured through auctions. Our analyses
combined the universe of business and worker tax records with newly collected records
from government procurement auctions. We used the estimated model to quantify
the markdown of wages and the markup of prices, to show that the impacts of an
increase in market power in one market are attenuated by the existence of market
power in the other market, and to quantify the rents, rent-sharing, and incidence of
procurements in the US construction industry.

#### 60


## References

Ackerberg, D. A., K. Caves, and G. Frazer(2015): “Identification properties
of recent production function estimators,”Econometrica, 83, 2411–2451.
Akerman, A., I. Gaarder, and M. Mogstad(2015): “The skill complementarity
of broadband internet,”The Quarterly Journal of Economics, 130, 1781–1824.
Athey, S. and P. A. Haile(2007): “Nonparametric approaches to auctions,”Hand-
book of econometrics, 6, 3847–3965.
Autor, D., D. Dorn, L. F. Katz, C. Patterson, and J. Van Reenen(2020):
“The fall of the labor share and the rise of superstar firms,”The Quarterly Journal
of Economics, 135, 645–709.
Azar, J., S. Berry, and I. E. Marinescu (2021): “Estimating labor market
power,”.
Balat, J., T. Komarova, and E. Krasnokutskaya(2017): “Ex-ante and Ex-
post Subcontracting in Highway Procurement Markets,” Tech. rep., Working Paper,
Johns Hopkins University.
Berger, D., K. Herkenhoff, and S. Mongey(2022): “Labor market power,”
American Economic Review, 112, 1147–93.
Bhaskar, V., A. Manning, and T. To(2002): “Oligopsony and Monopsonistic
Competition in Labor Markets,”Journal of Economic Perspectives, 16, 155–174.
BLS(2021): “Labor Force Statistics from the Current Population Survey. 2002 - 2021
Annual Averages: Persons at work in nonagricultural industries by class of worker
and usual full- or part-time status.”Data Tables, U.S. Bureau of Labor Statistics.

Boal, W. M. and M. R. Ransom (1997): “Monopsony in the labor market,”
Journal of Economic Literature, 35, 86–112.
Bonhomme, S., K. Holzheu, T. Lamadon, E. Manresa, M. Mogstad, and
B. Setzler(2023): “How Much Should we Trust Estimates of Firm Effects and
Worker Sorting?” Journal of Labor Economics.
Caldwell, S. and E. Oehlsen(2018): “Monopsony and the Gender Wage Gap:
Experimental Evidence from the Gig Economy,”MIT Working Paper.
Callaway, B. and P. H. Sant’Anna(2020): “Difference-in-differences with mul-
tiple time periods,”Journal of Econometrics.
Card, D.(2022): “Who Set Your Wage?” American Economic Review, 112, 1075–90.
Card, D., A. R. Cardoso, J. Heining, and P. Kline(2018): “Firms and labor
market inequality: Evidence and some theory,”Journal of Labor Economics, 36,
S13–S70.
Castro-Vincenzi, J. M. and B. Kleinman(2022): “Intermediate input prices
and the labor share,”Unpublished manuscript, Princeton University.

#### 61


CBO(2007): “The Impact of Unauthorized Immigrants on the Budgets of State and
Local Governments,” Tech. rep., Congressional Budget Office.
Chan, M., K. Kroft, E. Mattana, and I. Mourifié(2023): “An Empirical
Framework for Matching with Imperfect Competition,”Unpublished manuscript.
Chassang, S., K. Kawai, J. Nakabayashi, and J. M. Ortner(2022): “Robust
Screens for Noncompetitive Bidding in Procurement Auctions,”Econometrica, 90,
315–346.
de Loecker, J., J. Eeckhout, and G. Unger(2020): “The rise of market power
and the macroeconomic implications,”The Quarterly Journal of Economics, 135,
561–644.
Dixit, A. K. and J. E. Stiglitz(1977): “Monopolistic competition and optimum
product diversity,”The American Economic Review, 67, 297–308.
Dube, A., A. Manning, and S. Naidu(2020): “Monopsony and employer mis-
optimization explain why wages bunch at round numbers,”Unpublished manuscript.
Dube, A., S. Naidu, and A. D. Reich(2022): “Power and Dignity in the Low-
Wage Labor Market: Theory and Evidence from Wal-Mart Workers,”Unpublished
manuscript.
Duncan, K. and R. Ormiston (2019): “What does the research tell us about
prevailing wage laws?” Labor Studies Journal, 44, 139–160.
Ferraz, C., F. Finan, and D. Szerman(2015): “Procuring firm growth: the
effects of government purchases on firm dynamics,” NBER Working Paper w21219.

Gandhi, A., S. Navarro, and D. A. Rivers(2020): “On the identification of
gross output production functions,”Journal of Political Economy, 128, 2973–3016.
Goldberg, P. K. and M. M. Knetter(1999): “Measuring the intensity of com-
petition in export markets,”Journal of International Economics, 47, 27–60.
Goldberg, P. K. and F. Verboven(2001): “The evolution of price dispersion in
the European car market,”The Review of Economic Studies, 68, 811–848.
Gugler, K., M. Weichselbaumer, and C. Zulehner(2020): “Employment
behavior and the economic crisis: Evidence from winners and runners-up in pro-
curement auctions,”Journal of Public Economics, 182, 104112.
Guvenen, F., F. Karahan, S. Ozkan, and J. Song(2021): “What do data on
millions of US workers reveal about lifecycle earnings dynamics?” Econometrica,
89, 2303–2339.
Howell, S. T. and J. D. Brown (2020): “Do Cash Windfalls Affect Wages?
Evidence from R&D Grants to Small Firms,” CES Working Paper 20-06, U.S.
Census Bureau.
Hvide, H. K. and T. Meling(2020): “Do Temporary Demand Shocks Have Long-
Term Effects for Startups?” SSRN 3437270.

#### 62


Jarosch, G., J. S. Nimczik, and I. Sorkin(2023): “Granular Search, Market
Structure, and Wages,” NBER Working Paper w26239.
Kessler, D. P. and L. F. Katz(2001): “Prevailing Wage Laws and Construction
Laborc Markets,”ILR Review, 54, 259–274.
Kline, P., N. Petkova, H. Williams, and O. Zidar(2019): “Who profits from
patents? rent-sharing at innovative firms,” The Quarterly Journal of Economics,
134, 1343–1404.
Lamadon, T., M. Mogstad, and B. Setzler(2022): “Imperfect Competition,
Compensating Differentials, and Rent Sharing in the US Labor Market,”American
Economic Review, 112, 169–212.
Levinsohn, J. and A. Petrin (2003): “Estimating production functions using
inputs to control for unobservables,” The Review of Economic Studies, 70, 317–
341.

Lewis, G. and P. Bajari(2011): “Procurement Contracting With Time Incentives:
Theory and Evidence,”The Quarterly Journal of Economics, 126, 1173–1211.
Luo, Y.(2020): “Unobserved heterogeneity in auctions under restricted stochastic
dominance,”Journal of Econometrics, 216, 354–374.
MacKenzie, G.(2021): “Trade and market power in product and labor markets,”.
Manning, A.(2003):Monopsony in motion: Imperfect competition in labor markets,
Princeton University Press.
——— (2011): “Imperfect competition in the labor market,”Handbook of Labor Eco-
nomics, 4, 973–1041.
Maskin, E. and J. Riley (1984): “Optimal auctions with risk averse buyers,”
Econometrica, 1473–1518.
Milgrom, P. R. and R. J. Weber(1982): “A theory of auctions and competitive
bidding,”Econometrica, 1089–1122.
Robinson, J.(1933):The Economics of Imperfect Competition, Macmillan and Co.
Rosen, S.(1986): “The theory of equalizing differences,” Handbook of Labor Eco-
nomics, 1, 641–692.
Roussille, N. and B. Scuderi(2022): “Bidding for Talent,”.

RSMeans(2008):Building Construction Cost Data, 66 ed.
Sharma, G.(2022): “Monopsony and Gender,”.
Sokolova, A. and T. Sorensen(2021): “Monopsony in labor markets: A meta-
analysis,”ILR Review, 74, 27–55.
Song, J., D. J. Price, F. Guvenen, N. Bloom, and T. Von Wachter(2019):
“Firming up inequality,”The Quarterly Journal of Economics, 134, 1–50.

#### 63


Suárez Serrato, J. C. and O. Zidar(2016): “Who benefits from state corporate
tax cuts? A local labor markets approach with heterogeneous firms,” American
Economic Review, 106.
Takahashi, H.(2018): “Strategic design under uncertain evaluations: structural
analysis of design-build auctions,”The RAND Journal of Economics, 49, 594–618.

van Reenen, J.(1996): “The creation and capture of rents: wages and innovation
in a panel of UK companies,”The Quarterly Journal of Economics, 111, 195–226.
Yagan, D.(2019): “Employment hysteresis from the great recession,” Journal of
Political Economy, 127, 2505–2558.

#### 64


# Online Appendix to “Imperfect Competition and

# Rents in Labor and Product Markets: The Case of

# the Construction Industry”

## A Model Derivations

### A.1 The Composite Production Function

In this appendix, we derive equation (9). To do so, we express revenues and costs as
functions ofQjtso as to separate the joint maximization into two steps: In the first
step, we find the optimal combination(Kjt,Ljt)for eachQjt. In the second step, we
solve for the optimalQjt.
Recall that firms can rent capital at pricepKand hire labor at priceWjt=UjtLθjt.
The production function (in physical units) satisfies

```
Qjt= ΩjtKβjtKLβjtL. (29)
```
Intermediate inputs have constant pricepMand, due to the Leontief functional form,
must satisfyMjt=Qjt/βM. Given any production levelQjt, the firm can find the
most cost efficient combination(Kjt,Ljt)by solving the Hicksian cost-minimization
problem,
min
(Kjt,Ljt):Qjt=ΩjtKβjtKLβjtL

```
pKKjt+UjtL1+jtθ, (30)
```
wherepKKjt+UjtL1+jtθis the total cost of capital and labor. We now solve for the
Hicksian demand for capital and labor using the Lagrangian,

```
Ljt≡pKKjt+UjtL1+jtθ+λjt(Qjt−ΩjtKβjtKLβjtL), (31)
```
whereλjtis the Lagrange multiplier. The first-order conditions for capital and labor,
respectively, are as follows:

#### A1


```
pK=λjtΩjtβKKjtβK−^1 LβjtL, (32)
(1 +θ)UjtLθjt=λjtΩjtβLKjtβKLβjtL−^1. (33)
```
These equations lead to the optimal choice of capital as a function of labor:

```
Kjt=βK
βL
```
```
(1 +θ)
pK
UjtL1+jtθ. (34)
```
```
Substituting equation (34) into equation (29), the inverse Hicksian demand is
```
```
Qjt= Ωjt
```
```
β
K
βL
```
```
(1 +θ)
pK
UjtL1+jtθ
```
```
βK
LβjtL= ΦjtLρjt, (35)
```
where we defineρ≡ (1 +θ)βK+βLandΦjt ≡Ωjt

#### 

```
βK
βL
```
```
(1+θ)
pK Ujt
```
```
βK
```
. Thus,Ljt =

(Qjt/Φjt)^1 /ρ. Substituting into the first-order condition for intermediate inputs (equa-
tion 10), the Hicksian expenditure on intermediate inputs is

```
Xjt≡pMMjt=pMQjt/βM=pβM
M
```
```
ΦjtLρjt. (36)
```
Lastly, lettingκU ≡ ββKL(1 +θ) + 1, total costs can be expressed purely in terms of
labor as

```
WjtLjt+pKKjt+pMMjt=κUUjtL1+jtθ+βpM
M
```
```
ΦjtLρjt. (37)
```
### A.2 Firm’s Behavior in the Private Product Market

In this appendix, we derive equation (13) and several related results on firm behav-
ior in the private market. We assume a downward-sloping private product demand
curve (ε > 0 ) and increasing composite returns to labor (ρ > 1 ), consistent with the
empirical evidence.
Ifd= 0, the firm’s profit maximization problem is,

```
maxL
0 jt
pH
```
#### 

```
ΦjtLρ 0 jt
 1 −ε
−κUUjtL1+ 0 jtθ−pβM
M
```
```
ΦjtLρ 0 jt, (38)
```
where we substituted equations (9) and (37) into equation (8) for the case withd= 0.

#### A2


The profit-maximizing first-order condition is,

```
∂π 0 jt
∂L 0 jt≡pHΦ
```
(^1) jt−ε(1−ε)ρL(1 0 jt−ρ)ε−(1−ρ)−ε
| {z }
MRP

#### −

#### 

```
κUUjt(1 +θ)Lθ 0 jt+βpM
M
```
```
ΦjtρL− 0 jt(1−ρ)
```
#### 

```
| {z }
MCL
```
#### = 0.

#### (39)

This expression shows thatL 0 jtonly varies across firms due toΦjtandUjt. We now
derive equation (13) and several implications. Equation (39) can be arranged as

```
markupz}|{−^1
(1−ε)
```
```
z P}|jt {
pHΦ−jtεL− 0 jtρε
```
```
z MP}|jt {
ΦjtρLρ 0 −jt^1 /κU
| {z }
MRPjt
```
#### =

```
markdownz }| {−^1
(1 +θ)
```
```
zW}|jt{
UjtLθ 0 jt
| {z }
MCLjt
```
#### +

```
sz}|{MPjt
pM
βM
```
```
z MP}|jt {
ΦjtρLρ 0 −jt^1 /κU
| {z }
marginal intermed. costs
```
#### , (40)

which is the same as equation (19), where we use thatβM =Qjt/MjtimpliespβMM =
pMMjt
Qjt =

```
pMMjt
QjtPjtPjt=
```
Xjt
RjtPjt.
We will now show that MRP is greater than MCL asL 0 jtapproaches zero. Mul-
tiplying marginal profits in (39) byLρε 0 jt+(1−ρ), which is strictly positive, we have

```
∂π 0 jt
∂L 0 jt
Lρε 0 jt+(1−ρ)=pHΦ^1 jt−ε(1−ε)ρ
| {z }
MRP×Lρε 0 jt+(1−ρ)
```
#### −

#### 

```
κUUjt(1 +θ)Lθ 0 +jtρε+(1−ρ)+pM
βM
ΦjtρLρε 0 jt
```
#### 

```
| {z }
MCL×Lρε 0 jt+(1−ρ)
```
#### . (41)

Note that MRP×Lρε 0 jt+(1−ρ)is constant with respect toL 0 jtand positive. By contrast,
givenθ+ρε+ (1−ρ)> 0 , then MCL×Lρε 0 jt+(1−ρ)converges to zero asL 0 jtapproaches
zero. Thus, we have shown thatlimL 0 jt→ 0 +∂π∂L^00 jtjt> 0. As a result, it is always optimal
to chooseL 0 jt> 0 ifθ+ρε+ (1−ρ)> 0.
Furthermore, multiplying both sides of equation (39) byL 0 jt, we have
∂π 0 jt
∂L 0 jt
≡pHΦ^1 jt−ε(1−ε)ρLρ 0 jt(1−ε)−κUUjt(1 +θ)L1+ 0 jtθ−pM
βM
ΦjtρLρ 0 jt= 0. (42)

Recall thatκUUjtL1+ 0 jtθ=βρLB 0 jt,R 0 Hjt=pHΦ^1 jt−εLρ 0 (1jt−ε), andX 0 jt=pβMMΦjtLρ 0 jt. Sub-
stituting, we have
(1−ε)RH 0 jt=1 +β θ
L

```
B 0 jt+X 0 jt. (43)
Similarly, ifd= 1, the firm’s profit maximization problem is,
```
#### A3


```
max
L 1 jt: ΦjtLρ 1 jt≥QG
```
```
pH
```
#### 

```
ΦjtLρ 1 jt−QG
```
```
 1 −ε
−κUUjtL1+ 1 jtθ−pβM
M
```
```
ΦjtLρ 1 jt. (44)
```
The first-order condition is,

```
∂π 1 jt
∂L 1 jt
≡pHΦjt(1−ε)ρ
```
#### 

```
ΦjtLρ 1 jt−QG
```
−ε
L− 1 jt(1−ρ)−κUUjt(1+θ)Lθ 1 jt−pM
βM
ΦjtρL− 1 jt(1−ρ)= 0.
(45)
AsΦjtLρ 1 jtapproachesQG,

#### 

```
ΦjtLρ 1 jt−QG
```
```
−ε
approaches infinity while all other terms
```
involvingL 1 jt approach constants. Thus,ΦjtLρ 1 jt >QGis necessary to satisfy the
equation. SinceQ 1 jt= ΦjtLρ 1 jt, it follows thatQH 1 jt=Q 1 jt−QG> 0 , so the winning
firm always produces for the private market. Furthermore, it is always true that
∂π 1 jt
∂L 1 jt|L^1 jt=L^0 jt>^0. Thus,Qdjtis larger ifd= 1thand= 0.
Multiplying both sides of equation (45) byL 1 jtand replacingRH 1 jt=pH

#### 

```
ΦjtLρ 1 jt−QG
```
```
 1 −ε
,
```
```
RH 1 jtΦjt(1−ε)
```
#### 

```
ΦjtLρ 1 jt−QG
```
#### − 1

```
Lρ 1 jt−1 +β θ
L
```
```
B 1 jt−X 1 jt= 0. (46)
```
SinceQH 1 jt= ΦjtLρ 1 jt−QGandQ 1 jt= ΦjtLρ 1 jt, it follows that

```
RH 1 jt(1−ε)Q^1 jt
QH 1 jt
−1 +β θ
L
```
```
B 1 jt−X 1 jt= 0. (47)
```
Thus, combining equations (43) and (47), we have equation (13).
Lastly, it is interesting to consider if winning a procurement project will lead
a firm to produce more for the private market (crowd-in) or less (crowd-out). To
determine this, we evaluate the marginal profits of the winner when the total output
isQˆ 1 jt≡QG+QH 0 jt; that is,Qˆ 1 jtis the hypothetical output of the firm in thed= 1case
such that there is neither crowd-in nor crowd-out. The winner would prefer to produce
more (less) thanQˆ 1 jtif the marginal profit is positive (negative, respectively). Let
the corresponding labor choice beLˆ 1 jtsuch thatΦjtLˆρ 1 jt−QG=QH 0 jt= ΦjtLρ 0 jt. Note
that, sinceρ > 1 andLˆρ 1 jt=Lρ 0 jt+QG/Φjt, thenLˆ 1 jt> L 0 jt. Evaluating equation
(45) atLˆ 1 jt, marginal profits for the firm if it wins and produces hypothetical output
Qˆ 1 jtare,

```
∂π 1 jt
∂L 1 jt
|L 1 jt=Lˆ 1 jt=pHΦjt(1−ε)ρ(QH 0 jt)−εLˆρ 1 −jt^1 −κUUjt(1 +θ)Lˆθ 1 jt−pM
βM
ΦjtρLˆρ 1 −jt^1. (48)
```
#### A4


Multiplying byL^11 −jtρand substitutingQH 0 jt= ΦjtLρ 0 jt, we have,

```
L^11 −jtρ∂π∂L^1 jt
1 jt
```
```
|L 1 jt=Lˆ 1 jt=pHΦ^1 jt−ε(1−ε)ρL− 0 jtρε−κUUjt(1 +θ)Lˆθ 1 +1jt−ρ−pβM
M
```
```
Φjtρ. (49)
```
Finally, substituting equation (42), this simplifies to,

```
L^11 −jtρ∂π^1 jt
∂L 1 jt
|L 1 jt=Lˆ 1 jt=κUUjt(1 +θ)(Lθ 0 +1jt−ρ−Lˆθ 1 +1jt−ρ). (50)
```
SinceLˆ 1 jt> L 0 jt, we have that∂L∂π^11 jtjt|L 1 jt=Lˆ 1 jt< 0 ifθ+1−ρ > 0 , and∂L∂π^11 jtjt|L 1 jt=Lˆ 1 jt> 0
otherwise. Therefore, winning a government project crowds-out private projects when
1 +θ > ρand crowds-in if1 +θ < ρ.

### A.3 Worker Rents Expressions

We derive the key expressions for worker rents in Section 2.5. First, following
Lamadon et al. (2022), total worker rents at firmjin yeartare,

```
Vjt(Wjt) =
```
```
ZWjt
```
```
0
```
```
(Wjt−W)dLdWjt(W)dW. (51)
```
Define ω ≡ WWjt so that dWdω = W^1 jt, and note that labor supply can be expressed

in termsωasL ̃(ωWjt) =ω^1 /θL(Wjt). Thus,dLdWjt(W)dW = dL ̃jt(dωωWjt)dω. Moreover,
dL ̃jt(ωWjt)
dω =Ljt(Wjt)
∂ω^1 /θ
∂ω , which implies

Vjt(Wjt) =Wjt

#### Z 1

```
0
```
```
(1−ω)d
L ̃(ωWjt)
dω dω=WjtLjt(Wjt)
```
#### Z 1

```
0
```
```
(1−ω)∂ω
```
```
1 /θ
∂ω dω=
```
```
WjtLjt(Wjt)
1 + 1/θ
```
Second, we derive the decomposition of incidence for incumbents and new hires.
LetIjtdenote the set of incumbent workers at firmj. For two potential wagesW 1 jt
andW 0 jt, the corresponding rentsV 1 ijtandV 0 ijtfor anyi∈Ijtmust satisfy,

Uit(j,W 1 jt−V 1 ijt) = maxj′̸=j Uit(j′,Wj′,t) and Uit(j,W 0 jt−V 0 ijt) = maxj′̸=j Uit(j′,Wj′,t).

Since the right-hand side is the same in both of these equations (that is, the outside
option is unchanged by a wage increase at the incumbent employer), it follows that
Uit(j,W 1 jt−V 1 ijt) = Uit(j,W 0 jt−V 0 ijt), ∀i ∈ Ijt, which can only be satisfied by

#### A5


V 1 ijt−V 0 ijt=W 1 jt−W 0 jt, ∀i∈Ijt. Thus, the incidence for incumbents is

```
X
Ijt
```
```
(V 1 ijt−V 0 ijt)
| {z }
Incidence for incumbents
```
```
= |{z}L 0 jt
Number of incumbents
```
```
× (|W 1 jt{z−W 0 jt})
Incidence for each incumbent
```
#### .

The incidence for new hires is then,

```
V| 1 jt{z−V 0 jt}
Incidence
```
−L| 0 jt(W (^1) {zjt−W 0 jt})
Incidence for incumbents

#### =

```
W 1 jtL 1 jt
1 + 1/θ −
```
```
W 0 jtL 0 jt
| 1 + 1/θ{z−L^0 jt(W^1 jt−W^0 jt})
Incidence for new hires
```
which can be rearranged as the decomposition in Section 2.5.

### A.4 Over-identifying Restriction

In this appendix, we derive equation (25). Taking the log of both sides of equation
(13) for thed= 1case, we have,

```
log(1−ε) +r 1 Hjt+q 1 jt−q 1 Hjt= log
```
#### 

```
1 +θ
βL B^1 jt+X^1 jt
```
#### 

#### .

From equation (7),rH 1 jt= logpH+ (1−ε)qH 1 jt, soqH 1 jt = 1 −^1 εrH 1 jt− 1 −^1 εlogpH. From
equation (10),q 1 jt=ρℓ 1 jt+φjt+ejt. Substituting, we have

log(1−ε)+r 1 Hjt+(ρℓ 1 jt+φjt+ejt)−

#### 

#### 1

```
1 −ε
rH 1 jt−^1
1 −ε
logpH
```
#### 

```
= log
```
#### 

```
1 +θ
βL
B 1 jt+X 1 jt
```
#### 

#### ,

which can be rearranged as equation (25).

## B Product Market with Perfect Competition

This section solves the firm’s problem in the private product market assuming the
firm is a price-taker (ε= 0). Denote the competitive price aspH. In terms of the
composite production functionQjt= ΦjtLρjt, the firm’s problem is

```
max
Ljt: ΦjtLρjt≥dQG
```
```
pH
```
#### 

```
ΦjtLρjt−dQG
```
#### 

```
−κUUjtL1+jtθ−pβM
M
```
```
ΦjtLρjt
```
where the government’s output must be produced if the firm receives a procurement
contract (ΦjtLρjt≥dQG). We consider three cases:
Supposed= 0. The government constraint is always satisfied, so we can ignore

#### A6


this constraint. The profit-maximizing solution is simplyQ 0 jt= ΦjtLρ 0 jtand

```
L 0 jt=
```
#### 

```
pH−βpM
M
```
#### 

```
Φjtρ
κUUjt(1 +θ)
```
```
θ+1^1 −ρ
.
```
Supposed= 1andQ 0 jt>QG. Then, the solutionLinterior 1 jt =L 0 jtandQinterior 1 jt =
Q 0 jtsatisfies the government constraint and otherwise solves the profit-maximization
problem, so this is the optimal solution. An implication is thatQinterior 1 jt is invariant
to marginal changes in the size of the government contract, i.e., government projects
crowd-out the firm’s private market production one-for-one. Since input costs are
not affected by receiving a procurement contract, the opportunity cost of receiving
a procurement contract is simply the loss in revenues in the private product market,
σinteriorjt =pH

#### 

```
Q 0 jt−
```
#### 

```
Qinterior 1 jt −QG
```
#### 

=pHQG.
Supposed = 1 andQ 0 jt ≤ QG. Then, the firm is at the corner solution in
which it only produces for the government market, i.e.,Qcorner 1 jt =QGandLcorner 1 jt =

QG/Φjt

```
 1 /ρ
```
. The opportunity cost isσcornerjt =pHQ 0 jt−

#### 

```
Tjt(L 0 jt)−Tjt
```
#### 

```
Lcorner 1 jt
```
#### 	

#### ,

whereTjt(L)≡κUUjtL1+θ+βpMMΦjtLρis the total cost of production using laborL.

## C Cobb-Douglas Production Function

### C.1 Cobb-Douglas Model: Composite Production Function

Consider a Cobb-Douglas production function (in physical units)

```
Qjt= ΩjtLβjtLKjtβKMjtβM. (52)
```
Given any production levelQjt, the firm can find the most cost efficient combination
(Ljt,Kjt,Mjt)by solving the cost-minimization problem,

```
L min
jt,Kjt,Mjt
Cjt s.t. Qjt= ΩjtLβjtLKjtβKMjtβM. (53)
```
whereCjt ≡ UjtL1+jtθ+pKKjt+pMMjt denotes the total cost. This leads to the
Lagrangian,

```
Ljt≡UjtL1+jtθ+pKKjt+pMMjt+λjt(Qjt−ΩjtKjtβKLβjtLMjtβM) (54)
```
#### A7


whereλjtis the Lagrange multiplier. The first-order conditions are:

```
pK=λjtΩjtβKKjtβK−^1 LβjtLMjtβM,
(1 +θ)UjtLθjt=λjtΩjtβLKjtβKLβjtL−^1 MjtβM,
pM=λjtΩjtβMKjtβKLβjtLMjtβM−^1.
```
#### (55)

We can use these first-order conditions to write the optimal choices of capital and
intermediate inputs as a function of labor

Kjt=ββK
L

```
(1 +θ)Ujt
pK L
```
```
1+jtθ=χ(K)UjtL1+jtθandMjt=βM
βL
```
```
(1 +θ)Ujt
pM L
```
1+jtθ=χ(M)UjtL1+jtθ
(56)
whereχ(K)≡ββKL(1+pKθ)andχ(M)≡ββML(1+pMθ). We can substitute these expressions into
Qjt= ΩjtLβjtLKjtβKMjtβMand obtain

```
Qjt= Ωjt
```
```
h
χ(jK)UjtL1+jtθ
```
```
iβK
LβjL
```
```
h
χ(jM)UjtL1+jtθ
```
```
iβM
= ΦjtLρjt (57)
```
whereΦjt≡Ωjt

#### 

```
χ(K)Ujt
```
```
βK
χ(M)Ujt
```
βM
andρ≡βL+ (1 +θ)(βK+βM). We can
also use equations (57) and equation (56) to rewrite the firm’s problem in the private
product market as

```
maxL
djt
πdjt=pH(ΦjtLρdjt−Q ̄Gd)^1 −ε−χ(W)UjtL1+djtθ, (58)
```
where cost-minimization impliesCdjt=χ(W)UjtLθdjt+1,χ(W)≡βρL≡

#### 

```
1 +(βM+ββKL)(1+θ)
```
#### 

#### .

### C.2 Cobb-Douglas Model: First-order Conditions

We now derive the profit-maximizing first-order conditions in the model with Cobb-
Douglas production. These derivations assumeρ≡βL+ (1 +θ)(βK+βM)> 1 and
ε > 0.
If the firm loses the auction, its profit maximization problem is

```
maxL
0 jt
pH(ΦjtLρ 0 jt)^1 −ε−χ(W)UjtL1+ 0 jtθ. (59)
```
The first-order condition is,

#### A8


```
ρ(1−ε)pHΦ^1 jt−εLρ 0 (1jt−ε)−^1 =χ(W)UjtLθ 0 jt(1 +θ), (60)
```
which implies,

```
L 0 jt=
```
#### "

```
ρ(1−ε)pHΦ^1 jt−ε
χ(W)Ujt(1 +θ)
```
#θ+1−ρ (^1) (1−ε)

. (61)

Thus 0 < L 0 jt<∞.
Similarly, if the firm wins the auction, the profit maximization problem is:

```
L max
1 jt: ΦjtLρ 1 jt≥Q ̄G
pH(ΦjtLρ 1 jt−Q ̄G)^1 −ε−χ(W)UjtL1+ 1 jtθ. (62)
```
The first-order condition is

```
∂π 1 jt
∂L 1 jt
≡ρ(1−ε)ΦjtpH(ΦjtLρ 1 jt−Q ̄G)−εLρ 1 −jt^1 −χ(W)UjtLθ 1 jt(1 +θ) = 0, (63)
```
which implies,

```
ρ(1−ε)ΦjtpH(ΦjtLρ 1 jt−Q ̄G)−ε=χ(W)UjtL1+ 1 jtθ−ρ(1 +θ). (64)
```
As ΦjtLρ 1 jt approachesQ ̄G, the left-hand side of equation (64) approaches infinity
while the RHS approaches a constant. Thus,ΦjtLρ 1 jt>Q ̄Gis necessary to satisfy the
equation. SinceQ 1 jt= ΦjtLρ 1 jt, it follows thatQH 1 jt=Q 1 jt−Q ̄G> 0 , so the winning
firm always produces for the private market.
Furthermore, since the solution is interior (i.e.,L 0 jt≥QG) due toε > 0 , equation
(60) impliesρ(1−ε)ΦjtpH(ΦjtLρ 0 jt)−εLρ 0 −jt^1 −χ(W)UjtLθ 0 jt(1 +θ) = 0and therefore
ρ(1−ε)ΦjtpH(ΦjtLρ 0 jt−Q ̄G)−εLρ 0 −jt^1 −χ(W)UjtLθ 0 jt(1 +θ)≡∂L∂π^11 jtjt|L 1 jt=L 0 jt> 0. Thus,
∂π 1 jt
∂L 1 jt|L^1 jt=L^0 jt>^0 , so total production will be larger if the firm receives a procurement
contract than if it does not.

### C.3 Cobb-Douglas Model: Identification

We now show identification of(1−ε,ρ,βL)in the model with a Cobb-Douglas pro-
duction function.
In thed= 0case, revenues are related to labor by

```
rjt= logpH+ (1−ε)φjt+ρ(1−ε)ℓjt (65)
```
#### A9


From this, we can identifyρ(1−ε)by regressingrjtonℓjtcontrolling forφjtamong
Djt= 0firms. In practice, we can control for(bujt,Zjt)in place ofφjtas in equation
(22) due to the invertibility of bids with respect to TFP, conditional on amenities.
Thus,ρ(1−ε)is recovered by the estimator

```
ρ\(1−ε)≡Cov[rjt,ℓjt|ubjt,Zjt,Djt= 0]
Var[ℓjt|ubjt,Zjt,Djt= 0]. (66)
In thed= 0case, equation (60) implies
```
```
ρ(1−ε)
RH 0 jt
L 0 jt
=χ(W)UjtLθ 0 jt(1 +θ).
```
Since we showed above that cost-minimization requiresCdjt=χ(W)UjtLθdjt+1, it follows
that
ρ(1−ε) = (1 +θ)CR^0 Hjt
0 jt

#### . (67)

Taking expectations in logs and rearranging, this yields another estimator that over-
identifiesρ(1−ε):

```
ρ^(1−ε)≡explog (1 +θ) +Ecjt−rHjt|Djt= 0. (68)
```
```
In thed= 1case, multiplying both sides of equation (63) byL 1 jtimplies
```
```
ρ(1−ε)ΦjtpH(ΦjtLρ 1 jt−Q ̄G)−εLρ 1 jt=χ(W)UjtLθ 1 +1jt(1 +θ) = (1 +θ)Cjt
```
Furthermore, since(ΦjtLρ 1 jt−Q ̄G)−ε= (QH 1 jt)−ε= (RH 1 jt/pH)^1 −−εε, we can rewrite this
expression as
ρ(1−ε)pH(RH 1 jt/pH)^1 −−εεΦjtLρ 1 jt= (1 +θ)Cjt

Taking logs,

```
logρ+ log(1−ε) + logpH+ −ε
1 −ε
r 1 Hjt− −ε
1 −ε
logpH+φjt+ρℓ 1 jt= log(1 +θ) +cjt
```
Rearranging, this gives,

```
cjt+ 1 −εεrHjt
| {z }
ΛCDjt (ε)
```
```
=constant+φjt+ρℓjt, (69)
```
where constant≡logρ+ log(1−ε) + 1 −^1 εlogpH−log(1 +θ). Thus, for any candidate

#### A10


value ofε, a regression ofΛCDjt (ε)onℓjtcontrolling forφjtfor the winners identifies
ρ. Sinceρ(1−ε)is identified above, this implies(1−ε)is uniquely determined by this
implicit system of equations.
Furthermore, since we showed above that cost-minimization requiresCjt=βρLBjt,
the expected labor share of costs is

```
βL
ρ =E
```
#### 

```
Bjt
Cjt
```
#### 

#### , (70)

so we identifyβLgivenρ.
In practice, we simultaneously estimate(1−ε,ρ,βL)by applying equally-weighted
GMM to equations (66), (68), (69), and (70).
For the remaining parameters, note thatXjt=(1+βθL)βMBjtandpKKjt=(1+βθL)βKBjt,
which implies the following expressions:

```
βM= exp
```
#### 

```
E[xjt−bjt]−log(1 +β θ)
L
```
#### 

#### , (71)

```
βK= exp
```
#### 

```
E[log (pKKjt)−bjt]−log(1 +β θ)
L
```
#### 

#### , (72)

```
E[ujt] =E[bjt]−(1 +θ)E[ℓjt], (73)
logpH=E[rjt]−ρ(1−ε)E[ℓjt], (74)
```
where we normalizeE[φjt] = 0without loss of generality.

## D Expected Impact of an Increase in Market Power

Set up: For simplicity, we consider a production function in which labor is the only
input, returns to scale are constant (ρ= 1), and firms can only sell output to the
private market when deriving theoretical predictions. We focus on firmjat timet,
omitting these subscripts without loss of generality, and normalize TFP asΦ = 1.
The production function is thenQ=L. This implies that revenue can be expressed
in terms of labor asR=pHL^1 −ε, so marginal revenue is MRP=pH(1−ε)L−ε. Since
labor is the only input, the marginal cost of production is given by the marginal cost of
labor, which is MCL=U(1+θ)Lθ. We solve for the baseline equilibrium by equating

#### A11


MRP and MCL. The baseline equilibrium is characterized byL=Q=

```
pH
U
1 −ε
1+θ
```
θ+ (^1) ε
,
P=pHL−ε,R=pHL^1 −ε, andWjt=ULθ.
Rotation of labor supply curve: We now consider a compensated rotation of
the labor supply curve. In particular, consider an (inverse) labor supply curve
W(L|U′,θ′) =U′Lθ′for someθ′̸=θ. This labor supply curve is a “rotation” around
the initial equilibrium only ifW

#### 

```
L|U′,θ′
```
#### 

=W; that is, the baseline labor quantity
receives the same wage after the rotation as it did in the baseline equilibrium. This
rotationW

#### 

```
L|U′,θ′
```
#### 

```
=W is solved by U′ = W L−θ
```
′
; that is, there is a unique
“compensation”U′−Uto the location parameter of the labor supply curve such that
W(L|U′,θ′)is a “rotation” around the initial equilibrium andθ′̸=θ.
Suppose labor supply is rotated to become more inelastic; that is,θ′> θ, which
also implies U′ < U. The new equilibrium satisfiesL′ = Q′ =
pH
U′
1 −ε
1+θ′

```
θ′^1 +ε
=
```
L

```
1+θ
1+θ′
```
```
θ′^1 +ε
```
. Since

```
1+θ
1+θ′
```
θ′^1 +ε
< 1 , thenL′<Land therebyQ′<Q. An implication
is thatpH(Q′)−ε> pH(Q)−ε, soP′>P. Another implication is thatW′=U′(L′)θ′=

U′

#### 

#### L

```
1+θ
1+θ′
```
```
θ′^1 +εθ′
=WUU′
```
```
1+θ
1+θ′
```
```
θ′θ+′ε
```
. Since UU′

```
1+θ
1+θ′
```
θθ′+′ε
< 1 , it follows thatW′<
W. Therefore, a compensated rotation of the labor supply curve to become less
elastic results in reductions in the firm’s employment, wage, and output, as well as
an increase in its price.

Rotation of product demand curve: We now consider a compensated rotation of
the product demand curve. In particular, consider an (inverse) product demand curve
P(Q|p′H,ε′) =p′HQ−ε′ for someε′̸=ε. This product demand curve is a “rotation”
around the initial equilibrium only ifP

#### 

```
Q|p′H,ε′
```
#### 

=P; that is, the baseline output
quantity receives the same price after the rotation as it did in the baseline equilibrium.
This rotationP

#### 

```
Q|p′H,ε′
```
#### 

```
=P is solved byp′H =PQε
```
′
; that is, there is a unique
“compensation”p′H−pHto the location parameter of the product demand curve such
thatP(Q|p′H,ε′)is a “rotation” around the initial equilibrium andε′̸=ε.
Suppose product demand is rotated to become more inelastic; that is,ε′ > ε,

which also impliesp′H> pH. The new equilibrium satisfiesL′=Q′=

```
p′
UH^1 1+−εθ′
```
θ+ (^1) ε′
=

#### A12


#### L

```
 1 −ε′
1 −ε
```
```
θ+^1 ε′
```
. Since

```
 1 −ε′
1 −ε
```
θ+^1 ε′
< 1 , thenL′<Land therebyQ′<Q. An implication
is thatU(L′)θ< U

#### 

#### L

```
θ
, soW′<W. Another implication is thatP′=p′H(Q′)−ε
′
=
```
p′H

#### 

#### Q

```
 1 −ε′
1 −ε
```
```
θ+^1 ε′−ε′
=Pp
```
```
′H
pH
```
```
 1 −ε′
1 −ε
```
```
θ−+εε′′
```
. Sincep

```
′H
pH
```
```
 1 −ε′
1 −ε
```
θ−+εε′′
> 1 , it follows thatP′>
P. Therefore, a compensated rotation of the product demand curve to become less
elastic results in reductions in the firm’s employment, wage, and output, as well as
an increase in its price.

Rotation of both labor supply and product demand curves: Lastly, we
consider rotating both the labor supply and product demand curves to become
more inelastic; that is, ε′ > εand θ′ > θ. Following the same logic as above,
L′=L

```
1+θ
1+θ′
1 −ε′
1 −ε
```
```
θ′^1 +ε′
.Since
```
```
1+θ
1+θ′
1 −ε′
1 −ε
```
```
θ′+^1 ε′
< 1 , thenL′ <Land therebyQ′<Q.
```
SinceW′=WUU′
1+θ
1+θ′
1 −ε′
1 −ε

```
θ′θ+′ε′
and UU′
1+θ
1+θ′
1 −ε′
1 −ε
```
```
θ′θ+′ε′
< 1 , it follows thatW′<W.
```
SinceP′ =Pp
′H
pH

```
1+θ
1+θ′^1 −ε
```
```
′
1 −ε
```
```
θ−′+ε′ε′
and p
′H
pH
```
```
1+θ
1+θ′^1 −ε
```
```
′
1 −ε
```
θ−′+ε′ε′
> 1 , it follows thatP′ > P.
Therefore, a simultaneous compensated rotation of both the labor supply and product
demand curves to become less elastic results in reductions in the firm’s employment,
wage, and output, as well as an increase in its price.
Lastly, we show that the impacts of increased market power in one market are
attenuated by the existence of market power in the other market. In particular, we
show that

```
∂^2 L
∂θ′∂ε′
```
(^)
(^)
{P(Q|p′H,ε′)=P, W(L|U′,θ′)=W}

#### =L^1

```
(θ+ε)^2
```
####  1

```
1 +θ
```
#### +^1

```
1 −ε
```
#### +^1

```
(1 +θ)(1−ε)
```
#### 

#### > 0.

Proof. We start withL=L

```
h(1+θ)(1−ε′)
(1−ε)(1+θ′)
```
```
iθ′^1 +ε′
, which implies
```
```
logL−logL=θ′+^1 ε′
```
#### 

```
log(1 +θ)(1−ε
```
#### ′)

```
(1−ε)(1 +θ′)
```
#### 

Settingθ=θ′ andε=ε′deliverslogL−logL= 0. We can calculate the following
derivatives:

#### A13


```
dlogL
dθ′ =
```
#### 1

#### L

```
dL
dθ′=−
```
#### 1

```
(θ′+ε′)^2
```
#### 

```
log(1 +θ)(1−ε
```
#### ′)

```
(1−ε)(1 +θ′)
```
#### 

```
−θ′+^1 ε′1 +^1 θ′
```
```
dlogL
dε′ =
```
#### 1

#### L

```
dL
dε′=−
```
#### 1

```
(θ′+ε′)^2
```
#### 

```
log(1 +θ)(1−ε
```
#### ′)

```
(1−ε)(1 +θ′)
```
#### 

```
−θ′+^1 ε′ 1 −^1 ε′
```
Substituting,

```
dL
dθ′=−
```
#### 

#### 1

```
(θ′+ε′)^2
```
#### 

```
log(1 +θ)(1−ε
```
#### ′)

```
(1−ε)(1 +θ′)
```
#### 

```
+θ′+^1 ε′1 +^1 θ′
```
#### 

#### L

```
dL
dθ′=−
```
#### 1

```
θ′+ε′
```
#### 

```
logL−logL+1 +^1 θ′
```
#### 

#### L

```
dL
dε′=−
```
#### 1

```
θ′+ε′
```
#### 

```
logL−logL+ 1 −^1 ε′
```
#### 

#### L

Thus,

```
d^2 L
dθ′dε′=
```
#### 1

```
(θ′+ε′)^2
```
#### 

```
logL−logL+1 +^1 θ′
```
#### 

```
L−θ′+^1 ε′Ldlogdε′L−dLdε′θ′+^1 ε′
```
#### 

```
logL−logL+1 +^1 θ′
```
#### 

#### =^1

```
(θ′+ε′)^2
```
#### 

```
logL−logL+1 +^1 θ′
```
#### 

```
L+θ′+^1 ε′
```
#### 

#### 1

```
θ′+ε′
```
#### 

```
logL−logL+ 1 −^1 ε′
```
#### 

#### L

#### +

#### 1

```
θ′+ε′
```
#### 

```
logL−logL+
```
#### 1

```
1 −ε′
```
####  1

```
θ′+ε′
```
#### 

```
logL−logL+
```
#### 1

```
1 +θ′
```
#### 

#### L

#### =^1

```
(θ′+ε′)^2
```
(^) 
logL−logL+1 +^1 θ′

#### 

#### L+

#### 

```
logL−logL+ 1 −^1 ε′
```
#### 

#### L

#### +

#### 

```
logL−logL+ 1 −^1 ε′
```
#### 

```
logL−logL+1 +^1 θ′
```
#### 

#### L

#### !

Finally, evaluating atL=L,θ=θ′, andε=ε′delivers:

```
d^2 L
dθ′dε′ =L
```
#### 1

```
(θ′+ε′)^2
```
#### 

#### 1

```
1 +θ′+
```
#### 1

```
1 −ε′+
```
#### 1

```
1 −ε′
```
#### 1

```
1 +θ′
```
#### 

#### > 0.

#### A14


## E Additional Institutional Details on the Construc-

## tion Industry and Procurement Auctions

### E.1 Prevalence of Non-wage Compensation

The Economic Census of the Construction Sector (EC), which is collected every five
years by the US Census Bureau, provides informative descriptive statistics on the
wage and non-wage compensation paid by the US construction industry. The EC
provides measures of non-wage compensation separately for legally-required fringe
benefits (social security, unemployment insurance, worker injury-compensation in-
surance, etc.) and voluntary fringe benefits (health insurance, pensions, training,
etc.), as well as total payroll. We analyze the EC data for the construction industry,
aggregated to the state-level at five-year frequency, for the period from 1977 to 2017.
In Online Appendix Figure A.10, we present the share of total compensation from
wages, legally-required fringe benefits, and voluntary fringe benefits over time. In
2012, which is near the end of the time frame considered in our main analysis, we find
that about 10% of total compensation is due to legally-required benefits and about
10% is due to voluntary benefits, with wages accounting for the remaining 80%. Thus,
voluntary benefits – which is the component of non-wage compensation that the firm
can in principle adjust – accounts for only one-tenth of total compensation in the
construction industry.
It is perhaps not surprising that the construction industry primarily compensates
workers through wages rather than voluntary benefits, as these benefits may be costly
to provide. Industry experts summarize the role of wages versus non-wage benefits
in recruiting workers to construction jobs by noting that “base pay has been the
single most important piece of compensation” and “benefits aren’t usually a driving
factor in recruiting.”^1 However, some workers may be offered non-wage benefits that
are proportional to wages, such as bonuses and incentives which are offered as a

(^1) See “What you need to know about compensation in construction” by Carpenter-Beck,
https://www.sage.com/en-us/blog/need-know-compensation-construction/.

#### A15


percentage of base salary and thus adjust when wages increase.^2 We show in Online
Appendix H that proportional adjustments in non-wage benefits do not introduce
bias in our estimation of the labor supply curve.

### E.2 Relevance of Prevailing Wage Laws

Prevailing wage laws require that workers employed by private construction firms on
government-funded construction projects be paid at least the wages and benefits paid
to similar workers in the same location where the project is located. The Davis-Bacon
Act was passed by Congress in 1931 to require that private construction firms pay
the prevailing wage to their employees on all federally-funded construction projects.
Subsequently, most state governments passed so-called “little Davis-Bacon” laws to
extend prevailing wage requirements to state-funded construction projects. However,
15 of those states have since repealed their prevailing wage laws.^3
One potential concern in our estimation of the labor supply elasticity is that first-
time procurement auction winners may become subject to the prevailing wage for
the first time, which could force them to increase the wages of incumbent workers,
independently of whether or not they hire new workers. In order for such an effect
to occur, three conditions would need to be satisfied. First, the firm must have
initial wages below the prevailing wage. This is unlikely to be true for many firms
in our sample, as we find that procurement auction participants (both winners and
losers) have higher than average wages in the pre-period. Second, even if the winning
firms had initial wages below the prevailing wage, prevailing wage laws would only
bind if the new wage after winning the procurement contract would not have met the
prevailing wage in the absence of a prevailing wage law. In the presence of an upward-
sloping labor supply curve, the wage increase required to recruit new workers may
reach the prevailing wage even among winners that did not initially pay the prevailing

(^2) See “Competitive pay to recruit and retain employees” by Robinson, https://www.sage.com/en-
us/blog/competitive-pay-to-recruit-and-retain-employees/. 3
The list of states that currently have prevailing wage laws as well as the history of repeals is pro-
vided by the US Department of Labor here: https://www.dol.gov/agencies/whd/state/prevailing-
wages.

#### A16


wage. Third, the procurement contract must be funded by a state government that
currently has a prevailing wage law, or be funded by the federal government.
To investigate if there are actually effects of prevailing wage laws, we use repeals
of state prevailing wage laws in a difference-in-differences analysis at the state-level to
examine how wage and non-wage compensation are impacted by prevailing wages. For
outcome measures, we use the EC data described above on wages and non-wage fringe
benefits in the construction sector. In Online Appendix Table A.8, the difference-in-
differences estimates for repeals suggest that prevailing wage laws have little to no
effect on total compensation, wages, non-wage fringe benefits, or the share of total
compensation from non-wage fringe benefits.^4 For example, the effect of a repeal on
the log wage in the construction industry is 0.009 with standard error 0.029, and
the effect on log non-wage fringe benefits in the construction industry is 0.015 with
standard error 0.031.

### E.3 Safety Regulations and Procurement Auctions

The construction industry is governed by extensive safety regulations. For example,
construction employers in California must comply with Cal/OSHA regulations found
in the following subchapters of California Code of Regulations, title 8, chapter 4:
subchapter 4 (Construction Safety Orders); subchapter 5 (Electrical Safety Orders);
and subchapter 7 (General Industry Safety Orders).^5 These regulations are typically
task-specific, e.g., California requires certification and various safety procedures to be
followed by crane operators.
It is important to observe that these safety regulations apply to all firms in the
construction industry. In particular, government procurement projects are governed
by the same safety regulations as private projects. Thus, receiving a procurement

(^4) Prior work, reviewed by Duncan and Ormiston (2019), has found little evidence that prevailing
wage laws increase wages in the construction industry. In their study of the first 9 repeals of
prevailing wage laws and outcomes only through 1993, Kessler and Katz (2001) find economically
small impacts on wages that become statistically insignificant when controlling for pre-trends. Our
analysis includes more recent repeals, effects on non-wage outcomes, and uses modern difference-in-
differences estimators for staggered treatment contexts (Callaway and Sant’Anna, 2020). 5
See https://www.dir.ca.gov/dosh/construction-guide-summary.html.

#### A17


contract does not change the safety regulations governing the construction firm. Sim-
ilarly, we have read the annual reports of public construction firms to examine the
language they use to describe participation in government projects.^6 While they dis-
cuss the costs and opportunities associated with government contracts, we find no
mention of changing safety policies in consideration of procurements.^7
While we find no legal requirement that safety must be improved in response to
winning a procurement auction, we may still worry that winning firms make safety
improvements. In order to check for such effects, we download publicly-available data
from OSHA safety inspections and link it to our procurement auction records. Since
each state provides OSHA data in a different format, we focused on the largest state
in our sample, California. Given our linked dataset between procurement auction
and OSHA records, we the used these data to run the same regression specification
as our baseline research design in equation (21), but now using safety investigations
and violations as the outcome variables.
Reassuringly, we find fairly precisely estimated zero effects on the probability of a
safety violation and on the probability of a safety investigation: As shown in Online
Appendix Table A.7, the point estimates are 0.000 and 0.009, with standard errors
0.006 and 0.008 respectively, for the safety violation and investigation probabilities.
These estimates suggest little if any impacts. By comparison, the probability of a
safety violation is 4.1% and the probability of an investigation is 7.5% in the year
that a firm is a bidder (both winners and losers) in an auction.

### E.4 Prevalence of Auctions with a Quality Dimension

Lewis and Bajari (2011) study a special type of auction, called an A+B auction, in
which firms bid both a price and a time-to-completion. A bid submission contains

(^6) We accessed annual reports using https://www.annualreports.com. E.g.,
the annual report for Granite Construction Inc, one of the the largest auc-
tion winners in the procurement auction records for California, is available at
https://www.annualreports.com/HostedData/AnnualReports/PDF/NYSE_GVA_2022.pdf.
(^7) Although receiving a procurement contract does not lead to different safety regulations, a history
of serious workplace safety violations may be a reason to deny a firm the chance to participate in a
procurement auction at the pre-qualification phase.

#### A18


a dollar amount, the “A” component, and a total number of days to complete the
project, the “B” component. The score is a weighted sum of these two components,
and the bidder with the lowest score wins. The A+B design provides an incentive for
the bidder to disrupt traffic for a shorter period of time, and it is rarely used outside
a few categories of construction projects that require road lane or shoulder closure.
The empirical context considered by Lewis and Bajari (2011) is California DOT
procurement auctions during 2003-2008. They restrict the sample of auctions to the
small set of project types that are more likely to use the A+B format. They also
restrict the analysis to 5 districts (4, 6, 8, 11, and 12) that use the A+B format more
frequently, with most auctions coming from the San Francisco Bay Area. Even with
such selective sampling, among 708 auctions that fit the criteria, only 80 have the
A+B format. The contracts auctioned through the A+B format are exceptionally
large: the average engineer’s estimate is $21.9 million for A+B auctions versus $4.6
million for other auctions.
To examine the prevalence of the A+B design in our analysis sample, we identify
the list of A+B auctions in our 2001-2015 California DOT procurement auction data.
In this sample, only 4.2% of auctions use the A+B format. We also check how these
auctions enter our regressions. Recall that we only use auctions with a first-time
winner to implement our estimation of the labor supply curve. In all of California
during our sample period, only 12 auctions use the A+B format and are won by a
first-time winner. Thus, A+B auctions comprise a very small share of our estimation
sample for California.
Among the few auctions that use the A+B format in our sample, one may worry
that the ultimate payment differs significantly from the total bid. According to Lewis
and Bajari (2011), “standard contracts typically finish 7% early, whereas A+B con-
tracts finish exactly on time.” More specifically, in their sample, 52% of the A+B
contracts are completed exactly on time. Completing on time means that the pay-
ment equals the part A bid. Using the A+B auctions that satisfy their sample time
frame and districts, we find that about 87% of the total bids are determined by the
A price component rather than the B time-to-completion component, suggesting that
the price-only auction might remain a good approximation. We find similar statistics

```
A19
```

using the A+B auctions that fit our analysis sample criteria.
Another paper discussing auctions with a quality dimension is Takahashi (2018).
He considers so-called design-bid auctions, in which each bidder submits a design
and a price bid, and the price-per-quality score ratio determines the winner. In his
sample from the Florida DOT between 2000 and 2011, only 152 auctions are design-
bid auctions. In this case, quality-and-price-based auctions are again exceptions.

### E.5 Prevalence of Subcontracting

Along with the project announcement, DOT publishes a detailed project description,
including an engineer’s estimate of the size and cost of each item. The winners of
procurement auctions may subcontract some of those project items to be completed
by other firms. However, data on subcontracting is limited, so there has been little
empirical research on subcontracting.
The California DOT requires that bidders settle all subcontracting agreements
prior to bid submission. Bidders must list all project items that will be subcon-
tracted, along with the prices that will be paid to associated subcontractors. While
subcontracting agreements are not available in a readily-usable data form, Balat et al.
(2017) digitized this information from bidding documents submitted to the California
DOT for projects auctioned between 2002 and 2016. Because their sample overlaps
well with ours, their summary statistics represent ours well.
Using their data on subcontracting in California procurement auctions, Balat
et al. (2017) find that subcontracting is common, with about 95% of auction winners
subcontracting at least one item in road or bridge projects. However, the amount of
subcontracting relative to the total value of the project is small. They find that, for
the average (median) winner of a procurement contract, subcontractors only account
for 8% (4%) of the bid value of the project. Thus, for the largest state in our data,
subcontracting accounts for a relatively small share of the bid value.

#### A20


## F Details on Labor Supply Elasticity Estimators

### F.1 Identification using the LMS Estimator

Following Lamadon et al. (2022, LMS), we consider instrumenting for long-differences
in log labor using short-differences in log value added (VA). Denoting the short-
difference in log VA by∆vajt≡logVAjt−logVAjt− 1 , the estimator of LMS is,

```
θb∆va≡Cov[wjt+e−wjt−e′,∆vajt]
Cov[ℓjt+e−ℓjt−e′,∆vajt].
```
Unlike the estimators of Propositions 3–4, this estimator does not make use of infor-
mation on procurement auctions and thus can be applied to the entire construction
industry rather than only construction firms that bid for procurement projects.
Consider the following assumption, which compares short-run changes in VA to
longer-run changes in TFP and firm-specific amenity shocks:

Assumption 1.Suppose ∃e,e′ > 0 sufficiently large such that (i)φjt+e−φjt−e′ is
correlated with∆vajt, and (ii)∆vajtis orthogonal toνjt+e−νjt−e′.

```
We then have the following result:
```
Proposition 6.Under Assumption 1 and the rank condition Cov[(ℓjt+e−ℓjt−e′),∆vajt]̸=
0 ,bθ∆varecoversθ.

Proof. By equation (4),

```
θb∆va=Cov[θ(ℓjt+e−ℓjt−e′),∆vajt]
Cov| [(ℓjt+e−{zℓjt−e′),∆vajt}]
=θ
```
```
+Cov[(νjt+e−νjt−e
′),∆vajt]
Cov| [(ℓjt+e−{zℓjt−e′),∆vajt}]
= 0
```
```
=θ,
```
where the denominator of each term is non-zero (i.e., the rank condition is satisfied)
by Assumption 1(i) and the second term is zero by Assumption 1(ii).

The key result, the exclusion condition Cov[(νjt+e−νjt−e′),∆vajt] = 0, relies on
the assumption that firm-specific amenity shocks are transitory while TFP shocks are
persistent. Thus, short-run VA growth is correlated with long-run employment growth

```
A21
```

(satisfying the rank condition due to persistence in TFP shocks), but orthogonal to
long-run firm-specific amenity shocks. In practice, we must take a stand on the
persistence of the transitory shocks. LMS argue that these transitory shocks are well-
approximated as a moving average of order one, in which case, Assumption 1 holds
as long ase≥ 2 ,e′≥ 3 and TFP shocks persist for at leasteperiods. We use the
same choices ofeande′as LMS in our empirical implementation.

### F.2 Implementation of RDD Estimators

We now describe the implementation of the RDD estimation defined in Proposition

4. Recall that, for a firmjthat bids in auctionιat timet, we define the loss margin
asτjt ≡ Zjt−Z
    ∗ι
Zι∗ , whereZ∗ι is the winning bid in auctionι. We can interpretτjt as
a measure of proximity to the discontinuity, satisfyingτjt= 0for auction winners
(Djt= 1) andτjt> 0 for auction losers (Djt= 0). The regression specification is,

1 {τjt≤τ}wjt+e=

#### X

```
e′̸= ̄e
```
```
1 {τjt≤τ} 1 {e′=e}μτte′
| {z }
event time fixed effect
```
#### +

#### X

```
j′
```
#### X

```
ι′
```
```
1 {τjt≤τ} 1 {j′=jandι′=ι}ψτj′ι′t
| {z }
firm-auction fixed effect
(75)
+
```
#### X

```
e′̸= ̄e
```
```
1 {τjt≤τ} 1 {e′=e}Djtλτte′
| {z }
treatment status by event time
```
```
+ 1|{τjt≤{zτ}εjte}
residual
```
#### ,

where we have fully interacted the regression with the indicator 1 {τjt≤τ}to remove
any control units that do not place close bids to the winning firms. The parameterλτte
recovers the numerator ofθRDD(τ)for a particular choice ofτ, pair(e,t), and ̄e=− 2
is the omitted event time. As in the baseline implementation, we estimateλτtefor allt
andeand then average acrosst, using the delta method to compute standard errors.
The analogous regression in whichℓjt+eis the outcome recovers the denominator of
θRDD(τ). We average across event timeseto form the main estimate.
As an alternative implementation of the RDD estimator defined in Proposition
4, consider a regression that controls for the loss margin, rather than restricting the

#### A22


sample based on the loss margin, as,

```
wjt+e=
```
#### X

```
e′̸= ̄e
```
```
1 {e′=e}μte′
| {z }
event time fixed effect
```
#### +

#### X

```
j′
```
#### X

```
ι′
```
```
1 {j′=jandι′=ι}ψj′ι′t
| {z }
firm−auction fixed effect
```
#### (76)

#### +

#### X

```
e′̸= ̄e
```
```
1 {e′=e}Djtλte′
| {z }
treatment status by event time
```
#### +

#### X

```
e′̸= ̄e
```
```
1 {e′=e}ρe(τjt)
| {z }
polynomial in loss margin
```
```
+ |{z}εjte
residual
```
#### ,

whereρe(τjt)is an event time-specific polynomial in the loss margin τjt. In prac-
tice, we consider a linear specification,ρe(τjt) =φeτjt, and a third-order polynomial
specification,ρe(τjt) =φ 1 eτjt+φ 2 eτjt^2 +φ 3 eτjt^3.

### F.3 Implementation of Local Labor Market Estimators

Letmdenote the market in which the firm participates, and letJm denote the set
of firms that participate in marketm. Possible markets include the auction in which
the firm bids or the commuting zone in which the firm employs workers. Our goal
is to estimateθDiD while controlling for market-specific shocks. To do so, we will
implement the Proposition 3 estimator separately by market, allowing each market
to experience its own sequence of event time effects.
Consider the cohort of firms that receive a procurement contract in yeart(Djt= 1)
and the set of comparison firms that bid for a procurement in yeartbut lose (Djt= 0).
Letedenote an event time relative tot. For each event timee=− 4 ,..., 4 , our DiD
estimation for marketmis implemented as

```
wjt+e=
```
#### X

```
e′̸= ̄e
```
```
1 {e′=e}μmte′
| {z }
market-specific event time fixed effect
```
#### +

#### X

```
j′
```
```
1 {j′=j}ψj′t
| {z }
firm fixed effect
```
#### (77)

#### +

#### X

```
e′̸= ̄e
```
```
1 {e′=e}Djtλmte′
| {z }
treatment status by event time
```
```
+ |{z}εjte
residual
```
```
among j∈Jm
```
#### A23


where, for marketm,λmterecovers the numerator ofθmDiDfor a particular pair(e,t)and
̄e=− 2 is the omitted event time. This estimator differs from the baseline specification
in that it only considers comparison firms that participate in the same market as the
firm that receives a procurement contract, ensuring that market-specific shocks are
controlled. In particular, market-specific shocks are captured by theμmteparameters.
The analogous regression in whichℓjt+eis the outcome recovers the denominator of
θDiDm. We average across event timeseto form the main estimate. Finally, we average
θDiDm across all of the marketsmto form the overallθDiDestimate that controls flexibly
for market-specific shocks.

#### A24


## G Additional Tables and Figures

```
DOT Auction Records Final Sample: Matched Auction-Tax Data
State Data Source Includes EIN Bidders in 2010 Share of 2010 Construction Sector:
(Num. Firms) Value Added FTE Workers
ALAR State WebsiteState Website 77 196149 15.7%7.9% 17.4%12.8%
```
AZCA State WebsiteNo (^77) 1,041* 8.3%* 11.2%*
COCT FOIA RequestFOIA Request 37 241126 12.6%9.4% 14.7%15.5%
FLGA State WebsiteBidX Website 37 344137 30.7%4.3% 10.6%7.0%
IAID BidX WebsiteBidX Website 77 256112 15.4%17.2% 20.7%13.6%
ILIN State WebsiteNo 73 213 * 10.6%* 16.6%*
KSKY BidX WebsiteNo (^37130) * 13.7%* 21.6%*
LAMA BidX WebsiteNo (^77167) * 11.5%* 10.8%*
MDME BidX WebsiteNo 77 141 * 13.7%* 16.9%*
MIMN BidX WebsiteBidX Website (^77391262) 13.5%9.5% 16.3%19.8%
MOMS BidX WebsiteNo (^77179) * 14.9%* 13.3%*
MTNC FOIA RequestBidX Website 77 122135 15.0%5.2% 23.6%9.8%
NDNE FOIA RequestNo 77 ** ** **
NHNJ NoNo 77 ** ** **
NMNV BidX WebsiteNo 77 ** ** **
NYOH BidX WebsiteNo 77 320 * 43.7%* 17.5%*
OKOR NoNo 77 ** ** **
PASC NoNo 77 ** ** **
SDTN BidX WebsiteNo 77 140 * 5.3%* 11.5%*
TXUT FOIA RequestNo (^37551) * 4.9%* 9.6%*
VAVT BidX WebsiteBidX Website (^77241) * 14.2%* 12.0%*
WAWI BidX WebsiteBidX Website (^77200194) 12.1%7.5% 14.0%14.6%
WV BidX and State Websites 3 103 13.7% 19.0%
National 6,792 10.7% 9.9%
Table A.1: Summary of Auction Data by State
Notes: The first two columns provide information on in-state DOT data sources by state, where
“state” refers to the state in which the auction occurred. The first column indicates the source from
which we obtained data on that state’s DOT auctions, and the second column indicates whether or
not EINs were included in the auction records. The final three columns provide information on the
final sample of firms in the matched auction-tax data, where “state” refers to the state in which the
firm filed taxes. Among firms in the construction industry in 2010, the last two columns consider the
share of value added and FTE workers due to the firms that participated in auctions in our sample.
We drop from these calculations firms that have missing values on the variables displayed, so the
total sample size must be smaller than in Online Appendix Table A.2. An asterisk (*) denotes that
number of bidders is non-zero but below the disclosure threshold.
A25


```
Share of the
Sample Size Construction Sector
Number of Firms 7,876 0.9%
Workers per Firm 46 11.7%
Value Per Firm Share of the
($millions) Mean of the Log Construction Sector (%)
Sales 19.927 15.061 12.1%
EBITD 9.159 14.075 9.6%
Intermediate Costs 14.661 14.719 12.4%
Wage bill 2.737 13.549 13.4%
```
Table A.2: Sample Characteristics
Notes: This table displays descriptive statistics for the sample of firms that place bids in 2010. The
third column compares aggregates for this sample to all firms in the construction industry in the
2010 tax records.

Figure A.1: Chassang et al. (2022) Visual Test for Collusion
Notes: This figure displays the histogram of bid competition for each of the 28 states in our sample.
Negative values indicate the difference between the winner’s bid and the bid of the runner-up.
Positive values indicate the difference between each loser’s bid and the winner’s bid. Differences
are scaled by the winner’s bid in each case. Chassang et al. (2022) demonstrate that, under some
assumptions on the auction environment, these differences should display discontinuities in the
histogram near zero if there is collusion.

```
A26
```

```
Effect on Employment Effect on Earnings Implications for Labor Market
Parameter Elasticity Markdown
Estimate Std. Err. Estimate Std. Err. θ 1 /θ (1 +θ)−^1
Panel A) By Proximity:
Any Proximity 0.083 (0.019) 0.020 (0.008) 0.245 4.084 0.803
Proximity 1.0 0.083 (0.019) 0.021 (0.008) 0.251 3.991 0.800
Proximity 0.5 0.080 (0.019) 0.020 (0.008) 0.251 3.980 0.799
Proximity 0.4 0.079 (0.020) 0.022 (0.008) 0.277 3.608 0.783
Proximity 0.3 0.079 (0.020) 0.022 (0.008) 0.281 3.559 0.781
Proximity 0.2 0.079 (0.021) 0.020 (0.009) 0.257 3.892 0.796
Proximity 0.1 0.065 (0.025) 0.019 (0.010) 0.286 3.491 0.777
Panel B) By Proximity for Stayers:
Any Proximity 0.083 (0.019) 0.023 (0.006) 0.278 3.600 0.783
Proximity 1.0 0.083 (0.019) 0.024 (0.006) 0.283 3.530 0.779
Proximity 0.5 0.080 (0.019) 0.022 (0.006) 0.277 3.605 0.783
Proximity 0.4 0.079 (0.020) 0.023 (0.006) 0.294 3.403 0.773
Proximity 0.3 0.079 (0.020) 0.023 (0.006) 0.288 3.467 0.776
Proximity 0.2 0.079 (0.021) 0.021 (0.007) 0.271 3.689 0.787
Proximity 0.1 0.065 (0.025) 0.019 (0.007) 0.286 3.499 0.778
Panel C) By Worker Incumbency:
Stayer Spell: (− 1 ,...,1) 0.083 (0.019) 0.023 (0.005) 0.272 3.681 0.786
Stayer Spell: (− 2 ,...,2) 0.083 (0.019) 0.023 (0.006) 0.278 3.600 0.783
Stayer Spell: (− 3 ,...,3) 0.083 (0.019) 0.021 (0.007) 0.253 3.957 0.798
Tenure: 1 Year 0.083 (0.019) 0.023 (0.006) 0.277 3.615 0.783
Tenure: 2 Years 0.083 (0.019) 0.023 (0.006) 0.277 3.615 0.783
Tenure: 3 Years 0.083 (0.019) 0.025 (0.006) 0.301 3.326 0.769
Tenure: 4 Years 0.083 (0.019) 0.022 (0.006) 0.266 3.766 0.790
Panel D) By Employment Intensity:
Add Indep. Contractors 0.092 (0.021) 0.020 (0.009) 0.220 4.548 0.820
110% of FTE Wage 0.083 (0.019) 0.023 (0.006) 0.276 3.627 0.784
120% of FTE Wage 0.083 (0.019) 0.022 (0.006) 0.266 3.755 0.790
130% of FTE Wage140% of FTE Wage 0.0830.083 (0.019)(0.019) 0.0220.021 (0.006)(0.006) 0.2640.256 3.7883.909 0.7910.796
150% of FTE Wage 0.083 (0.019) 0.019 (0.006) 0.230 4.346 0.813
Panel E) Interacted DiD Designs:
Fully-interacted: CZ 0.074 (0.019) 0.017 (0.009) 0.224 4.467 0.817
Fully-interacted: Auction 0.088 (0.027) 0.018 (0.009) 0.206 4.846 0.829
Panel F) LMS Passthrough Regressions:
Full Construction Industry 0.087 0.023 0.266 3.758 0.790
Full Construction Industry, Control CZ 0.092 0.027 0.299 3.349 0.770
Table A.3: Specifications for Estimating the Parameterθ
```
Notes: This table presents estimates of the impacts of winning a procurement contract on employ-
ment and earnings per worker in the post-treatment time period. Employment and earnings per
worker are measured in log units. Proximity refers to the largest value ofτjtpermitted in the sample.
Specification details and sample definitions are provided in the main text.

#### A27


```
−0.2
```
```
0.0
```
```
0.2
```
```
0.4
```
```
0.6
```
```
0.8
```
```
1.0
```
```
−5 −4 −3 −2 −1 0 1 2 3 4
Event Year
(a) Indicator for First-time Winning
```
```
0.0
```
```
0.2
```
```
0.4
```
```
0.6
```
```
0.8
```
```
1.0
```
```
−5 −4 −3 −2 −1 0 1 2 3 4
Event Year
DiD: No Proximity ControlRDD: Proximity 0.3 RDD: Proximity 0.2RDD: Proximity 0.1
```
```
(b) Indicator for Any Wins
Figure A.2: Visualizing the Research Design
```
Notes: This figure presents estimates based on equation (21) of the impacts of winning a procurement
contract. The omitted event time is− 2. The outcomes considered are the probability of winning
an auction for the first time (subfigure a) and the probability of winning any auction in the current
year (subfigure b). It provides these estimates separately by event year. Proximity refers to the
largest value ofτjtpermitted in the sample. 95% confidence intervals are displayed in brackets.
Specification details and sample definitions are provided in the main text.

```
Design: DiD RDD
Proximity: Any 0.3 0.2 0.1
Impact: Before Treatment -0.003 0.003 0.003 -0.007
(0.013) (0.019) (0.020) (0.024)
Impact: After Treatment 0.010 0.017 0.016 0.009
(0.011) (0.017) (0.018) (0.021)
```
```
Table A.4: Impacts of Winning a Procurement Contract: Earnings of New Hires
```
Notes: This table presents estimates of the impacts of winning a procurement contract on the log
earnings per worker at the new employer among new hires in the post-treatment and pre-treatment
time periods. Proximity refers to the largest value ofτjtpermitted in the sample. Specification
details and sample definitions are provided in the main text.

#### A28


```
Design: DiD RDD
Proximity: Any 0.3 0.2 0.1
Impact: Before Treatment -0.002 -0.009 -0.003 0.004
(0.019) (0.027) (0.029) (0.034)
Impact: After Treatment 0.009 0.012 0.014 0.023
(0.016) (0.024) (0.026) (0.030)
```
```
Table A.5: Impacts of Winning a Procurement Contract: Quality of New Hires
```
Notes: This table presents estimates of the impacts of winning a procurement contract on worker
quality. Worker quality is measured by log earnings per worker in the previous firm. Proximity refers
to the largest value ofτjtpermitted in the sample. Specification details and sample definitions are
provided in the main text.

```
−0.05
```
```
0.00
```
```
0.05
```
```
0.10
```
```
0.15
```
```
−5 −4 −3 −1 0 1 2 3 4
Event Year
DiD: No Proximity ControlRDD: Proximity 0.3 RDD: Proximity 0.2RDD: Proximity 0.1
```
```
(a) Outcome: Log Number of Employees
```
```
−0.02
```
```
0.00
```
```
0.02
```
```
0.04
```
```
−5 −4 −3 −1 0 1 2 3 4
Event Year
DiD: No Proximity ControlRDD: Proximity 0.3 RDD: Proximity 0.2RDD: Proximity 0.1
```
```
(b) Outcome: Log Earnings per Employee
Figure A.3: DiD and RDD Estimates of the Effects of Winning a Procurement
```
Notes: This figure displays estimates of the effects of winning a procurement contract on winners
relative to losers across event times. The winner is announced during event time 0 and outcomes
are normalized to zero for both winners and losers in event time -2. All specifications control for
time-invariant auction and firm characteristics as well as time fixed effects. The outcomes are log
employment in subfigure a and log earnings per employee in subfigure b. Proximity refers to the
largest value ofτjtpermitted in the sample. 95% confidence intervals are displayed in brackets.

#### A29


```
−0.01
```
```
0.00
```
```
0.01
```
```
0.02
```
```
0.03
```
```
0.04
```
```
(−1) Stayer Spell (Event Times)(−1,...,1) (−2,...,2) (−3,...,3)
Event Time Before After
(a) Stayer Definitions
```
```
−0.01
```
```
0.00
```
```
0.01
```
```
0.02
```
```
0.03
```
```
0.04
```
(^1) Years of Tenure (Count) 2 3 4
Event Time Before After
(b) Tenure Definitions
−0.01
0.00
0.01
0.02
0.03
0.04
(^100110) Share of FTE Wage (%) 120 130 140 150
Event Time Before After
(c) FTE Definitions
Figure A.4: Impacts on log Earnings per Worker: Sensitivity to Worker Sample
Notes: This figure presents estimates based on equation (21) of the impacts of winning a procure-
ment contract. The outcome considered is log earnings per worker. It provides these estimates
for alternative sample definitions for stayers (subfigure a), tenured workers (subfigure b), and full-
time equivalence (FTE) thresholds as a percentage of the annualized minimum wage (subfigure c).
95% confidence intervals are displayed in brackets. Specification details and sample definitions are
provided in the main text.
A30


```
RDD Implementations Time Heterogeneity Worker Heterogeneity Alternative Estimators
```
```
Proximity 0.3Proximity 0.2Proximity 0.1
Polynomial in Bids
```
```
Linear in BidsEvent Year 0Event Year 1Event Year 2All Event YearsAdd Contractors
```
```
Tenure125% FTE150% FTE
```
```
Fully−interacted: Auction
Fully−interacted: CZ
```
```
LMS Design
LMS Design, Control CZ
```
```
0
```
```
1
```
```
2
```
```
3
```
```
4
```
```
5
```
```
6
```
```
7
```
```
(a) Labor Supply Elasticity, 1 /θ
```
```
RDD Implementations Time Heterogeneity Worker Heterogeneity Alternative Estimators
```
```
Proximity 0.3Proximity 0.2Proximity 0.1
Polynomial in Bids
```
```
Linear in BidsEvent Year 0Event Year 1Event Year 2All Event YearsAdd Contractors
```
```
Tenure125% FTE150% FTE
```
```
Fully−interacted: Auction
Fully−interacted: CZ
```
```
LMS Design
LMS Design, Control CZ
```
```
0.5
```
```
0.6
```
```
0.7
```
```
0.8
```
```
0.9
```
```
1.0
```
```
(b) Wage Markdown relative to MRPL,(1 +θ)−^1
```
Figure A.5: Specification Checks: Estimates of the Labor Supply Elasticity and Wage
Markdown

Notes: This figure presents the sensitivity checks for the estimates of the labor supply elasticity, 1 /θ,
and the wage markdown relative to MRPL,(1 +θ)−^1. Specification details and sample definitions
are provided in the main text.

```
A31
```

```
0
```
```
1
```
```
2
```
```
3
```
```
4
```
```
5
```
```
6
```
```
7
```
```
(−1) Stayer Spell (Event Times)(−1,...,1) (−2,...,2) (−3,...,3)
(a) Stayer Definitions: Labor Supply Elasticity
```
```
0.5
```
```
0.6
```
```
0.7
```
```
0.8
```
```
0.9
```
```
1.0
```
```
(−1) Stayer Spell (Event Times)(−1,...,1) (−2,...,2) (−3,...,3)
(b) Stayer Definitions: Wage Markdown
```
```
0
```
```
1
```
```
2
```
```
3
```
```
4
```
```
5
```
```
6
```
```
7
```
(^1) Years of Tenure (Count) 2 3 4
(c) Tenure Definitions: Labor Supply Elasticity
0.5
0.6
0.7
0.8
0.9
1.0
(^1) Years of Tenure (Count) 2 3 4
(d) Tenure Definitions: Wage Markdown
0
1
2
3
4
5
6
7
(^100110) Share of FTE Wage (%) 120 130 140 150
(e) FTE Definitions: Labor Supply Elasticity
0.5
0.6
0.7
0.8
0.9
1.0
(^100110) Share of FTE Wage (%) 120 130 140 150
(f) FTE Definitions: Wage Markdown
Figure A.6: Labor Supply Elasticity and Wage Markdown: Sensitivity to Worker
Sample
Notes: This figure presents estimates of the labor supply elasticity, 1 /θ, and the wage markdown
relative to MRPL,(1 +θ)−^1 for alternative sample definitions for stayers (subfigure a-b), tenured
workers (subfigure c-d), and full-time equivalence (FTE) thresholds as a percentage of the annualized
minimum wage (subfigure e-f). Specification details and sample definitions are provided in the main
text.
A32


```
All States Prevailing Wage States
All Workers Stayers All Workers Stayers
Impacts of Winning an Auction:
Log Employment: 0.083 0.081
(0.019) (0.023)
Log Earnings per Worker: 0.020 0.023 0.023 0.027
(0.008) (0.006) (0.010) (0.007)
Implied Labor Parameters:
Labor Supply Elasticity: 4.084 3.600 3.508 3.054
Markdown relative to MRPL: 0.803 0.783 0.778 0.753
```
```
Table A.6: Impacts of Winning a Procurement Contract: Prevailing Wage States
```
Notes: This table presents estimates of the impacts of winning a procurement contract on log
employment and log earnings per worker in the post-treatment time period. It provides the impacts
on log earnings per worker separately for all workers in the firm and stayers. It compares all states
to states that have a state-specific prevailing wage requirement. Specification details and sample
definitions are provided in the main text.

```
OSHA Investigations OSHA Violations
Probability Count Probability Count
Occurrence
Observed Average: 0.075 0.139 0.041 0.110
Impacts of Winning a Procurement Auction
Impact: Before Treatment 0.000 -0.012 0.000 -0.009
(0.006) (0.016) (0.004) (0.018)
Impact: After Treatment 0.009 0.004 0.000 -0.006
(0.008) (0.020) (0.006) (0.023)
```
Table A.7: Impacts of Winning a Procurement Contract: OSHA Safety Outcomes in
California

Notes: This table presents estimates of the impacts of winning a procurement contract on OSHA
safety investigations and violations in California during 2001-2015. The observed average is reported
for bidders (winners and losers) in the years of active bidding.

#### A33


```
0.6
```
```
0.7
```
```
0.8
```
```
0.9
```
```
1.0
```
```
200120022003200420052006200720082009201020112012201320142015
```
```
Figure A.7: Interquartile Range in TFP by Year
```
Notes: This figure presents the interquartile range of TFP estimated separately by calendar year.
Specification details and sample definitions are provided in the main text.

```
0.00
```
```
0.25
```
```
0.50
```
```
0.75
```
```
1.00
```
```
1.25
```
```
MidwestNortheast South West
```
```
(a) Estimate of 1 −ε
```
```
0.8
```
```
1.0
```
```
1.2
```
```
1.4
```
```
MidwestNortheast South West
```
```
(b) Implied Price Markup
Figure A.8: Heterogeneity across Census Regions in the Estimate of 1 −ε
```
Notes: This figure presents heterogeneity across Census regions in the estimate of 1 −εusing the
estimator in equation (24), as well as the implied price markup(1−ε)−^1.

#### A34


```
−100
```
```
0
```
```
100
```
```
200
```
```
300
```
```
400
```
(^20) Percentile in TFP Distribution of Firms 40 60 80
Outcome relative toMedian TFP Firm (%)
Labor Wage Wage bill Output Profits
(a) Outcomes
0
100
200
(^20) Percentile in TFP Distribution of Firms 40 60 80
Outcome relative toMedian TFP Firm (%)
Total RentsFirms Total RentsWorkers Total RentsWorkers Share
(b) Total Rents
Figure A.9: Outcomes and Rents for Alternative TFP Percentiles, among Firms
without Procurement Contracts (Djt= 0)
Notes: In this figure, we assign alternative TFP quantiles to the median-TFP firm in theDjt= 0
sample without changing any other primitives of the model, then re-solve the model to obtain this
firm’s alternative outcomes and rents. The x-axis displays the alternative TFP assigned to the firm
(as a percentile in the population TFP distribution). Each y-axis value is expressed as a percent
change relative to the actual value for the median-TFP firm.
0
20
40
60
80
(^1977198219871992) Survey Year 1997 2002 2007 2012 2017
Share of Total Compensation (%)
Compensation Type Legally−Required Benefits Voluntary Benefits Wages
Figure A.10: Survey Evidence from the Economic Census of the Construction Sector:
Sources of Compensation in the Construction Industry
Notes: This figure uses survey data from the Economic Census of the Construction Sector to estimate
the share of total compensation from legally-required benefits, voluntary benefits, and wages. See
Appendix E.1 for details.

#### A35


```
Total Wage Non-wage Share Non-wage
Compensation Compensation Fringe Benefits Fringe Benefits
(log) (log) (log) (fraction)
Difference-in-Differences for State Davis-Bacon Repeals
0.009 0.009 0.015 0.000
(0.026) (0.029) (0.031) (0.005)
```
```
Table A.8: Impacts of Repeals of State Prevailing Wage Laws
```
Notes: This table combines information on repeals of state prevailing wage laws with survey data
from the Economic Census of the Construction Sector to estimate the impacts of prevailing wage
law repeals on wage and non-wage compensation. See Appendix E.2 for details.

```
0
```
```
1
```
```
2
```
```
3
```
```
4
```
```
5
```
```
6
```
```
7
```
```
−20 −15 −10 −5 0 5 10 15 20
Percent Increase in Compensation relative to Wages
Estimator DiD RDD
(a) Labor Supply Elasticity
```
```
0.5
```
```
0.6
```
```
0.7
```
```
0.8
```
```
0.9
```
```
1.0
```
```
−20 −15 −10 −5 0 5 10 15 20
Percent Increase in Compensation relative to Wages
Estimator DiD RDD
(b) Wage Markdown relative to MRPL
```
Figure A.11: Sensitivity to Allowing Endogenous Amenity Responses to Winning a
Procurement Auction
Notes: In this figure, we allow for amenity responses to winning a procurement auction, and adjust
theθDiDandθRDDestimates to account for these amenity responses. See Appendix H for details.

#### A36


## H Sensitivity to Assuming there are Causal Effects

## of Winning an Auction on Amenities

Let Compjtdenote the total compensation offered by the firm (inclusive of wages and
amenities). If we observed Compjt, we could infer the (inverse) labor supply elasticity

with respect compensation from the estimandeθ=E[∆ logCompE[∆ℓjtjt||ττjtjt=0=0]]−−EE[[∆∆ logℓjt| 0 Comp<τjt≤jtτ|]^0 <τjt≤τ].
In practice, however, we only observe wages Wjt, so we use∆ logWjt in place of
∆ logCompjt.
We now examine how the key conclusions regarding the labor supply curve would
change if log compensation in reality increased more (or less) than log earning. To
do so, it is useful to defineλ≡ E[∆ logE[∆ logCompWjtjt||ττjtjt=0=0]]−−EE[[∆ log∆ logWCompjt| 0 <τjt|^0 jt<τ≤τjt]≤τ]− 1 , so that
λ×100%is the percent increase in log compensation relative to log wages. Ifλ= 0,
then the change in compensation is proportional to the change in wages. In this
case, there is no bias in using wages in place of total compensation when estimating
θ. However, ifλ > 0 (orλ < 0 ), then the change in log compensation is greater
(or smaller) than the change in log wages, so the estimate ofθusing wages may be
downward-biased (or upward-biased).
In Online Appendix Figure A.11, we calibrateλ×100%and examine how our
conclusions would change if winning a procurement auction had a causal effect on
amenity provision. We find that, even in the rather extreme case in which log com-
pensation increases by 20% more (or less) than log earnings due to amenity responses,
the labor supply curve is upward sloping with an elasticity that would be close to our
baseline estimates in Figure 3. Furthermore, there is still a significant wage markdown
relative to MRPL, and it is close to our baseline estimates using log wages.

## I Computational Details

Overview: Simulating model outcomes is computationally challenging. Since 1 /θ
and− 1 /εboth appear in the firm’s opportunity costσ(φjt,ujt)(recall the definition
associated with equation 8), it follows that changing these parameters also changes the
optimal bidZjt∗ (equation 14). In turn, the bid affects the additional rents captured

```
A37
```

by firms from winning a procurement contract. To simulate from the model, we first
solve the second stage problem for eachφjtto find the distribution of opportunity
costs. Next, we solve the first stage problem to obtain the distribution of optimal
bids given the opportunity costs. Finally, we combine the optimal bid distribution
from the first stage with the optimal private market profits from the second stage.
From this, we recover all outcomes. To ease the computational burden in solving for
these distributions we implement the quantile representation method of Luo (2020).
Our main results focus on outcomes for the typical firm (the firm with the median
value ofφjt), which further reduces the computational burden.

Second stage: Denote the TFP quantile function as φ(α) where, for example,
α = 0. 10 indicates the 10th quantile of the TFP distribution. We use a log Nor-
mal distribution to approximate the distribution of TFP, which allows for a simple
mapping betweenφ andα, choosing the standard deviation that matches the in-
terquartile range of TFP (reported in Table 2). For each combination of winner
status, TFP quantile, and auction size

#### 

```
d,α,Q ̄G
```
#### 

, we solve the second-stage problem
for firm and worker outcomes. This is done by numerical optimization of the profit
function (equation 8) subject to the labor supply curve (equation 2), the production
function (equation 9), and optimal intermediate inputs (equation 10).

First stage: The challenge is to compute expectations of the second-stage across
the distribution of outcomes from the first-stage. To solve the first-stage, note that the
opportunity cost of winning an auction of sizeQGisσ

#### 

```
α|QG
```
#### 

```
=πH 0 (α)−πH 1
```
#### 

```
α|QG
```
#### 

#### .

SinceπH 1 jtis the winning firm’s revenue in the private market net of the total cost,
it follows thatπH 0 jt> π 1 Hjtand thusσ > 0. π 1 His decreasing inQG, andπH 0 does not
depend onQG. Moreover,σis decreasing inα. In other words, a higher TFP firm has
a lower opportunity cost of producing in the government procurement market. Sinceα
represents quantiles of TFP, it has the standard uniform distribution. The probability
that the winning quantile is less thanαis the probability that it is the lowest among all
Ibidders’ draws from the standard uniform distribution, yielding the probabilityαI
and associated density functionf 1 (α,I) =IαI−^1. By similar reasoning, the density

#### A38


function of a losing firm’s TFP quantile isf 0 (α,I) =I−I 1 (1−αI−^1 ).

Solution: LetYd

#### 

```
α|QG
```
#### 

```
denote a second-stage outcome for a firm characterized
```
by TFP quantileαbidding in an auction of sizeQG. Using the distribution func-
tions from the first stage, we compute the expected outcome as E

```
h
Yd|QG,I
```
i
=
R 1
0 Yd

#### 

```
α|QG
```
#### 

fd(α,I)dα. For example, the probability that a bidder with TFPφjt
wins the project is the probability that its TFP is the highest among all participating
bidders, i.e,H(φjt)I,whereHdenotes the distribution of TFP. This implies that the
density function of the winner’s TFP isIH(φjt)I−^1 h(φjt). The profit function de-
pends on who wins the auction, in particular, the TFP of the winner. The expected
profit of the winner is then

```
̄π 1 jt=
```
#### Z

```
π 1 jt(φjt|QG)[IH(φjt)I−^1 h(φjt)]dφjt=
```
#### Z

```
π 1 jt(φjt(α)|QG)IαI−^1 dα.
```
Note that this expectation depends on the combinations

#### 

#### QG,I

#### 

. One possibility is

to solve the model for each possible combination of

#### 

#### QG,I

#### 

, and then average across
them. In our setting, this is computationally infeasible. An alternative is to evaluate
QG,I

#### 

```
at representative values. In practice, we choose the values of
```
#### 

#### QG,I

#### 

that
provide the best fit to the additional rents from procurement projects,(Vjt∆,πjt∆),
for the typical firm. The best fit yields a model-simulated incidence on workers of
about $6,500, which is the same as the main estimate in Table 4, and incidence on
firms of $9,200, which is very close to the main estimate of about $9,600 in Table 4.
The implied incidence share on workers is about 41%, which is about the same as
our main estimate. The best fit is achieved atI= 5bidders per auction, which is
in the right ballpark to the mean observed value in the data of around 8 bidders per
auction.

Additional details: We now provide the derivation of the quantile representation
of the optimal bidding strategy. Consider a standard first-price auction model. Fol-
lowing Guerre et al. (2000), we can rewrite the first-order condition and obtain a

#### A39


representation of the cost as a function of observables:

```
c=b−I−^111 −h(Hb)(b),
```
where H(·)and h(·)are the bid distribution and density, respectively. Since the
bidding strategy is strictly increasing, we can further rewrite this expression in terms
of quantiles:

```
c(α) =b(α)−I−^11 [1−α]b′(α),
```
where c(·)and b(·)are the cost quantile function and the bid quantile function,
respectively. The boundary condition is that the least efficient firm bids the highest,
i.e.,c(1) =b(1).Following Luo (2020), we solve this ODE and obtain the mapping
from the cost quantile function to the bid quantile function:

```
b(α) = (I−1)(1−α)^1 −I
```
#### Z 1

```
α
```
```
c( ̃α)(1−α ̃)I−^2 dα. ̃
```
This representation is convenient for numerically solving the first-price procurement
auction model.

#### A40


## S Online Data Supplement

### S.1 Acquisition and Preparation of Auction Data

This supplement describes our data sources for auction bids and how we build the
data set for our main application. Online Appendix Table A.1 provides a summary
of the sources of DOT records by state.

Bid Express Auction Records

The Bid Express website collects information on bids and bidders for procurement
auctions held by Departments of Transportation of many US states. It can be freely
accessed atwww.bidx.com, although the access to information on the bidders requires
a paid account registration. We obtained 17 states’ DOT auction records from Bid
Express. We performed the download using the Python librarySeleniumto automate
browser actions. We registered a BidX.com account, which is required to access bidder
information.
We collect the auction information for a given state using the following procedure:

1. We go to the web page of that state on BidX.com and select the latest letting.
    Browser actions: visitwww.bidx.com, select the desired agency from “Select a
    U.S. Agency” drop down menu and click the button “go”. An illustration is
    provided in Appendix Figure S.1a. Then click the “Letting” tab on the top left
    corner of the new refreshed web page and click the first letting date hyperlink
    in “List of Letting” table. An illustration is provided in Appendix Figure S.1b.
2. There are two different sources of information - “Apparent Bids” and “Bid Sum-
    mary” - on a letting page. More specifically, “Apparent Bids” and “Bid Sum-
    mary” contain auction information but in different formats, and both of them
    have links to additional bidder information, which requires a paid account to
    access. Starting from the latest letting page, our function clicks the hyperlink
    “Apparent Bids” (Appendix Figure S.1c) then downloads a csv file for every

#### S1


bidder by clicking on the bidder hyperlink (Appendix Figure S.1d) and “Ex-
port(csv)” on the refreshed page.

```
(a) Front Page (b) Letting Page
```
```
(c) Apparent Bids Page (d) Bid Summary Page
Figure S.1: Web Pages from BidX.com
```
If there is no information on the refreshed page, it moves to a new letting by
clicking the arrow with html class “prev_arrow”. The procedure is iterated until
the arrow is not clickable. We repeat the same procedure for the “Bid Summary”
hyperlink.

Through this procedure, we obtain three tables for each letting:

```
a. auction information from “Apparent Bids”, which contains: bidder names,
bidder ID, bidder ranks, bid amounts, bidder call orders, project descrip-
tion, counties, letting ID and letting date. We do note that a few states
record two extra variables: DBE Percentage and DBE Manual.
b. auction information from “Bid Summary”, which contains: bidder names,
bidder ID, bidder ranks, bid amounts, bidder call orders, counties, proposal
ID and letting date.
```
```
S2
```

```
c. additional bidder information from bidder links, which contains: company
name, company address, company phone number, company fax number.
```
```
We then merge the table c into a and b. Therefore, two files are created for
every letting, one for “Apparent Bids” and one for “Bid Summary” with both
auction and firm level information.
```
The information at the letting level is then further aggregated for each state as follow:

1. For a stateX, we merge its “Apparent Bids” files into one single fileX_apparentbid
    and “Bid Summary” files into one single fileX_bidsummary. Then we add a new
    variableState, which is the two-letter abbreviation of states, inX_apparentbid
    andX_bidsummary.
2. Then we find lettings that are inX_bidsummarybut not inX_apparentbid, and
    augment them so that they have the same variables as lettings inX_apparentbid.^1
    The variables added are filled with “N/A”. Then we merged these lettings with
    X_apparentbidinto one fileX_all
3. We merge all*_all files into one final file.

As a result, we obtain a comprehensive file that has the following variables: Date
of the auction, unique auction identifier, name of the bidding firm, address of the
bidding firm, unique firm identifier, total bid amount, and state in which the auction
occurred.

State-specific Auction Records

We obtained auction records on 12 other states from two types of sources: down-
loading from state-specific bidding websites (7 states) and submitting Freedom of
Information Act (FOIA) requests to state governments (5 states). Each dataset in-
cluded different variables and were organized in different formats. For example, the
data from Texas included 121 variables while the data from West Virginia included

(^1) Proposal inX_bidsummaryis treated as Letting ID.

#### S3


only 11 variables. We harmonized these datasets focusing on the core set of variables:
Date of the auction, unique auction identifier, name of the bidding firm, address of
the bidding firm, unique firm identifier, total bid amount, and state in which the
auction occurred.
Note that one state, West Virginia, transitioned from its own website to Bid
Express in 2011, so we use combined records from both sources. Once harmonized,
we combined the various state-specific DOT auction records with the records obtained
from Bid Express.

EIN Availability

We were able to obtain the EINs for firms that bid in DOT auctions in six states:

- Florida, Indiana, and West Virginia: These states’ DOT auction records were
    downloaded from state-specific websites. The EINs were available from these
    websites.
- Colorado and Kansas: These states’ DOT auction records were obtained through
    FOIA requests. The requested data included EINs.
- Texas: This state’s DOT auction records were obtained through a FOIA request.
    Although this request did not include EINs, we were able to look up EINs by
    firm name and address through a Texas state government website: https:
    //mycpa.cpa.state.tx.us/coa/.

### S.2 Matching Auction Data to Tax Records

This supplement describes the procedure adopted to match the bidders in our auction
sample to the tax data. For a subset of bidders, the EIN is available in the auction
data, providing a unique identifier for the matching. For those observations an exact
matching can be performed. We refer to this subset of perfect matches as thetraining
data. In any other case, we rely on the fuzzy matching algorithm described below.
The procedure takes advantage of some regularities in the denomination of firms
and common abbreviations to improve the quality of matching. Furthermore, in order

```
S4
```

to properly distinguish different branches of the same company, additional information
on value added or state will be used.

Overview of denominations

Generally, a business name consists of three parts: a distinctive part, a descriptive
part, and a legal part.^2 The distinctive part is named by the business owner and is
usually required by governments to be “substantially different” from any other existing
name. The descriptive part describes what the business does, or its sector.^3 Finally,
the legal part refers to the business structure of a corporation. For example, for the
name “Rogers Communications Inc.”, “Rogers” is the distinctive part, “Communica-
tion” is the descriptive part, and “Inc.” is the legal part. Most of the discrepancies
of company names between different sources arise from the descriptive and the legal
parts, since they are more subject to be abbreviations or common synonyms.
The legal part of corporation names takes a fairly small number of denominations,
therefore can be identified using a properly constructed dictionary and treated sep-
arately. Conversely, disentangling the distinctive and the descriptive parts is not as
straightforward. However, conventionally, the descriptive part follows the distinctive
one within the string. This observation motivates a procedure that gives more weight
to the first words within a company name, since they are more likely to be part of
the distinctive part.

Legal-Parts Dictionary

In order to construct a uniform abbreviation in the legal part, we constructed a
many-to-one dictionary using a subsample of our training data. We manually select
abbreviations (including for misspelled words) by comparing mismatched names for
the same firm in multiple databases. For example, “Incorporated” appears as “Inc.”

(^2) Although there are no specific regulations on this naming structure, it is in alignment with
naming convention and government guidelines. https://www.ic.gc.ca/eic/site/cd-dgc.nsf/
eng/cs01070.html 3
An example would be California Code of Regulations for business entities. https:
//www.sos.ca.gov/administration/regulations/current-regulations/business/
business-entity-names/#section-21000
S5


Algorithm 1Matching Algorithm Pseudocode

“INC”, “Incorp” and so on in our data. Therefore, these abbreviations, when found,
are mapped into “Incorporated” as described below. Our dictionary and matching
algorithm are available upon request for replicability.

Matching Algorithm

We now describe the database matching algorithm (written in Python). A pseudocode
representation of this procedure is provided in Appendix Algorithm 1. For each
company name in the auction database, the algorithm searches the best match in
the tax database. Although the algorithm is meant for the comparison of corporate
names, it can be augmented with additional information if available. In our main
application, the auction data contains information about the name and the state of
origin of the bidding firms. The latter can be used to improve the quality of the
matching by using a “blocking” procedure that prioritizes firms from the same origin
state, as explained below. Letabe the firm,Sabe the firm’s string name andStatea
be the firm’s state of origin. The state of origin is only used if thestate option is

```
S6
```

enabled in the code provided. The algorithm proceeds as follow.

1. Name Normalization
    All non-alphanumeric characters with the exception of spaces are removed from
    Sa and all letter characters are capitalized. Consecutive white spaces are re-
    placed with one white space. Any sub-string separated by one space is consid-
    ered a “word”. Every word in the legal-parts dictionary is removed. For example,
    “Amnio Brothers Inc.” is composed by the three words “Amnio” “Brothers” and
    “Inc.”. After the first step, it would be normalized to “AMNIO BROS”, since
    the word “Brothers” is recognized in our dictionary as a synonym for “BROS”
    and “Inc.” is recognized in our dictionary as a legal part and therefore removed.
    We refer to the normalized string asSanorm. The same normalization is applied
    to every company name in the tax database. If the normalized name is not
    unique in the tax database, we restrict to the ones that ever filed at least one
    of the three firm tax returns (1120,1120-S or 1065). If the same firm name filed
    multiple firm tax returns, we select the one with highest value added, as the
    firm with greater value added is participating in more economic activity and
    therefore more likely to be the firm that participated in the auction.
2. Shortlisting
    Let Snorma be composed by n ≥ 2 words. Starting from the first word, we
    search in the list of normalized tax data company names the subset of names
    that contains that word. If the subset is empty, no matching occurs and the
    matching forAends. If the subset is a singleton,Ais paired with the unique
    element of the set and the shortlisting step ends for A. If the subset has more
    than one element, we proceed with the second word inSnorma and consider only
    the candidate matches that also contain the second word. If the set still contains
    more than one element, we proceed with the third word and so on, until all then
    words are used or we obtain either a singleton or an empty set. If this iteration
    leads to a singleton,Ais paired with the unique element of the set. If it leads
    to an empty set, thenAis paired with the smallest non-empty subset from the
    previous iterations. In short, this step selects a shortlist of candidate matches

```
S7
```

```
that share, after normalization, the highest number of initial words with A.
If the state option is enabled, only firms that match exactly theStatea are
considered for shortlisting.
```
3. Scoring
    This step employs the Levenshtein ratio (LR), a widespread measure of distance
    between strings, to select the best match from the shortlist. For each element of
    the set paired toAwe compute its LR with respect toSa. The company whose
    name has the highest score is selected as the match. If multiple companies tie
    for the top score, the one with the highest value added is selected. If the option
    strictis enabled, all the company names that do not reach a minimum threshold
    T∈(0,1)in their LR are dropped. If all candidate matches are dropped, then
    Ais considered unmatched. Hence the higher theT, the more stringent is the
    matching process. In our application, we consideredT= 0. 6.

Appendix Table S.1 illustrates how the algorithm works with an example search, using
“Hannaford Bros. Distribution Co.” as the search query. In our example,strictand
stateare disabled.

In-Sample Algorithm Validation

In order to validate the algorithm, we apply it to the subset of firms for which we
were provided the EIN by the state DOT, thus allowing us to link records exactly
rather than using the algorithm (the “Known EIN” sample). The results are displayed
in Appendix Table S.2. In Column (1), we provide results from using a simple string
matching algorithm, in which a firm in the auction database is only matched to a
firm in the tax database if they have identical names. In Columns (2-5), we apply
our approach presented in Appendix Algorithm 1. Overall, the algorithm outper-
forms string matching in both accuracy and number of matches achieved. In our
preferred specification in column (5), the algorithm correctly matches 84.5 percent of
the bidders whose EIN are known and could be found in tax database. The use of

#### S8


```
Steps Output
String Normalization Normalized Name: HANNAFORD BROS DISTRIBUTION
```
```
Shortlisting
```
```
The names(in bracket) and normalized names in the shortlist are shownbelow. The shared word is in bold.
KELLYHANNAFORD BROS DISTRIBUTION(Kelly Hannaford
HANNAFORD BROS DISTRIBUTIONBrothers Distribution Company)(Hannaford Brothers Distri.
C.)
HASTINGHannaford Bros. Distribution Inc.)HANNAFORD BROS DISTRIBUTION(Hasting
```
```
Scoring
```
```
Normalized names in the shortlist are shown below.The scores are shown on the right of the names.
KELLY HANNAFORD BROS DISTRIBUTIONHANNAFORD BROS DISTRIBUTION(LR =1)(LR = 0.9)
HASTING HANNAFORD BROS DISTRIBUTION(LR =0.87)
Unique match HANNAFORD BROS DISTRIBUTION(Hannaford Brothers Distri. C.)
```
```
Table S.1: Example Search
```
theStateoption proves effective in increasing the number of true matches, while the
Strictoption withT= 0. 6 improves accuracy by reducing the false matches.

Out-of-Sample Algorithm Validation

In order to assess the external validity of the algorithm outside our specific appli-
cation, we constructed two test data sets using data from the Employee Benefits
Security Administration (ESBA). Our test data sets,PensionDataandPensionTest,
are constructed using Form 5500 data sets that are published by the Employee Ben-
efits Security Administration (ESBA)^4. Form 5500 data sets contain information,
including company names and EINs, about the operations, funding and investments
of approximately 800,000 business entities. We consider both retirement and Health
and Welfare data sets, drop every variable except the Company Name and EIN, then
remove duplicate observations. For every unique EIN, we find all names that are asso-
ciated with it, then we discard any duplicate names. Most of the EINs are associated
with multiple company names, which reproduces a challenge in the tax database. For
each EIN, if multiple names are associated with it, we select the first name and put

(^4) https://www.dol.gov/agencies/ebsa/researchers/data
S9


```
Simple Search Fuzzy Match
(1) (2) (3) (4) (5)
% Bidders Matched to Any Tax Record 80.2 99.9 97.6 99.9 95.8
% Bidders Matched to the True Tax Record 65.3 63.0 62.5 71.0 70.3
% Potential Matches Correctly Matched to Tax Records 78.6 75.8 75.1 85.4 84.5
Algorithm Parameters:
Match must be perfect (string score = 1.0) X 7777
Match must be high-quality (string score≥ 0 .6) 77 X 7 X
Prefer matches in same state as auction X 77 XX
```
```
Table S.2: In-Sample Algorithm Validation
```
Notes:This table provides summary statistics on the in-sample performance of the matching algo-
rithm when applied to the six states that provided EINs. For these six states, we observe the true
match between auction and tax records. Since some contractors are individuals rather than firms
or are otherwise not required to file one of the three firm tax forms, not all contractors in auction
data have a true match in firm tax records. First row provides share of contractors in the auction
data that the algorithm matches to a firm tax record. Second row provides share of contractors in
the auction data that the algorithm matches to a firm tax record and the match is true. Third row
provides share of contractors in the auction data that the algorithm matches to a firm tax record
and the match is true, among contractors in the auction data for which the true match exists in the
firm tax data.

in into thePensionDatadata set and all the others into thePensionTestdata set. If
there is only one name associated with the EIN, we still add that name intoPension-
Data. This gives us 709,850 companies inPensionTest and 1,270,079 companies in
PensionData. We then proceeded to test our program usingPensionDataas a main
data set andPensionTestas a query set.

```
T 0 0.2 0.4 0.6 0.8 0.9 1
Matches 99.05% 99.04% 98.46% 91.68 % 74.52% 64.44% 49.01%
Correct
Matches
```
```
70.36% 70.37% 70.57% 73.39 % 80.69% 84.12% 82.58%
```
```
(a) Performance for Values ofT
Quantile 1% 10% 30% 50 % 70% 90% 99%
Length 1 1 1 1 2 37 2733
(b) Quantiles of Shortlist Lengths
Table S.3: Out-of-Sample Algorithm Validation using Pension Data
```
```
We tested the program by searching inPensionDataall the 709 , 850 PensionTest
```
```
S10
```

firms. Since we have the EIN for all the names in the two data sets, we can evaluate
the matching performance. The program achieved an average speed of 152 queries
per second and an average accuracy of 73.39 percent among matched queries for a
T = 0. 6 using thestrict option. Appendix Table S.3a presents the percentage of
correctly matched firms and false matches for different values ofT. We note that
the percentage of correct matches is not monotone inT whenT is close to 1. In
fact, requiring extreme level of string similarity leads to a loss of correct matches that
outweighs the gains in precision. Therefore, we do not recommend settingT above
0. 9. In Appendix Table S.3b, instead, we provide a closer look at the effectiveness
of the shortlisting step. Looking at the distribution of the shortlists’ length, we see
that over50%of the sample is matched at the shortlisting step and 70 percent of the
candidate matches requires the scoring of at most 2 candidates. Furthermore, the
99 th percentile of the longest shortlist amounts to 2 , 733 candidates. This is only 0. 2
percent of the potential matches that a standard matching algorithm would have to
consider for each query and, therefore, much more efficient.

### S.3 Description of the Tax Data

All firm-level variables are constructed from annual business tax returns over the
years 2001-2015: C-Corporations (Form 1120), S-Corporations (Form 1120-S), and
Partnerships (Form 1065). Worker-level variables are constructed from annual tax
returns over the years 2001-2015: Direct employees (Form W-2) and independent
contractors (Form 1099).
Tax Return Variable Definitions:

- Earnings: Reported on W-2 box 1 for each Taxpayer Identification Number
    (TIN). Each TIN is de-identified in our data.
- Employer:The Employer Identification Number (EIN) reported on W-2 for a
    given TIN. Each EIN is de-identified in our data.
- Employees:Number of workers matched to an EIN in year t from Form W-2
    with annual earnings above the annualized full-time minimum wage and where

```
S11
```

```
the EIN is this worker’s highest-paying employer.
```
- Wage bill: Total earnings among employees in year t.
- Independent contractors: Number of workers matched to an EIN in year t
    from Form 1099-MISC with annual compensation above the annualized full-time
    minimum wage.
- NAICS Code:The NAICS code is reported on line 21 on Schedule K of Form
    1120 for C-corporations, line 2a Schedule B of Form 1120S for S-corporations,
    and Box A of form 1065 for partnerships.
- Sales:Line 1 of Form 1120 for C-Corporations, Form 1120S for S-Corporations,
    and Form 1065 for partnerships. Also referred to as gross revenues.
- Intermediate Input Expenditures:Line 2 of Form 1120 for C-Corporations,
    Form 1120S for S-Corporations, and Form 1065 for partnerships. Also referred
    to as cost of goods sold.
- EBITD:We follow Kline et al. (2019) in defining Earnings Before Interest,
    Taxes, and Depreciation (EBITD) as the difference between total income and
    total deductions other than interest and depreciation. Total income is reported
    on Line 11 on Form 1120 for C-corporations, Line 1c on Form 1120S for S-
    corporations, and Line 1c on Form 1065 for Partnerships. Total deductions
    other than interest and depreciation are computed as Line 27 minus Lines 18
    and 20 on Form 1120 for C-corporations, Line 20 minus Lines 13 and 14 on
    Firm 1120S for S-corporations, and Line 21 minus Lines 15 and 16c on Form
    1065 for partnerships.

Procurement Auction Variable Definitions:

- Bid: The dollar value submitted by the firm as a price at which it would be
    willing to complete the procurement project.
- Auction winner: A firm is an auction winner if it placed the lowest bid in a
    procurement auction.

```
S12
```

- Amount of winnings:Bid placed by the winner in each auction.
- Year of first win: First year in which the firm is an auction winner. To
    account for left-censoring, we do not define a win as a “first win” unless there
    were at least two observed years of data during which the firm could have won
    and did not win an auction. For example, if a state provided auction records
    for 2001-2015, and a firm is first observed winning in 2001 or 2002, we do not
    consider this firm a first-time winner, but if the firm is first observed winning
    in 2003 or later, we consider it a first time winner.

Firm Sample Definitions:

- Baseline sample: A firm that files Form 1120, 1120-S, or 1065 is considered
    part of the baseline sample centered around auction cohorttif it is observed
    bidding in an auction in yeart.
- Sample of non-winners:A firm in the baseline sample attthat does not win
    an auction before or duringtis called a non-winner if it continues to not win
    any auctions until at least relative timee≥ 4. For example, ift= 2005, then
    a non-winner must not win its first auction until at least 2009.
- Sample of first-timers: A firm in the baseline sample attthat does not bid
    in an auction beforetand bids in an auction att.
- Sample in the same location: Firmjandj′are in the same location attif
    their business address zip codes reported on the business tax filings correspond
    to the same commuting zone att.
- Known EIN sample: Firms from the six states in which the auction records
    included the EIN, thus allowing us to link records exactly rather than using a
    fuzzy matching algorithm.

Worker Sample Definitions:

- Main sample: A worker is considered part of the main sample att if the
    worker’s highest-paying firm atton Form W-2 is in the baseline sample of firms

```
S13
```

```
and the W-2 wage payments from that firm are greater than $15,000 in 2015
USD. We also restrict to workers aged 25-60.
```
- Add Contractors: Add to the main sample any independent contractor whose
    highest-paying firm atton Form 1099 is in the baseline sample of firms and the
    1099 wage payments from that firm are greater than $15,000 in 2015 USD. We
    also restrict to contractors aged 25-60.
- Stayers: A worker is a stayer for 2 e+ 1years at firmjin the baseline sample
    of firms attif the worker’s highest-paying W-2 firm is the same firm during
    each time period in(t−e,...,t+e)and the W-2 wage payments from that firm
    in each year are greater than $15,000 in 2015 USD.
- Tenure:A worker haseyears of tenure at firmjin the baseline sample of firms
    attif the worker’s highest-paying W-2 firm is the same firm during each time
    period in(t−e,...,t)and the W-2 wage payments from that firm in each year
    are greater than $15,000 in 2015 USD.
- New Hires:A worker is a new hire at firmjin yeartif the worker’s highest-
    paying W-2 employer in yeartwas firm jand highest-paying W-2 employer
    in yeart− 1 was firmj′̸=j, where the worker received W-2 wage payments
    greater than $15,000 in 2015 USD fromj′int− 1 as well as fromjint.

A potential drawback of tax data is limited coverage of undocumented immigrants.
As a result, we primarily interpret our paper as providing an analysis of the legal
labor market. However, there is substantial coverage of undocumented immigrants
in our W-2 returns. Since 1996, the IRS has assigned a tax identification number,
called the ITIN, to undocumented immigrants in order to facilitate filing. By law, the
IRS cannot share undocumented immigrant status with other agencies for purposes of
immigration enforcement, so filing does not pose deportation risks. The IRS imposes
penalties on employers for failing to file W-2 tax forms on behalf of undocumented
employees, while tax refunds (e.g., child tax credits) and other benefits (e.g., evidence
of consistently filing taxes can be used in support of citizenship applications) provide

#### S14


substantial incentives for undocumented immigrants to file. For example, the CBO
(2007) estimated that up to 75 percent of all undocumented immigrants filed during
the earlier part of our sample, and this rate may have risen due to DACA and other
reforms instituted during the latter part of our sample.

### S.4 Description of the Norwegian Data

The Norwegian data comes from the State Register of Employers and Employees,
which covers the universe of workers and firms. Our sample spans 2009-2014. For each
job, it includes information on start and end dates, annual earnings, and contracted
hours. We construct annual earnings at the primary employer as our main outcome
of interest. Because the Norwegian data also provides hours worked per day, we can
construct the average hourly wage. We supplement the employer-employee data with
a measure of value added, which we define as the difference in sales and non-wage
operating costs as reported to the Norwegian tax authority by the firm.
To harmonize the Norwegian data with our sample from the US, we follow Bon-
homme et al. (2023) by applying the following steps. First, as is common in the
literature, whenever a worker is employed by multiple employers in the same year,
we focus on the employer associated with the greatest annual earnings. Second, we
restrict attention to workers employed in the construction industry. Third, we restrict
attention to workers who are between 25 and 60 years of age. Lastly, we restrict at-
tention to full-time equivalent (FTE) workers. Recall that, since we do not observe
hours worked in US data, or a formal measure of full-time employment, we defined a
worker as FTE if his or her annual earnings exceed $15,000, which is approximately
the annualized minimum wage and corresponds to 32.5% of the national average. To
harmonize the sample selection across countries, we similarly restrict the Norwegian
sample to workers with annual earnings above 32.5% of the national average.

#### S15