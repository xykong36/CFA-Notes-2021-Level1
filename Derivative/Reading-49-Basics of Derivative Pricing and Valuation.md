# Basics of Derivative Pricing and Valuation.md

## Objective

* **Describe/Define/Explain**
  * Explain how the concepts of arbitrage, replication, and risk neutrality are used in pricing derivatives
  * Explain how the value and price of a forward contract are determined at expiration, during the life of the contract, and at initiation
  * Describe monetary and nonmonetary benefits and costs associated with holding the underlying asset and explain how they affect the value and price of a forward contract
  * Define a forward rate agreement and describe its uses
  * Explain why forward and futures prices differ
  * Explain how swap contracts are similar to but different from a series of forward contracts
  * Explain the exercise value, time value, and moneyness of an option
  * Identify the factors that determine the value of an option and explain how each factor affects the value of an option
  * Explain put–call parity for European options
  * Explain put–call–forward parity for European options
  * Explain how the value of an option is determined using a one-period binomial model
  * Explain under which circumstances the values of European and American options differ
  
* **Calculate**
* Calculate a forward price of an asset with zero, positive, or negative net cost of carry

* **Distinguish**
* Distinguish between value and price of forward and futures contracts
* Distinguish between the value and price of swaps

## 基础词汇/概念

## Notes
open question: asset定价需要考虑risk premium, 为什么derivative定价不要考虑risk premium?
- 为什么value derivative一定要 use no-arbitrage condition？
- risk-free和no-arbitrage的关系？

如何理解49.1的这一段？
- 当forward > S0: 买进asset，再用forward价格卖出去（short forward)
- 当forward < S0: forward价格买进asset(long forward)，再市场价格卖出去

如何理解put-call parity

为什么at initiation of swap，forward contracts不是zero value？(R49.i)
假设每天结算，对于swap的
open question: 怎么理解size of up-move 和size of down-move？这里的size是什么？(看下书上有没有解释）


### 课后练习
Q1： 有risk的话要在分母加risk premium （有risk的时候对于risk averse的人要降价）
Q4 (尽早套利跑路，等到后面value就offset了）

理解replication(Q5)

第一题问的是定价 前提是asset是相同的 要算的是定价
Q8: price >0, initiation时value=0
Q8 Price肯定大于0 Value在开始的时候一定为0  Forward / Future 
Q12 多交Cost 需要增加价格 多加Benefit需要降低价格 (S + Cost + Benefit) 
Q18 mark to market   positive -> future  negative -> forward    future 和 forward的区别在于每天的利润都可以存银行赚interest.  
Q21 Swap present value of net cash flow fix
Q22 Swap 只有在B特定情况下才能等价于一系列Forward
Q33 为什么必须是Present value of the exercise price 而不直接是exercise price ？ 
- B选项：理解为差值的折现
European是不能提前settle的，value是未来的值 =， 算今天的value要折现到今天
Q38 C: Number of unit 是什么 
Q39： call下限就是0，volatility降低会让option value降低，upper payoff 会降低，但是lower payoff还是0
Q40：actual probability 不会被bimonial model考虑
Q45 Put-call-forward parity 用forward contract来替代stock
protective put == fiduciary call吗? 
payoff of fiduciary call = the payoff on protective put
Q50：题目要求以下哪个组合会获得一个risk free的东西 ---- c+bond (risk free) = S+P; long forward + long risk-free bond 合成一个asset （S）；S+P(long put)-C(short call) = bond(risk free) 

Q22：题目问的是在以下哪种情况下一系列的forward会相当于swap

Q35 怎么拼出来的
put-call parity 都用哪几个资产来拼
Stock + Put = Bond + Call 
股票跌了: Put赚钱 Stock亏钱 = Bond不变 Call不执行不亏
股票涨了: Stock 赚钱 Put不亏钱 = Bond不变  Call赚钱

European Option的特点是只能在最后的expiration date行权

押题:
Q29 影响Option price的factors (49.k)
Option获利计算


