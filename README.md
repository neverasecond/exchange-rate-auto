# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-07 13:24:32（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.8053	7.8318	0.8507	0.7355	156.3480
CNY	0.1469		1.1508	0.1250	0.1081	22.9744
HKD	0.1277	0.8689		0.1086	0.0939	19.9632
EUR	1.1755	7.9996	9.2063		0.8646	183.7875
GBP	1.3596	9.2526	10.6483	1.1566		212.5738
JPY	0.0064	0.0435	0.0501	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*