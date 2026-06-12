# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-13 00:38:11（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7621	7.8355	0.8639	0.7455	160.2270
CNY	0.1479		1.1587	0.1278	0.1102	23.6949
HKD	0.1276	0.8630		0.1103	0.0951	20.4489
EUR	1.1575	7.8274	9.0699		0.8629	185.4694
GBP	1.3414	9.0706	10.5104	1.1588		214.9256
JPY	0.0062	0.0422	0.0489	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*