# 汇率数据自动更新（美元基准）

**更新时间**：2026-09-14 15:22:31（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7063	7.8430	0.8651	0.7409	154.3500
CNY	0.1491		1.1695	0.1290	0.1105	23.0157
HKD	0.1275	0.8551		0.1103	0.0945	19.6800
EUR	1.1559	7.7521	9.0660		0.8564	178.4187
GBP	1.3497	9.0516	10.5858	1.1676		208.3277
JPY	0.0065	0.0434	0.0508	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*