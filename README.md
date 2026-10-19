# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-19 15:07:31（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6804	7.8481	0.8909	0.7503	157.9640
CNY	0.1497		1.1748	0.1334	0.1123	23.6459
HKD	0.1274	0.8512		0.1135	0.0956	20.1277
EUR	1.1225	7.4985	8.8092		0.8422	177.3083
GBP	1.3328	8.9036	10.4599	1.1874		210.5345
JPY	0.0063	0.0423	0.0497	0.0056	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*