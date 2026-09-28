# 汇率数据自动更新（美元基准）

**更新时间**：2026-09-29 04:19:11（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7098	7.8447	0.8792	0.7546	157.3850
CNY	0.1490		1.1691	0.1310	0.1125	23.4560
HKD	0.1275	0.8553		0.1121	0.0962	20.0626
EUR	1.1374	7.6317	8.9225		0.8583	179.0093
GBP	1.3252	8.8919	10.3958	1.1651		208.5675
JPY	0.0064	0.0426	0.0498	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*