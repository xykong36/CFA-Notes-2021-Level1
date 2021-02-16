## Objectives 
* Describe
    * matrix pricing
* Define
    * spot rates
    * spot curve, yield curve on coupon bonds, par curve, and forward curve
* Identify
    * relationships among a bond's price, coupon rate, maturity, and market dicount rate(yield-to-maturity)
* Calculate
    * bond's price given a market discount rate
    * annual yield on a bond for varying compounding periods in a year
    * flat price, accrued interest, and the full price of a bond
    * forward rates, spot rates <=> forward rates, bond price using forward rates
    * price of bond price using spot rates
    * yield measures for fixed-rate bonds and floating-rate notes
    * yield spread measures

## 基础单词/概念
* premium bond: coupon rate > YTM
* discount bond: coupon rate < YTM
* spot curve
* yield curve
* par curve
* forward curve
* full price = flat price + accrued interest
* flat price is quoted by bond dealers. 更容易比较 不需要考虑accrued interest
* accrued interest = (t / T) * PMT 买债券的需要把没有支付的部分coupon付给卖债券的
* spot rates: YTM on zero-coupon bonds
* forward rates
* yield spread
* settlement date: when the bond buyer makes cash payment and the seller delivers the security.
**benchmark rate**: time-to-maturity相同或接近的政府债券/国债的YTM 
**spread over the benchmark**: yield spread between the YTM on the new bond and the benchmark rate.
basis point: 计量单位 0.01% 75bps = 0.75%

## Notes

### 单一折现率 Market Discount Rate Bond Pricing

债券当中给的利率都是年化的 需要进行转换 注意看清楚是否是每半年付息

**Relationship between the bond price and bond characteristics**
* coupon rate, maturity, price change percentage, market discount rate
* bond price 增大, market discount rate减小
* coupon rate time-to-maturity相同, r下降时的价格变化率大于r上升时
* time-to-maturity相同, coupon rate低, 相同r变化 -> 价格变化率大
* coupon rate 相同，r变化 -> 长期债券百分比变化大

* accrued interest: $\frac{t}{T}$ * PMT
  * t: number of days from the last coupon payment to the settlement date
  * T: number of days in the coupon period
  * t/T: fraction of the coupon period that has gone by since the last payment
  * PMT: coupon payment per period


actual/actual: 按照实际的日期直接进行转换
30/360: 每个月30天 一年360天 

进行更精细的计算数到天
每年会有发息日，计算现在这天的债券价格 先倒着数到上一个发利息日，然后 
计算flat price先从最近的前一个发息日往后算还剩多少个发息周期，折现
折出来的PV PV * (1+r)^(t/T) 计算full price


例题: 课后题19题
Matrix Pricing: 
no market price available for bonds that are not yet issued.  需要找一些同类债券作比较 
estimation process is **matrix pricing**

**Option-adjusted price**
**Option-adjusted yield**: the required market discount rate whereby the price is adjusted for the value of the embedded option
* callable bond:  OAY < YTM  callable bond 对于投资者不利  发债人有权利提前赎回 卖的价格更高
* putable bond: OAY > YTM

### Yield Measures 
* Fixed Rate Bonds
* Floating-Rate Notes
* Money Market Instruments


不同的Call会影响到
maturity时长 以及 future value 


**floater**: interest payment on a floating-rate note 
**quoted margin**: specified yield spread over the reference rate.

Coupon rate = reference rate + quoted margin

Discount rate = reference rate + required margin(discount margin) 

par: required margin = quoted margin
discount: quoted margin < required margin
premium: quoted margin > required margin


**required margin**: yield spread over/under the reference rate such that the FRN is priced at par value on a rate reset date. 


### The Maturity Structure of Interest Rates

### Yield Curve
yield 和 maturity之间的关系, 横轴是时间 t, 纵轴是收益率 y

* spot curve
* yield curve
* par curve
* forward curve


### Yield Spreads


Yield Measures For Money Market Instruments

Money Market是短期的 一天到一年 

```math
PV = FV * (1 - \frac{Days}{Year} * DR)
```
DR: discount rate, stated as an annual percentage rate

e.g. 
91-day US T-bill with a face value of USD 10 million is quoted at a discount rate of 2.25% for an assumed 360-day year. 

FV = 10,000,000
Days = 91
Year = 360
DR = 0.0225

PV = 10,000,000 * (1 - (91/360) * 0.0225) = 9,943,125


```math
DR = \frac{Year}{Days} * \frac{FV-PV}{FV}
```

```math
AOR = \frac{Year}{Days} * \frac{FV-PV}{PV}
```

no-arbitrage price: 用不同期的债券spot rate来进行折现求出来的价格 

YTM 是一种不同期限债券的平均

**bond equivalent yield**: 
money market rate stated on a 365-day add-on rate basis. 

### Maturity Structure of Interest Rates

* Yield Curve: 横轴是期限 纵轴是各种yield 
    * spot curve
    * yield curve
    * par curve

G-Spread: Government
Z-Spread


## 课后练习
* lower coupon rate的bond对于利率的变化更加sensitive 
* Q24: 计算器怎么用
* Q27 什么是first-call ? call price = 当年的future value?  coupon rate 不变 maturity 变短 FV， PMT 同号，PV, FV反的（一个正一个负） 已知4个变量 求最后一个变量
* Q31 Discount margin / required margin ?


## Q&A
coupon rate 和 discount rate的区别是什么？ quoted margin 和 required margin 的区别?