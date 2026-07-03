# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-03 23:48:39（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7692	7.8425	0.8740	0.7489	161.2880
CNY	0.1477		1.1586	0.1291	0.1106	23.8267
HKD	0.1275	0.8631		0.1114	0.0955	20.5659
EUR	1.1442	7.7451	8.9731		0.8569	184.5400
GBP	1.3353	9.0389	10.4720	1.1670		215.3665
JPY	0.0062	0.0420	0.0486	0.0054	0.0046	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*