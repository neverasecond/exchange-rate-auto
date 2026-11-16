# 汇率数据自动更新（美元基准）

**更新时间**：2026-11-17 07:07:10（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6539	7.8460	0.9088	0.7583	159.4060
CNY	0.1503		1.1792	0.1366	0.1140	23.9568
HKD	0.1275	0.8481		0.1158	0.0966	20.3168
EUR	1.1004	7.3216	8.6334		0.8344	175.4027
GBP	1.3187	8.7748	10.3468	1.1985		210.2150
JPY	0.0063	0.0417	0.0492	0.0057	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*