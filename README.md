# 汇率数据自动更新（美元基准）

**更新时间**：2026-11-06 16:46:30（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6690	7.8399	0.8937	0.7464	158.0140
CNY	0.1499		1.1756	0.1340	0.1119	23.6938
HKD	0.1276	0.8506		0.1140	0.0952	20.1551
EUR	1.1189	7.4622	8.7724		0.8352	176.8088
GBP	1.3398	8.9349	10.5036	1.1973		211.7015
JPY	0.0063	0.0422	0.0496	0.0057	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*