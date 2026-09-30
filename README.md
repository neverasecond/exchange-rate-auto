# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-01 02:43:38（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6978	7.8465	0.8822	0.7541	157.3200
CNY	0.1493		1.1715	0.1317	0.1126	23.4883
HKD	0.1274	0.8536		0.1124	0.0961	20.0497
EUR	1.1335	7.5922	8.8942		0.8548	178.3269
GBP	1.3261	8.8818	10.4051	1.1699		208.6195
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