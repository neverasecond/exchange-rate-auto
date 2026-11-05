# 汇率数据自动更新（美元基准）

**更新时间**：2026-11-06 04:53:05（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6675	7.8415	0.8909	0.7433	157.8030
CNY	0.1500		1.1761	0.1336	0.1115	23.6675
HKD	0.1275	0.8503		0.1136	0.0948	20.1241
EUR	1.1225	7.4840	8.8018		0.8343	177.1276
GBP	1.3454	8.9701	10.5496	1.1986		212.3006
JPY	0.0063	0.0423	0.0497	0.0056	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*