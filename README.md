# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-18 00:50:58（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7572	7.8343	0.8625	0.7465	160.2080
CNY	0.1480		1.1594	0.1276	0.1105	23.7092
HKD	0.1276	0.8625		0.1101	0.0953	20.4496
EUR	1.1594	7.8344	9.0832		0.8655	185.7484
GBP	1.3396	9.0518	10.4947	1.1554		214.6122
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