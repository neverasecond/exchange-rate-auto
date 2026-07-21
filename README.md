# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-21 23:28:28（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7557	7.8416	0.8761	0.7475	162.9470
CNY	0.1480		1.1607	0.1297	0.1106	24.1199
HKD	0.1275	0.8615		0.1117	0.0953	20.7798
EUR	1.1414	7.7111	8.9506		0.8532	185.9913
GBP	1.3378	9.0377	10.4904	1.1720		217.9893
JPY	0.0061	0.0415	0.0481	0.0054	0.0046	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*