# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-31 02:55:30（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6449	7.8436	0.8953	0.7467	157.3690
CNY	0.1505		1.1804	0.1347	0.1124	23.6827
HKD	0.1275	0.8472		0.1141	0.0952	20.0634
EUR	1.1169	7.4220	8.7609		0.8340	175.7724
GBP	1.3392	8.8990	10.5044	1.1990		210.7526
JPY	0.0064	0.0422	0.0498	0.0057	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*