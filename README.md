# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-03 14:44:39（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7699	7.8359	0.8607	0.7436	159.9370
CNY	0.1477		1.1575	0.1271	0.1098	23.6247
HKD	0.1276	0.8640		0.1098	0.0949	20.4108
EUR	1.1618	7.8656	9.1041		0.8639	185.8220
GBP	1.3448	9.1042	10.5378	1.1575		215.0847
JPY	0.0063	0.0423	0.0490	0.0054	0.0046	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*