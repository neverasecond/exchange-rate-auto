# 汇率数据自动更新（美元基准）

**更新时间**：2026-09-28 16:00:09（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7128	7.8442	0.8783	0.7539	157.2160
CNY	0.1490		1.1685	0.1308	0.1123	23.4203
HKD	0.1275	0.8558		0.1120	0.0961	20.0423
EUR	1.1386	7.6429	8.9311		0.8584	179.0003
GBP	1.3264	8.9041	10.4048	1.1650		208.5369
JPY	0.0064	0.0427	0.0499	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*