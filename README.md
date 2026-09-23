# 汇率数据自动更新（美元基准）

**更新时间**：2026-09-24 02:04:17（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7009	7.8432	0.8777	0.7547	158.1990
CNY	0.1492		1.1705	0.1310	0.1126	23.6086
HKD	0.1275	0.8544		0.1119	0.0962	20.1702
EUR	1.1393	7.6346	8.9361		0.8599	180.2427
GBP	1.3250	8.8789	10.3925	1.1630		209.6184
JPY	0.0063	0.0424	0.0496	0.0055	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*