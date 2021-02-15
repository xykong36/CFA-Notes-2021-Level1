## Objective 

**Calculate**
* quartiles, quintiles, deciles, and percentiles
* calculate and interpret relative frequencies and cumulative relative frequencies
* coefficient of variation
* range, mean absolute deviation, variance and standard deviation of a population and sample
* measures of central tendency, population mean, sample mean, arithmetic mean, weighted average or mean, geometric mean, harmonic mean, median and mode
* falling in standard deviations of the mean using Chebyshev's inequality

**Explain/Interpret/Demonstrate/Define**
* explain skewness and the meaning of a positively or negatively skewed return distribution
* measures of sample skewness and kurtosis
* parameter, a sample statistic, and a frequency distribution 

**Compare/Distinguish**
* descriptive statistics and inferential statistics, population vs. sample and types of measurement scales
* use of arithmetic and geometric means when analyzing investment returns

**Describe**
* relative locations of mean, median, and mode for a unimodal, nonsymmetrical distribution


## Notes


### Describing Data Sets

* descriptive: e.g. 身高180cm
* inferential: forecast, estimates, or judgments about a large set of data 从抽样样本来推断总体

#### Measurement Scales
* Nominal scales: contains the least information 只分类 不排序 苹果、梨、橘子
* Ordinal scales: Make things in order 按照一个顺序排 差值没有意义 e.g. 增长最快的股票 1-10编号
* Interval scales: relative ranking e.g. 温度 有相对值 20度和40度差值 0度选择不是真的没有 30度也不是10度的3倍
* Ratio scales: 成比例 4块钱 = 2倍2块钱

**Frequency distribution**: summarize statistical data by assigning it to specified groups or intervals.
* interval: 某一个数值范围内 80-90分之间的学生数量
* modal interval: the interval with the greatest frequency 
* absolute frequency: 绝对量 10 8 
* relative frequency: 相对比例  10% 3% 
* commulative absolute frequency: 考试在60分以上的学生数
* commulative relative frequency: 及格率
* Histogram: 柱状图📊
* Frequency Polygon: 折线图


### Means and Variance

* Arithmetic Mean: 可以作为estimate的依据 forward-looking
* Weighted Mean: 加权平均 Portfolio
* Geometric Mean: 复利思想 用于计算investment returns over multiple periods or when measuring compound growth rates 
* Harmonic Mean(调和平均) 专门用于计算average cost of shares purchased over time e.g. 计算定投的平均成本 例题: 三个月每个月买1000块的股票，股价分别是 10， 9， 8， 计算每股的价格 不能直接 (10 + 9 + 8) / 3 因为买的份数不相同， 应该是 3000 / (1000/ 10 + 1000/9 + 1000/8) 或者直接调和平均 3 / (1 / 8 + 1 / 9 + 1 / 10)

sample variance 与 population variance的区别在于 sample variance的分母用`$N - 1$`, 而population variance的分母用`$N$`
 

需要算一下 L = (n + 1) * (y / 100) 为了保证当N为奇数和偶数都能得到有效的结果
* Quartile: 4等分
* Quintile: 5等分
* Decile: 10等分
* Percentile: 百分


### Skew and Kurtosis
**Measure of Dispersion**
* Absolute dispersion: amount of variability present without comparison to any reference point or benchmard
    * Range: Max - Min
    * MAD(Mean Absolute Deviation): 每个data point与平均值的差值 求和 / 数据点个数
    * Population Variance: 每个数据点与平均值的差值 求和 / 数据点个数
    * Population Standard Deviation:  Population Variance开根号 
    
**Chebyshev's inequality**: 对于任意一组观测值，个体落在均值周围k个标准差之内的概率不小于1 - 1/k^2,只有一个k所以两边是对称的

![efde67584d8219c4cbc62d13a6ca3d6a.png](evernotecid://1FC78D12-88FB-4FAC-95A1-F7FB5953B0DF/appyinxiangcom/29211871/ENResource/p27)

例题: 

Coefficient of variation(CV): 变异系数
$$CV = \frac{s_x}{\mu}$$
是一种relative measure of dispersion,应用于不同的金融产品的比较
measure the risk(variability) per unit of expected return 
e.g. Sharpe ratio: 夏普比率 $sr = \frac{R_p - R_f}{\sigma}$, 用return的方差或者标准差来衡量风险,每单位风险的超额收益


**Skewness**
![db78c6d668d7e6595a0a61b812c1f180.png](evernotecid://1FC78D12-88FB-4FAC-95A1-F7FB5953B0DF/appyinxiangcom/29211871/ENResource/p28)

sample skewness
```math
\frac{1}{n} \frac{\sum_{i=1}^{n}(X_i - \bar{X})}{s^3}
```

sample kurtosis
```math
\frac{1}{n} \frac{\sum_{i=1}^{n}(X_i - \bar{X})}{s^3}
```

**Kurtosis**: 判断一个distribution是否比normal distribution更具有峰度 peaked

计算
![e91e95979cd0fb1c1939b355689d7ee7.png](evernotecid://1FC78D12-88FB-4FAC-95A1-F7FB5953B0DF/appyinxiangcom/29211871/ENResource/p29)
l: 竖直 峰度更高 大于 3 大于 0 
p: plat 更平坦 小于 3 小于 0


## Q&A

* cumulative relative / relative: cumulative 需要将当前interval之前的所有的值都加起来 relative frequency只需要考虑当前的interval的相对值 但是题目里面还是会以当前interval来出题
