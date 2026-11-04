# 汇率数据自动更新（美元基准）

**更新时间**：2026-11-04 16:19:55（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6769	7.8458	0.8895	0.7419	158.1310
CNY	0.1498		1.1751	0.1332	0.1111	23.6833
HKD	0.1275	0.8510		0.1134	0.0946	20.1549
EUR	1.1242	7.5064	8.8205		0.8341	177.7752
GBP	1.3479	8.9997	10.5753	1.1989		213.1433
JPY	0.0063	0.0422	0.0496	0.0056	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*