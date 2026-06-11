# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-12 01:32:10（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7751	7.8366	0.8667	0.7480	160.3000
CNY	0.1476		1.1567	0.1279	0.1104	23.6602
HKD	0.1276	0.8645		0.1106	0.0954	20.4553
EUR	1.1538	7.8171	9.0419		0.8630	184.9544
GBP	1.3369	9.0576	10.4767	1.1587		214.3048
JPY	0.0062	0.0423	0.0489	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*