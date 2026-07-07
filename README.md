# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-07 13:59:34（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7960	7.8429	0.8745	0.7472	161.8680
CNY	0.1471		1.1540	0.1287	0.1099	23.8181
HKD	0.1275	0.8665		0.1115	0.0953	20.6388
EUR	1.1435	7.7713	8.9684		0.8544	185.0978
GBP	1.3383	9.0953	10.4964	1.1704		216.6328
JPY	0.0062	0.0420	0.0485	0.0054	0.0046	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*