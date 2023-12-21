# 留学生日常作业/课程设计/代码辅导/CS/DS/商科，仅为漂洋过海的你❥
标签：Computer Science、Data Science、Business Administration，留学生编程作业代写&&辅导

## 个人介绍:
本人是一名资深码农，酷爱投资。

[为您提供 CS , DS , 商科 编程作业代写](http://dzuoye.work "编程代写")

<img src="design2023866.jpg"  width="200" />

This dataset wa extracted from public company filings required by the Securities and Exchange Commission(SEC).Each row is the numeric financials of one company for one quarter.The final column is a label saying whether the company's filing in that quarter were deemed by the SEC to be fraudulent.

The goal is to build a predictor that could be applied to new filings to predict whether or not they are fraudulent.This would be of practical use,since it often takes the SEC a long time to declare a filing fraudulent but investors would like to know right away,

The SEC is conservative in its labelling of reports as fraudulent,so it would not be surprising if a predictor predicted more reports to be fraudulent than are labelled fraudulent.The converse would be more surprising.

The attributes are standard accounting measures.You can look up their menings online or ask a Commerce student.






Must be uploaded by 10:00 p.m. on Monday September 25th(but preferably by Sept 18th)
Expected to take you:3hours(after you've covered the relevant material of course)

Note that these exerclses are worth at most 2 marks each,and will be marked simply:2 -- good attempt,1 -- half-hearted attempt,0 -- not a serous attempt.

The dataset we are going to work with for the first half of the term is about detecting fraud using the financial data filed by companies.This is easy dataset,with no missing values,so we can focus on the way that different predictors work,especially within KNIME.

You can find the dataset in the Week 1 material.Each column of the dataset corresponds to some financial quantity,and each row corresponds to one quarterly filing.

The deliverable for this exercise sheet is a Word or pdf document containing the answers to the questions below.Include an image of your workflow whenever that's appropriate Recall that,on a Windows computer,the PrtScr(print screen) button copies the entire desktop view to the clipboard,while Alt-PrtScr copies only the active window.

Questions:

1.Your first task is to keep a diary,for one of the days of this week,of all the times and places that you notice that data is being collected about you as an individual as you live your life.For example,if you buy something online then data about your credit card is obviously collected,but so is data about what kinds of things you buy.

Try and capture as many different sources as you can,remembering that some data capture is hidden from you.Hand in a list of all of the sources you notice,with brief comments on anything that seems interesting or surprising.



2.The Second task is to use the dataset to get familiar with KNIME.Hand in a brief description of the properties you extracted from the data.

For Example,you might look at the distributions of the attributed ,properties such as means and standard deviations,and what the difference between the minimum and maximum values for each attribute are.

Try to plot some values,including correlations between pairs of attributes.

Play around with KNIME properties.For example,you could tweak some of the example workflows to do simple predictions.

Some of these properties could also be investigated using a tool such as excel.While that is acceptable,you will need to become familiar with KNIME,and the sooner the better,so do everything you can in the KNIME environment.


We will continue to work with the numerical fraud dataset and with KNIME.
The deliverable for this exercise sheet is a Word or pdf document containing the answers to the questions below.
This week we will build some simple predictors and see how they perform in predicting when a financial statement is fraudulent.
Questions:
1.Use the Naive Bayes classifier as a predictor.Report results such as classification accuracy,confusion matrix,and perhaps some of the other measures we discussed.Explore the options for binning at least one attribute in KNIME,and see what effect this has on prediction performance.

Numeric fraud dataset -- deleted empty column

To make everyone's life a little easier,i've uploaded a version of the numeric fraud dataset without the empty column(in the same place as you found the data originally)
But see the Column Filter node for a way to remove columns within KNIME.


act: Accounts Receivable Turnover - 应收账款周转率
at: Total Assets - 总资产
ceq: Common Equity - 普通股权益
che: Cash and Cash Equivalents - 现金及现金等价物
csho: Common Shares Outstanding - 普通股股本
dlc: Current Portion of Long-Term Debt - 长期债务的流动部分
dltis: Long-Term Debt Issued - 发行的长期债务
dltt: Long-Term Debt Total - 长期债务总额
emp: Total Employees - 总雇员数
ib: Income Before Taxes - 税前利润
invt: Inventory - 存货
ivao: Invested Assets Other - 其他投资资产
ivst: Investments - 投资
lct: Current Liabilities - 流动负债
lt: Total Liabilities - 总负债
pstk: Preferred Stock - 优先股
rect: Receivables - 应收款项
sale: Sales - 销售额
sstk: Treasury Stock - 回购股票
exchg: Exchange - 交易所
prcc-f: Closing Price - 收盘价格
ret-t: Total Return - 总回报
ret-t1: Total Return T-1 - 总回报 T-1
vwretd: Value-Weighted Return - 市值加权回报
vwretd-t1: Value-Weighted Return T-1 - 市值加权回报 T-1
oplease: Operating Lease Expense - 经营租赁费用
lease-dum: Lease Dummy - 租赁虚拟变量
r-vwretd: Residual Value-Weighted Return - 剩余价值加权回报
r-1-vwretd: Residual Value-Weighted Return T-1 - 剩余价值加权回报 T-1
WC: Working Capital - 营运资本
NCO: Net Cash from Operations - 经营活动产生的净现金流
FIN: Net Cash from Financing - 融资活动产生的净现金流
ATA: Total Assets - 总资产
rsst-acc: Research and Development Expense - 研发费用
ch-rec: Change in Receivables - 应收款项的变动
ch-inv: Change in Inventory - 存货的变动
cs: Common Shares - 普通股股本
ch-cs: Change in Common Shares - 普通股股本的变动
earn-ATA: Earnings After Taxes - 税后收益
ch-earn: Change in Earnings - 收益的变动
ch-emp: Change in Employees - 雇员数量的变动
issue: Issuance of Shares - 股票发行
bm: Book-to-Market Ratio - 市账比率
new-comp: New Company - 新公司
fraud?: Fraud Indicator - 欺诈指示符

## 作业代写价格:
|类型|美元|人民币|
|-----:|-----:|-----:|
|Assignment|$40-$120|¥400-¥800|

### 为了方便快速定价和确定是否代做，麻烦提供私聊的时候提供以下信息：
如果是作业，提供本次作业要求文档；如果是考试，提供考试范围和考试时间
一两句话概括一下作业任务或者考试任务，比如”可以帮忙实现一个决策树算法吗？”、”网络安全选择题考试，范围是内网横向移动知识点”
### 作业定价有两种方式：
    - 根据定价标准进行
    - 通过微信我们一起协商
## 联系方式
[为您提供 CS , DS , 商科 编程作业代写](http://dzuoye.work "编程代写")
微信（WeChat）：design2023866

<img src="design2023866.jpg"  width="200" />
