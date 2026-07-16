# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-16 12:52:31（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7655	7.8379	0.8719	0.7389	162.1120
CNY	0.1478		1.1585	0.1289	0.1092	23.9616
HKD	0.1276	0.8632		0.1112	0.0943	20.6831
EUR	1.1469	7.7595	8.9894		0.8475	185.9296
GBP	1.3534	9.1562	10.6075	1.1800		219.3964
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