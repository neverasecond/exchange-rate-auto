# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-17 12:55:38（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7744	7.8407	0.8742	0.7430	162.4140
CNY	0.1476		1.1574	0.1290	0.1097	23.9747
HKD	0.1275	0.8640		0.1115	0.0948	20.7142
EUR	1.1439	7.7493	8.9690		0.8499	185.7859
GBP	1.3459	9.1176	10.5528	1.1766		218.5922
JPY	0.0062	0.0417	0.0483	0.0054	0.0046	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*