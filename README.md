# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-14 00:13:36（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7903	7.8304	0.8536	0.7396	157.8400
CNY	0.1473		1.1532	0.1257	0.1089	23.2449
HKD	0.1277	0.8672		0.1090	0.0945	20.1573
EUR	1.1715	7.9549	9.1734		0.8664	184.9110
GBP	1.3521	9.1810	10.5873	1.1541		213.4127
JPY	0.0063	0.0430	0.0496	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*