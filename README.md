# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-08 03:39:01（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7045	7.8480	0.8927	0.7567	158.0170
CNY	0.1492		1.1706	0.1331	0.1129	23.5688
HKD	0.1274	0.8543		0.1137	0.0964	20.1347
EUR	1.1202	7.5104	8.7913		0.8477	177.0102
GBP	1.3215	8.8602	10.3713	1.1797		208.8238
JPY	0.0063	0.0424	0.0497	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*