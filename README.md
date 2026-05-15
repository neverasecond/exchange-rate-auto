# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-15 23:57:06（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.8087	7.8304	0.8601	0.7506	158.7100
CNY	0.1469		1.1501	0.1263	0.1102	23.3099
HKD	0.1277	0.8695		0.1098	0.0959	20.2684
EUR	1.1627	7.9162	9.1041		0.8727	184.5251
GBP	1.3323	9.0710	10.4322	1.1459		211.4442
JPY	0.0063	0.0429	0.0493	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*