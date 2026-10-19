# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-20 03:33:50（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6707	7.8481	0.8916	0.7516	158.5390
CNY	0.1499		1.1765	0.1337	0.1127	23.7665
HKD	0.1274	0.8500		0.1136	0.0958	20.2009
EUR	1.1216	7.4817	8.8023		0.8430	177.8140
GBP	1.3305	8.8753	10.4419	1.1863		210.9353
JPY	0.0063	0.0421	0.0495	0.0056	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*