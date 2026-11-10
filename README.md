# 汇率数据自动更新（美元基准）

**更新时间**：2026-11-11 04:39:21（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6703	7.8453	0.8955	0.7494	158.8060
CNY	0.1499		1.1762	0.1343	0.1123	23.8079
HKD	0.1275	0.8502		0.1141	0.0955	20.2422
EUR	1.1167	7.4487	8.7608		0.8369	177.3378
GBP	1.3344	8.9009	10.4688	1.1950		211.9109
JPY	0.0063	0.0420	0.0494	0.0056	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*