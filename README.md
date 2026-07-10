# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-11 00:14:57（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7643	7.8396	0.8739	0.7451	161.3430
CNY	0.1478		1.1590	0.1292	0.1102	23.8521
HKD	0.1276	0.8628		0.1115	0.0950	20.5805
EUR	1.1443	7.7404	8.9708		0.8526	184.6241
GBP	1.3421	9.0784	10.5215	1.1729		216.5387
JPY	0.0062	0.0419	0.0486	0.0054	0.0046	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*