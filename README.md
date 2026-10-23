# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-24 02:01:18（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6596	7.8433	0.8932	0.7480	156.8950
CNY	0.1502		1.1777	0.1341	0.1123	23.5592
HKD	0.1275	0.8491		0.1139	0.0954	20.0037
EUR	1.1196	7.4559	8.7811		0.8374	175.6549
GBP	1.3369	8.9032	10.4857	1.1941		209.7527
JPY	0.0064	0.0424	0.0500	0.0057	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*