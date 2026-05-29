# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-30 01:27:22（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7657	7.8366	0.8569	0.7429	159.2420
CNY	0.1478		1.1583	0.1267	0.1098	23.5367
HKD	0.1276	0.8633		0.1093	0.0948	20.3203
EUR	1.1670	7.8956	9.1453		0.8670	185.8350
GBP	1.3461	9.1071	10.5487	1.1535		214.3519
JPY	0.0063	0.0425	0.0492	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*