# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-11 00:53:57（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7740	7.8363	0.8653	0.7468	160.5100
CNY	0.1476		1.1568	0.1277	0.1102	23.6950
HKD	0.1276	0.8644		0.1104	0.0953	20.4829
EUR	1.1557	7.8285	9.0562		0.8631	185.4964
GBP	1.3390	9.0707	10.4932	1.1587		214.9304
JPY	0.0062	0.0422	0.0488	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*