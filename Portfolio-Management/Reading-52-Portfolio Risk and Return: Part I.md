# Portfolio Risk and Return: Part I

## Objectives
* **Describe / Explain**
  * Describe the effect on a portfolio’s risk of investing in assets that are less than perfectly correlated
  * Describe and interpret the minimum-variance and efficient frontiers of risky assets and the global minimum-variance portfolio
  * Describe characteristics of the major asset classes that investors consider in forming portfolios
  * Explain risk aversion and its implications for portfolio selection
  * Explain the selection of an optimal portfolio, given an investor’s utility (or risk aversion) and the capital allocation line

* **Calculate**
  * Calculate and interpret portfolio standard deviation
  * Calculate and interpret the mean, variance, and covariance (or correlation) of asset returns based on historical data
  * Calculate and interpret major return measures and describe their appropriate uses

* **Compare**
  * Compare the money-weighted and time-weighted rates of return and evaluate the performance of portfolios based on these measures


## 基础单词/概念
* Time-Weighted Return(TWRR) vs. Money-Weighted Return(MWRR)
  * TWRR
    * not influenced by the timing
    * measure the compound growth
  * MWRR
    * accounts for the timing and amount of all cash flows into and out of the portfoloi
    * internal rate of return
    * 
* minimum-variance
* efficient frontiers
* capital allocation line
* gross return: 没有扣除基金经理的管理费
* net return: 扣除了基金经理的管理费

## Notes

### Return & Risk

* Time-Weighted Return(TWRR) 
  * 计算步骤
    * calculate the HPR on the portfolio for each subperiod
    * compound the HPR to obtain the annual rate of return (注意开根号的时候用的是所有计算区间的年数)
  * 特点
    * 不受到现金流的影响
    * 
* Money-Weighted Return(MWRR)
  * 计算步骤
    * 画时间轴标记现金流
    * 使用计算器来计算IRR
    * 将期间利率进行转化
  * 特点
    * influenced by cash flow
    * Only appropriate for the investment when manager can control the timing and direction of CF. 可以作为基金经理的参考指标

* Covariance and Correlation of Returns for Two Securities
  * Cov = (R1 - Mean1)*(R2 - Mean2) / (T - 1)
  * Correlation = Cov / 标准差1 * 标准差2   Correlation是对于Covariance的标准化
  * 
* Variance of Portfolio
  * weight1^2 * 标准差1^2 + weight2^2 * 标准差2^2 + 2 * weight1 * weight2 * Cov12

### Efficient Frontier
Asset Allocation
主观世界和客观世界的最优解 主客观统一
Return 收益 和 Risk风险

* Risk preference
  * risk averse: A > 0 无差异曲线开口向上
  * risk neutral: A = 0
  * risk seeking: A < 0
* Utility function => 确定相同效用的曲线 => 得到开口向上的抛物线 => 抛物线上的点的效用相同 但是风险和要求回报率不同 => 不同截距代表不同效用
* 

## 课后练习
Q: time weight rate of return和money weighted rate of return 的区别?
怎么理解 "If fund are contributed to an investment portfolio just before a period of relatively poor portfolio performance, the money weighted rate of return will be lower than the time weighted rate of return"? 
A: IRR 折旧模型中 后期折旧大 前期折旧小

* Q4 geometric 是利滚利，buy and hold 会利滚利，money weighted 现金流time value但没有利滚利
The money-weighted rate of return is an internal rate of return (IRR). The time-weighted rate of return is a geometric mean return over the whole investment period. 
* Q6 A和B 直接看return rate关系不考虑绝对值 只有C考虑绝对值
geometric （time weighted）不考虑本金大小，可以只看return rate；money weighted是看现金流折现的，要考虑本金大小的
* Q7 money weighted前期收益（无论好坏）的效果比后期更显著，所以前期更好的money weighted算出来的值会大于time weighted算出来的值；前期更差的money weighted值会小于time weighted的值
* Q12 correlation = 1 时，portfolio standard deviation = w1SD1+w2SD2
Q18 brokerage commissions 是提前商量好的数值 不随着liquidity变化
Q25 risk version 
Q33 when number of assets in the equally weighted portfolio increases, the contribution of each individual asset's variance impact decreases 

### 思考
* 应该从本质上来理解相关性究竟代表了什么,两个变量之间有关联 表象是因为存在同步的变化趋势 有同步的趋势之后还需要考虑什么呢? 趋势的一致性 这个就是standard deviation ??
