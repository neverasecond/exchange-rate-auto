# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-22 14:51:14（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6736	7.8425	0.8894	0.7461	157.0590
CNY	0.1498		1.1752	0.1333	0.1118	23.5344
HKD	0.1275	0.8510		0.1134	0.0951	20.0266
EUR	1.1244	7.5035	8.8177		0.8389	176.5898
GBP	1.3403	8.9446	10.5113	1.1921		210.5066
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