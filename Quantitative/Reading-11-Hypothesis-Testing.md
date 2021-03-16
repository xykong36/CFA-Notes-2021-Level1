# Hypothesis Testing

## 重点梳理视频


## Objective
* **Define**
    * a hypothesis, describe the steps of hypothesis testing, and describe and interpret the choice of the null and alternative hypotheses
* **Calculate/Construct**
    * Identify the appropriate test statistic and interpret the results for a hypothesis test concerning the population mean of both large and small samples when the population is normally or approximately normally distributed and the variance is 1) known or 2) unknown
    * Identify the appropriate test statistic and interpret the results for a hypothesis test concerning the equality of the population means of two at least approximately normally distributed populations, based on independent random samples with 1) equal or 2) unequal assumed variances
    * Identify the appropriate test statistic and interpret the results for a hypothesis test concerning the mean difference of two normally distributed populations
    * Identify the appropriate test statistic and interpret the results for a hypothesis test concerning 1) the variance of a normally distributed population, and 2) the equality of the variances of two normally distributed populations based on two independent random samples
* **Describe/Explain/Interpret/Distinguish** 
    * one-tailed and two-tailed tests of hypotheses
    * a test statistic, Type I and Type II errors, a significance level, and how significance levels are used in hypothesis testing
    * a decision rule, the power of a test, and the relation between confidence intervals and hypothesis tests
    * a statistical result and an economically meaningful result
    * the p-value as it relates to hypothesis testing
    * parametric and nonparametric tests and describe situations in which the use of nonparametric tests may be appropriat


## 基础词汇/概念
* null hypothesis ($H_0$): 
* alternative hypothesis($H_a$): 
* significance level: 可以理解成人为设定的对于不确定性范围的定性, 表示出现的误差小于多少区间的时候就拒绝null hypothesis
* confidence level
* power of a test: correctly reject a false null hypothesis
* critical value 
* single-tailed test
* two-tailed test
* test statistic: t / z / F
* Type I Error vs. Type II error
  * Type I Error: 你拒绝了事实上是正确的原假设 => 拒绝了好人
  * Type II Error: 你接受了事实上是错误的原假设 => 接受了坏人


## Notes

### Critical value method

* Steps
    * State null and alternative hypotheses
    * Identify the test statistic 
    * Select a level of significance
    * Formulate a decision rule
    * Take a sample arrive at decision  

Test statistic= 
Sample statistic−Value of the population parameter under $H_0$ / Standard error of the sample statistic


$\bar{X} - \mu$ 标准化 可以通过查表来做 

标准化之后得到的Z-value 作为检验统计量 
总体方差已知的情况 -> t分布
总体方差未知的时候 -> $S_x$ Sample 

Sample statistics - Hypothesized value / standard error of the sample statistic\\

* k值的影响因素
    * 显著性水平 $\alpha$ significance level 尾巴的面积和
    * 查表 
    * 双尾巴 / 单尾  单尾5% = 双尾10%

两种指标本质上是一样的，都是来检查我们观察到的数据点是否是”正常的“。一个是通过绝对的临界值，一个是通过相对标准差系数。
原假设是要拒绝的,备择假设是要接受的 
总体参数 $\mu \sigma \rho$
找到拒绝域: 单双尾 
找到拒绝域的面积
k = 1.96
计算检验统计量 标准化
观察检验统计量的大小

这个用样本计算出来的$\mu$究竟正不正确? 这里就要用到假设检验了 

假设检验的依据是“置信区间法”以及 检验统计量两个概念

置信区间规定的是你所认为的"小概率事件"究竟有多小

本质上说的都是同一件事情 区别就在于表示形式上 一个是绝对的 (投掷的环数、分数) 一个是相对的 检验统计量是相对于标准差的倍数



#### 不同分布的适用情况
* T-test: normal + unknown variance
* Z-test: normal + known variance
* chi-square test: hypothesis tests concerning the **variance** of a normal distribution
* paired comparisons T-test: mean differences between two dependent samples
* F-test: **variances of two** normally distributed populations with random **independent samples**

#### P-value method

原假设能够被认定的最小值? 可以作为一个分界线。
p-value is lesson than $\alpha$ 原假设可以reject

和 $\alpha$正相关
Error的原因是因为样本数量太小?能否通过增加样本数量来减小出现Error的概率呢? 

[假设检验的逻辑是是什么？ - 王小明的回答 - 知乎](https://www.zhihu.com/question/20254932/answer/45583793)

[Khan- Hypothesis Testing](https://www.khanacademy.org/math/ap-statistics/tests-significance-ap)

p-value 小于significance level的时候 拒绝? why? p-value代表的是计算出来的拒绝域的水平 


Non-parametric test: 
* small sample + do not meet distributional assumptions for a parametric test(e.g. non-normally distributed) 没办法进行估计  
* when data are given in ranks
* when the hypothesis we are addressing does not concern a parameter


### 课后练习
* The power of a test is the probability of rejecting the null hypothesis when it is false
* The smaller the p-value, the stronger the evidence is against the null hypothesis and in favor of the alternative hypothesis