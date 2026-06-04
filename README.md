# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-05 00:45:31（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7730	7.8349	0.8598	0.7443	159.9810
CNY	0.1476		1.1568	0.1269	0.1099	23.6204
HKD	0.1276	0.8645		0.1097	0.0950	20.4190
EUR	1.1631	7.8774	9.1125		0.8657	186.0677
GBP	1.3435	9.0998	10.5265	1.1552		214.9416
JPY	0.0063	0.0423	0.0490	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*