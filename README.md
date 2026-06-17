# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-17 15:00:04（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7557	7.8333	0.8612	0.7455	160.2470
CNY	0.1480		1.1595	0.1275	0.1104	23.7203
HKD	0.1277	0.8624		0.1099	0.0952	20.4572
EUR	1.1612	7.8445	9.0958		0.8657	186.0741
GBP	1.3414	9.0620	10.5074	1.1552		214.9524
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