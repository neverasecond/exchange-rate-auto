# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-06 13:22:04（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.8175	7.8358	0.8521	0.7360	156.2970
CNY	0.1467		1.1494	0.1250	0.1080	22.9259
HKD	0.1276	0.8700		0.1087	0.0939	19.9465
EUR	1.1736	8.0008	9.1959		0.8637	183.4257
GBP	1.3587	9.2629	10.6465	1.1577		212.3601
JPY	0.0064	0.0436	0.0501	0.0055	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*