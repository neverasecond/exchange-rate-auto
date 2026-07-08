# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-08 23:57:11（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7926	7.8394	0.8773	0.7484	162.6700
CNY	0.1472		1.1541	0.1292	0.1102	23.9481
HKD	0.1276	0.8665		0.1119	0.0955	20.7503
EUR	1.1399	7.7426	8.9358		0.8531	185.4212
GBP	1.3362	9.0762	10.4749	1.1722		217.3570
JPY	0.0061	0.0418	0.0482	0.0054	0.0046	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*