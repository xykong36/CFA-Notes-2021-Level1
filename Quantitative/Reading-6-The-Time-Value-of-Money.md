

## Objective
**Calculate**
* calculate and interpret the **effective annual rate**
* future value(FV), present value(PV) of a single sum of money, an ordinary annuity, an annuity due(期初年金 BGN 模式), a perpetruity, and a series of unequal cash flows

**Explain/Interpret/Demonstrate**
* interest rates, required rates of return, discount rates, opportunity costs
* interest = rist-free rate + premiums of risk
* time value of money problems for different frequencies of compounding
*  the use of a time line in modeling and solving time value of money problems

## Notes

### Interest
```math
R_i = R_f + R_p 

```
$R_f$: Nominal risk-free: real risk-free + inflation premium
$R_p$: risk premium = default premium + liquidity premium + maturity premium

* Simple interest
* Compounding interest: interest on interest
* Types of risk: 
    * Default risk: 违约 欠钱不还 
    * Liquidity risk: 急需用钱的时候 可能要赔本卖
    * Maturity risk: 长期的利率风险市场不稳定
* Effective Annual Rate(EAR): The rate of interest that investors actually realize as a result of compounding.
    * 计算公式
```math
    EAR=(1 + R_{period})^m  - 1 
```

* EAR例题
    1. Compute EAR if the stated annual rate is 12%, compounded quarterly. 
    
       **12% / 4 = 3% -> (1 + 0.03)^4 - 1 = 1.1255 -> EAR = 12.55%**
       
    2. John plans to invest $2,500 in an account that will earn 8% per year with quarterly compounding. How much will be in the account at the end of two years?
   
       **8 / 4 = 2% -> (1 + 0.02)^8 - 1 = 1.1717 -> EAR = 17.17%**
       
* 时间段划分: 相同年化利率前提下，频率越高，EAR越大 
    * semiannual 半年期
    * quarterly 季度
    * montly 月度
    * daily 天

### PV and FV
```math
FV = PV(1 + I/Y)^N
```
* 题型
    * 还房贷/摊销: TMV AMORT
    * 教育金/养老金: 嵌套
* 计算公式
    * PV: Present Value
    * FV: Future Value
    * I / Y: rate of return per compounding period
所有的题目都是 N I/Y PV PMT FV 给出四个已知量 求 最后一个未知量
 *  PV 与 FV 的转换: at common point in time 划定基准时间才好比较
    *  FV: 从当前的PV + interest rate -> FV
    *  PV: 从未来的PV + interest rate -> PV 
    *  Type
        * single cash flow: 只涉及一笔现金流 用不到PMT健
             * 例题
                1. 算FV: 200 PV 4年 10%利率 求FV ![333667a50a357c39bc1ad00d1a95f4d5.png](evernotecid://1FC78D12-88FB-4FAC-95A1-F7FB5953B0DF/appyinxiangcom/29211871/ENResource/p1)
                2. 算PV: Given a discount rate of 10%, calculate the PV of a $200 cash flow that will be received in two years. 2 -> N 10 -> I/Y 200 -> FV CPT -> PV

        * annuity: stream of equal cash flows that occurs at *equal intervals* over a given period 固定钱 固定周期 需要用PMT健
            * ordinary annuities vs annuities due
                * ordinary annuities(后付年金-默认的): 每一次都在期末投入钱
                * annuities due(先付年金): 每一次都在期初投入本金
            * 例题
                * What is the future value of an ordinary annuity that pays $200 per year at the end of each of the next three years, given the investment is expected to earn a 10% rate of return? **Answer**: 2nd -> FV (clear) 3 -> N 10 -> I/Y -200 -> PMT CPT -> FV
                * 
        * a series of uneven cash flow: 不固定的钱数
            * 例题
                * Using a rate of return 10%, PV = 0, 300, 600, 200,求第三年的FV  BGN是干嘛的? Answer: 300*(1.1)^2 + 600*(1.1) + 200 如果求PV -> 300 / 1.1 + 600 / (1.1)^2 + 200 / (1.1)^3 反过来折
                * 
        * perpetuity 永续年金 优先股估值/永续债券
            * PV = PMT / r PMT: 每年的payment, r: 利率
   
### Financial Calculator
* P/Y periods per year function: 年化利率转为当期利率 12(1年 = 12个月): converts the annual interest rate into monthly rates.
* Keys
    * N: Number of compounding periods
    * I/Y: Interest rate per compounding period
    * PV: Present value
    * FV: Future vaule
    * PMT: Annuity payments, constant periodic cash flow
    * CPT: Compute

## Questions
为什么钱有时间价值? 因为投资回报?? 

什么是碎片化的知识? 

举例 money具有时间价值，你知道如何计算 时间价值 用interest rate来算 interest rate的组成包括。。。 但是具体的实例有吗？量化的数据有吗？相关的理论知识有吗? 

想清楚变量和常量 
