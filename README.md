# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-06 00:26:09（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7650	7.8348	0.8673	0.7493	160.2810
CNY	0.1478		1.1581	0.1282	0.1108	23.6927
HKD	0.1276	0.8635		0.1107	0.0956	20.4576
EUR	1.1530	7.8001	9.0336		0.8639	184.8046
GBP	1.3346	9.0284	10.4562	1.1575		213.9076
JPY	0.0062	0.0422	0.0489	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*