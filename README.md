# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-10 13:55:26（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7792	7.8382	0.8739	0.7448	161.5800
CNY	0.1475		1.1562	0.1289	0.1099	23.8347
HKD	0.1276	0.8649		0.1115	0.0950	20.6144
EUR	1.1443	7.7574	8.9692		0.8523	184.8953
GBP	1.3426	9.1020	10.5239	1.1733		216.9441
JPY	0.0062	0.0420	0.0485	0.0054	0.0046	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*