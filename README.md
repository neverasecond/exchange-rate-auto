# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-28 15:44:34（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6661	7.8444	0.8988	0.7525	157.8870
CNY	0.1500		1.1768	0.1348	0.1129	23.6851
HKD	0.1275	0.8498		0.1146	0.0959	20.1274
EUR	1.1126	7.4167	8.7276		0.8372	175.6642
GBP	1.3289	8.8586	10.4245	1.1944		209.8166
JPY	0.0063	0.0422	0.0497	0.0057	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*