# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-29 15:50:30（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6609	7.8457	0.8971	0.7505	157.8300
CNY	0.1501		1.1779	0.1347	0.1127	23.6950
HKD	0.1275	0.8490		0.1143	0.0957	20.1168
EUR	1.1147	7.4249	8.7456		0.8366	175.9336
GBP	1.3324	8.8753	10.4540	1.1953		210.2998
JPY	0.0063	0.0422	0.0497	0.0057	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*