# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-10 14:15:16（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7727	7.8367	0.8651	0.7465	160.3390
CNY	0.1477		1.1571	0.1277	0.1102	23.6743
HKD	0.1276	0.8642		0.1104	0.0953	20.4600
EUR	1.1559	7.8288	9.0587		0.8629	185.3416
GBP	1.3396	9.0726	10.4979	1.1589		214.7877
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