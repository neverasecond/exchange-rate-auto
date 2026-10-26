# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-26 15:14:18（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6676	7.8439	0.8917	0.7479	157.0270
CNY	0.1500		1.1764	0.1337	0.1122	23.5508
HKD	0.1275	0.8500		0.1137	0.0953	20.0190
EUR	1.1215	7.4774	8.7966		0.8387	176.0985
GBP	1.3371	8.9151	10.4879	1.1923		209.9572
JPY	0.0064	0.0425	0.0500	0.0057	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*