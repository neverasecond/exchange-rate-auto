# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-04 02:17:08（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7687	7.8368	0.8621	0.7455	160.0430
CNY	0.1477		1.1578	0.1274	0.1101	23.6446
HKD	0.1276	0.8637		0.1100	0.0951	20.4220
EUR	1.1600	7.8514	9.0904		0.8647	185.6432
GBP	1.3414	9.0794	10.5121	1.1564		214.6787
JPY	0.0062	0.0423	0.0490	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*