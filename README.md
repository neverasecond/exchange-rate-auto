# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-06 14:19:21（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7888	7.8419	0.8751	0.7498	162.2380
CNY	0.1473		1.1551	0.1289	0.1104	23.8979
HKD	0.1275	0.8657		0.1116	0.0956	20.6886
EUR	1.1427	7.7577	8.9611		0.8568	185.3937
GBP	1.3337	9.0541	10.4587	1.1671		216.3750
JPY	0.0062	0.0418	0.0483	0.0054	0.0046	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*