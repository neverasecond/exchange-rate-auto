# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-06 23:56:33（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.8105	7.8351	0.8505	0.7356	156.4150
CNY	0.1468		1.1504	0.1249	0.1080	22.9667
HKD	0.1276	0.8692		0.1085	0.0939	19.9634
EUR	1.1758	8.0076	9.2123		0.8649	183.9095
GBP	1.3594	9.2584	10.6513	1.1562		212.6359
JPY	0.0064	0.0435	0.0501	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*