# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-14 00:21:33（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7678	7.8383	0.8771	0.7475	162.3650
CNY	0.1478		1.1582	0.1296	0.1104	23.9908
HKD	0.1276	0.8634		0.1119	0.0954	20.7143
EUR	1.1401	7.7161	8.9366		0.8522	185.1157
GBP	1.3378	9.0539	10.4860	1.1734		217.2107
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