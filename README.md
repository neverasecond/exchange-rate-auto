# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-15 13:47:20（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.8018	7.8306	0.8588	0.7492	158.6240
CNY	0.1470		1.1513	0.1263	0.1101	23.3209
HKD	0.1277	0.8686		0.1097	0.0957	20.2569
EUR	1.1644	7.9201	9.1181		0.8724	184.7042
GBP	1.3348	9.0788	10.4519	1.1463		211.7245
JPY	0.0063	0.0429	0.0494	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*