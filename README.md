# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-30 03:20:49（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6605	7.8451	0.8955	0.7482	157.9100
CNY	0.1501		1.1779	0.1344	0.1123	23.7084
HKD	0.1275	0.8490		0.1141	0.0954	20.1285
EUR	1.1167	7.4377	8.7606		0.8355	176.3372
GBP	1.3365	8.9020	10.4853	1.1969		211.0532
JPY	0.0063	0.0422	0.0497	0.0057	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*