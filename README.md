# 汇率数据自动更新（美元基准）

**更新时间**：2026-09-23 15:01:06（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7048	7.8436	0.8751	0.7508	157.7360
CNY	0.1491		1.1698	0.1305	0.1120	23.5258
HKD	0.1275	0.8548		0.1116	0.0957	20.1102
EUR	1.1427	7.6618	8.9631		0.8580	180.2491
GBP	1.3319	8.9302	10.4470	1.1656		210.0906
JPY	0.0063	0.0425	0.0497	0.0055	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*