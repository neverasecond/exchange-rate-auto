# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-15 23:18:47（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7576	7.8387	0.8743	0.7422	162.1850
CNY	0.1480		1.1600	0.1294	0.1098	24.0004
HKD	0.1276	0.8621		0.1115	0.0947	20.6903
EUR	1.1438	7.7292	8.9657		0.8489	185.5027
GBP	1.3473	9.1048	10.5614	1.1780		218.5193
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