# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-13 16:43:46（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6933	7.8478	0.8940	0.7556	157.9940
CNY	0.1494		1.1725	0.1336	0.1129	23.6048
HKD	0.1274	0.8529		0.1139	0.0963	20.1323
EUR	1.1186	7.4869	8.7783		0.8452	176.7271
GBP	1.3235	8.8583	10.3862	1.1832		209.0974
JPY	0.0063	0.0424	0.0497	0.0057	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*