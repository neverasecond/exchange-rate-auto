# 汇率数据自动更新（美元基准）

**更新时间**：2026-09-16 15:00:34（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7068	7.8439	0.8657	0.7418	154.9760
CNY	0.1491		1.1695	0.1291	0.1106	23.1073
HKD	0.1275	0.8550		0.1104	0.0946	19.7575
EUR	1.1551	7.7473	9.0608		0.8569	179.0181
GBP	1.3481	9.0413	10.5741	1.1670		208.9188
JPY	0.0065	0.0433	0.0506	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*