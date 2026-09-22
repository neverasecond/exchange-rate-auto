# 汇率数据自动更新（美元基准）

**更新时间**：2026-09-23 01:50:14（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6996	7.8437	0.8742	0.7502	157.5050
CNY	0.1493		1.1708	0.1305	0.1120	23.5096
HKD	0.1275	0.8541		0.1115	0.0956	20.0804
EUR	1.1439	7.6637	8.9724		0.8582	180.1704
GBP	1.3330	8.9304	10.4555	1.1653		209.9507
JPY	0.0063	0.0425	0.0498	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*