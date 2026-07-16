# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-16 23:26:31（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7727	7.8388	0.8738	0.7416	162.4370
CNY	0.1477		1.1574	0.1290	0.1095	23.9841
HKD	0.1276	0.8640		0.1115	0.0946	20.7222
EUR	1.1444	7.7509	8.9709		0.8487	185.8972
GBP	1.3484	9.1326	10.5701	1.1783		219.0359
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