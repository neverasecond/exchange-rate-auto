# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-16 14:34:55（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6877	7.8470	0.8899	0.7513	157.8470
CNY	0.1495		1.1733	0.1331	0.1123	23.6026
HKD	0.1274	0.8523		0.1134	0.0957	20.1156
EUR	1.1237	7.5151	8.8178		0.8443	177.3761
GBP	1.3310	8.9015	10.4446	1.1845		210.0985
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