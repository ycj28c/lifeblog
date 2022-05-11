---
layout: post
title: 自由现金流
category: 金融概念
tag: create-blog
---

学习自由现金流和学看简单公司财报。

最近股市不行，有大萧条的迹象。除非像苹果这样稳定钱多的，其他的出一个财报跌爆一个。
资本家给某公司提出了自由现金流的要求。当然啦，这些是shareholder的要求，meet不meet他们说了算，总之是除了之前的要满足，现在还要增加free cash flow要求了。

## 自由现金流的定义
自由现金流 = （A）税后净营业利润 + （B）折旧和摊销 - （C）资本支出

英文版的定义
We define free cash flow as net cash flows from operating activities less capital expenditures
Free Cash flow = Operating Activities - Capital Expenditures

## 自由现金流的理解
自由现金流可以理解成一家公司可以赚到的可以给股东自由支配的钱。
Free cash flow是正的表示公司的确在赚钱/攒钱。是比较纯粹的现金流入和流出。
Operating Activities(核心业务经营性收入)就是一些运营收支，类似利润。除去收入，支出上人力应该是主要部分，福利啥的也需要收紧，比如股票激励。
Capital Expenditures资本支出：现金流量表 - 投资活动产生的现金流量 - 购建固定资产、无形资产和其他长期资产所支付的现金。我理解是包括买资产和支付贷款之类的支出。对于软件公司来说就是投资开发app的feature开销吧。

所以公司首先要保证运营赚钱（包括利润，人力支出等），然后还要不随便花钱（减少市场啊，福利啊等budget）

## 自由现金流和财报的关联
这部分来自一亩三分地的知识普及[Link](https://www.1point3acres.com/bbs/thread-893492-2-1.html)

所谓市场预期其实是无数分析师们根据公司未来现金流折现计算出的预测股价公式如下
（DCF）StockPrice=FCF(year0)+(FCF(year1)/(1+r)+FCF(year2)/(1+r)^2+FCF(yearn)/(1+r)^n

根据这个公式我们可以发现股价是由折现率（discountrate==r）和每年的freecashflow（自由现金流量在财报中计算得出）决定的。
因为我们不可能准确预测未来的自由现金流，所以这个数量是通过假定增长率恒定（g）来实现的（永续年金）。
而在公司发布财报之前，分析师们只能够通过以往的FCF来预测未来现金流，从而折现到今天的预测股价，这也是所谓的市场预期。
当公司发布实际财报后，分析师们会将财报中的实际FCF（自由现金流）计算出来替代自己公式里的FCF'。
哪怕这个FCF只是miss了一点点，但是apply到N年后这个数量就会误差非常大，因此股价会迅速反应实际现金流贴现后的价格。
这也是为什么META会大跌，因为一旦它开始miss预期，相当于第0年（今天）的基础FCF减少了，影响到未来第N年会放大影响。

根据2021年Q3 SP500 EPS，财报反馈统计如果财报不及预期EPS会平均下跌4%；而如果beat预期股价仅仅会上升1.5%。
有些公司是因为核心业务经营性收入降低（opeartingincome）导致的FCF减少，这是值得警惕的（Meta网飞），证明你的商业模式遇到了挑战。

在所有财务报表之中金融分析师最关注cash flow statement，因为它直接关乎流动性，在会计准则中大量的收入和支出是Accrual的（权责发生制）。
而公司的隐患往往会隐藏在“应计支出和收入”的背后。常见的现象是一个公司可以赚钱（Netincome净利润是正的），但依然破产，因为它缺乏流动性。
一个公司也可以把投资者常用的指标搞得很好看（高EPS高ROE）但实际营收减少（原因是增加了债务）。
如果缺乏必要的财务知识，千万不要盲信某一财务指标，他可以会让你做出错误的判断。

## 看财报和捕风捉影
这个工具看财报很方便：[stockanalysis](https://stockanalysis.com/stocks/uber/financials/cash-flow-statement/quarterly/)
可以方便的看到重要的指标比如EPS，Operation Income，Cash on hand，Cash flow等等。

另外上市公司是有SEC记录的，所有的E级别的交易是会公开的。[SEC](https://www.sec.gov/edgar/browse/?CIK=0001184237)
也可以从中发现一些情况。

## 大萧条下怎么生存
对于独角兽，或者之前高速发展时期的用烧钱来换增长的策略。在经济大萧条的情况下行不通。
因为这个时候大家都缺钱，大萧条下投资者不喜欢烧钱的行为，越稳定越好，才能成为基本的避风港。
Startups with high growth & moderate burn will get funded through the downturn.
Startups with moderate growth & high burn will not get funded through the downturn.

这里对增长和烧钱给了一个定义：
Rough Definitions:
* High growth = 2x+ YoY
* Moderate growth = 50% YoY
* High Burn = 2-3x Burn Multiple 
* Moderate Burn = 1x Burn Multiple

而相对于高增速，cut burn比较简单，所以这个期间领导层更倾向于cut cost。

## 引用
1. [David Sacks Twitter](https://twitter.com/DavidSacks/status/1522745450347958272?s=20&t=Q2r0cjIQBzKR3hre7V7Q6Q)  
2. [财报不及预期意味着什么？](https://www.1point3acres.com/bbs/thread-893492-2-1.html)



