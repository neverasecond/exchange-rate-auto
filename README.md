# 汇率数据自动更新（美元基准）

**更新时间**：2026-11-12 16:59:27（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6683	7.8444	0.9012	0.7535	159.6990
CNY	0.1500		1.1764	0.1351	0.1130	23.9490
HKD	0.1275	0.8501		0.1149	0.0961	20.3583
EUR	1.1096	7.3994	8.7044		0.8361	177.2071
GBP	1.3271	8.8498	10.4106	1.1960		211.9429
JPY	0.0063	0.0418	0.0491	0.0056	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*