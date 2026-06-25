# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-25 13:58:00（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.8052	7.8398	0.8800	0.7589	161.7970
CNY	0.1469		1.1520	0.1293	0.1115	23.7755
HKD	0.1276	0.8680		0.1122	0.0968	20.6379
EUR	1.1364	7.7332	8.9089		0.8624	183.8602
GBP	1.3177	8.9672	10.3305	1.1596		213.1994
JPY	0.0062	0.0421	0.0485	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*