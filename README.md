# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-14 23:16:42（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7576	7.8376	0.8732	0.7458	161.9060
CNY	0.1480		1.1598	0.1292	0.1104	23.9591
HKD	0.1276	0.8622		0.1114	0.0952	20.6576
EUR	1.1452	7.7389	8.9757		0.8541	185.4169
GBP	1.3408	9.0609	10.5090	1.1708		217.0904
JPY	0.0062	0.0417	0.0484	0.0054	0.0046	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*