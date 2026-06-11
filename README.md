# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-11 14:40:54（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7755	7.8358	0.8659	0.7474	160.5670
CNY	0.1476		1.1565	0.1278	0.1103	23.6982
HKD	0.1276	0.8647		0.1105	0.0954	20.4915
EUR	1.1549	7.8248	9.0493		0.8631	185.4337
GBP	1.3380	9.0654	10.4841	1.1585		214.8341
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