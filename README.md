# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-24 00:21:41（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7784	7.8404	0.8783	0.7578	161.5380
CNY	0.1475		1.1567	0.1296	0.1118	23.8313
HKD	0.1275	0.8645		0.1120	0.0967	20.6033
EUR	1.1386	7.7176	8.9268		0.8628	183.9212
GBP	1.3196	8.9448	10.3463	1.1590		213.1671
JPY	0.0062	0.0420	0.0485	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*