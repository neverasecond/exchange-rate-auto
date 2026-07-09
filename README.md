# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-10 00:22:21（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7812	7.8366	0.8738	0.7459	162.3140
CNY	0.1475		1.1556	0.1289	0.1100	23.9359
HKD	0.1276	0.8653		0.1115	0.0952	20.7123
EUR	1.1444	7.7606	8.9684		0.8536	185.7565
GBP	1.3407	9.0913	10.5062	1.1715		217.6083
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