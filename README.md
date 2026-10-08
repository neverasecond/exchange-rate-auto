# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-09 03:34:31（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6938	7.8475	0.8918	0.7561	157.8680
CNY	0.1494		1.1724	0.1332	0.1130	23.5842
HKD	0.1274	0.8530		0.1136	0.0963	20.1170
EUR	1.1213	7.5059	8.7996		0.8478	177.0218
GBP	1.3226	8.8531	10.3789	1.1795		208.7925
JPY	0.0063	0.0424	0.0497	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*