# 汇率数据自动更新（美元基准）

**更新时间**：2026-11-10 16:59:05（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6665	7.8436	0.8886	0.7433	157.9360
CNY	0.1500		1.1766	0.1333	0.1115	23.6910
HKD	0.1275	0.8499		0.1133	0.0948	20.1357
EUR	1.1254	7.5023	8.8269		0.8365	177.7358
GBP	1.3454	8.9688	10.5524	1.1955		212.4795
JPY	0.0063	0.0422	0.0497	0.0056	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*