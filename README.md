# 汇率数据自动更新（美元基准）

**更新时间**：2026-09-17 14:55:57（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7063	7.8449	0.8706	0.7462	155.5730
CNY	0.1491		1.1698	0.1298	0.1113	23.1980
HKD	0.1275	0.8549		0.1110	0.0951	19.8311
EUR	1.1486	7.7031	9.0109		0.8571	178.6963
GBP	1.3401	8.9873	10.5131	1.1667		208.4870
JPY	0.0064	0.0431	0.0504	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*