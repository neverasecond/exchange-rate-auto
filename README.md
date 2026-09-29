# 汇率数据自动更新（美元基准）

**更新时间**：2026-09-29 15:41:31（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7029	7.8444	0.8808	0.7556	157.2440
CNY	0.1492		1.1703	0.1314	0.1127	23.4591
HKD	0.1275	0.8545		0.1123	0.0963	20.0454
EUR	1.1353	7.6100	8.9060		0.8579	178.5241
GBP	1.3235	8.8710	10.3817	1.1657		208.1048
JPY	0.0064	0.0426	0.0499	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*