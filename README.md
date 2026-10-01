# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-01 16:03:13（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7048	7.8464	0.8848	0.7557	158.3860
CNY	0.1491		1.1703	0.1320	0.1127	23.6228
HKD	0.1274	0.8545		0.1128	0.0963	20.1858
EUR	1.1302	7.5778	8.8680		0.8541	179.0077
GBP	1.3233	8.8723	10.3830	1.1708		209.5885
JPY	0.0063	0.0423	0.0495	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*