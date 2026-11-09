# 汇率数据自动更新（美元基准）

**更新时间**：2026-11-10 07:13:31（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6622	7.8417	0.8908	0.7440	157.9190
CNY	0.1501		1.1770	0.1337	0.1117	23.7037
HKD	0.1275	0.8496		0.1136	0.0949	20.1384
EUR	1.1226	7.4789	8.8030		0.8352	177.2777
GBP	1.3441	8.9546	10.5399	1.1973		212.2567
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