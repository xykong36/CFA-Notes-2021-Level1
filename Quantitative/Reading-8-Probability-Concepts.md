
## Objective

**Calculate**

* the joint probability of two events, the probability that at least one of two events will occur, given the probability of each and the joint probability of the two events, and a joint probability of any number of independent events
* an unconditional probability using the total probability rule
* covariance and correlation and interpret a scatterplot
* the expected value, variance, and standard deviation of a random variable and of returns on a portfolio
* covariance given a joint probability function
* an updated probability using Bayes’ formula

**Explain/Interpret/Demonstrate/Define**
* random variable, an outcome, an event, mutually exclusive events, and exhaustive events
* two defining properties of probability and distinguish among empirical, subjective, and a priori probabilities
* the probability of an event in terms of odds for and against the event
* the multiplication, addition, and total probability rules
* the use of conditional expectation in investment applications
* the use of a tree diagram to represent an investment problem
* the most appropriate method to solve a particular counting problem and solve counting problems using factorial, combination, and permutation concepts

**Compare/Distinguish**
* unconditional and conditional probabilities
* dependent and independent events

## Notes

### Probability Concepts and Odds Ratios
独立事件 Independent events: 事情A发生不影响B发生的概率
互斥事件 Mutually exclusive events: 事情A发生了 B就不能发生

*赔率(odds for the event occurring)*: 定义和赌博的定义不同事件发生的概率 / 事件不发生的概率 事件E发生的赔率: P(E) / 1 - P(E)
事件E不发生的赔率: 1 - P(E) / P(E)

* 加法法则(addition rule of probability) 两件事情中至少有一件事件发生的概率: determine the probability that at least one of two events will occur P(A or B) = P(A) + P(B) - P(AB)
* 乘法法则(multiplication rule) 两件事情同时发生的概率: joint probability of two events P(AB) = P(A | B) * P(B)
    * 如果是independent event直接将每个事件发生的概率相乘即可 P(A|B) = P(A) 
* 全概率(total probability rule): 对于set of events{S1, S2, ... Sn) mutually exclusive and exhaustive P(R) = P(R | S1) * P(S1) + P(R | S2) * P(S2) + ... + P(R | Sn) * P(Sn) 事件R发生的概率是S1,S2发生的概率乘以条件概率求和得到


Permutation formula: N个里面挑出来K个，需要考虑顺序 排列 $A_N^k$
Multinomial formula: 多项分布的拆分公式 $(a + b)^n$
![60a047c58e7f3ac7b81cc8657bc905aa.png](evernotecid://1FC78D12-88FB-4FAC-95A1-F7FB5953B0DF/appyinxiangcom/29211871/ENResource/p289)

Combination formula: N个里面挑出来k个，不需要考虑顺序 组合 $C_N^k$

### Conditional and Joint Probability


#### Covariance and Correlation
* Covariance: measure of how two assets move together 两个随机变量变化的方向性 [Covariance and Correlation Part 1: Covariance](https://www.youtube.com/watch?v=qtaqvPAeEJY)
* Correlation: measure the strength of the linear relationship between two random variables 


### Portfolio variance, Bayes, and Counting Problems

**Portfolio variance**
$w_i$= market value of investment in asset i / market value of the portfolio
$Var(R_p) = w_Aw_ACov(R_A,R_A) + w_Aw_BCov(R_A,R_B) + w_Bw_ACov(R_B,R_A) + w_Bw_BCov(R_B,R_B)$


spurious correlation: 没有相关性

$Cov(AB) = \rho_{AB}\sigma_A\sigma_B$
  
covariance positive: 同方向

### Baye's Formula

事件A的
先验概率: P(A)
后验概率: P(A|B) = P(B|A) * P(A) / P(B)
