# Security Market Indexes

## Objective
* describe
    * security market index
    * choices and issues in index construction and management
    * rebalancing and reconstitution of an index
    * uses of security market indexes 
    * types of equity/fixed-income/alternative/market indexes
* calculate
    * value, price return, total return of an index
    * value and return of an index given different weighting method
## 基础词汇/概念
* price return: 只考虑股票价格增长带来的收益
* total return: 股票价值增长 + 分红带来的总收益
* inception: 起始、开端 最初发售的时刻
* constituent securities 成分股
* [Compare outstanding shares vs. treasure shares vs. issued shares vs. listed shares](https://zhuanlan.zhihu.com/p/31841811)
   * outstanding shares: 发行在外 包括了员工持股计划中还没有授予的部分 暂时还不能进行公开交易
   * treasure shares: 库存股 公司回购的还没有注销的股票
   * issued shares: 已发行股份 = outstanding shares + treasure shares 
   * listed shares == shares available to the investing public: 可以在市场上流通公开交易的部分
* [value tilt](https://www.bogleheads.org/wiki/Value_tilting_-_stock): 向价值股倾斜 使用fundamental weighting过程中容易出现
* contrarian effect: 反向投资 使用fundamental weighting过程中容易出现
* appraisal: 房产估价

## Note

### Index Definition and calculations of value and returns
* 样本 -> 整体市场的推断 
* A security market index represents a given security market, market segment, or asset class. Most indexes are constructed as portfolios of marketable securities.

### Index Construction
* Steps
  * 选择target market
  * 选择which securities from the target market to include
  * 选择weighting method
  * rebalance the index
  * re-examine the selection
* Index Weighting
    * Price Weighting / price-weighted index: 每支成分股的股数相等 比如每只股票买一股 直接算价格的权重
    * Equal Weighting / equal-weighted index: 最不合理的权重分配方式 每支成分股的**比重**相等 比如总共10支成分股 那么每支股票占比 10%
    * Market-Capitalization Weighting / value-weighted index: 按照市值分配权重
    * Float-Adjusted Market-Capitalization Weighting: 只考虑流通股市值
    * Fundamental Weighting: 按照基本面数据分配权重

### Index Management: Rebalancing and Reconstitution 
* rebalance: 调整股票的权重
* reconstitution: 调整指数中的股票 GE从S&P500除名 e.g. 2020年TSLA被加入S&P500

### Uses of Market Indexes
* gauges(度量) of market sentiment(情绪)
* proxies for measuring and modeling returns, systematic risk, and risk-adjusted performance
* proxies for asset classes in asset allocation models
* benchmarks for actively managed portfolios
* model portfolios for index fund and ETFs

### Type of Indexes
* Equity Indexes
  * Broad Market Indexes: A broad equity market index, as its name suggests, represents an entire given equity market and typically includes securities representing more than 90 percent of the selected market.
  * Multi-Market Indexes: Multi-market indexes usually comprise indexes from different countries and regions and are designed to represent multiple security markets. 
  * Sector Indexes: Sector indexes represent and track different economic sectors—such as consumer goods, energy, finance, health care, and technology—on either a national, regional, or global basis.
  * Style Indexes: Style indexes represent groups of securities classified according to market capitalization, value, growth, or a combination of these characteristics. 
* Fixed-income Indexes
  *  fixed-income securities can be categorized according to the issuer’s economic sector, the issuer’s geographic region, or the economic development of the issuer’s geographic region.
* Indexes for Alternative Investments
  * Commodity Indexes: based on futures contract prices
  * Real Estate Investment Trust Indexes
  * Hedge Fund Indexes

### 课后练习
* Q1: security market index 可以代表 security market, market segment, asset class
* Q2: C错在哪里? 用actual **OR** estimated price 来估值 课本原文: The value of an index is calculated on a regular basis using either the actual or estimated market prices of the individual securities, known as constituent securities, within the index. 
* Single perior return: 同样的一组数据不同的weight 方法计算出来的结果可能不一样
  * Q12: price-weighted index的single period return 直接算所有security的**价格**总和 begin = 100, end = 120 那么return = 120 / 100 - 1 = 20%
  * Q13: value-weighted index的single period return 直接算所有security的**市值**总和 begin = 10000 end = 15000 return = 15000 / 10000 - 1 = 50%
  * Q14: equally-weighted index 的single period return 如果单个成分股的价格不一致，需要先算出同样投入100块能够买入的share, 然后再算总净值return 类似value-weighted  
* Q17: float-adjusted 是指在市场中流通的可以公开交易的listed shares 数量小于outstanding shares
* Q18: value tilt 向价值股倾斜
* Q20: index weighting 是在初始创建index维持的 比如分别买入AMAZON $10, FACEBOOK $10, APPLE $10股票各10支，得到一个组合，
每支股票在组合中有一个weight值，这个权重weight是按照你的portfolio的当前价值 (share * price/share)来确定（分别是100,100,100)，
随着价格会进行动态变化, 1个月后变为(100, 120, 105), weight自然也变了,需要根据你的weighting原则定期rebalance来调整(买入/卖出)
* Q22: index只能作为proxy for measuring market/systematic risk 而不是 measures of systematic risk
* Q31: Initial sales index is not a real estate index
* Q32: unique feature of hedge fund indexes is that they are determined by the constituents of the index. 因为对冲基金的业绩不需要披露，自己报告即可
* Q34: In comparison to equity indexes, fixed-income indexes drawn from a larger investment universe. 有更多的发行主体 不同类型的资产

