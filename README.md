# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-09 13:56:10（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7963	7.8373	0.8745	0.7460	162.3600
CNY	0.1471		1.1532	0.1287	0.1098	23.8895
HKD	0.1276	0.8672		0.1116	0.0952	20.7163
EUR	1.1435	7.7716	8.9620		0.8531	185.6604
GBP	1.3405	9.1103	10.5058	1.1723		217.6408
JPY	0.0062	0.0419	0.0483	0.0054	0.0046	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*