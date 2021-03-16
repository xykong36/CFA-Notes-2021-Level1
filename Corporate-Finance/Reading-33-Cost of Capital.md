# [重点]Cost of Capital

## Objective
* **Describe/Explain**
  * Describe how taxes affect the cost of capital from different capital sources
  * Describe the use of target capital structure in estimating WACC and how target capital structure weights may be determined
  * Describe uses of country risk premiums in estimating the cost of equity
  * Describe the marginal cost of capital schedule, explain why it may be upward-sloping with respect to additional capital, and calculate and interpret its break-points
  * Explain and demonstrate the correct treatment of flotation costs
  * Explain how the marginal cost of capital and the investment opportunity schedule are used to determine the optimal capital budget
  * Explain the marginal cost of capital’s role in determining the net present value of a project

* **Calculate**
  * Calculate and interpret the weighted average cost of capital (WACC) of a company
  * Calculate and interpret the cost of debt capital using the yield-to-maturity approach and the debt-rating approach
  * Calculate and interpret the cost of noncallable, nonconvertible preferred stock 
  * Calculate and interpret the cost of equity capital using the capital asset pricing model approach, the dividend discount model approach, and the bond-yield-plus risk-premium approach
  * Calculate and interpret the beta and cost of capital for a project


## 基础词汇/概念
* flotation cost: 发行成本 
  * 正确处理: 一次付清作为inital cash outflow的一部分 
  * 错误处理: 在计算r的时候从当前股价中扣除发行成本，错误在于计算出来的r会影响到未来现金流的折现，而未来现金流和发行成本应该是无关的
* country risk premium: Sovereign yield spread * (Annualized standard deviation of equity index of developing country) / (Annualized standard deviation of bond in developed market) 


## Notes

### Weighted Average Cost of Capital(WACC)
* WACC = wd * rd(1 – t) + wp * rp + we * re  

### Cost of Different Sources of Capital
* **Cost of Debt**
  * YTM approach (持有到期日): 直接折现求解
  * debt-rating approach: 找到可比债券进行定价 同样的行业 相似的资本结构

* **Cost of Preferred Stock**
  * rp = Dp / Pp 直接按照永续年金来计算即可

* **Cost of Equity**
  * CAMP: risk free return rate + beta * market risk premium(注意看题目是直接给出的premium风险溢价还是给出了预期收益率,如果给了风险溢价 直接用即可，如果是预期收益率需要减掉risk free return rate)
  * dividend discount model: D1 / P0 + g  g的计算可能还是要ROE * RR
  * bond yied + risk premium

#### Estimate Beta 
* Project beta Pure-play method
* Steps 杠杆计算公式: 1 + (D / E) * (1 - Tax rate)
  * Step 1: Select the comparable     Determine comparable company or companies. These are companies with similar business risk.
  * Step 2: Estimate comparable’s beta     Estimate the equity beta of the comparable company or companies. -> beta E
  * Step 3: Unlever the comparable’s beta     Unlever the beta of the comparable company or companies, removing the financial risk component of the equity beta, leaving the business risk component of the beta. -> beta A
  * Step 4: Lever the beta for the project’s financial risk     Lever the beta of the project by adjusting the asset beta for the financial risk of the project. -> beta A * 当前公司杠杆 = beta E(当前公司)
  
#### Optimal Capital Budget
* Marginal Cost of Capital (MCC) 斜率向上 资金量越大 边际成本越高 
* Investment Opportunity Schedule (IOS) 斜率向下，资金量越大，收益率越低
* marginal cost: 不同的金额，成本不同，金额越大，成本越高


### 课后练习
* 如果啊要计算未来的Project需要用到Forcast Market Value  
* 注意选择IRR大于 Cost of Capital的项目
* 计算器求救I/Y的时候必须要注意PV 和 FV的符号, PV FV是 
* coupon rate都是按照年度计算的，每年发放的总额等于coupon rate * face value, 如果是semi-annual 则每次发放的PMT减半 同时期数N加倍
* interest coverage ration = EBITDA / Interest expense
* 需要按照market value来计算 D/E ratio  债券的市场价格需要进行折现计算PV而不能使用face value来计算 Equity的市场价格等于股数 * 每股价格

* Q2 A. average tax rate错了 应该使用marginal tax cost, 通常借债的成本会低于发股票的 同时要注意税率t必须使用边际税率marginal tax rate而不能是average tax rate
* Q4 coupon rate 是年化利率 PMT是按照单期利率 each compounding period 可能需要进行一个转化, face value是FV 最后要换的钱,未来的现金流 ->正数, issue value是PV要马上交的钱, 是买入的价格 -> 负数,如果符号不对可能导致结果报错
  * Q:Face value是FV还是PV? A: face value == par value 是债券的面值表示到期日将要清偿的金额 是一个FV
* Q7 cost of equity有三种算法: CAPM(capital asset pricing model) /dividend discount/ bond yield plus risk premium 
* Q9 book value 还是 market value是如何确定的?  这题算的是预期的weight 所以用的是forecast
* Q10 asset beta / equity beta  之间的关系 asset beta是不考虑Debt影响的  D/E ratio 增大的时候 asset risk(beta) 不变而equity risk(beta) 增大 杠杆增加导致风险和波动率增加
* Q11 将公司的 D/E ratio和Project的 D/E ratio分开 C是表示将新借的债加到现在已有的债务 
* Q24 注意必须要使用D1(next year's dividend) 根据payout rate 来进行计算 g = (1 - payout rate) * ROE
