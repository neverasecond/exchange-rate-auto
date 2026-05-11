# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-12 00:24:32（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7947	7.8288	0.8488	0.7330	157.0920
CNY	0.1472		1.1522	0.1249	0.1079	23.1198
HKD	0.1277	0.8679		0.1084	0.0936	20.0659
EUR	1.1781	8.0051	9.2234		0.8636	185.0754
GBP	1.3643	9.2697	10.6805	1.1580		214.3138
JPY	0.0064	0.0433	0.0498	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*