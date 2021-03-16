
# Sampling and Estimation

## Objective

* **Define**
    * simple random sampling and a sampling distribution
* **Calculate/Construct**
    * confidence interval for a population mean, given a normal distribution with known population variance/unknown population variance/unknown population variance + large sample size
    * the standard error of the sample mean

* **Describe/Explain/Interpret/Distinguish** 
    * sampling error
    * simple random and stratified random sampling
    * central limit theorem and its importance
    * time-series and cross-sectional data
    * point estimate and a confidence interval estimate of a population parameter
    * t-distribution
    * selection of the appropriate sample size, data-mining bias, sample selection bias, survivorship bias, look-ahead bias, time-period bias


## 基础词汇/概念

## Notes

### Sampling and Estimation
* **Simple random sampling**: 随机直接采样
* **Stratified random sampling**: 根据特性(one or more distinguishing characteristics) 进行分组抽样 M * N 
* **Sampling error**: 样本和真实的Population之间各种统计指标的差异 
* **Sampling distribution**: 多次抽样得到样本分布 500个抽样结果的分布
* **Time-series data**: over a period 2000-2010年苹果股票分红数据 
* **Cross-sectional data**: 在一个特定时间点上的数据 a sample of observations taken at a single point in time
* **Central Limit Theory**: 原来不论是什么分布b在n->$\infty$的时候最终都会收敛于正态分布$\bar{X}$ ~ $N(\mu, \frac{\sigma^2}{n})$


* Known population variance $\frac{\sigma}{\sqrt{n}}$
* Unknown population variance $\frac{s}{\sqrt{n}}$

* sample: standard deviation 
* sample mean: standard error


Confidence interval: estimates result in a range of values within which the actual value of a parameter will lie

level of significance: $\alpha$
degree of confidence: 1 - $\alpha$

68%: 1
90%: 1.645
95%: 1.96
99%: 2.575
standard error of sample mean: 

Desirable properties:

* efficiency: the estimator has the smallest variance
* consistency: probability of accurate estimates increases as sample size increases
* unbiasedness: the expected value of the estimator equals the population paramter

known variance: Z table
unknown variance: T Table

#### Sampling biases
* data-mining bias: 通过sample得到的model本身是依赖于dataset的，需要用out sample data来做test
* sample selection bias: 使用的sample data必须是可得的，而有些数据不可得 systematicaslly excluded from the analysis
* survivor bias: 幸存者偏差
* look-ahead bias: 使用了预测时不可得的信息
* time-period bias: sample data的时间段的太短 

## 课后练习
* Q26: continuously compounded return $\ln{\frac{120}{112}}$