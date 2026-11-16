# 汇率数据自动更新（美元基准）

**更新时间**：2026-11-16 16:47:50（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6664	7.8461	0.9069	0.7566	159.4120
CNY	0.1500		1.1770	0.1360	0.1135	23.9128
HKD	0.1275	0.8496		0.1156	0.0964	20.3174
EUR	1.1027	7.3508	8.6516		0.8343	175.7768
GBP	1.3217	8.8110	10.3702	1.1987		210.6952
JPY	0.0063	0.0418	0.0492	0.0057	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*