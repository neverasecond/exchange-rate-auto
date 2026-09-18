# 汇率数据自动更新（美元基准）

**更新时间**：2026-09-18 14:52:55（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6986	7.8451	0.8706	0.7479	156.8770
CNY	0.1493		1.1712	0.1300	0.1117	23.4194
HKD	0.1275	0.8539		0.1110	0.0953	19.9968
EUR	1.1486	7.6942	9.0111		0.8591	180.1941
GBP	1.3371	8.9565	10.4895	1.1641		209.7567
JPY	0.0064	0.0427	0.0500	0.0055	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*