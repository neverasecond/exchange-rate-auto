# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-24 13:59:14（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.8012	7.8410	0.8794	0.7578	161.6070
CNY	0.1470		1.1529	0.1293	0.1114	23.7615
HKD	0.1275	0.8674		0.1122	0.0966	20.6105
EUR	1.1371	7.7339	8.9163		0.8617	183.7696
GBP	1.3196	8.9749	10.3471	1.1605		213.2581
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