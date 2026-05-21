# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-21 14:02:23（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.8032	7.8324	0.8601	0.7443	159.0090
CNY	0.1470		1.1513	0.1264	0.1094	23.3727
HKD	0.1277	0.8686		0.1098	0.0950	20.3014
EUR	1.1627	7.9098	9.1064		0.8654	184.8727
GBP	1.3435	9.1404	10.5232	1.1556		213.6356
JPY	0.0063	0.0428	0.0493	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*