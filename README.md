# 汇率数据自动更新（美元基准）

**更新时间**：2026-11-03 16:50:47（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6713	7.8453	0.8931	0.7455	157.9260
CNY	0.1499		1.1760	0.1339	0.1117	23.6724
HKD	0.1275	0.8504		0.1138	0.0950	20.1300
EUR	1.1197	7.4698	8.7843		0.8347	176.8290
GBP	1.3414	8.9488	10.5235	1.1980		211.8390
JPY	0.0063	0.0422	0.0497	0.0057	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*