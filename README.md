# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-23 02:12:44（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6641	7.8371	0.8909	0.7461	156.9440
CNY	0.1501		1.1760	0.1337	0.1120	23.5507
HKD	0.1276	0.8503		0.1137	0.0952	20.0258
EUR	1.1225	7.4802	8.7968		0.8375	176.1634
GBP	1.3403	8.9319	10.5041	1.1941		210.3525
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