## Objective

* **Define**
    * a probability distribution and distinguish between discrete and continuous random variables and their probability functions
    * Bernoulli, binomial, uniform, normal distribution
    * shortfall risk, calculate the safety-first ratio, select an optimal portfolio using Roy's safety-first criterion
* **Calculate/Construct**
    * a binomial tree to describe stock price movement
    * probabilities for a random variable, given its cumulative distribution function, the discrete uniform and the binomial distribution functions
    * a continuously compounded rate of return, given a specific holding period return
* **Describe/Explain/Interpret/Distinguish** 
    * the set of possible outcomes of a specified discrete random variable
    * cumulative distribution function
    * Distinguish between a univariate and a multivariate distribution and explain the role of correlation in the multivariate normal distribution
    * interval, standard normal distribution
    * standardize a random variable
    * the relationship between normal and lognormal distributions and why the lognormal distribution is used to model asset prices
    * Monte Carlo simulation, application and limitations and compare Monte Carlo simulation and historical simulation


## 词汇
* holding period return(HPR)


## Notes
### Introduction and Discrete Random Variables

* probability distribution: A distribution that specifies the probabilities of a random variable’s possible outcomes. 随机变量可能结果的分布 
* probability function: 得到某一个特定值的概率
* probability density function(PDF)
    * $0 <= p(x) <= 1$
    * sum == 1
* discrete random variable: 🎲
* continuous random variable: rate of return
* cumulative distribution function: A function giving the probability that a random variable is less than or equal to a specified value.

### Uniform, Binomial Distributions, Binomial Tree
* discrete random variable: number of possible outcomes can be counted $P(X)$ 
* continuous random variable: number of possible outcomes is infinite $P(x_1 \leq X \leq X_2)$
* cumulative distribution function(distribution function): the probability that a random variable, X, takes on a value equal to or less than a specific value x.
* binomial distribution: 


**Safety First Ratio**
* Shortfall risk: 低于客户要求的最低回报率的风险 $R_L$
* Roy's safety-first criterion $SFR = \frac{E(R_p) - R_L}{\sigma_p}$


**Lognormal Distribution**
* If lnX is normal, then X is lognormal
* Right skewed 右边有长尾巴
* values are always be positive, useful for modeling asset prices
* Return 用 normal distribution 建模

### Bernoulli Distribution

Binomial 和 Bernoulli 区别: Binomial 是多个伯努利实验的结果
Bernoulli 算的是success的概念 Bernoulli Trail 只有两种实验结果 1 / 0


Monte Carlo simulation

68.27: 1
90: 1.65
95: 1.96
95.45: 2
99: 2.58 
99.73: 3

univariate distribution
multivariate distribution: a group of related random vairables
Z-table

## 例题
Binomial 
Binomial Tree
Expected Value / 

continuous compound
discrete compound
Monte Carlo: http://www.ruanyifeng.com/blog/2015/07/monte-carlo-method.html

$e^{i} - 1$

$R_i = ln(\frac{S_1}{S_0}) - 1$