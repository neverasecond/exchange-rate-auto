# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-07 03:14:24（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7040	7.8472	0.8878	0.7532	158.1580
CNY	0.1492		1.1705	0.1324	0.1124	23.5916
HKD	0.1274	0.8543		0.1131	0.0960	20.1547
EUR	1.1264	7.5513	8.8389		0.8484	178.1460
GBP	1.3277	8.9007	10.4185	1.1787		209.9814
JPY	0.0063	0.0424	0.0496	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*