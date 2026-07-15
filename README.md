# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-15 12:42:14（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7679	7.8370	0.8740	0.7461	162.2090
CNY	0.1478		1.1580	0.1291	0.1102	23.9674
HKD	0.1276	0.8636		0.1115	0.0952	20.6978
EUR	1.1442	7.7436	8.9668		0.8537	185.5938
GBP	1.3403	9.0710	10.5040	1.1714		217.4092
JPY	0.0062	0.0417	0.0483	0.0054	0.0046	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*