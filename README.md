# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-14 12:42:15（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7812	7.8381	0.8775	0.7484	162.2940
CNY	0.1475		1.1559	0.1294	0.1104	23.9329
HKD	0.1276	0.8652		0.1120	0.0955	20.7058
EUR	1.1396	7.7279	8.9323		0.8529	184.9504
GBP	1.3362	9.0609	10.4731	1.1725		216.8546
JPY	0.0062	0.0418	0.0483	0.0054	0.0046	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*