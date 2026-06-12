# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-12 14:25:45（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7617	7.8357	0.8643	0.7458	160.2700
CNY	0.1479		1.1588	0.1278	0.1103	23.7026
HKD	0.1276	0.8629		0.1103	0.0952	20.4538
EUR	1.1570	7.8233	9.0659		0.8629	185.4333
GBP	1.3408	9.0664	10.5064	1.1589		214.8968
JPY	0.0062	0.0422	0.0489	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*