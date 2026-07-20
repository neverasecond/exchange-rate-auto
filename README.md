# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-20 13:31:17（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7704	7.8395	0.8737	0.7426	162.3510
CNY	0.1477		1.1579	0.1290	0.1097	23.9795
HKD	0.1276	0.8636		0.1114	0.0947	20.7094
EUR	1.1446	7.7491	8.9728		0.8499	185.8201
GBP	1.3466	9.1172	10.5568	1.1765		218.6251
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