# [重点] Equity Valuation: Concepts and Basic Tools

## Objectives

* **Describe/Explain**
  * major categories of equity valuation models
  * regular cash dividends, extra dividends, stock dividends, stock splits, reverse stock splits, share repurchases
  * dividend payment chronology
  * present value models / dividend discount and free-cash-flow-to-equity models
  * characteristics of companies for which the constant growth or multistage dividend discount model
  * rationale for price multiples, how it relates to fundamentals, and the use of multiples based on comparables
  * enterprise value multiples
  * asset-based valuation models
  * advantages and disadvantages of each category of valuation model

* **Calculate**
  * intrinsic value of a non-callable, non-convertible preferred stock
  * intrinsic value of an equity security based on the Gordon(constant) growth dividend discount model / two-stage dividend discount model
  * P/E, P/B, P/S, P/CF 的计算

### 核心模型
* Discounted Cash Flow Models (DCF Model)
    * Dividends, Splits, and Repurchases
    * Dividend Discount Models
    * Free Cash Flow Models
* Multiplier Models (价格倍数法 基本面数据)
* Asset-based Models(根据净资产 assets - liabilities - preferred shares进行估值)

## 基础词汇/概念
* overvalued / undervalued / fairly valued 
* liquidation 清算
* EBITDA

## Notes


### Discounted Cash Flow Models


#### Dividend Discount Models (Present value models)**
* **Dividend**
  * regular dividend (默认发放的股利是现金)
  * extra dividend / special dividend
  * stock dividend
  * cash dividend
* Share Repurchase
  * 支撑股价
  * 方式灵活
  * 股东赚到的是资本利得能够帮助避税
  * 回购可以反稀释 option和可转债
* Dividend Payment Chronology: 
  * declaration date: 股利宣告日 
  * ex-dividend date: 除息日
  * Holder-of-record: 股权登记日(美股规定必须是在ex-dividend date后1-2天)
  * payment date: 实际支付

* **Gordon growth model**
* 假设
  * going-concern
  * g < r
  * g 恒定
* 缺点
  * 对于r和g的取值敏感
  * 不适用于不发股利的公司
  * 增长率恒定的假设不符合实际
* 基本计算流程:
1. 根据题目描述来确定要使用的公式 判断是D1还是D0 已经发了钱 D0的描述 current, actual, this year, recent paid, D1还没发钱 D1的描述projected, estimated, next year, to be paid 
2. 算股利的金额 
3. 算growth rate 

* 区分针对D0和D1有两个不同的计算公式
  * D1 / r - gc
  * D0 * (1 + gc) / r - gc
  * Do = (1 - RR) * EPS #从每股收益中划出一部分钱来发股利
  * growth rate = ROE * RR
  * required rate of return = risk-free rate + /beta(risk-market - RFR)

* Two-stage model: 两个stage都要折现到当前时间
  * 第一个stage every year one by one,
  * second stage: calculate the present value 

#### Price Multiple Approach 
* Justified P/E: P不使用市场价格 而是使用intrinsic value 通过DDM算出来的 D1 / r - g
  * Leading P/E: P0 / E1 折现的价格 / 未来预估利润 直接用的D1 所以结果的分子没有(1+g) 除未来的利润 E1(expected 12-month earnings)  (1 - b1) / (r - g) 明年的b1
  * Trailing P/E: P0 / E0 折现前的价格 / 当前利润  P  (1-b0)(1+g) / (r-g) 今年的b0

* EV / EBITDA
  * EV 是total company, 是equity + debt的总和 = market value of common stock + market value of preferred equity + market value of debt - cash and short-term investments
  * EBITDA: 不扣利息、税、折旧&摊销的利润  = NI + Tax + Interest + D&A

#### Asset-based valuation models
* 根据company's assets - liability 来估值

### 课后练习
* Q7: cash flow from operations model 有讲过吗 A: 没有 dividend-paying capacity 是现金流 expected dividend 是股利折现
* Q15: 为什么只算到第5年就停止？第5年卖掉了? A: 在中间第二阶段时直接终止 Pn = Dn+1/(r-g) r: required return g: growth rate(第二阶段的)
* Q20: 这几个model如何区分 two-stage 和 three-stage 有区别吗 The two-stage model is best for companies that are transitioning from agrowth stage to a mature stage. The three-stage model is appropriate for young companies just entering the growth phase.
* Q22 P/E comparable 和 fundermental 的区别是什么? A: comparable 和别人比 fundermental 和自己比
* Q24 为什么可以用平均值? A: historical average: 2014-2017年的P/E 取平均值之后可以作为benchmark value作比较
* security exchange 决定Ex-dividend date, 公司决定Holder-of-record date 和 Declaration date, payment date可以是周末, ex-date 和record date必须是business days
* 75bps = 0.75%
* perpetual == preferred stock 直接用 D / r 即可
* financial leverage ratio = assets
* 股利对于FCFE没有影响, Net borrowing高 -> FCFE增大
* FCFE model assumes that dividend-paying capacity is reflected in FCFE
* fundamentals P/E based on the Gordon growth model, 考虑future expected dividends, comparable P/E 基于historical data 和 law of the one price
* assets-based valuation不适用于PP&E很多 难估值






* Q24 为什么可以用平均值? A: historical average: 2014-2017年的P/E 取平均值之后可以作为benchmark value作比较
