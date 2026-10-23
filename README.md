# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-23 14:45:52（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6716	7.8399	0.8917	0.7469	157.1090
CNY	0.1499		1.1751	0.1337	0.1120	23.5489
HKD	0.1276	0.8510		0.1137	0.0953	20.0397
EUR	1.1215	7.4819	8.7921		0.8376	176.1904
GBP	1.3389	8.9324	10.4966	1.1939		210.3481
JPY	0.0064	0.0425	0.0499	0.0057	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*