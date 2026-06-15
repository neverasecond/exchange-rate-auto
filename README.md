# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-15 15:08:51（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7571	7.8351	0.8613	0.7441	160.0840
CNY	0.1480		1.1595	0.1275	0.1101	23.6912
HKD	0.1276	0.8624		0.1099	0.0950	20.4316
EUR	1.1610	7.8452	9.0968		0.8639	185.8632
GBP	1.3439	9.0809	10.5296	1.1575		215.1378
JPY	0.0062	0.0422	0.0489	0.0054	0.0046	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*