# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-27 14:10:40（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7809	7.8356	0.8585	0.7435	159.3450
CNY	0.1475		1.1555	0.1266	0.1096	23.4991
HKD	0.1276	0.8654		0.1096	0.0949	20.3360
EUR	1.1648	7.8985	9.1271		0.8660	185.6086
GBP	1.3450	9.1202	10.5388	1.1547		214.3174
JPY	0.0063	0.0426	0.0492	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*