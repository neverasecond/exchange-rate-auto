# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-24 13:12:46（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7745	7.8412	0.8785	0.7512	163.8130
CNY	0.1476		1.1575	0.1297	0.1109	24.1808
HKD	0.1275	0.8640		0.1120	0.0958	20.8913
EUR	1.1383	7.7114	8.9257		0.8551	186.4690
GBP	1.3312	9.0182	10.4382	1.1695		218.0684
JPY	0.0061	0.0414	0.0479	0.0054	0.0046	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*