# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-25 00:09:09（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7990	7.8393	0.8806	0.7597	161.7520
CNY	0.1471		1.1530	0.1295	0.1117	23.7906
HKD	0.1276	0.8673		0.1123	0.0969	20.6335
EUR	1.1356	7.7209	8.9022		0.8627	183.6839
GBP	1.3163	8.9496	10.3189	1.1591		212.9156
JPY	0.0062	0.0420	0.0485	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*