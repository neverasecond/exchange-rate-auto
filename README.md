# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-13 00:13:50（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7915	7.8284	0.8518	0.7393	157.7110
CNY	0.1472		1.1527	0.1254	0.1089	23.2218
HKD	0.1277	0.8675		0.1088	0.0944	20.1460
EUR	1.1740	7.9731	9.1904		0.8679	185.1503
GBP	1.3526	9.1864	10.5889	1.1522		213.3248
JPY	0.0063	0.0431	0.0496	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*