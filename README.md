# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-04 14:28:37（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7745	7.8357	0.8611	0.7447	159.8620
CNY	0.1476		1.1566	0.1271	0.1099	23.5976
HKD	0.1276	0.8646		0.1099	0.0950	20.4018
EUR	1.1613	7.8673	9.0996		0.8648	185.6486
GBP	1.3428	9.0970	10.5220	1.1563		214.6663
JPY	0.0063	0.0424	0.0490	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*