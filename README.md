# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-13 05:55:26（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6831	7.8471	0.8960	0.7570	158.5560
CNY	0.1496		1.1742	0.1341	0.1133	23.7249
HKD	0.1274	0.8517		0.1142	0.0965	20.2057
EUR	1.1161	7.4588	8.7579		0.8449	176.9598
GBP	1.3210	8.8284	10.3661	1.1836		209.4531
JPY	0.0063	0.0421	0.0495	0.0057	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*