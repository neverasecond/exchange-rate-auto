# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-06 05:18:17（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7040	7.8464	0.8907	0.7564	157.9240
CNY	0.1492		1.1704	0.1329	0.1128	23.5567
HKD	0.1274	0.8544		0.1135	0.0964	20.1269
EUR	1.1227	7.5267	8.8093		0.8492	177.3032
GBP	1.3221	8.8630	10.3733	1.1776		208.7837
JPY	0.0063	0.0425	0.0497	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*