# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-28 00:57:02（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7783	7.8339	0.8592	0.7445	159.4980
CNY	0.1475		1.1557	0.1268	0.1098	23.5307
HKD	0.1277	0.8653		0.1097	0.0950	20.3600
EUR	1.1639	7.8891	9.1177		0.8665	185.6355
GBP	1.3432	9.1045	10.5224	1.1541		214.2351
JPY	0.0063	0.0425	0.0491	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*