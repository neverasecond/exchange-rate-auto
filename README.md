# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-29 03:11:35（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6549	7.8452	0.8959	0.7504	157.8930
CNY	0.1503		1.1789	0.1346	0.1128	23.7258
HKD	0.1275	0.8483		0.1142	0.0957	20.1261
EUR	1.1162	7.4282	8.7568		0.8376	176.2395
GBP	1.3326	8.8685	10.4547	1.1939		210.4118
JPY	0.0063	0.0421	0.0497	0.0057	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*