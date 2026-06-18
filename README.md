# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-18 14:44:00（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7614	7.8372	0.8675	0.7506	160.6390
CNY	0.1479		1.1591	0.1283	0.1110	23.7582
HKD	0.1276	0.8627		0.1107	0.0958	20.4970
EUR	1.1527	7.7941	9.0342		0.8652	185.1746
GBP	1.3323	9.0080	10.4412	1.1557		214.0141
JPY	0.0062	0.0421	0.0488	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*