# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-21 02:11:51（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6665	7.8482	0.8899	0.7473	158.1690
CNY	0.1500		1.1773	0.1335	0.1121	23.7259
HKD	0.1274	0.8494		0.1134	0.0952	20.1535
EUR	1.1237	7.4913	8.8192		0.8398	177.7379
GBP	1.3382	8.9208	10.5021	1.1908		211.6540
JPY	0.0063	0.0421	0.0496	0.0056	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*