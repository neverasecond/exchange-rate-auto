# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-22 02:18:22（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6642	7.8463	0.8896	0.7462	158.1340
CNY	0.1501		1.1774	0.1335	0.1120	23.7289
HKD	0.1274	0.8493		0.1134	0.0951	20.1540
EUR	1.1241	7.4912	8.8200		0.8388	177.7585
GBP	1.3401	8.9308	10.5150	1.1922		211.9191
JPY	0.0063	0.0421	0.0496	0.0056	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*