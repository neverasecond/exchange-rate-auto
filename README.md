# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-08 12:48:27（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.8034	7.8271	0.8520	0.7371	156.8810
CNY	0.1470		1.1505	0.1252	0.1083	23.0592
HKD	0.1278	0.8692		0.1089	0.0942	20.0433
EUR	1.1737	7.9852	9.1867		0.8651	184.1326
GBP	1.3567	9.2300	10.6188	1.1559		212.8354
JPY	0.0064	0.0434	0.0499	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*