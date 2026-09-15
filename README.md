# 汇率数据自动更新（美元基准）

**更新时间**：2026-09-16 01:50:09（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6997	7.8444	0.8665	0.7421	155.1760
CNY	0.1493		1.1709	0.1293	0.1108	23.1616
HKD	0.1275	0.8541		0.1105	0.0946	19.7818
EUR	1.1541	7.7319	9.0530		0.8564	179.0837
GBP	1.3475	9.0280	10.5705	1.1676		209.1039
JPY	0.0064	0.0432	0.0506	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*