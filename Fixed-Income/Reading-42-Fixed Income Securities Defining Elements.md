# Fixed Income Securities: Defining Elements

## Objective
* **Describe**
  * describe basic features of a fixed-income security
  * describe content of a bond indenture
  * describe how legal, regulatory, and tax considerations affect the issuance and trading of fixed-income securities
  * describe how cash flows of fixed-income securities are structured
  * describe contingency provisions affecting the timing and/or nature of cash flows of fixed-income securities and identify whether such provisions benefit the borrower or the lender
* **Compare**
  * compare affirmative and negative covenants and identify examples of each

## 基础词汇/概念
* tenor: the time remaining until the bond's maturity date 当前债券距离到期日剩余的时间
* borrower = issuser: 发债的
* lender = bondholder = investor: 购买债券的
* conventional bond = plain vanilla bond: a bond with fixed coupon rate
* zero-coupon bond = pure discount bond: 不发coupon的bond
* par Value = face value = nominal value = redemption value = maturity value: 面值 到期之后要还的钱
* national market: 发行地 = 发行货币(currency)
  * domestic: 发行人 = 发行地
  * foreign: 发行人 != 发行地
* eurobond: 发行地 != 发行货币
* global bonds: 同时在多个国家发行债券
* registered bond: the ownership is recorded by either name or serial number vs. bearer bond: no records of ownership
* Covenants(条款): legally enforceable rules that borrowers and lenders agree on at the time of a new bond issue. 
* bond ndenture:
* dual-currency bond: coupon in one currency and principal in another currency
* currency option bond: a combination of a single-currency bond + a foreign currency option
* affirmative covenant: 必须要遵守的合同条款
* negative covenants: 被禁止做的合同条款
* money market: maturity < 1 year
* capital market: maturity > 1 year
* perpetual bonds: no stated maturity date
* securitized bonds: issued by a separate legal entity created for the purpose of owning specific assets  e.g. special purpose entities(SPE)
* secured bonds: have collateral
* unsecured bonds: no collateral
* 100bps = 1%
* [LIBOR](https://en.wikipedia.org/wiki/Libor): 1. 单利 2. 360 day / year The London Inter-bank Offered Rate is an interest-rate average calculated from estimates submitted by the leading banks in London
* callable bond(价格相比no-option的更低 因为对investor更不利): give the issuer the right to buy bonds back prior to maturity, thereby raising the reinvestment risk for the bondholder
* putable bond(价格相比no-option的更高 因为对investor更有利): gives the bondholders the right to sell the bond back to the issuer at a **pre-determined** price on specified dates 
* convertible bond(价格相比no-convertible的更高 因为对investor更有力): bondholder有将债权转换为优先股的权利
* cap vs. floor
  * cap: the upper limit of floating rate
  * floor: the lower limit of floating rate
## Notes

* Issuer
  * Supranational organizations: World Bank
  * Sovereign (national) governments: US
  * sovereign (local) governments: Georgia State
  * Quasi-government entities
  * Companies (i.e., corporate issuers)

* Bond Indenture
  * affirmative covenants
    * comply with laws
    * maintain its current lines of business
    * insure and maintain its seets
  * negative covenants: costly and do materially constrain the issuer's potential business decision 
    * restrictions on asset disposals
    * negative pledges
    * restrictions on prior claims

* Credit enhancement
  * Internal credit enhancement
    * subordination: 分级 MBS中常用
    * overcollateralization: 过度抵押 使用超过bond价值的抵押物 
    * reserve accounts
      * cash reserve fund: 单独留一笔cash在违约的时候还钱
      * excess spread: 
  * External credit enhancement
    * surety bond: issued by insurance companies
    * bank guarantee: 
    * letter of credit
  * Limitation of external credit enhancement: third-party (counterparty) risk -> cash collateral account (CCA): 借一笔钱来专门还债

### Bond indenture
* Issuer
* Collateral
* Credit
* Covenants
* Tax
  * Interest income
  * Capital gain
  * Original issue discount bonds
    * pure-discount bonds
    * premium bonds

### Regulation & Tax
* Global Bond Market
    * domestic bond(国内债券): **发行地**和**发行方使用的货币**一样，发行人也一样 e.g. 万科在中国发行人民币计价
    * foreign bond(外国债券): 发行地和发行货币一样，发行人不一样 e.g. 沃尔玛在中国发行人民币计价的债券
    * Eurobond: 发行地而发行方使用货币不一样 e.g. 沃尔玛在中国发行美元计价的债券
* bearer bonds: 监管宽松，受托方不会登记债券所有人的名字，大部分欧洲债券

### 债券分类
* Principal repayment structure
  * Bullet: 只在到期的时候偿还本金 entire principal value at maturity 
  * Amortizing: repay part of principal at each payment date
  * Sinking fund provision
    * advantages: less credit risk
    * disadvantages: more reinvestment risk

* Coupon payment
  * Fixed-rate
  * Step-up: coupon rate
  * Deferred coupon
  * Floating-rate notes(FRN): 
    * coupon rate = reference rate(e.g. LIBOR) + quoted margin
      * coupon rate determined at the coupon reset date  期初决定期末利率 reference是用上一期的
      * 时间频率必须一致
  * Credit-linked: 和信用评级绑定 如果评级下降 要求coupon rate会增加
  * Equity-linked bonds

### 课后练习
* Q1: redemption value = face value = par value, 就是最后要还的钱 注意和债券本身的价格进行区分 bond price不是 par value
* Q4: indenture是合同，covenant是条款 debenture 是unsecured bonds
* Q6: 对ratio的限制一般都是negative的
* Q8: national domestic
  * 中国公司在中国发RMB债券，national domestic
  * 美国公司在中国发RMB债券，national foreign
  * 只要发行地和货币不在一个国家 就是euro bond e.g. 在中国发行 日元/美元债券
* Q9: Eurobonds are most likely to be **bearer bonds**
* Q18 题目中implied 指隐含的 pure discount bond 没有支付coupon只是通过价格和par value的差价来获得收益
* Q24 multiple put bond offers the most benefit to bondholders

## 思考
* 债券估值、项目估值、股票估值 本质上都是用的现金流折现模型，将未来的现金流折到现在 区别在于折现率的不同 而折现率 债券是由 Libor / risk free来 股票是股东要求回报 / 项目估值是出资人的要求回报率决定的