# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-17 01:44:30（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6760	7.8480	0.8902	0.7508	158.1290
CNY	0.1498		1.1756	0.1333	0.1125	23.6862
HKD	0.1274	0.8507		0.1134	0.0957	20.1490
EUR	1.1233	7.4994	8.8160		0.8434	177.6331
GBP	1.3319	8.8918	10.4529	1.1857		210.6140
JPY	0.0063	0.0422	0.0496	0.0056	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*