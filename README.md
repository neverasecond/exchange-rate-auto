# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-09 14:01:30（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7724	7.8353	0.8660	0.7485	160.1420
CNY	0.1477		1.1569	0.1279	0.1105	23.6463
HKD	0.1276	0.8643		0.1105	0.0955	20.4385
EUR	1.1547	7.8203	9.0477		0.8643	184.9215
GBP	1.3360	9.0480	10.4680	1.1570		213.9506
JPY	0.0062	0.0423	0.0489	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*