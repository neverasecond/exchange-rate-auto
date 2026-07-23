# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-23 23:47:23（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7659	7.8404	0.8790	0.7514	163.8320
CNY	0.1478		1.1588	0.1299	0.1111	24.2144
HKD	0.1275	0.8630		0.1121	0.0958	20.8959
EUR	1.1377	7.6973	8.9197		0.8548	186.3845
GBP	1.3308	9.0044	10.4344	1.1698		218.0357
JPY	0.0061	0.0413	0.0479	0.0054	0.0046	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*