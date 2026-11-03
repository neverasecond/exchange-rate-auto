# 汇率数据自动更新（美元基准）

**更新时间**：2026-11-04 04:20:40（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6696	7.8465	0.8934	0.7454	158.7160
CNY	0.1499		1.1765	0.1340	0.1118	23.7969
HKD	0.1274	0.8500		0.1139	0.0950	20.2276
EUR	1.1193	7.4654	8.7827		0.8343	177.6539
GBP	1.3416	8.9477	10.5266	1.1986		212.9273
JPY	0.0063	0.0420	0.0494	0.0056	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*