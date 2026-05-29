# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-29 14:05:00（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7688	7.8341	0.8585	0.7441	159.3040
CNY	0.1477		1.1574	0.1268	0.1099	23.5350
HKD	0.1276	0.8640		0.1096	0.0950	20.3347
EUR	1.1648	7.8844	9.1253		0.8667	185.5609
GBP	1.3439	9.0966	10.5283	1.1537		214.0895
JPY	0.0063	0.0425	0.0492	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*