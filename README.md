# 汇率数据自动更新（美元基准）

**更新时间**：2026-09-26 02:08:50（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7123	7.8441	0.8776	0.7551	157.2970
CNY	0.1490		1.1686	0.1307	0.1125	23.4341
HKD	0.1275	0.8557		0.1119	0.0963	20.0529
EUR	1.1395	7.6485	8.9381		0.8604	179.2354
GBP	1.3243	8.8893	10.3882	1.1622		208.3128
JPY	0.0064	0.0427	0.0499	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*